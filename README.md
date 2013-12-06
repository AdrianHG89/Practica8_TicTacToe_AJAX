![](http://banot.etsii.ull.es/alu3891/fotosstw/tictactoe.jpg)

Práctica 8 - Tic Tac Toe usando AJAX:
===========
 
1. Objetivo
-----------

Extienda la práctica del TicTacToe realizada durante la practica 7 para que la página no se recarge cada vez que el jugador hace click en una de las casillas.

El código Javascript se encargará de que el navegador envíe la jugada elegida por el usuario ""b2". Si la jugada es correcta (la casilla b2 no está ocupada) el servidor retornará al navegador la información necesaria para que pueda proceder a mostrar los movimientos elegidos por el jugador y el computador. En caso contrario el servidor envía un código de jugada ilegal. El código javascript es el que modifica la clase de la casilla a cross o circle de manera adecuada.

Mejore las hojas de estilo usando SAAS. Despliegue la aplicación en Heroku.  


2. Instalación de las gemas
--------------

Instalaremos las gemas necesarias: bundle install o rake install

3. Ejecución
------------

* Para ejecutar desde el local la aplicacion deberemos hacer lo siguiente:

1. En la consola escribir rake. Entonces ahora ya nuestra aplicación esta arrancada.
2. Iremos a 'http://localhost:4567/' en nuestro navegador para poder usar la aplicación y empezar a jugar.

* Para ejecutar con rake SASS:

1. rake css (asi generaremos el fichero style.css)

4. Heroku
------------

	http://tresenraya-stw1314.herokuapp.com/
![](http://i1296.photobucket.com/albums/ag1/adrihg89/heroku3_zps5cc6ffd8.png)

5.Desarrollador
---------------

* Adrián Hernández González - STW - ULL-ETSII
