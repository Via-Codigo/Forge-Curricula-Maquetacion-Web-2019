# Notas sobre toda la sección 9 (JAVASCRIPT)


## Intro 

**JavaScript** ("JS" for short) is a full-fledged dynamic programming language that, when applied to an HTML document, can provide dynamic interactivity on websites. It was invented by Brendan Eich, co-founder of the Mozilla project, the Mozilla Foundation, and the Mozilla Corporation.

**Existen 2 JavaScripts**: El de los clientes y el de los servidores. Y hay una gran diferencia entre ambos. ¿Recuerdan qué es un Servidor? Pues tan simple como una computadora a la que podemos acceder a través de internet, utilizando probablemente un Dominio o una IP. Si el lenguaje de JS se ejecuta en el servidor y 3 personas entran a esa misma página, todos estarían llamando al mismo archivo, que está en el servidor. En cambio, el JS del cliente (que es el que se usa más para la programación web), se descarga junto con el HTML y se ejecuta en el cliente de quien lo descargó. Entonces, lo que estamos ejecutando en el navegador, es en realidad una copia del código que está online. Y una vez que ya se lo enviamos (nosotros como servidor) al cliente, ya está en sus manos la ejecución. 

**JavaScript es muy versátil: ¿Qué se puede hacer con JS?**. You can start small, with carousels, image galleries, fluctuating layouts, and responses to button clicks. With more experience, you'll be able to create games, animated 2D and 3D graphics, comprehensive database-driven apps, and much more!


**Algunos ejemplos** : webs a mostrar.  

**Diferencias entre HTML, CSS y JS:** Para entender cómo funciona JS tenemos que entender que el HTML y el CSS son lenguajes de maquetación simples y JS es un lenguaje de programación completo con funcionalidades mucho más complejas. [continuar diferencia]

## ¿Cómo comenzamos a usar JS?

**JS File vs Console**

**Script Tag**

**Primeros Ejemplos**: Aquí podríamos hacer console.log("mensaje"), alert("mensaje"), y tal vez un document.querySelector('h1') y element.textContent = "mensaje". 

## Primeros conceptos de programación: 

**Variables**: const, let (history var)

**Operators**: Addition, Substraction, Multiplication, Division, Exponent, Asignment, Equality, Not, Does-not-equal, [less-than, more-than, less-than-or-equal, more-than-or-equal, or, and, remainder, ++, --, +=, -=, *=, /=]

**Types**: String, Number, Boolean, [Array, Object, Functions]

**Comments**: 1000000 times more important here

**Conditionals**: if, else if, else, ternary operators

**Loops**: for, while, [ forEach, ]

**Functions**: arrow, normal, saved in variable, IEF, etc.

## DOM & other JS internals

**Events**




## -- General concepts we need to put in the middle of that -- 

- String scaping characters, concatenation, numbers vs strings
- Variable Typing vs Typed languages
- Strings as objects (string.length), string[0], string[string.length-1] [See this.](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/First_steps/Useful_string_methods)
- Arrays [See this.](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/First_steps/Arrays)
- Method vs Function
- Functions Lexical Scope, Global Variables, Local Variables
- Memory Usage (flow of execution)
- ¿Should we use Canvas API to test some things like math as game design?

## [JS Building Blocks](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Building_blocks) 

- [Making decisions in your code — conditionals](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Building_blocks/conditionals)
- [Looping code](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Building_blocks/Looping_code)
- [Functions — reusable blocks of code](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Building_blocks/Functions)
- [Build your own function](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Building_blocks/Build_your_own_function)
- [Function return values](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Building_blocks/Return_values)
- [Introduction to events](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Building_blocks/Events)

## [Introducing JavaScript objects overview](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Objects)

- [Object basics](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Objects/Basics)
- [Object-oriented JavaScript for beginners](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Objects/Object-oriented_JS)
- [Object prototypes](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Objects/Object_prototypes)
- [Inheritance in JavaScript](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Objects/Inheritance)
- [Working with JSON data](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Objects/JSON)
- [Object building practise](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Objects/Object_building_practice)
- [Assessment: Adding features to our bouncing balls demo](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Objects/Adding_bouncing_balls_features)

## (y si alcanza el tiempo... )

- [Client-side web APIs](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Client-side_web_APIs)
- Introduction to web APIs
- Manipulating documents
- Fetching data from the server
- Third party APIs
- Drawing graphics
- Video and audio APIs
- Client-side storage
