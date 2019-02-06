**¿Qué es arduino?** 

Es una compañía de código abierto y hardware abierto así como un proyecto que diseña placa de desarrollo de hadware , Su propósito es utilizar trabajos sencillos que no requieren gran capacidad
¿como funciona el hardware de arduino?

Arduino tiene hardware libre, sus diseños de referencia están disponibles en el sitio web de arduino, basada en una placa con un microcontrolador y un entorno de desarrollo, diseñada para facilitar el uso de la electrónica en proyectos multiples.

¿cal es el lenguaje de programacion de arduino? que esta disponible es  un pagina web.

Lenguaje de programación C++ El lenguaje de programación de Arduino está basado en C++

**¿Cómo funciona arduino?**

* Arduino es una plataforma  de código abierto, basada en software libre, flexible y fácil de utilizar para los creadores y cualquier tipo de perosna que desee hacer algun proyecto. Esta plataforma permite crear diferentes tipos de microordenadores de una sola placa, a los que la comunidad de creadores pueden darles diferentes tipos de uso.

* En estos casos la placa Arduino se conecta con una serie de sensores como entrada y salida, se conecta a un ordenador u otro dispositivo capaz de ejecutar tareas complejas. 

* Disponemos de un entorno de desarrollo sobre el que programar el microcontrolador y que nos permitirá cargar el programa en el mismo a través de la misma plataforma de desarrollo. 

* Arduino se basa en tres pilares. Por un lado, tenemos una interfaz de entrada que se corresponderá con los diferentes periféricos o sensores que conectemos a los puertos que dispone la placa Arduino. A través del puerto USB de la placa Arduino, traspasaremos la programación al microcontrolador. El programa gestionará las entradas para proporcionar las salidas que queramos.

**Historia de arduino**

Arduino fue inventado en el año 2005 por Massimo Banzi ,estudiante del instituto IVRAE(Interaction Design Institute University)  en Italia , el desde el principio pensaba en hacer Arduino por una necesidad de aprendizaje para los estudiantes de computación y electrónica del mismo instituto, ya que ,adquirir una placa de micro controladores eran bastante caro y no ofrecían el soporte adecuado; no obstante, nunca se imaginó que esta herramienta se llegaría a convertir en años más adelante en el líder mundial de tecnologías DIY (Do It Yourself). Inicialmente fue un proyecto creado no solo para economizar la creación de proyectos escolares dentro del instituto, sino que además, Banzi tenía la intención de ayudar a su escuela a evitar la quiebra de la misma con las ganancias que produciría vendiendo sus placas dentro del campus.

**Partes de una Placa Arduino**

*Potencia - USB  / Conector de Adaptador 

Cada placa Arduino necesita una forma de estar alimentado electricamente. Esta puede ser alimentado desde un cable USB que viene de su ordenador o un cable de corriente eléctrica con su respectivo adaptador. La conexión USB es también cómo va a cargar código en su placa Arduino.

*Pines (5V, 3.3V, GND, Analog, Digital, PWM, AREF)

Los pines en la placa Arduino es donde se conectan los cables de un circuito. El Arduino tiene varios tipos diferentes de entradas, cada uno de las cuales está marcado en el tablero y utilizan para diferentes funciones.

*Botón de reinicio 

Empujando este botón se conectará temporalmente el pin de reset a tierra y reinicie cualquier código que se carga en el Arduino. Esto puede ser muy útil si el código no se repite, pero quiere probarlo varias veces.

*Indicador LED de alimentación 

Este LED debe encenderse cada vez que conecte la placa Arduino a una toma eléctrica. Si esta luz no se enciende, hay una buena probabilidad de que algo anda mal.

*Microcontrolador 

Lo negro con todas las patas de metal es un circuito integrado (IC, por sus siglas en Ingles). Piense en ello como el cerebro de nuestro Arduino. La principal IC en el Arduino es ligeramente diferente del tipo de placa a placa tipo, pero es por lo general de la línea de ATmega de CI de la empresa ATMEL. Esto puede ser importante, ya que puede necesitar para saber el tipo de IC (junto con su tipo de tarjeta) antes de cargar un nuevo programa desde el software de Arduino.

*Regulador de Voltaje 

Esto no es realmente algo que se puede (o debe) interactuar con el Arduino. Pero es potencialmente útil para saber que está ahí y para qué sirve. El regulador de voltaje hace exactamente lo que dice - que controla la cantidad de tensión que se deja en la placa Arduino. Piense en ello como una especie de guardián; se dará la espalda a una tensión adicional que podría dañar el circuito. Por supuesto, tiene sus límites, por lo que no conecta tu Arduino a nada superior a 20 voltios.

*¿Que hace?**

El hardware y el software de Arduino fue diseñado para artistas, diseñadores, aficionados y cualquier persona interesada en la creación de proyectos electronicos.
Arduino puede interactuar con botones, LEDs, motores, altavoces, unidades de GPS, cámaras y hasta una casa en funciones amplias y de poca memoria. eg: Arduino puede controlar las luces y apartos electronicos de una casa con un codigo en el cual se le delimitan funciones basicas aunque ya hay aparatos para prender las luces con un control arduino se puede controlar desde el propio celular facilitando el trabajo de estar prendiendo y apagando las luces.
Algunos modelos de arduinos son:Arduino UNO, Arduino Leonardo, Arduino Due, Arduino Yún, Arduino Robot, Arduino Esplora, Arduino Mega ADK, Arduino Ethernet, Arduino Mega 2560, Arduino Mini, Arduino Nano, Arduino Pro Mini, Arduino Pro, Arduino Micro, Arduino Fio, LilyPad Arduino USB, LilyPad Arduino Simple, LilyPad Arduino SimpleSnap, LilyPad Arduino.

Arduino UNO:	caracteristicas
Microcontrolador: ATmega328
-Voltaje de funcionamiento: 5 V
-Pines I/O digitales: 14 (de los cuales 6 proveen salida PWM)
-Pines de entradas análogas: 6
-Corriente DC por cada pin I/O: 40 mA
-Corriente DC en el pin de 3.3 V: 50 mA
-Memoria Flash: 32 KB (ATmega328) de los cuales 0.5 KB son utilizados por el bootloader
-SRAM: 2 KB (ATmega328)
-EEPROM: 1 KB (ATmega328)
-Velocidad de reloj: 16 MHz

Arduino Robot:caracteristicas
-Microcontrolador: ATmega32u4
-Voltaje de funcionamiento: 5 V
-Pines I/O digitales: 5
-Canales PWM: 6
-Canales de entradas análogas: 4 (de los pines digitales I/O)
-Canales (multiplexados) de entradas análogas: 8
-Corriente DC por cada pin I/O: 40 mA
-Memoria Flash: 32 KB (ATmega32u4) de los cuales 4 KB son utilizados por el bootloader
-SRAM: 2 KB (ATmega32u4)
-EEPROM (interno): 1 KB (ATmega32u4)
-EEPROM (externo): 512 KB (I2C)
-Velocidad de reloj: 16 MHz
-Teclado: 5 teclas
-Perilla: Potenciómetro conectado a un pin análogo
-LCD a color: Comunicación SPI
-Lector de tarjetas SD: Para tarjetas formateadas FAT16

Arduino Mega ADK:caracteristicas
-Microcontrolador: ATmega2560
-Voltaje de funcionamiento: 5 V
-Pines I/O digitales: 54 (de los cuales 15 proveen salida PWM)
-Pines de entradas análogas: 16
-Corriente DC por cada pin I/O: 40 mA
-Corriente DCen el pin de 3.3 V: 50 mA
-Memoria Flash: 256 KB de los cuales 8 KB son utilizados por el bootloader
-SRAM: 8 KB
-EEPROM: 4 KB
-Velocidad de reloj: 16 MHz
