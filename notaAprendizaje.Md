# Desarrollo de Habilidades de Programación con Recursos Limitados

<img src ="./imagenes/programacion.jpg" width="300" height="300" alt="programacion_habilidad">

## ¿Por qué aprender a programar, aunque no tengamos muchos recursos?

<p>Es esencial porque el conocimiento en programación nos da acceso a herramientas poderosas para resolver problemas en cualquier contexto. Primero, entender cómo funcionan las aplicaciones y los sistemas que usamos todos los días nos permite adaptarnos mejor a un mundo tecnológico que sigue avanzando sin parar. Además, la programación desarrolla nuestro pensamiento lógico y habilidades de resolución de problemas, que son valiosas no solo en tecnología, sino en cualquier área de estudio o trabajo.</p>

## ¿Qué es la programación?

<p>La programación es el proceso de crear instrucciones detalladas que le dicen a una computadora qué hacer, paso a paso. Estas instrucciones se escriben en lenguajes específicos que la máquina puede entender, como JavaScript, Python o C++. Es como escribir una receta, pero en lugar de comida, estamos "cocinando" soluciones, aplicaciones o sistemas que pueden realizar tareas automáticamente.</p>

<p>Programar implica pensar en cómo resolver un problema de la manera más eficiente, traduciendo ideas en código que una computadora pueda ejecutar. Además, la programación no solo es técnica; también es creativa. Nos permite construir desde una simple calculadora hasta aplicaciones complejas, juegos, o programas que manejan datos, y eso puede tener un impacto enorme en cómo vivimos y trabajamos.</p>

## ¿Qué es Javascript?

<img src ="./imagenes/JavaScript-logo.png" width="250" height="250" alt="Javascript">

<p> Es un lenguaje de programación popular que se utiliza para crear sitios web interactivos y dinámicos. Es el "cerebro" detrás de muchas funciones que vemos en una página web, como cuando un botón cambia de color al hacer clic, un formulario valida nuestros datos, o se muestran gráficos en tiempo real. Aunque suele asociarse con el desarrollo web, JavaScript también puede usarse en otros entornos, como en el desarrollo de aplicaciones móviles y de escritorio, e incluso en el control de dispositivos como drones o robots.</p>

## Cómo interactuar con la consola de JavaScript

<img src ="./imagenes/InteraccionConsola.png" alt="Consola Javascript Chrome">

<h2>Guía para abrir la consola de desarrolladores y escribir codigo en javascript</h2>

<p><b>1. Utilizamos nuestro navegador de preferencia. </b></p>

<img src ="./imagenes/navegadores.png" alt="navegadores_preferencia" width="300" height="300">

<p><b>2. Entramos a la siguiente url: <code>about:blank</code> </b>
Nos genera un espacio en blanco para escribir nuestro codigo.
</p>

<img src ="./imagenes/about_blank.png" alt="about_blank_sitio">



## Tipos de datos en JavaScript

<h4>Existen diferentes tipos de datos en JavaScript, los tipos de datos más comunes son: </h4>

 ```javascript
23; // Valor númerico entero.

2.34; // Valor númerico decimal.

"¡Hola, Estudiantes!"; // Cadena de texto con comillas dobles.
`¡Hola, Estudiantes!` // Cadena de texto con comillas invertidas.

true // Valor de tipo booleano (verdadero).

false // Valor de tipo booleano (falso).
```

<h2>Tipos de Variables</h2>

<p>En JavaScript, las variables son espacios de memoria que se utilizan para almacenar valores. Estas variables se pueden crear, modificar y eliminar de la misma manera que las cadenas de texto. </p>

<h4>Ejemplo</h4>

```javascript
var esMayorDeEdad = true; // Crea una variable de ámbito global o de función (dependiendo de dónde se declare), pero no estrictamente "global".

let nombre = "Andres Felipe"; // Crea una variable de ámbito de bloque (local al bloque, bucle o instrucción donde se declara).

const edad = 14; // Crea una variable de ámbito de bloque que es constante, lo que significa que su valor no puede ser reasignado.
```

<h2>Mostrar Valores en Consola</h2>

```javascript

//Ejemplo #1

let nombre = "Andres Felipe"; // Variable declarada.

console.log(nombre); // Muestra el valor de la variable en la consola.

//Ejemplo #2

let edad = 23; // Variable declarada.

console.log(edad); // Muestra el valor de la variable en la consola.

```

<h2>Ejercicio Práctico ⌨️</h2>

<p><b>1.</b> Declara una variable llamada nombre y asígnale como valor tu  primer nombre. Luego, muestra el valor de la variable en 
en consola.
</p>

```javascript
let nombre = "Andres" // Declaramos la variable.

console.log(nombre) // Resultado: "Andres" ✅.
```

<h2>Operadores Aritméticos</h2>

<p>Los operadores aritméticos permiten realizar operaciones aritméticas de suma, resta, multiplicación y división. </p>

```javascript	


let n1 = 25 // Declaramos la variable

let n2 = 13 // Declaramos la variable

let suma = n1 + n2 // Declaramos la variable y sumamos los valores de las variables.
console.log(suma) // Resultado: 38 ✅

let resta = n1 - n2 //Declaramos la variable y sumamos los valores de las variables.
console.log(resta) // Resultado: 12 ✅

let multiplicacion = n1 * n2 //Declaramos la variable y sumamos los valores de las variables.
console.log(multiplicacion) // Resultado: 325 ✅

let division = n1 / n2 //Declaramos la variable y sumamos los valores de las variables.
console.log(division) // Resultado: 1.92307 ✅

let residuo = n1 % n2 //Declaramos la variable y sumamos los valores de las variables.
console.log(residuo) // Resultado: 12 ✅

```

<h2>Ejercicio Práctico ⌨️</h2>

<p><b>2.</b> Declara dos variables, lado1 y lado2, y asígnales un valor entero que represente las dimensiones de un rectángulo. Calcula el área multiplicando ambos lados y muestra el resultado en la consola.
</p>

````javascript

let lado1 = 5 // Declaramos la primera variable del primer lado.
let lado2 = 5 // Declaramos la segunda variable del segundo lado.

let area = lado1 * lado2 // Declaramos la variable y multiplicamos los valores de las variables.

console.log("El area del rectangulo es: " + area) // Resultado: El area del rectangulo es: 25 ✅.

````


<h2>Ejercicio Práctico ⌨️</h2>

<p><b>3.</b> Declara una variable número y asígnale un valor entero. Escribe un código que verifique si número es par o impar, y que te muestre en consola true si es par y false si es impar.
</p>

```javascript

let numero = 5 // Declaramos la variable con el valor entero.

let verificar = numero % 2 == 0 // Declaramos la variable y verificamos si el numero es par.

console.log(verificar) // Resultado: false ✅.

```


<h2>Estructuras de Control</h2>

<p>Las estructuras de control nos permiten controlar el flujo de ejecución de un programa. Estas estructuras de control son:</p>

```javascript


// (if y else) ✅

let edad = 14 // Declaramos la variable

if (edad >= 18){

    // Bloque de instrucciones a ejecutar si la condición es verdadera.
    console.log("Es mayor de edad");

} else {

    // Bloque de instrucciones a ejecutar si la condición es falsa. 
    console.log("Es menor de edad");
}


//(switch) ✅
let nota = 4 // Declaramos la variable

switch (nota) {
    case 1:
        // Bloque de instrucciones a ejecutar si la condición es igual a nota 1.
        console.log("Lo siento, usted ha perdido la nota");
        break;

    case 2:
        // Bloque de instrucciones a ejecutar si la condición es igual a valor2.
        console.log("Lo siento, usted ha perdido la nota");
        break;

    case 3:
        // Bloque de instrucciones a ejecutar si la condición es igual a valor3.
        console.log("Uyy, usted ha aprobado la nota por poco"); 
        break;

    case 4:
        // Bloque de instrucciones a ejecutar si la condición es igual a valor4.   
        console.log("Felicidades, muy bien aprobaste la nota"); // Respuesta correcta ✅
        break;

    default:
        // Bloque de instrucciones a ejecutar si la condición no coincide con ninguno de los valores anteriores. 
        console.log("Esa nota no existe");
        break;   
}
```

<h2>Ejercicio Práctico ⌨️</h2>

<p><b>4.</b> Declara dos variables num1 y num2 y asígnales valores enteros. Escribe un código que compare ambos números y muestre en la consola cuál es el mayor, o si son iguales. 
</p>

```javascript

let num1 = 14 // Declaramos la primera variable con el valor entero.

let num2 = 8 // Declaramos la segunda variable con el valor entero.

if (num1 > num2){

    // Bloque de instrucciones a ejecutar si la condición es verdadera.

    console.log("El primer valor es mayor"); // Respuesta correcta ✅

} else if (num1 < num2){

    // Bloque de instrucciones a ejecutar si la condición es falsa. 

    console.log("El segundo valor es mayor");

} else {

    // Bloque de instrucciones a ejecutar si la condición es falsa. 

    console.log("Los valores son iguales");
}

```

<h2>Bucle o Loops</h2>

<p>Un bucle o loop es una secuencia de instrucciones que se repite un número de veces.</p>

```javascript

//i --> (indice)

// i  --> Es el iterador y se incrementa de 1 hasta que el valor sea 10.

for(let i = 1; i<=10; i++){

    // Bloque de instrucciones a ejecutar.
     console.log(i);
}

```

<h2>Ejercicio Práctico ⌨️</h2>

<p><b>5.</b> Declara una variable llamada número y asígnale un valor entero. Utiliza el ciclo for para que te muestre en consola cada número hasta el valor asignado en tu variable.
</p>

```javascript
for(let i = 1; i<= 15; i++){

    console.log(i) // Respuesta: 1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 11, 12, 13, 14, 15 ✅
}

```

<h2>Funciones</h2>

<p>Una función es un bloque de código que se ejecuta cuando se llama a ella. Las funciones pueden recibir argumentos y devolver valores. </p>

```javascript

//Ejemplo #1

function Saludar(){

    // Bloque de instrucciones a ejecutar.

    return "Hola, estudiantes"; // Devuelve el saludo. ✅
}

Saludar();

//Ejemplo #2

function SaludarEstudiante(nombre, apellido){

return "Hola, tu nombre es "+nombre + " y tu apellido es " + apellido;
}

SaludarEstudiante("Andres", "Felipe"); // Respuesta: "Hola, tu nombre es Andres y tu apellido es Felipe" ✅        
```

<h2>Ejercicio Práctico ⌨️</h2>

<p><b>6.</b> Crea una función llamada doblarNumero que tome un número cómo parámetro, la función debe devolver el doble del número que se le pasa
</p>

```javascript

function DoblarNumero(numero){
    return numero * 2
}

DoblarNumero(5) // Respuesta: 10 ✅
```