# ![alt text](https://assets.breatheco.de/apis/img/images.php?blob&random&cat=icon&tags=breathecode,32)  The Postcard

Who does not like postcards? This is one of your first exercises (if not the first) and it's fun and relatively easy :)

Lets create a postcard with HTML5 and CSS and then you can share it with your mom or with your other half, she/he is going to be proud! :)

## 🌱  How to start this project.

This project comes with the necessary files to start working, so you just need to clone its repository to start. You have two options for that:

a) Most 4Geeks students should open this project with Gitpod by simply clicking on the link: https://gitpod.io#https://github.com/breatheco-de/exercise-postcard.git
	
+ If you do not have a Gitpod account yet, please register with your Github username at: https://www.gitpod.io/ 

+ You can start your Github account at:  https://github.com/
 
b) Only if the method above is not possible, and you need to work locally in an IDE on your computer, you can clone the project by running the below command in the terminal of your IDE: 

```
$ git clone  https://gitpod.io#https://github.com/breatheco-de/exercise-postcard.git 
```

The exercises will start and show the instructions automatically but if you encounter any issues you can try running them manually by typing in your command line the following:

```
$ learnpack start
```

## Instructions

Create the HTML and CSS needed to replicate [this exact same picture](https://raw.githubusercontent.com/breatheco-de/exercise-postcard/main/.learn/assets/preview.png).

![postcard preview](https://raw.githubusercontent.com/breatheco-de/exercise-postcard/main/.learn/assets/preview.png)

Here is the url for 4Geeks logo: [https://github.com/breatheco-de/exercise-postcard/blob/main/.learn/assets/4geeks.png?raw=true](https://github.com/breatheco-de/exercise-postcard/blob/main/.learn/assets/4geeks.png?raw=true)

## Create by drawing your strategy

![Postcard Strategy](https://github.com/breatheco-de/exercise-postcard/raw/main/.learn/assets/strategy.gif?raw=true)

## What to do if you are stuck?

There is a video about this exercise, watch it if you are lost. But don't copy everything, try to code some of your own.

## Fundamentals
This exercise covers the following fundamentals:
1. Basic structure for every HTML5 website.
2. The *Link* tag to import CSS Rules.
3. Using google fonts.
3. Using the different selectors available in CSS.
4. Working with boxes: border, padding and margins.
5. Overflow.
6. Using a simple form


EXPLICACIÓN DE CÓMO HICE EL EJERCICIO:

·HTML:
Dividí el contenido de la postal en varios divs.
En el head, puse el link de google fonts para poder cambair el estilo de la letra.

Uno general que abarca toda la postal, para poder separarla del resto del body, que es el de la class "postcard".

Luego dividí el contenido de ese div en las tres partes de la postal (header, body y footer).

-postcard-header: dentro puse el título de la postal y el logo.

-postcard-body: volví a dividir este div en dos divs distintos, uno para la parte izquierda del contenido del body, y otro para la parte derecha; para poder luego en CSS referirme a todo el contenido de cada uno. 

-postcard-footer: en este div va el botón.


·CSS:
Empecé poniendo el fondo del body en negro, luego me referí a el div general (.postcard) y le puse el fondo blanco, ajusté el tamaño con el width y heigth, luego usé margin:auto para que se centrara horizontalmente, y el margin-top para centrarla verticalmente. Después cambié el tipo de fuente y el tamaño con font-size.

-header: usé display:flex para que el contenido se colocara uno al lado del otro, luego le di margen de los lados y quité en margen inferior para que el texto del body estuviera más cerca.
Luego ajusté el tamaño del logo y le di margen de arriba. Y con el <h1> lo que hice fue ajustarlo con el margen de arriba, amplié el tamaño de las letras y le puse margen derecho para mover el logo.

-body: igual que en header, usé display:flex y usé los márgenes y el padding para ajustar el body left y right y que se vieran como en la postal del ejemplo. Y lo mismo hice con el input del body right.

-footer: le dejé solo el borde del final y puse el color y el padding para que fuera lo más parecido al ejemplo.





