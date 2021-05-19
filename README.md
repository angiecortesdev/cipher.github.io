
## Índice

* [1. Criptolove](#1-Criptolove)
* [2. Instalación](#2-Instalacion)
* [3. Objetivos de aprendizaje](#3-Objetivos-de-aprendizaje)
* [4. Definición del producto](#Definicion-del-producto)
* [5. Consideraciones técnicas](#Consideraciones-tecnicas)
* [9. Checklist](#9-checklist)

***

## 1. Críptolove

Criptolove es una aplicación que permite encriptar y desencriptar mensajes para tu amad@, sugar daddy o sugar mommy, nuestro programa funciona con el uso del cifrado cesar para poder encriptar o desencriptar tu mensaje, puedes así obtener un párrafo completo o una frase para que no te descubran mientras escribes a esa persona secreta.

En Criptolove usamos un desplazamiento de 3 posiciones.

Ejemplo:

* La letra A se cifra como D.
* La palabra CASA se cifra como FDVD.
* Alfabeto sin cifrar: A B C D E F G H I J K L M N O P Q R S T U V W X Y Z
* Alfabeto cifrado:    D E F G H I J K L M N O P Q R S T U V W X Y Z A B C

## Diseño:

Para el diseño de nuestra aplicación, iniciamos a hacer un boceto en modo compartido con Figma, procuramos que la paleta de colores fuera armonica y acoorde con el fondo, sin embargo en el proceso hubo una modificacion en la parte de la opacidad del fondo, debido a que es dificil poder ver la letra y los botones para el usuario.

![Pantalla de inicio](./src/assets/inicio.jpeg)

Posteriormente continuamos con el mismo formato y distribucion de los elementos para las pantallas de desencriptado y encriptado, manteniendo la paleta de colores de la pantalla de inicio.

![Pantalla encriptado](./src/assets/encriptar.jpeg)
![Pantalla desencriptado](./src/assets/desencriptado.jpeg)

## 2. Instalación

Si quieres correr el código de este proyecto sigue estas instrucciones:

1. Ingresa a la página:

github.com/angiecortesdev/BOG002-cipher.

2. Haz Fork dentro de la página, esto con el fin de copiar el repositorio en tu GitHub.

3. Ahora debes clonar el codigo mediante el comando:

```
 git clone github.com/angiecortesdev/BOG002-cipher.git.
```

4. Abre el archivo con visual studio code o el editor de tu preferencia.

5. Asegurate de tener instalado node.js. En caso de no tenerlo dirigete a está página:

[node js](https://nodejs.org/en/)

6. Si por lo contrario ya cuentas con node js en tu computadora, ve tu terminal e ingresa el comando:

``` 
npm i (para actualizar los packetes de node)
```

7. Cuando actualicen los paquetes de node, En tu terminal ingresa npm start, podras ver y comenzar a trabajar en el proyecto.

## 3. Objetivos de aprendizaje

Trabajando en parejas aprenderán a construir una aplicación web que interactuará
con lx usuarix final a través del navegador, utilizando HTML, CSS y JavaScript
como tecnologías.

### HTML y CSS

* [X] [Uso de HTML semántico.](https://developer.mozilla.org/en-US/docs/Glossary/Semantics#Semantics_in_HTML)
* [X] Uso de selectores de CSS.
* [X] Construir tu aplicación respetando el diseño realizado (maquetación).

### DOM

* [X] Uso de selectores del DOM.
* [X] Manejo de eventos del DOM.
* [X] [Manipulación dinámica del DOM.](https://developer.mozilla.org/es/docs/Referencia_DOM_de_Gecko/Introducci%C3%B3n)
(appendChild |createElement | createTextNode| innerHTML | textContent | etc.)

### JavaScript

* [X] Manipulación de strings.
* [X] Uso de condicionales (if-else | switch | operador ternario)
* [X] Uso de bucles (for | for..in | for..of | while)
* [X] Uso de funciones (parámetros | argumentos | valor de retorno)
* [X] Declaración correcta de variables (const & let)

### Testing

* [X] [Testeo unitario.](https://jestjs.io/docs/es-ES/getting-started)

### Estructura del código y guía de estilo

* [X] Organizar y dividir el código en módulos (Modularización)
* [X] Uso de identificadores descriptivos (Nomenclatura | Semántica)
* [X] Uso de linter (ESLINT)

### Git y GitHub

* [X] Uso de comandos de git (add | commit | pull | status | push)
* [X] Manejo de repositorios de GitHub (clone | fork | gh-pages)

### UX

* [X] Diseñar la aplicación pensando y entendiendo al usuario.
* [X] Crear prototipos para obtener feedback e iterar.
* [X] Aplicar los principios de diseño visual (contraste, alineación, jerarquía)

## 4. Definición del producto

* ¿Quiénes son los principales usuarios de producto?: Nuestro público objetivo son personas con edades entre 18 a 80.

* ¿Cuáles son los objetivos de estos usuarios en relación con tu producto?: Tener un lugar seguro para poder chatear con tu persona amada.

* ¿Cómo crees que el producto que estás creando está resolviendo sus problemas?: Ya sabemos que para nuestros usuarios es importante su seguridad y sencillez a la hora  del uso.

## 5. Consideraciones técnicas

El boilerplate contiene una estructura de archivos como punto de partida así como toda la configuración de dependencias y tests:

```text
./
├── .babelrc
├── .editorconfig
├── .eslintrc
├── .gitignore
├── README.md
├── package.json
├── src
│   ├── assets
          ├── besos.jpg
          ├── desencriptado.jpg
          ├── encriptado. jpg
          └── inicio.jpg
│   ├── cipher.js
│   ├── index.html
│   ├── encriptado.html
│   ├── desencriptado.html
│   ├── index.js
│   └── css
          └── styles.css
└── test
    ├── .eslintrc
    └── cipher.spec.js
```

### Parte Obligatoria

* [ ] `README.md` incluye info sobre proceso y decisiones de diseño.
* [ ] `README.md` explica claramente quiénes son los usuarios y su relación con
  el producto.
* [ ] `README.md` explica claramente cómo el producto soluciona los
  problemas/necesidades de los usuarios.
* [X] Usa VanillaJS.
* [X] No utiliza `this`.
* [X] Implementa `cipher.encode`.
* [X] Implementa `cipher.decode`.
* [X] Pasa linter con configuración provista.
* [X] Pasa pruebas unitarias.
* [X] Pruebas unitarias cubren 70% de _statements_, _functions_ y _lines_, y un
  mínimo del 50% de _branches_.
* [ ] Interfaz permite elegir el `offset` o _desplazamiento_ a usar en el
  cifrado/descifrado.
* [X] Interfaz permite escribir un texto para ser cifrado.
* [X] Interfaz muestra el resultado del cifrado correctamente.
* [X] Interfaz permite escribir un texto para ser descifrado.
* [X] Interfaz muestra el resultado del descifrado correctamente.

### Parte Opcional: "Hacker edition"

* [ ] Cifra/descifra minúsculas
* [ ] Cifra/descifra _otros_ caracteres (espacios, puntuación, `ñ`, `á`, ...)
* [ ] Permite usar un `offset` negativo.
