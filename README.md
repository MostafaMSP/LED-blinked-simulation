# LED-blinked-simulation

int led=9;
void setup() {
  // put your setup code here, to run once:
  pinMode(led,OUTPUT);
}

void loop() {
  // put your main code here, to run repeatedly:
  
  digitalWrite(led,1);
  delay(200);
  digitalWrite(led,0);
  delay(200);
}
