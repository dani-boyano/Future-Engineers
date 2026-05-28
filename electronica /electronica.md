# Electrónica:

### Motor trasero unidireccional:

Este mecanismo nos ayuda a poder controlar el robot de manera más rápida y sencilla haciendo posible el desplazamiento del mismo.
### Servomotor:

El servomotor proporciona la fuerza junto a un eje de direcciones que nos permite controlar la orientación del robot de manera curvilínea y unidireccional. Junto al mecanismo anterior podemos controlar el mismo.

Lineas de código usadas:
- #include <Servo.h>: Importa las librerias necesarias para usar el servomotor

### Alimentación

El sistema de alimentación está compuesto por dos baterías de 3.7V modelo TR18650 conectadas mediante un portapilas.
Estas baterías suministran energía a la placa Arduino, los sensores, el servomotor, el motor trasero, entre otros. Además, utilizamos un shield con protoboard integrada que facilita la distribución de energía, la conexión de componentes y la organización del cableado.

### Ultrasonidos

Manda un sonido en una frecuencia demsiado alta para que los humanos lo escuchen y uando lo rcibe calcula la distancia que ha recorrido para saber a que distancia hay una pared

Lineas de código usadas:
- #include <Ultrasonic.h>: Import las librerias necesarias para usar el utrasonidos
- Ultrasonic.read(): Lee a que distancia está la pared y si esta a la deseada.
