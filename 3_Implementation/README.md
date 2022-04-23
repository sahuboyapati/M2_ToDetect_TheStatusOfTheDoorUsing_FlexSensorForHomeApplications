int a;
void setup()
{
 // put your setup code here, to run once:
 Serial.begin(9600);
 pinMode(13,OUTPUT);
}
void loop() {
 // put your main code here, to run repeatedly:
 a = analogRead(A0);
 a = a - 700;
 Serial.print(a);
if(a>200)

{
 Serial.println("\tON");

 digitalWrite(13,HIGH);
 }
 else

{
 Serial.println("\tOFF");
 digitalWrite(13,LOW);
 }

 delay(100);
}


Program 2

int a;
void setup()
{
 // put your setup code here, to run once:
 Serial.begin(9600);
 pinMode(13,OUTPUT);
}
void loop() {
 // put your main code here, to run repeatedly:
 a = analogRead(A0);
 a = a - 700;
 Serial.print(a);
 if(a>230)
 {

 Serial.println("\t100% ON");
 digitalWrite(13,HIGH);
 }

else if(a>210)
 {
 Serial.println("\t50% ON");

 digitalWrite(13,LOW);
 }


 else

 {

 Serial.println("\tOFF");

 digitalWrite(13,LOW);

}

 delay(100);
}
