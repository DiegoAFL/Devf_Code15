# Notas por limpiar

---

```html
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
```

```html
<br />

<br />
```

---

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

---

### Selectores _CSS_

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
      /*.medidas-viewport {
        background-color: green;
        height: 50vh;
        width: 50vw;
}*/
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

# **NOTAS DEVF** ———————————————————

## — **2022-01-26** ———————————————————

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

## — **2022-01-27** ———————————————————

### **Terminal (linux)**

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

#### **Git & Github**

— Historial de versiones, git nos permite llevar un control de versiones git es el programa que nos puede ayudar con esto.
instalar git, se puede hacer de la siguiente manera

— `git --version` Nos muestra la version de nuestro y git nos permite saber si tenemos git en la pc.

— `git update` para actualizar nuestro git por mantenimiento es necesario darse un tiempo para actualizar dicho tema.

— Nos ayudara gestionar nuestro protafolio

— Para instalar en mac es con Homebrew.

— Git es la tecnologia y github es la aplicacion que ayuda a gestionar remotamente git. Hay muchas plataformas la mas famosa es github.

— Realizar cuenta con un correo y una cuenta

— `git config --list` nos puede listar nuestra configuracion en git (repositorio local)
user.email=diego-afl@outlook.com / user.name=DiegoAFL asi podremos modificar en caso de que lo necesites.
cuando se instale git se tendra que dar de alta estos datos.

```
git config --global user.name "John Doe"
git config --global user.email johndoe@example.com

```

### Como conectar repositorio remoto con local pasos

**El objetivo** es vincular una carpeta

→ 1. Abrimos terminal o gitbash

→ 2. En terminal nos ubicamos en la carpeta con los comandos (puede utilizar CD por si tienes algun conflicto.) recuerda el sensitive case(mayusculas).

→ 3. Escribiremos el siguiente comando `$ git init` se debe transformar nuestra carpeta a master o main

Nos sirve para iniciar nuestra carpeta en git y los comandos git solo funcionan en carpetas con `git init` (otra forma de ver es que se marca como main o master)

Se puede inicializar carpeta sin la ayuda de la terminal selecciona carpeta y click derecho > gitbash here > se abre terminal

→ 4. `$ echo textitos > NameArch.txt` genera en la ubicacion un archivo junto con contenido.

→ 5. `git status`

→ 6. `git add .` prepara los archivos para almacenar en el historial de cambios.

→ 7. `git commit -m "mensaje"` Es para preparar los archivos y guardar en el historial (repositorio local)

**Finalizamos** en nuestro espacio de trabajo local (computadora) ahora nos iremos a github.

→ 1. Crea nuevo repositorio, nombrar y escribir descripcion.

→ 2. Ahora nos saldra algunos pasos para vincular solo se requiere copiar / un consejo o buena practica es agregar el readme.md (archivo markdown).

→ 3. `git remote add origin <urlgithub_server>` **>** `git branch -M main` cambia nombre del antiguo master por main **>** `git push -u origin main`

→ 4. Listo nos mostrara en git hub los archivos listos.

→ 5. Recuerda leer y verificar cuando te diga quien eres `$ git config --global user.name "username"`→`$ git config --global user.email user@example.com`

Etapas de git = es importante entender esta logica pues nos ayudar a ubicar el status de nuestro trabajo.

_working directory_ **→** `git add` → _staging area (index)_ **→** `git commit` → _Repository (local) (se ubica en head)_

- Links guias

[guia git/ github modo dummie](https://rogerdudler.github.io/git-guide/index.es.html).

[Bash para principiantes](https://towardsdatascience.com/basics-of-bash-for-beginners-92e53a4c117a)

---

## — **2022-01-28** ———————————————————

_git_ - Es un controlador de versiones recuerdalo.

_github_ - Plataforma en nube que alamacena y gestiona nuestro repositorio local

pasos para subir mi repositorio local a repositorio remoto una vez modificado

→ 0. Nos ubicamos en carpeta conectada con github y save en VSC

→ 1. `$ git add .` o `$ git add <nameArch>`

→ 2. `$ git status` verificar si hicimos lo correcto

→ 3. `$ git commit -m "mensaje"`

→ 4. `$ git push origin main`

Hacemos un archivo **HTML** y lo agregamos en una carpeta

— `$ mk dir <NameFolder>` hacer una carpeta nueva en nuestra ubicacion

— tag o etiquetas ▬ html es un lenguaje basado en etiquetas y si revisamos cada uno es un contenedor de acciones.

— Inspeccionamos una pagina web _→_ click der _→_ inspeccionar _→_ ir a **Elements**

— w3 school es una pagina donde puede apoyarnos a entender nuestras tecnologias.

— Las etiquetas se abren y se cierran. o solamente cuenta con una etiqueta

— VSC se pueden colocar unos comentarios

---

— *Ver en*→ /01_IntroHtml/ index_EJ.01.html **ejercicio en html**

**→** Se toco el temas de etiquetas en HTML → si son etiquetas con apertura y cierre

**→** Los atributos son muy importantes en algunas etiquetas, pueden ser obligatorias en unas y opcionales en otras, tambien adicionar alguna ejecucion.

**→** VAMOS A CREAR UN SITIO WEB - Blog de viajes - Con media queries o diseno responsivo

---

— *Ver en*→ /02_IntroHtml_Ej.01 **ejercicio en html**

_1._ Crear una pagina personal donde se muestre algunos datos como:

- Nombre
- Ocupacion
- Hobbies

_2._ Add 2 imagenes

- UNO con atributos clasicos
- DOS que al darle click me lleve a otro lado

_3._ Insertar ligas que lleven a redes

- Que se abran en pesetanas diferentes

_4._ Usar 5 etiquetas mas que no se hayan explicado.

_5._ Utilizar etq <a> para ir a una pagina llamada contacto.html

---

## — **2022-02-01** ———————————————————

- INTRO A LA WEB / Recap git y github glosario intro

_→_ Repositorio / repo — Base de datos donde se almacena el historial del codigo

_→_ Branch / Rama — Entorno o espacio de trabajo independiente en git

_→_ Commit — Registro de uno o varios cambios hechos en el repositorio

_→_ Master — Rama principal de un repositorio

_→_ Stage — Lista de archivos que se usaran para un commit

_→_ Checkout — Es la accion de moverse entre diferentes ramas.

_→_ Fork — Copia bifurcada de un repositorio

_→_ Merge — Combina dos o mas ramas en una

_→_ `ctrl + shft + p` Para abrir comando y teclear loremp ipsum

**Como clonar un repositorio**

1.  `git clone <urlgithub>` Clonaremos una rama

2.  `git checkout -b <NombreBranch>` hacemos una rama y vamos esa rama esto en la carpeta local actual

3.  Ahora vamos a git hub para crear una rama nueva vamos a repositorio remoto → code → Main → Despliegue → Nombrar rama _verificar los permisos_

4.  Ahora nos ensena a hacer un _pull request_ a repositorio remoto desde nuestro local.

---

**Elementos DIV y etiquetas semanticas.**

— Iremos a web browser → Inspeccionar → Elements

— `<div></div>` nos hacen divisiones de contenido de manera virtual.

— Div = Division se usa para dividir el contenido en secciones (son contenedores)

— La anidacion de DIV puede provocar un caos en las paginas.

— _Elemento semantico_ da significado a navegador, motor de busqueda, desarrollador, determina el contexto de contenido web.

**Estas son etiquetas semanticas (es mejor que usar solo divs)**

```html
<!-- Etiquetas semanticas -->

<header></header>
<!-- Titulos o logos de identidad -->

<nav></nav>
<!-- Barras de navegador -->

<main></main>
<!-- Especifica el contenido principal de un documento -->

<section></section>
<!-- Define seccione en un documentos -->

<article></article>
<!-- Nos sepra elementos independientes que estan contenidos en <section> Textos principalmente / Puede tener atributos estandares globales -->

<aside></aside>
<!-- Define contenidos laterales / representacion de una seccion  -->

<figcaption></figcaption>
<!-- define una captura de un elemento <figure>  define un texto coherente y complementario mara a documento y elemento y asi definir un titulo para la foto / Puede colocarse como primer o ultimo hijo del elemento -->

<figure></figure>
<!-- Imagenes  ilustraciones, diagramas, photos, code listings-->

<mark></mark>
<!-- Marcador (tipo fluorescente) se debe colocar en css sus caracteristicas luego en html marcar el contenido (texto) -->

<time></time>
<!-- define fechas y horario -->

<details></details>
<!-- contenido que que el usuario puede ver u ocultarse -->

<summary></summary>
<!-- define un encabezado visible para el elemento <detalles> . Se puede hacer clic en encabezado para ver/ocultar los detalles. -->
<!-- El <summary> elemento debe ser el primer elemento secundario del elemento <details>. -->

<footer></footer>
<!-- Pie de pagina / notas legales / Agradecimientos / Site map -->
```

**Lista de PLUGGINS que pueden instalar a VISUAL STUDIO CODE**

auto close tag
git lens
prettier
lorem ipsum
Live server

**Ejercicio** (ir a archivo)[/03_IntroHtml_Practica]

Para hacer este ejercicio en devf se realizo una rama (div clases) el cual no se realizo.

_→_ Estructurar bosquejo para el proximo proyecrto.

_→_ Hacer un archivo coloreando backgrounds o colocar contornos.

**Formularios** introduccion para

Todos los formularios comienzan comienzan con un `<form></form>`

```html
<form action="/myhandking-form-page" method="post">aqui va otra etiqueta</form>
```

_→_ Todos los atributos son opcionales , practica estandar establecer _action_ y _method_.

_→_ Los elementos comunes en un formulario son _input_, _textarea_, _select_ y _label_ estos son para recolectar la informacion de cierto tipo.

_→_ Action nos dice a que pagina vamos a enviar formulario server o etc.

_→_ Method en que tipo de metodo se envia esta informacion. `get` o `post

_→_ `get` Cuando lo enviamos se envia directo de la URL es visible para un usuario.

_→_ `post` Lo envia por debajo por un canal oculto no es visible para el usuario. Correo o contrasenas

_→_ Todos los form debe tener un submit pues no puede enviar informacion.

**git y github** Como se cerro la rama que andaba por ahi volando.

_→_ Y con esto la rama que habia quedado se le hizo un merge (pullrrequest) a la rama main poco explicado pero ya estudiado.

_→_ No todos los que hacen PR tienen autorizacion para para ejecutarlos hay formatos de trabajo que dictan como se realiza este proceso.

---

## — **2022-02-02** ———————————————————

**Formularios / Css / Selectores**

Formulario es la interacción que tenemos con los usuarios hay que dominarlo y es un ingreso de datos

_1._ Inicia con <form> que activa el espacio de los formularios y dentro debe ir un INPUT y es por una funcion en especifico.

_2._ <Method> son get y post

_3._ <Action>

_4._ Un _form_ funciona con botón tipo `submit`

**Ejercicio** (ir a archivo)[/00.Index_Form.01.html]

_-_ Empecemos con form → action hacemos una url nos enviará a contacto →

_-_ Method get

_-_ Botón tipo summit con nombre enviar

_-_ Haremos <input > haremos la básica de texto pero hay varios por aprender ponerle name es para identificarlo y además le pondremos un id este debe ser único no se repite name y id pueden ser iguales pero atraves de los demás apartados de código id no se debe repetir

_-_ Si nos fijamos en el web browser, se ven las acciones → _url_ ahora de accionar

_-_ Los input aceptan cierto tipo de información hay algunos que aceptan texto o números.

_-_ _Method post_ Revisamos en (antes de ejecutar para que lo detecte) → Inspeccionar → Nertwork → pestaña _Name_ verificamos hacia donde dirige el _action_ del <form> que buscamos → _Payload_ y encontramos debajo toda la informacion enviada (verificar mas informacion adelante)

_-_ El Input email debe estaren este apartado con el atributo `method="post"`

_-_ El formulario de `tipo Get` se mira como en la Url aprecia la concatenación

_-_ El formulario de `tipo post` Se esconde la informaciona a enviar pero se puede ver en la consola network → `payload`

_-_ <Labels> etiqueta como su nombre lo dice al input

_-_ <Input>hay varios tipos y llevan _etiqueta de cierre_:

<input type="button">

<input type="checkbox">

<input type="color">

<input type="date">

<input type="datetime-local">

<input type="emial">

<input type="file">

<input type="hidden">

<input type="image">

<input type="month">

<input type="number">

<input type="password">

<input type="radio">

<input type="range">

<input type="reset">

<input type="search">

<input type="submit">

<input type="tel">

<input type="text"> este es un valor por defecto.

<input type="time">

<input type="url">

<input type="week">

_-_ Y todas esta eiquetas estan en el archivo: 00.Index_Form.01.html

**CSS HOJAS DE ESTILOS EN CASCADA**

Parte de un concepto simple y muy potente: aplicar estilos (colores, fcormas, margenes, etc ...) a **uno o varios documentos**.
sin CSS una pagina web seria un simple documento de texto.

_-_ Es el formato que se le puede dar al producto web.

_-_ La idea de CSS es utilizar el concepto de \*\*Separacion de presentacion y contenido, intentando que los documentos HTML solo incluyan informacion y datos.

_-_ Los tres pilares del CSS

1. **HERENCIA**

Los hijos heredan estilos de sus padres, asi no necesitas escribir esto para todo

```css
body {
  color: blue;
}
h1 {
  color: blue <!-- no es necesario definir un color de texto para todos los;
}
/* titulos pues son heredados de body */
```

2. **ESPECIFICIDAD**

Cuando hay conflictos de estilos el navegador aplica solo el de mayor especificidad.

```css
.parrafo {
  colo: blue;
}
.article .parrafo {
  color: red;
}
/* el parrafo es rojo por que el segundo selector es mas especifico */
```

3. **CASCADA**

Todo esstilo sobnre escribe a uno anterior. La C de CSS significa cascada

```css
.parrafo {
  color: blue;
}

.parrafo {
  color: blue;
}
/* El parrafo es rojo por que sobreescribe a los anteriores estilos */
```

**ESTRUCTURA COMUN CSS**

Selector→ → → Declaration → → Declaration

`h1` → → → → `{color:blue;` → `font-size:12px;}`

→ → → → → Property → Value

cerrar con punto y coma para cerra declaracion.

las declaraciones se cierran en llaves.

**CSS impor**

Unidades de medidas que se ocupan en CSS las comunes son porcentajes y pixeles

_-_ Los **selectores** se identifican a un elemento dentro de la pagina web, para leugo poder definir sus propiedades. Pueden ir desde el simple nombre de etiquetas hasta combinaciones complejas.

_-_ Diferentes tipos de **Selectores** conocerlos nos ayudara a encontrar la herramienta adecuada para nuestro proyecto

_-_ 3 tipos comunes de
selectores y son:

1. De tipo `<div></div>`

2. De clase `<div class="clase"> </div>`

3. De ID `<div id="id"> </div>`

DE TIPO

```css
p {
  color: red;
  text-align: center;
}
```

DE CLASE

```css
#p {
  color: red;
  text-align: center;
}
```

DE ID

```css
.p {
  color: red;
  text-align: center;
}
```

**Unificar o concatenar estilos**

```css
h1 {
  color: blue;
}
.ide {
  color: blue;
}

/* puede ser asi, de esta maner si se desea unificar el estilo */
h1,
.ide {
  color: blue;
}
```

Hay selectores para atributos y se indica asi.

```css
a [atributo] {
  color: blue;
}
```

**TIPOS DE SELECTORES**

1. Selector de Tipo → `h1 {declaration}`

2. Selector universal → `* {declaration}`

3. Selector de clase →`.class {declaration}`

4. Selector de ID → `#unico {declaration}`

5. Selector de atributo → `a[title] {declaration}`

6. Pseudoclase → `p: first-child { declaration}`

7. Pseudo elemento → `p::first-line {declaration}`

8. Operador de combinacion descendentes → `article p`

9. Operador de combinacion de elementos hijos → `article > p`

10. Operador de combinacion de elementos hermanos adyacentes → `h1 + p`

11. Operador de combinacion general de elementos hermanos → `h1 - p`

_-_ Leer documentacion de w3schools

_-_ Buena practicas buscar **eniun.com**

_-_ Etiquetas CSS de tipo de alinear **(CSS ALIGN)**

_-_ CSS veremos a profundidad en la siguiente clase acerca de PADDING → MARGIN

_-_ Estilo puede ser inline external y reference

_-_ CSS Color se usan diferentres formatos y si se busca transparencia y sombreados revisar y colocar en el archivo de practica.

_-_ CSS Links hay distintas declaraciones que permiten formateear los links

_-_ Vamos a el archivo → **01.index_css.00.html**

Recuerda ejecutar la mejores **practicas de CSS**

_1._ Organizar la estructura de arriba hacia abajo

_2._ Nombrar correctamente los selectores

_3._ Separar las palabras mediante guiones o mediante mayúsculas

_4._ Legibilidad

_5._ Combinar elementos

_6._ Utilizar selectores descendientes

_7._ Utilizar propiedades abreviadas

_8._ Utilizar nombres descriptivos en los selectores

_9._ Evitar utilizar como nombre de un selector una característica visual

_10._ Probar el diseño en los diferentes navegadores

_11._ Validar el código CSS

_12._ Agregar los prefijos de los navegadores en propiedades que no sean estables

---

## — **2022-02-XX** ———————————————————

**CSS** INTRO

— WWW.W3SCHOOLS.COM HAY EJERCICIOS Y TAMBIEN EN FREECODE CAMP.

— Minuto 10 continuar mañana.

— **05_IntroCSS_Blog** es donde se trabajo el css del blog que previamente llenamos de datos

— Un a buena practica es crear carpeta con un archivo style.CSS

**BOX- MODEL**

— Se lle llama modelo de caja por que en los navegadores todo se contruye a partir de cajas.

— No exxisten elementos triangulares,redondos, poligonales,etc.

— Haremos con propiedad outlines en el area de inspeccion del web browser facilitaremos la visualizacion de los borddes de la siguiente manera.

_1._ Abrir un Ventana en un navegador
_2._ Click derecho → Inspeccionar
_3._ Posicionarte en la seccion tag → style no mejor en head hasta el final
_4._ Click derecho → Edit HTML
_5._ Colocar `<style> * {outline: 1px solid red;} </style>` salimos con un click al exterior
_6._ Con esto analizas las cajas o el diseño de las paginas.

Areas de modelo de caja

- Cada elemento HTML es una caja que se compone de _4_ ladosy se compone de 4 areas
  por orden de color describiremos a que pertenecen

El sentido logico es **TOP** → **RIGHT** → **BOTTOM** → **LEFT**

— Figure es una propiedad adicional de model box

_→_ INTERNO

#8CB3C0 → Content/

<!-- Contenido donde aparacen texto, imagenes, etc-->
<!-- El tamaño se puede modificar: --> height | widh | max-heigh | Max-width | Min-heigh | Min-width
<!-- Cuando se estable la anchura o altura afecta al contenido de la caja, no a la caja completa -->

#C5CB89 → Padding/

<!--  distancia del borde hacia dentro-->
<!-- Transparente , separacion o interior entre contenido y borde de la caja -->
<!-- al seguir diendo parte visible de la caja si hay color o imagen de fondo este se extendera a travez del padding -->
<!-- Modificaciones de padding --> padding | padding-top | padding-bottom | padding-left | padding-right

#FEDB99 → Border/ con este color identificamos en el panel de inspeccion.

<!-- Es la linea que rodea la caja, se utilica para una apariencia estetica a la caja -->
<!-- Permite dibuhjar una linea de color -->
<!-- Props basica de bordes --> border-style | border-width | border-color
<!-- Podemos agruparla en unica propiedad --> → border ←

#000000 → Linea (border)

<!-- estilos de linea -->

/ none / dotted / dashed / solid / double / groove / ridge / inset / outset

_→_ EXTERNO

#FCCE9B → Margin/

<!-- Separacion entre una caja y cajas adyacentes ultima area de box model -->
<!-- Contrario a padding al definir color o imagen de fondo, no se propaga a esta seccion -->
<!-- Propiedades principales o modificaciones --> margin | margin-top | margin-right | margin-bottom | margin-left

#000000 → Outline Linea (perimetral)

<!-- Linea rodea la caja entre border y margin -->
<!-- Traza liena fuera de bordes de elementos puede ser utilizado con fines decorativos -->
<!-- Propiedad no pertenece a modelo de caja pero hace que elementos ganen foco, como los input, tengan ligera aura que rodea -->
<!-- Propieades principales --> outline-style | outline-width | outline-color | outline-offset

**DISPLAY** Block - Inline - Inline-block - None

**-** Display (pantalla) Propiedad mas importante para controlar el diseño

— Block — Contenedores, Siempre comienza en una nueva linea y ocupa todo el ancho disponible `<div>` es un elemento block

— Inline — No comienza en una nueva linea y solo ocupa ancho necesario `<>` elemento Inline, si falta espacio bajara a la siguiente linea.

— Inline-Block — Block tiene abierta las propiedas de padding y margin, caso diferentea inline que se restringen top y bottom
ahora esta propiedad de display funciona en inline con las propiedades del box model sin restriccion.

← Inline direcion →

↓ Block direction ↑

**Como funcionan** los margins y los paddins

- En el display inline podemos modificar/controlar tanto el paddin (en todas sus facetas) como el margin pero solo de izquierda a derecha.

- Por otro lado en el display block podemos modificar todas la facetas tanto el padding como el margin

---

`NOTAS`
`comentarios ctrl + /`
`panel propiedades ctrl + SpaceBar`

---

## — **2022-02-03** ———————————————————

**FLOAT — CLEAR — OVERFLOW**

_→_ `FLOAT`

- Alinea elementos

- Puede Adoptar 3 valores.

1. Left
2. Right
3. Inherit (heredado)
4. None

- Elemento que se aplica propiedad no tiene definida su anchura entonces no sera tratado como tal.

- No todo los elementos son validos para usar float, los que definnen propiedades del texto (span, strong, i. b, etc)

- Tampoco se usa en saltos de linea NO. Los que si soportan son divs,img, p, listas, etc.

_→_ `CLEAR`

- Lo elementos despues de un elemento flotante fluiran a su alrededor en caso que no quisieramos que esto pasara utilizarmeos la propiedad **CLEAR**

- Valores del CLEAR:

  1. None: Predeterminado, es el vale todo

  2. Left: No se permiten elementos flotantes en el lado izquierdo.

  3. Right: No se permiten elementos flotantes del lado derecho.

  4. Both: No se permite elementois flotante a amabos lados

  5. Inherit: Valor Heredado del padre

  → Vamos hacer el ejercio. **01_index_FCO.html**

_→_ `OVERFLOW`+

- Contenedor padre si tiene hijos con `float` debemos usar `OVERFLOW`

- Cuando usamos elementos float dentro de un contenedor este se ignora al elemento para sus altos

- Si no queremos que esto pase el **clearfix** sera nuestro bffo.

- Para ejecutar la props = `overflow: auto`

- Para que cuente a los elementos flotantes en su height.

_→_ `Ejercicio para blog de viaje`

recuerda usar display e FCO para ajustar tus cuadros.

Notas todo contenido una buena opcion es usar unidades de porcentaje recuerda ancho y ancho maximo

**POSITION - Elemento posicionado**

_→_ Relative

- _Que es el flujo normal del HTML_, es el orden natural en el que los elementos aparecen en pantall, es decir, los elementos apareceran colocados tal como estan ordenados en el codigo HTML, solo si no se aplica ningun CSS que cambie la forma en la que se compartan.

- Si colocamos un encabezado (en el codigo HTML) `<h1>title</h1>` y debajo un parrafo `<p>lorem...</p>` el navegador primero dibuja el encabezado y despues del parrafo y asi sucesivamente.

- _Que es un elemento posicionado?_
  Un elemento posicionado es aquel elemento que ha salido de su flujo normal a traves de la propiedad `position`, ademas adquiere nuevas propiedades.

- La propiedad `position`, adquiere nuevas propiedades.

- La propiedad `position` en que punto de la pagina comenzara a posicionarse, mostrarse o dibujarse el elemento que se haya establecido en el codigo HTML.

- los diferentes tipos de posicionamiento son los siguientes:

  <!--Fijo  -->

  - `static` (valor por defecto)

    - Es una propiedad que viene por defecto
    <!-- Comportamiento normal  -->

- `relative` (El elemento se coloca relativo al flujo normal)
  - Elemento que se posisiona relativo a su posicion normal, es decir relativo a su flujo normal.
  - Para delimitar copmo se desplazara la caja podemos utilizar las propiedades top, bottom, right, left.
  - Propiedades top y left tienen mas prioridad sobre las bottom y que right, idealmentes solo tienes que escoger una de las 2 opciones
  - Como lees un libro? Pues asi es la logica de propiedad. arriba e izquierda o abajo y dereecha.
  - las propiedades unicamente funcionan con los ELEMENTOS POSITION. -

<!-- vamos a el archivo 04_index_Position.html -->

- `absolute` (El elemento se coloca al especto a su contenedor posicionado mas cercano)

  - Hace que un elemento se coloque respecto a su contenedor posicionado cercano, si no encuentra ninguno sera respecto al viewport (toda la pantalla, es viewport.)
  - Cuando a un elemento le colocamos el valor `absolute`, ese elemento no conserva su espacio de flujo (ocupa su espacio natural inline o block).

<!-- vamos a el archivo 04_index_Absolute.html -->

- `fixed` (el elemento se coloca respecto al viewport)

  - Es de los mas comunes al disenar un sidebar, ventana de dialogo o un boton fijo en la web
  - Hace que un elemento se coloque respecto al viewport.
  - Elemeno con conserva su espacio de flujo
  - Las propiedades `top` → `left` → `right` → `bottom` siempre son relativas a la ventana del navegador

  - Esta caja nos permite definir la posicion en el eje z de los elementos posicionados.
  - Acepta un valor numerico positivo o negativo, entre mas alto mayor prioridad.
  - Pordefecto esta en auto, eso quiere decir que los ordenara en funcion de como aparezcan en el documento.

<!-- vamos a el archivo 03_index_Fixed.html -->

- `sticky` `sticked` (es un combinacion entre el relative y fixed)

  - Es un hibrido entre relativo y fijo que se activa cuando se le especifica
  - Se usa cuando queremos que se posicione en un lugar especifico y cuando lleguemos al alemento se quede de forma fija
  - Aca las coordenadas t,b,l,r, se usan para indicar en que lugar tendra un comportamiento diferente antes de eso se comportara de manera natural.
  - SCROLL TO THE BOTTOM

<!-- vamos a el archivo 04_index_Sticked.html -->

- `Z-index`

  - Esta caja nos permite definir la posicion en el eje Z de los elementos posicionados.
  - Acepta un valor numerico, positivo o negativo, entre mas alto mayor prioridad.
  - Por defecto esta en **auto**, eso quiere decir que los ordenara en funcion de como aparezcan en el documento.

<!-- vamos a el archivo 05_index_Z-index.html -->

- **POSICIONADO** Al tener un elemento posicionado podemos movernos en los 3 ejes X- Y - Z

  → Eje X

  `right` (movel el elemento desde DER a IZQ)

  `left` (mover el elemento desde IZQ a DER)

  → Eje Y

  `top` (mover elemento desde superiorio a Inferior)

  `bottom` ( mover elemento desde superior a inferior)

  → Eje Z

  `z-index` cuando dos o mas elementos se solapan. podemos decidir cual aparece primero y cual por detras de el.

  - Tiene un limite de elemento.

**RETO dentro de nuestro blog hacer agregar position (sticked)**

---

## — **2022-02-08** ———————————————————

Review CSS

- Desarrollo WEb
- Usamos Html CSS Javascript
- Forma correcta de importar archivo CSS `<link rel="stylesheet" href="./estilos.css">`
- Poner estilos en una clase `.hola{ color: red;}`
- La propiedad `color-text` _NO _ me ayuda aponer color a texto por que no existe.
- `display: grid → :flex → :none` son tipos de display excepto top no exite.
- Forma correcta de declarar con Javascript `let a=1;`

**RESPONSIVE DESIGN**

El diseño que es para que se ajuste a diferentes dispositivos.

1. Que es el responsive design?

- a→ Antes de empezar
- b→ Patrones

2. Bases del responsive design

- a→ El viewport
- b → Diseño con porcentajes
- c → Tamaño Maximos y minimos.

3. Media Queries.

**Que es?**

- Acceder a internet por diferentes dispositivos diferentes pantallas y soluciones. que se vea optimo y garantice la mejor experiencia del usuario.

- Diseño responsivo - responde al cambio se nota una transicion natural.

- Diseño adaptativo - y Adaptativo se nota el salto de cambio.

- Unidades relativas → porcentajes relativos se manejan con porcentajes. Vertical Hide.

- Unidades estaticas → PX son unidades absolutas.

- _The FLOW_ → Se colapsa se contrae debe fluir con el desencadenamiento de otro elemento.

- _Static_ → estatico donde no se mueve Nav bar

- Recolocacion\* de elementos./ Como se ubican los objetos. / depende la resolucion se puede modificar la posicion de algunos elementos.

  - With Breakpoints. cambia la ubicacion u y reacomodo
  - Without Breakpoints. Modifica el tamaño.

- Estrategias de diseño

  - Desktop first → Empieza el diseño desde la mayor resolucion soportada. Nos guiamos desde

  - Mobile First → Empezamos desde resoluciones pequeñas se puede revisar desde el inspector modo mobile. se puede girar y modificar dimensiones.

- **nota** El navegador baja su rendimiento para cuidar el performance y se ve en throting

**Conceptos Utiles en resp[onsive Design**

- `Viewport` El area visible del navegador

- Concepto introducida por apple / Leugo adoptada y desarrollada mas alla por otros /
- Se ve de la siguiente manera: `<meta name="viewport" content="#">`

- `Portrait - Landscape` Vertical u Horizontal global smarthphone orientation - Nota - _94%_ Vertical o portrait _6%_ Horizontal (landscape)

**UNIDADES Y MEDIDAS EN css**

- css has 2 kinds of units: Absolute & relative

  - Absolute: px, pt, pc, | in, cm, mm,
  - Relative: em, rem, ch, ex, | vw, vh, %,
  - _rem_ → the roor element's fint size `html{font-size: 14px}` this mean `1rem = 14px` everywhere in the document
  - _em_ the current element's font size | Heading and scroll text - these 2 elements have different values of `1em`
  - _0_ is rthe same in all units`.h1 {margin: 0;` no need put a some unit, 0 is always the same

- _in - cm - mm_ Great for print stylesheets, not so good for web

- _vw - vh_ `100vw` is the viewport width `100vh`is the viewport height

- **rem & em help with accessibility** `.modal { width: 20rem;}` → this sacles nicely if the user increases their browse`s default font size

- Unidades comunes para texto

  - PX → Para fijar tamaños hy espacios
  - EM → Dependera del parentesco del elemento
  - REM → de facil escalabilidad responsiveness suele ser equivalente a 16px

- _Porcentaje_ Longitud relacionado al elemento padre

- _EM_ Unidad relativa al tamaño de fuente especificada mas cercano.

- _REM_ unidad relativa al tamañ de fuente especifiacda en el ancestro mas lejano (html o body)

- _vw_ y _vh_ Unidad relativa porcentual con respecto al viewport

- **MEDIA QUERIES**

- Este modulo de CSS existe responsive design ( flexbox o grid) ya que permite adaptar la respresentacion del contenido a las caracteristicas del dispositivo.

- Los breakpoints estan dentro de los mediaqueries que es lo que permitirar recolocar o redimensionar segun, los busquemos.

- `@media media type and (condition) { /* regla css *}`

- `@media media type and not (condicion) {/*regla CSS*}`

- Se compone de una media type y una o mas condiciones

- _Media Types_ Decriben la categoria general de un archivo.

  - all (por defecto) - Apto para todos los dispositivos

  - print - Destinado a material impreso y visualizacion de documentos en una pantalla en el modo de vista previa de impresion

  - screen - Principalmente a las pantallas

    -Ejemplo: @media sreen and (max-width: 768px) {}

  - speech - Destinado a sintetizadores de voz

- ** Con el fragmento de codigo HTML estamos indicando que el nuevo ancho de la pantalla es el **es el ancho del dispositivo\*\* por lo que el aspecto del viewport se va a adaptar consecuentemente. `device-width` (dispositivo-Ancho)

<!-- Ir archivo Mediaqueries -->

- **LLEGA HIROMI** Hace preguntas sobre como se sienten con los temas y pide sus dudas y necesita un update.

  - Notas importantes
  - Se hara un clon de google. / Reto / diseño responsivo se hace con desktop o mobile (mobile first a desktop first)
  - Recuerda tu etiqueta, para que este diseño funcione.
  - Media Q es la reglas para ajusta el distribucion y dimension
  - La sentencia `@media screen and (max-width: 768px) { si sucede esto haz esto / if this happens do this}
  - Todas la pantallas con un ancho inferior o igual a 768px cumplen con esta condicion.

-

-

- ***

## — **2022-02-09** ———————————————————

---

## — **2022-02-10** ———————————————————

---

## — **2022-02-14** ———————————————————

--

## — **2022-02-15** ———————————————————

---

## — **2022-02-16** ———————————————————

---

## — **2022-02-17** ———————————————————

---

```

```

```

```

```

```
