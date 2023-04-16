
# Laboratorio 2 Robotica

### Integrantes: 
- Danilo Enrique Insuasty Delgado.
- Abraham Másmela Ramirez
- Nicolás Prieto Solano
## Descripción de la solución planteada
<p>Usando como base el codigo de RAPID de la practica 1 que escribia las iniciales de los miembros del grupo en el tablero se añade la funcionalidad dentro del codigo tal que al oprimir el boton 1 en el tablero de control del robot se ejecutara la rutina de escribir a la vez prendiendo el LED azul del mismo tablero. Adicionalmente al oprimir el boton 2 se ejecutara una funcion que llevara el brazo del robot a la posicion de mantenimiento.</p>

## Entradas y salidas digitales añadidas al programa.
Se agregaron dos entradas y una salida digital al programa realizado en robotStudio. En el mundo físico las entradas digitales corresponden a dos botones ubicados en la zona de control del robot, mientras que la salida digital representa una luz azul dispuesta también en la misma caja donde se encuentran los botones.
La tabla de entradas y salidas digitales se encuentra en la siguiente imagen

<div>
<p style = 'text-align:center;' align="center">
<img src="https://github.com/NicolasPrietoS/RoboticaLab2_Abraham_Danilo_Nicolas_2023/blob/main/imagenes/imagen%20entradas%20digitales1.png" width="600px" >
</p>
</div>

## Código de condicionales y bucle en rapid.
El código main realizado en rapid se muestra en la siguiente imagen.

<div>
<p style = 'text-align:center;' align="center">
<img src="https://github.com/NicolasPrietoS/RoboticaLab2_Abraham_Danilo_Nicolas_2023/blob/main/imagenes/codigo%20rapid.png" width="300px" >
</p>
</div>

Si la entrada digital (El botón 1) se aprieta y la entrada digital 2 (El botón 2) esta apagado, el robot empieza a realizar el movimiento de escritura y se prende un led, cuando este algoritmo acaba y se aprieta el botón 2, el robot empieza a realizar el movimiento de mantenimiento y se apaga el led




<h2>Videos:</h2>

<h3>1) Videos de funcionamiento del robot:</h3>
  <h4>a) Video 1 (hacer click en la imagen):</h4>
  <a href="https://youtu.be/UBZBv8D7sB0" target='_blank'><img width=500px src="Videos/image_2023-04-15_195242575.png"/></a>
  <h4>a) Video 2 (hacer click en la imagen):</h4>
  <a href="https://youtu.be/Xxzc5nZoff8" target='blank'><img width=500px src="Videos/Miniatura1.png"/></a>
