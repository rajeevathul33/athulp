# 10 day internship
## day 1
## day 2
## day 3 
## and
![and](https://github.com/rajeevathul33/athulp/blob/main/and.png)
// C++ code
//
void setup()
{
  pinMode(LED_BUILTIN, OUTPUT);
}

void loop()
{
  digitalWrite(LED_BUILTIN, HIGH);
  delay(1000); // Wait for 1000 millisecond(s)
  digitalWrite(LED_BUILTIN, LOW);
  delay(1000); // Wait for 1000 millisecond(s)
}


## day 4


## day 5
## and
![and](https://github.com/rajeevathul33/athulp/blob/main/Screenshot%20from%202023-05-15%2014-30-16.png)

const int potPin = 0;

void setup() {
  Serial.begin(9600);
}

void loop() {
  int potValue = analogRead(potPin);
  Serial.println(potValue);
  delay(100);
}


## day 5
[hello](https://www.tinkercad.com/things/0R3PTyPYjxt-glorious-fyyran-albar)
``` 
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

```

