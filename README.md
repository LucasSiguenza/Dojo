# DOJO - 1-1 

![LOGO TINKERCAD](https://github.com/iagovalverde/EjemploDocumentacion/blob/main/img/ArduinoTinkercad.jpg)

## INTEGRANTES
* Lucas Gabriél Sigüenza
* Iago Valverde Pachiani
* Nicolás Velázquez
* Victoria Rodríguez
* Enzo Pose 

## PROYECTO: DOJO 1-1

![IMAGEN DEL PROYECTO](https://i.im.ge/2023/04/25/LbesZT.FotoFulvo.png)

## DESCRIPCIÓN

El proyecto es un semáforo con 2 lámparas led (de cada color). <br/>
El verde dura 5 segundos. <br/>
El amarillo dura 3 segundos. <br/>
Rojo dura 5 segundos.<br/>
Además posee señalización para personas no videntes, que suena durante la luz roja dos veces a cada segundo.

## FUNCIÓN PRINCIPAL

Estas dos funciones se encargan de encender y apagar los leds. <br/> 
led, led_dos, tiempo, tiempo_dos son parametros que pasamos a las funciones para despues asignarles el led que se prende y apaga y el tiempo, respectivamente. <br/>
Los leds son asignados a través del hashtag define a los pines a los cuales están conectados.

```C++ 
void encenderDosLed(int led_uno, int led_dos,int tiempo)
{
  digitalWrite(led_uno, 1);
  digitalWrite(led_dos, 1);
  delay(tiempo);
}
void apagarDosLed(int led_uno, int led_dos,int tiempo)
{
  digitalWrite(led_uno, 0);
  digitalWrite(led_dos, 0);
  delay(tiempo);
}

```

## LINK AL PROYECTO

* [proyecto](https://www.tinkercad.com/things/i2CBQSHZGLf-dojo-1-1/editel?sharecode=MPb9SxTbzHUjMsSWyZcr3BQnK4RgUTSg-Y6jfeaZM7s)
----------------------------------------------------------------------------------------------------------------------------------
#DOJO 1-2
#DESCRIPCIÓN
*[Proyecto](https://www.tinkercad.com/things/eGYqkp8Cdgp-dojo-1-2-con-sueno/editel?sharecode=QBdMOxAWkjos47bNTdN34RYt6imzijOwldFQFdhOoTc)
