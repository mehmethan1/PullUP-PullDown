# PullUP-PullDown
BTK Akademiden öğrendiklerimi tekrarlıyorum


![Funky Wluff-Inari](https://github.com/mehmethan1/PullUP-PullDown/assets/71599621/f3f2ea92-ed04-40d1-8739-3863d334174e)


--------------CODE--------------

void setup()
{
  Serial.begin(9600);
  pinMode(7, INPUT);
  pinMode(6, INPUT);
}

void loop()
{
  Serial.print("PULLDOWN : ");
  Serial.print(digitalRead(7));
  Serial.print("                  ");
  Serial.print("PULLUP : ");
  Serial.println(digitalRead(6));
  delay(1000);
}

----MADE BY MEHMETHAN SAĞIR ------
