## SENSOR DE SONIDO
## Diagrama Pictórico
## Diagrama Esquemático
## Objetivo
Realizar un sensor de proximidad mediante el sensor ultrasónico HC-SR04, la proximidad de los materiales se imprime en la pantalla, pero también se evidencia según la cantidad de LEDs que prenden.
## Materiales
* Protoboard
* Resistencia 220 ohms
* Cable de Timbre
* Sensor PIR
* Placa Arduino MEGA 2560
* LEDs
* Jumpers
* Sensor ultrasónico HC-SR04
## Construcción
* Se conecta la entrada GND de la placa con el cable para timbre  a negativo(tierra) y positivo a un pin digital  y al protoboard.
*  en el Sensor ultrasónico HC-SR04, primero se conecta el Gnd al polo negativo (tierra) en el protoboard, luego el Ucc al polo positivo del protoboard luego el Trig al pin digital numero #3 y el Echo al pindigital del arduino #2
* Luego se colocan 5 LEDS al protoboard y 5 resistencia de 220 ohms  al cátodo y a tierra y un conector ente el ánodo y otro de los pines digitales del arduino . Los LEDS van en los pines digitales # 4,5,8,6,7 respectivamente 
## Montaje
## Software
Código que se debe subir a la placa de arduino ![Código sensor](https://github.com/kksksie28o/proyecto-guiado/blob/master/documentos/echo.ino)
