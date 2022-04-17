<!-- Etiquetas Semanticas -->
<article></article>
<aside></aside>
<details></details>
<figcaption></figcaption>
<figure></figure>
<footer></footer>
<header></header>
<main></main>
<mark></mark>
<nav></nav>
<section></section>
<summary></summary>
<time></time>

<br />
Lista de PLUGGINS que pueden instalar a VISUAL STUDIO CODE
<!-- auto close tag  -->
<!-- git lens -->
<!-- prettier  -->
<!-- lorem ipsum  -->
<!-- Live server -->
<br />

Lista de LINKS que van a ocupar al final de la clase para la ultima práctica: El
elemento HTML <input /> se usa para crear controles interactivos para
formularios basados en web para aceptar datos del usuario; Hay disponible una
amplia variedad de tipos de datos de entrada y widgets de control, según el
dispositivo y el agente de usuario. El elemento <input /> es uno de los más
potentes y complejos de todo HTML debido a la gran cantidad de combinaciones de
tipos de entrada y atributos.

<!-- https://developer.mozilla.org/en-US/docs/Web/HTML/Element/input -->
<!-- https://www.w3schools.com/tags/tag_input.asp -->
<!-- https://www.w3schools.com/tags/tag_select.asp -->
<!-- https://www.w3schools.com/tags/tag_textarea.asp -->

Selectores _CSS_

<!-- https://developer.mozilla.org/es/docs/Learn/CSS/Building_blocks/Selectors#tabla_de_referencia_de_selectores -->

Free code Camp / Learn /Usuario con Github

CSS
Herencia esppecificidad y cascada

Selector / declaracion / propiedad / valor asi esta armada una sentencia de CSS

Dimension comunes es Porcentaje aunque se llega a dar la unidad pixel

selector identifican elementos para luego dar propiedades CSS
Tipos de selectores comunes son 3
TIPO <div> </div>
CLASE <div class="clase"> </div>
ID <div id="id"></div>

tag tipo p {  
punto clase .p {
hashtag id #p #p {

Se escribe el codigo en HEAD antes de BODY
CSS propiedad  
 Text-align: "center"
"left"
"right"

padding
margin
div
Border color
border style

Links a:link ejemplo es un link sin visitar
text-decoration

ordena TU CSS.

Combinar tus elementos.

Utilizar selectores descendientes.

utilizar propiedades abrev.

Nombers descriptivos en los selectores.

Prueba diseno en los navegadores.

<!-- Martes 8 de febrero -->

<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Media Queries</title>
    <style>
      body {
        margin: 0;
      }
      /* .medidas-viewport {
        background-color: green;
        height: 50vh;
        width: 50vw;
      } */
      .container {
        background-color: wheat;
        height: 75vh;
        width: 75vw;
      }
      .mitad {
        height: 50%;
        width: 50%;
        background-color: aqua;
      }
      .viewport {
        height: 25vh;
        width: 100vw;
        background-color: brown;
      }
    </style>
  </head>
  <body>
    <!-- <div class="medidas-viewport"></div> -->
    <div class="container">
      <div class="mitad"></div>
      <div class="viewport"></div>
    </div>
  </body>
</html>

---

Float Clear overflow

--> FLOAT
sirve para alinear un elemento con 3 valores left/right/inherit/none en sentido horizontal
Si el elemento no tiene una ancho definido implicita o explicita (<divs>, <img>, <p>, <listas> etc.)
RESTRICCIONES FLOTA / Los que tengan propiedad de texto
<span> </span>
<strong>

Los elementos despues de un elemento con FLOAT fluiran alrededor. en caso que no quisieramos que esto pase usamos la propiedad Clear

-->CLEAR
none / predeterminado , vale todo
Left / Restriccion FLOAT side left
right / Restriccion FLOAT side right
both / Restriccion FLOAT both sides
inherit / Valor heredado del padre

-->OVERFLOW
Si usamos elementos float dentro de un contenedor este se ignora al elemento para sus alto.
ClearFIX se habilita con overflow: auto; que cuenta los elementos flotantes en su height.

Nota 1
cuando los hijo sel contenedor tienen un FLOAT se usara un OVERFLOW

POSITION
Como

## — 2022-01-26

Introduccion

Backend - Frontend que hacen estos personajes.

Servidor es igual a un server.

Cliente - Client.

Hacer un sitio web requiere mucha responsabilidad.

Web Development - Esrtas son las tecnologias.

- HTML Es la estructura - Constructor.

- CSS Formato de estilos - Artista.

- JS Funcionalidad - Mago - Logica.

Web browser - Chrome, Mozilla, Edge,

Herramientas - IDE, editores de codigo - Atom, visual studio code, - Vim.

Emmet - Tecnologia para reducir el tiempo para ejecutar codigos.

Stackoverflow - Lugar para encontrar soluciones relacionado a codigo.

Slack comunicacion / Katas / _instalar VSC_

VSC - Puedes arrastrar un archivo al icono de VSC para poder abrir.

Siguiente tema se entendera que es la terminal, que es git y que es github leer temas.

---

## — 2022-01-27

- **Terminal (linux)**

Depende del sistema operativo, powershell de windows y Linux para mac, _que tan conveniente es usar UBUNTU?`_

— Un directorio es una carpeta, se puede navegar con la terminal, es mucho mas rapido las ejecuciones

— En la terminal no se puede usar el mouse o con click, normalmente se utiliza el teclado

— Una linea de codigo o comando nos permite hacer una accion

— `pwd` Me muestra mi ubicacion dentro de las carpetas. saber mi ubicacion es muy importante.

— `/` Nos indica carpetas, folder o directorio `user/lupita` <---Me indicaque estoy dentro de la carpeta lupita y asi hasta llegar a la ultima carpeta.

— Una extension de archivo define el tipo de archivo que es y me permite saber como tratarlo. (imagenes, videos, textos, word, archivos especiales)

— `ls` Nos listara los archivos que hay en la carpeta

— `ls -a` Nos lista archivos tambien ocultos

— `cd` No permitira movernos entre folders `cd /documentos/carpeta`<--- nos llevara a esta carpeta.

— `cd ..` no regresa un nivel atras de la carpeta

— `clear` Limpia pantalla,

— El teclado tabular o doble fechita nos ayuda a completar algunos comando o intuitivamente el nombre de algun archivo.

— Con las flechas del teclado podemos verlos comandos y poder reutilizar comandos

— `history` me muestra todos los comandos que utilizar

En hostinger puedo encontrar palabras clave= comandos linux terminal 34 basicos.

— `cat <nombreArchivo>`(abrev concatenate) crea un nuevo archivo

— `cat NameArch1 NameArch2>NameArch3` une dos archivos (1 y 2) y almacena la salida de ellos en un nuevo archivo (3)

— `grep` `find` `Locate` Quieres seber como buscar un archivo con estos comandos.

- **github**

— Historial de versiones, git nos permite llevar un control de versiones git es el programa que nos puede ayudar con esto.
instalar git, se puede hacer de la siguiente manera

— `git --version` Nos muestra la version de nuestro y git nos permite saber si tenemos git en la pc.

— `git update` para actualizar nuestro git por mantenimiento es necesario darse un tiempo para actualizar dicho tema.

— Nos ayudara gestionar nuestro protafolio

— Para instalar en mac es con Homebrew.

—

Como hacer tu repositorio

---

## — 2022-01-28

---

## — 2022-02-01

---

## — 2022-02-02

---

## — 2022-02-XX

---

## — 2022-02-03

---

## — 2022-02-08

---

## — 2022-02-09

---

## — 2022-02-10

---

## — 2022-02-14

--

## — 2022-02-15

---

## — 2022-02-16

---

## — 2022-02-17

---

DEVF/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

https://docs.github.com/es/repositories/working-with-files/managing-large-files/about-git-large-file-storage
https://docs.github.com/es/repositories/working-with-files/managing-large-files/about-large-files-on-github

> > > > > > > > 2a2b87752fe50649d38f11ad32deb9b46dbaaf16:Notas html.txt

---

<!-- Los Formularios inician con -->
<form></form>
<!-- Todos su atributos son opcionales Pero es practica standard Establecer primero al menos  -->
primero action="" method=""

<!-- Elementos comunes en formulario -->
<input type="text" />
<textarea name="" id="" cols="30" rows="10"></textarea>
<select name="" id=""></select>
<label for=""></label>

para funcionar todo esto necesito un submmit.

---
