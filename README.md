# Arduino-
LED output


 /*
 LED output
*/

 int LED0 = 2; //Use digital pin 2 to drive the white LED
 int LED1 = 3; //use didgital pin 3 to drive the yellow LED
 int LED2 = 4; //Use digital pin 4 to drive the green LED
 int LED3 = 5; //Use digital pin 5 to drive the red LED
 int LED4 = 13; //Use Digital pin 13 to drive the onboard LED
 
 void setup(){
 //Initialize digital pin 2 to 5 as output
 pinMode(LED0, OUTPUT);
 pinMode(LED1, OUTPUT);
 pinMode(LED2, OUTPUT);
 pinMode(LED3, OUTPUT);
 pinMode(LED4, OUTPUT);
 
 }
 
 void loop(){
 //Toggle each LED at a time with a 500ms delay
 digitalWrite(LED0,HIGH);
 delay(100);
 digitalWrite(LED0,LOW);
 delay(100);
 
 digitalWrite(LED1,HIGH);
 delay(100);
 digitalWrite(LED1,LOW);
 delay(100);
 
 digitalWrite(LED2,HIGH);
 delay(100);
 digitalWrite(LED2,LOW);
 delay(100);
 
 digitalWrite(LED3,HIGH);
 delay(100);
 digitalWrite(LED3,LOW);
 delay(100);
 
 //Back Down...........
 digitalWrite(LED4,HIGH);
 delay(500);
 digitalWrite(LED4,LOW);
 delay(100);
 
 digitalWrite(LED3, HIGH);
 delay(100);
 digitalWrite(LED3, LOW);
 delay(100);
 digitalWrite(LED2,HIGH);
 delay(100);
 digitalWrite(LED2,LOW);
 delay(100);
 digitalWrite(LED1, HIGH);
 delay(100);
 digitalWrite(LED1, LOW);
 delay(100);
 digitalWrite(LED0, HIGH);
 delay(100);
 digitalWrite(LED0, LOW);
 delay(100);
 
 
 //on off at a time.....
 digitalWrite(LED2, HIGH);
 delay(100);
 digitalWrite(LED2, LOW);
 delay(100);
 digitalWrite(LED0, HIGH);
 delay(100);
 digitalWrite(LED0, LOW);
 delay(100);
 digitalWrite(LED3, HIGH);
 delay(100);
 digitalWrite(LED3, LOW);
 delay(100);
 digitalWrite(LED0, HIGH);
 delay(100);
 digitalWrite(LED0, LOW);
 delay(100);
 digitalWrite(LED4, HIGH);
 delay(100);
 digitalWrite(LED4, LOW);
 delay(100);
 
 }
