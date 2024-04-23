const int sensorPIR = A0; 
const int lampada1 = 2;    
const int lampada2 = 3;    

void setup() {
  pinMode(sensorPIR, INPUT); 
  pinMode(lampada1, OUTPUT); 
  pinMode(lampada2, OUTPUT);
}

void loop() {
  int valorSensorLuz = analogRead(sensorPIR); 
  if (valorSensorLuz < 100) {
    digitalWrite(lampada1, HIGH); 
    digitalWrite(lampada2, HIGH);
  } else {
    digitalWrite(lampada1, LOW); 
    digitalWrite(lampada2, LOW); 
  }
  delay(1000); 
}
