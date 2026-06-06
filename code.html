// --- LINE FOLLOWER ROBOT ---
// Logic: Black Line = HIGH (1), White Surface = LOW (0)
// NOTE: Some sensors are opposite (White=1, Black=0).
// If your robot goes backward or spins, flip the logic in the 'if' statements.

// Motor A (Left)
const int in1 = 5;  
const int in2 = 6;  

// Motor B (Right)
const int in3 = 10; 
const int in4 = 11; 

// IR Sensors
const int leftSensorPin = 2;
const int rightSensorPin = 3;

// Sensor Readings
int leftVal;
int rightVal;

// Speed Control (0-255)
// Start slow (100) to test, then increase if needed
int speed = 120; 

void setup() {
  // Set Motor pins as OUTPUT
  pinMode(in1, OUTPUT);
  pinMode(in2, OUTPUT);
  pinMode(in3, OUTPUT);
  pinMode(in4, OUTPUT);

  // Set Sensor pins as INPUT
  pinMode(leftSensorPin, INPUT);
  pinMode(rightSensorPin, INPUT);
  
  Serial.begin(9600);
}

void loop() {
  // 1. Read Sensors
  leftVal = digitalRead(leftSensorPin);
  rightVal = digitalRead(rightSensorPin);

  // Debugging (Optional: View in Serial Monitor)
  // Serial.print("Left: "); Serial.print(leftVal);
  // Serial.print(" | Right: "); Serial.println(rightVal);

  // 2. Logic Control
  
  // CASE 1: Forward (Both sensors see White/Surface)
  // Assuming 0 = White and 1 = Black Line
  if (leftVal == 0 && rightVal == 0) {
    moveForward();
  }
  
  // CASE 2: Turn Right (Right sensor sees Black Line)
  else if (leftVal == 0 && rightVal == 1) {
    turnRight();
  }
  
  // CASE 3: Turn Left (Left sensor sees Black Line)
  else if (leftVal == 1 && rightVal == 0) {
    turnLeft();
  }
  
  // CASE 4: Stop (Both sensors see Black/Finish Line)
  else if (leftVal == 1 && rightVal == 1) {
    stopRobot();
  }
}

// --- MOTOR FUNCTIONS ---

void moveForward() {
  // Left Motor Forward
  analogWrite(in1, speed);
  analogWrite(in2, 0);
  
  // Right Motor Forward
  analogWrite(in3, speed);
  analogWrite(in4, 0);
}

void turnLeft() {
  // Left Motor Backward (or Stop)
  analogWrite(in1, 0);
  analogWrite(in2, speed); // Or set to 0 for softer turn
  
  // Right Motor Forward
  analogWrite(in3, speed);
  analogWrite(in4, 0);
}

void turnRight() {
  // Left Motor Forward
  analogWrite(in1, speed);
  analogWrite(in2, 0);
  
  // Right Motor Backward (or Stop)
  analogWrite(in3, 0);
  analogWrite(in4, speed); // Or set to 0 for softer turn
}

void stopRobot() {
  analogWrite(in1, 0);
  analogWrite(in2, 0);
  analogWrite(in3, 0);
  analogWrite(in4, 0);
}
