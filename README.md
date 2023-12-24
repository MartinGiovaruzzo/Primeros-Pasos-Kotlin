# PrimerosPasosKotlin

JETPACK CON ANDROID STUDIO

Iniciar emulador dentro de Android Studio

Instalar app en smartphone (min 1:04)

Una vuelta por Android Studio

-COMPOSABLE Y MAINACTIVITY

Todo lo que esta dentro del setcontent se va a visualizar en nuestra app.

Surface es el color del background de la app

COMPOSABLE:

Toda funcion que lleve un composable, va a convertir todo lo que tenemos adentro en un componente.

El preview nos sirve para ver como va quedando algo que estamos diseñando sin que le demos al simulador.

-MODIFICADORES

Nos ayudan a personalizar la apariencia y el comportamiento de los componentes.

TENEMOS 4 TIPOS DE MODIFICADORES

-POSICIONAMIENTO Y TAMAÑO

with, height.

-FUNCIONALIDAD

click, scroll

-APARIENCIA

background, padding, border

-ESCUCHA

onKeyEvent

El orden de las funciones si afecta.

-COLUMNAS

Tener en cuenta modularizar lo mas que podamos nuestras funciones.

-FILAS

Tenemos otros tipos de columnas y filas que son la lazy column y la lazy row, que esta para lo que nos sirve es para hacer un scroll en caso de que no nos quepan los elementos en la pantalla.

-LAZYROW -LAZYCOLUMN

-USO DEL ESTADO DE LAS VARIABLES

Las variables que queremos que cambien su valor en tiempo real, vamos a utilizar remember.

La variable no puede estar afuera, tiene que estar si o si en un @composable.

Declaramos la var LIKES by remember { mutableStateOf(valor inicial) }.

El remember lo que hace es recordar el valor anterior que tenia en el estado de la variable.
