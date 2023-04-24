# Dojo
/* C++ Code
Nombre: Lucas Gabriél Sigüenza
Curso:1-D
Ejercicio:DOJO-Grupo E-Primera entrega.
*/
#define led_Rojo_A 12
#define led_Amarillo_A 11
#define led_Verde_A 10
#define led_Rojo_B 9
#define led_Amarillo_B 8
#define led_Verde_B 7
#define piezo 6
void setup()
{
  pinMode(led_Rojo_A, OUTPUT);
  pinMode(led_Amarillo_A, OUTPUT);
  pinMode(led_Verde_A, OUTPUT);
  pinMode(led_Rojo_B, OUTPUT);
  pinMode(led_Amarillo_B, OUTPUT);
  pinMode(led_Verde_B, OUTPUT);
  pinMode(piezo, OUTPUT);
}

void loop()
{
  for (int i=0; i<2000; i++)
  {
   	digitalWrite(piezo, 1);
    digitalWrite(piezo, 0);
  }
  digitalWrite(led_Verde_A, 1);
  digitalWrite(led_Verde_B, 1);
  delay(5000);
  digitalWrite(led_Verde_A, 0);
  digitalWrite(led_Verde_B, 0);
  delay(100);
  digitalWrite(led_Amarillo_A, 1);
  digitalWrite(led_Amarillo_B, 1);
  delay(3000);
  digitalWrite(led_Amarillo_A, 0);
  digitalWrite(led_Amarillo_B, 0);
  delay(100);
  digitalWrite(led_Rojo_A, 1);
  digitalWrite(led_Rojo_B, 1);
  delay(5000);
  digitalWrite(led_Rojo_A, 0);
  digitalWrite(led_Rojo_B, 0);
  delay(100);
  digitalWrite(led_Amarillo_A, 1);
  digitalWrite(led_Amarillo_B, 1);
  delay(3000);
  digitalWrite(led_Amarillo_A, 0);
  digitalWrite(led_Amarillo_B, 0);
  delay(100);
  for (int i=0; i<2000; i++)
  {
   	digitalWrite(piezo, 1);
    digitalWrite(piezo, 0);
  }
}
