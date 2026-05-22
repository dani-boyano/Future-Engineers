# Future-Engineers
Somos el equipo "az-zaiteros creepers" comformado por Daniel Boyano Lomas, Óliver López MartÍnez y Carmen Cruz Pérez del instituto IES Az-zait y este es nuestro cuaderno digital de la WRO donde hablaremos acerca de nuestro robot, los problemas encontrados, la programación y el reto entre otras cosas relativas al proyecto.
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
El objetivo de esta primera prueba consiste en dar vueltas alrededor de un centro que estará colocado aleatoriamente en el tablero cuadrado que recorreremos, debemos de hacer esto sin que se choque con ninguna pared, a ser posible.
En la segunda prueba trataremos de esquivar unos obstáculos de distintos colores colocados aleatoriamente.
## Materiales
La estructura del robot fué impresa con PLA de diferentes colores por falta de disponibilidad. Los PLAs usados son negro para la base, gris para el eje y amarillo ocre para nivelar los motores con la rueda de maneje. También como cerebro del robot usamos una placa de Arduino y un _shield_ con una protoboard encima. Para los detectores usamos tres ultrasonidos y, finalmente, para la energía usamos un portapilas estandar que funciona con baterías de 3.7 voltios.

Para más información: [materiales](https://github.com/dani-boyano/Future-Engineers/tree/main/materiales)

## Mecánica
Este robot basa su movimiento en un motor trasero unidireccional, dirigido por un servomotor con un rango de 180 posiciones conectado a un complejo sistema de direcciones que regulan la posición de las ruedas delanteras, manejando a su vez la orientación del robot.

Para más información: [mecánica](https://github.com/dani-boyano/Future-Engineers/tree/main/mecanica)
## Programación
Para la programación en este proyecto hemos empleado Arduino, en un inicio empleamos dos libreriías, para los ultrasonidos y para el servomotor.

Para más información: [programación](https://github.com/dani-boyano/Future-Engineers/tree/main/programacion)
## Problemas encontrados
La colocación del eje fue difícil y tuvimos que hacer varios modelos antes de llegar al actual, tuvimos que arreglar un  problema del eje que provocó que el mecanismo se atascara y no funcionara correctamente. Ciertos PLAs, usados principalmente en el eje, muestran gran fragilidad y poca resistencia a los esfuerzos.

Para más información: [problemas encontrados](https://github.com/dani-boyano/Future-Engineers/tree/main/problemas_detectados)
## Propuestas de mejora
Añadir componentes adicionales como el giroscopio o la cámara, así como mejorar en la participación de la segunda prueba de este proyecto, puliendo su programación asprando a obtener la máxima puntuación.

Para más información: [propuestas de mejora](https://github.com/dani-boyano/Future-Engineers/tree/main/propuestas_de_mejora)
## Electrónica
## Conclusiones
En definitiva, hemos desarrollado un proyecto desde 0, en el cual comprendemos el funcionamiento de un robot cuyo programa realiza el objetivo de la WRO de Future Eingnieers.
