**Voltage Indicator using Arduino**

A simple Arduino project using 3 LEDs and a potentiometer.



&#x20;**Components Used**

\- Arduino UNO

\- 3 LEDs

\- Resistors

\- Potentiometer

\- Breadboard

\- Jumper wires



**Working**

The potentiometer changes the analog voltage.

According to the voltage level, different LEDs glow.






int readVal;
int mypin=A2;
int V1;
int dt=500;
int red=5,green=7,blue=6;



void setup() {
  pinMode(5,OUTPUT);
  pinMode(6,OUTPUT);
  pinMode(7,OUTPUT);
  Serial.begin(9600); 

}

void loop() {
  readVal=analogRead(mypin);
  V1=(5./1025.)*readVal;
  Serial.println(V1);
  if(V1<2 && V1>0){
    digitalWrite(green,HIGH);
  }
  else{
    digitalWrite(green,LOW);
  }
  if(V1<4 && V1>=2){
    digitalWrite(blue,HIGH);
  }
  else{
    digitalWrite(blue,LOW);
  }
  if(V1<=5 && V1>=4){
    digitalWrite(red,HIGH);
  }
  else{
    digitalWrite(red,LOW);
  }
}
