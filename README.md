# CODTECH_TASK2
// Define the pin connected to the LED
const int ledPin = 13;  // Pin 13 has an onboard LED on most Arduino boards

// Define the blink interval (in milliseconds)
const int blinkInterval = 1000;  // 1000 milliseconds = 1 second

void setup() {
  // Initialize the digital pin as an output
  pinMode(ledPin, OUTPUT);
}

void loop() {
  // Turn the LED on (HIGH is the voltage level)
  digitalWrite(ledPin, HIGH);

  // Wait for the specified blink interval
  delay(blinkInterval);

  // Turn the LED off by making the voltage LOW
  digitalWrite(ledPin, LOW);

  // Wait for the specified blink interval
  delay(blinkInterval);
}
