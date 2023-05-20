[smart letter box](https://www.tinkercad.com/things/0R3PTyPYjxt-glorious-fyyran-albar)


int analogPin = A0; // potentiometer wiper (middle terminal) connected to analog pin 3
                    // outside leads to ground and +5V
int val = 0;  // variable to store the value read

void setup() {
  Serial.begin(9600);
  pinMode(13,OUTPUT);//  setup serial
}

void loop() {
  val = analogRead(analogPin);  // read the input pin
  Serial.println(val);
  if (val==1017)
  {
    digitalWrite(13,HIGH);
  }
  else {
    digitalWrite(13,LOW);
  }// debug value
}
![smart](https://github.com/rajeevathul33/athulp/blob/main/smart%20.png)


