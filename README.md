# Future-Engineers
Somos el equipo "az-zaiteros creepers" comformado por Daniel Boyano Lomas, Óliver López MartÍnez y Carmen Cruz Pérez del instituto IES Az-zait. Este cuaderno digital recoge toda la infornación acerca de nuestro robot, los problemas encontrados, la programación y el reto entre otras cosas relativas al proyecto para la realización de la competición World Robot Olimpiad en la categoría de Future Engineers.

Nuestra principal misión ha sido construir y diseñar un vehículo autónomo, siguiendo las indicaciones del torneo. Este vehículo debe de ser capaz de trasladarse de forma independiente, tomar decisiones con sus respectivos senores, entre otros, superando los retos que se proponen en dicho torneo.
## Condiciones previas
Las condiciones necesarias para competir en future engineers son las siguientes:
- Los parámetros del robot tienen que ser los siguientes:
  * 30 cm de largo
  * 20 cm de ancho
  * 30 cm de alto
- Uso de una controladora _Arduino_<sup>tm</sup>
- Uso de materiales propios.
## Objetivo
Este proyecto consta de dos pruebas:
El objetivo de esta primera prueba consiste en dar vueltas alrededor de un centro, dicho centro estará colocado aleatoriamente en el tablero cuadrado que recorreremos, debemos de hacer esto sin que se choque con ninguna pared, a ser posible. Además de corregir automaticamente su dirección. 

En la segunda prueba trataremos de esquivar ciertos obstáculos, con forma de torre, de distintos colores colocados de manera no definida por el tablero. En esta prueba será oportuno el uso de la cámara para poder detectar correctamente dichos colores de manera efectiva, aunque actualmente no disponemos de ella, debido a la falta de tiempo para su correcta programación, para entrenar y ajustarla correctamente.
## Materiales
La estructura del robot fué impresa con PLA de diferentes colores debido a la falta de disponibilidad. Los PLAs implementados son negro para la base, gris para el eje y amarillo ocre para nivelar los motores con la rueda de maneje. También como cerebro del robot usamos una placa de Arduino y un _shield_ con una protoboard encima. Para los detectores usaremos tres ultrasonidos y, finalmente, para la energía usamos un portapilas estandar que funciona con baterías de 3.7 voltios.

Para más información: [materiales](https://github.com/dani-boyano/Future-Engineers/blob/main/materiales/materiales.md)

## Mecánica
Este robot basa su movimiento en un motor trasero unidireccional, dirigido por un servomotor con un rango de 180 posiciones conectado a un complejo sistema de direcciones que regulan la posición de las ruedas delanteras, manejando a su vez la orientación del robot. La base de nuestro vehículo es un chasis impreso en una máquina de 3D, utilizamos este material para facilitar futuras modificaciones. Esta mecánica permite realizar giros precisos, corregir trayectorias y además mantener estabilidad durante el movimiento.

Para más información: [mecánica](https://github.com/dani-boyano/Future-Engineers/tree/main/mecanica)
## Programación
Para la programación en este proyecto hemos empleado Arduino.
En un inicio empleamos dos librerías, una para los ultrasonidos y otra para el servomotor.

Para más información: [programación](https://github.com/dani-boyano/Future-Engineers/tree/main/programacion)
## Problemas encontrados
La colocación del eje fue difícil y tuvimos que hacer varios modelos antes de llegar al actual, tuvimos que arreglar un  problema del eje que provocó que el mecanismo se atascara y no funcionara correctamente. Ciertos PLAs, usados principalmente en el eje, muestran gran fragilidad y poca resistencia a los esfuerzos.

Para más información: [problemas encontrados](https://github.com/dani-boyano/Future-Engineers/tree/main/problemas_detectados)
## Propuestas de mejora
Añadir componentes adicionales como el giroscopio o la cámara, así como mejorar en la participación de la segunda prueba de este proyecto, puliendo su programación asprando a obtener la máxima puntuación.

Para más información: [propuestas de mejora](https://github.com/dani-boyano/Future-Engineers/tree/main/propuestas_de_mejora)
## Electrónica
Nuestro robot cuenta con una fuente de alimentación basada en 2 baterías de 3.7V por ud. modelo TR18650 de 9900mAH, parte de las conexiones están canalizadas energéticamente por un escudo de protección. Además, todas las conexiones están unidas a una placa arduino que tiene una protoboard incorporada en la cual realizamos el cableado de los diversos sensores.

Para más información:[Electrónica](https://github.com/dani-boyano/Future-Engineers/blob/main/Electr%C3%B3nica)
## Conclusiones
En definitiva, todo el proceso de creación de nuestro proyecto para la prueba de future engineers nos ha permitido aprender mucho más que solo competir. Desde la construcción del vehículo hasta la programación y las distintas pruebas realizadas, hemos tenido que trabajar en equipo, resolver errores y mejorar constantemente nuestro diseño para conseguir que funcionara de la mejor manera posible. Gracias a esta experiencia hemos desarrollado conocimientos de robótica, programación e ingeniería, además de habilidades como la creatividad, la paciencia y la capacidad de buscar soluciones ante los problemas que iban surgiendo durante el proyecto.
