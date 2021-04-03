/*
 * Interface LDR with NodeMCU
 */

 // Buzzer positive to D5, negative to Ground
 // LDR to 10K resister to A0 to Ground
 // LDR other terminal to 3v3
void setup() {
  // initialize serial communication at 9600 bits per second:
  Serial.begin(9600);
  pinMode(D5, OUTPUT);
 
}

void loop() {
  // read the input on analog pin 0:
 
  int sensorValue = analogRead(A0);
  
  // Convert the analog reading (which goes from 0 - 1023) to a voltage (0 - 5V):
  float voltage = sensorValue * (5.0 / 1023.0);
  if(voltage<1.75){
  tone(14,780,200);
    delay(1000);}}
  
