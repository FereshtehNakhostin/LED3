# LED
 روشن خاموش شدن ال ای دی

 وسایل مورد نیاز:
 ال ای دی
سیم جامپر
مقاومت 220 اهم
برد اونو
برد بورد

کدپروژه:
int led = 9;
void setup() {
 pinMode(led , OUTPUT);
}
void loop() {
 digitalWrite(led,HIGH);
 delay(3000);
 digitalWrite(led,LOW);
 delay(3000);
 }
