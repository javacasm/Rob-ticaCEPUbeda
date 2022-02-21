# Deteniendo nuestro programas hasta que se pulse un botón


Hay 2 formas de detectar las pulsaciones (de los botones o de los pines):

* Con **eventos**, que es como lo hacemos normalmente, y donde se genera un nuevo hilo de programa con nuestro bloques
![](./images/PulsacionEventos.png)

* Desde dentro de nuestro programa con bloques condicionales. También podemos detectar si un botón está pulsado con este bloque condicional  (recordad que la forma hexagonal era para condiciones)
![](./images/BloqueCondicional.png)

Para esperar hasta que se presione, podemos usar el bucle Mientras:

![](./images/BucleMientras.png)

Y como lo que queremos es que espere hasta que se pulse, tendremos que hacer que espere "mientras no esté pulsado", es decir negar la condición, para lo que usaremos el bloque de operador lógico No (Not) 

![](./images/OperadorNot.png)

Poniendo dentro la condición de "Botón B presionado".

En este sencillo [programa](https://makecode.microbit.org/_C6g53V7EvhRC) vamos a contar de 0 a 5 cuando pulsemos el botón A, mostrando cada número hasta que se pulse el botón B. Quedará así:

![](./images/ProgramaEsperaTecla.png)

<div style="position:relative;height:calc(300px + 5em);width:100%;overflow:hidden;"><iframe style="position:absolute;top:0;left:0;width:100%;height:100%;" src="https://makecode.microbit.org/---codeembed#pub:_C6g53V7EvhRC" allowfullscreen="allowfullscreen" frameborder="0" sandbox="allow-scripts allow-same-origin"></iframe></div>

[![Vídeo: Deteniendo la ejecución de un programa hasta que pulsemos un botón con micro:bit](https://img.youtube.com/vi/tCFltkD2VBg/0.jpg)](https://youtu.be/tCFltkD2VBg)


[Vídeo: Deteniendo la ejecución de un programa en la micro:bit hasta que pulsemos un botón](https://youtu.be/tCFltkD2VBg)

