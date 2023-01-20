
# Excercise 4
void setup() {
  // put your setup code here, to run once:
  pinMode(13, OUTPUT);
  pinMode(11, OUTPUT);
}


void loop() {
  // put your main code here, to run repeatedly:
  digitalWrite(13, HIGH);
  delay(1000);
  digitalWrite(13, LOW);
  delay(1000);
digitalWrite(11, HIGH);
  delay(1000);
  digitalWrite(11, LOW);
  delay(1000);
}
















void setup() {
  // put your setup code here, to run once:
  pinMode(13, INPUT);
  Serial.begin(9600);
  }


void loop() {
  // put your main code here, to run repeatedly:
  if digitalRead(13) == HIGH{
    Serial.println( "Hello World.");
  }
  else {
    Serial.println("It's 2023")
  }


  }
   


}
Exercise IV

void setup() {
  // put your setup code here, to run once:
  pinMode(2, INPUT);
  pinMode(4, INPUT);
  pinMode(7, INPUT);
  pinMode(8, INPUT);
  pinMode(11, INPUT);
  pinMode(12, INPUT);
  pinMode(13, INPUT);

}

void loop() {
  // put your main code here, to run repeatedly:
  digitalWrite(2, LOW);
  digitalWrite(4, LOW);
  digitalWrite(7, LOW);
  digitalWrite(12, LOW);
  digitalWrite(8, LOW);
  digitalWrite(13, LOW);
  delay(1500);

  digitalWrite(2, LOW);
  digitalWrite(4, LOW);
  digitalWrite(7, LOW);
  digitalWrite(12, LOW);
  digitalWrite(8, LOW);
  digitalWrite(13, LOW);
  digitalWrite(11, LOW);
  delay(1500);

  digitalWrite(2, LOW);
  digitalWrite(4, LOW);
  digitalWrite(8, LOW);
  delay(1500);

  digitalWrite(4, LOW);
  digitalWrite(11, LOW);
  digitalWrite(7, LOW);
  digitalWrite(12, LOW);
  digitalWrite(8, LOW);
  digitalWrite(13, LOW);
  delay(1500);

  digitalWrite(4, LOW);
  digitalWrite(7, LOW);
  digitalWrite(12, LOW);
  digitalWrite(8, LOW);
  digitalWrite(13, LOW);
  delay(1500);

  digitalWrite(2, LOW);
  digitalWrite(7, LOW);
  digitalWrite(12, LOW);
  digitalWrite(8, LOW);
  delay(1500);

  digitalWrite(2, LOW);
  digitalWrite(4, LOW);
  digitalWrite(12, LOW);
  digitalWrite(8, LOW);
  digitalWrite(13, LOW);
  delay(1500);

  digitalWrite(2, LOW);
  digitalWrite(4, LOW);
  digitalWrite(12, LOW);
  digitalWrite(11, LOW);
  digitalWrite(13, LOW);
  delay(1500);

  digitalWrite(2, LOW);
  digitalWrite(8, LOW);
  delay(1500);

  digitalWrite(2, LOW);
  digitalWrite(4, LOW);
  digitalWrite(7, LOW);
  digitalWrite(11, LOW);
  digitalWrite(8, LOW);
  digitalWrite(13, LOW);
  delay(1500);
}

























