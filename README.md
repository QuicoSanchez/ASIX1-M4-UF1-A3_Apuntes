# ASIX1-M4-UF1-A3_Apuntes

Apuntes

## Primer Capitulo: MARKDOWN

Este texto esta en *cursiva*
Este texto esta en _cursiva_
Este texto esta en **negrita**
Este texto esta en __negrita__

Este texto está en **_negrita y cursiva_**.

1. Primera opción de menú
2. Seguna opción de menú
3. Tercera opción de menú

* Primera opción de lista desordenada
* Segunda opción de lista desordenada
- Tercera opción de lista desordenada
    1. Primer submenú
    2. Segundo submenú
- Cuarta opción de lista desordenada
    * Tercer submenú
    * Cuarto submenú
+ Quinta opción de lista desordenada
+ Sexta opción de lista desordenada

```
<html> 
    <head>
    </head>
    <body>
        <p>Esto es un párrafo</p>
    <body>
<html>
```
[Esto es un enlance](http://joan23.fje.edu "Enlance a la web del cole")

![Esto es una foto de prueba](https://github.com/QuicoSanchez/ASIX1-M4-UF1-A3_Apuntes/blob/main/Test.png "Titulo opcional de la imagen")

|Primera Col.|Segunda Col.|3 Col|
|---------------|:------------:|---------:|
|Col 2 es|centrada|35€|
|Col 3 es| derecha|134€|
|Estilo cebra|Gris|Blanco|
|Clase|ASIX1|M4|

-[ ] Opcion A
-[X] Opcion B
-[ ] Opcion C

## Segundo Capitulo: HTML

HTML es el código que se utiliza para estructurar y desplegar una página web.

Para crear una página con HTML se debe tener esta estructura: un head y el body donde va el contenido de página.

Para que Visual Studio Code nos de una estructura de html, escribiremos **hmtl:5** y no dara la siguiente estructura:
```
    <!DOCTYPE html>
    <html lang="es">
    <head>
        <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <script src="https://kit.fontawesome.com/02d480a03b.js" crossorigin="anonymous"></script>
        <link rel="icon" href="book-solid.ico">
        <title>Document</title>
    </head>
    <body>
        <h1>Titulo principal</h1>
        <h3>Primera seccion </h3> 
        <p>Fugit quas ea deserunt voluptatum voluptas qui! Esse voluptate molestiae reprehenderit laudantium id labore corporis repellat dolores laborum.Repellendus placeat nemo ipsum?</p>
        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. </p>
        <p>Veritatis ex asperiores corporis vel molestiae distinctio sit at sapiente rerum cupiditate reiciendis.</p>
        <p>Beatae unde placeat accusantium nisi officiis voluptatum ipsum sed.</p>
        Lorem ipsum dolor sit, amet consectetur adipisicing elit. Sit iusto earum et molestias. Tempora voluptates minus, voluptatem possimus corrupti in fugiat deleniti at voluptate quam sapiente doloremque laborum fuga ea?
        <br/> Enter/Intro

        Ejemplo de enlace
        <a href="http://www.google.com" alt ="Por aqui se va a Google" Target="_blank"> Este es el enlace a google </a>
        <blockquote>Esto es un documento que </blockquote>

    </body>
``` 

La lista ordenada y desordenada se basa se usa diferenetes etiquetas van desde el inicio para dar la forma que queremos por lo cual es separada por dos diferentes formas:

Lista ordenada: Para una lista ordenada al inicio va la etiqueta **<ol>**, a partir de ella hacemos enter en el teclado y abrimos una etiqueta nueva **<li>**, lo que hara sera enumerar en orden cada una sucesivamente de 1, 2, 3. 
Para finalizar esta lista orrdenada, lo cerraremos con un **</ol>**.

Lista desordenada: Para una lista desordenada al inicio va la etiqueta **<l>** a partir de ella hacemos enter en el teclado y abrimos una etiqueta nueva **<li>**, lo que hara sera enumerar en orden cada una sucesivamente de 1, 2, 3. 
Para finalizar esta lista orrdenada, lo cerraremos con un **</ul>**.

Ejemplo:
```
        <ol>Es una lista ordenada
            <li>Primer elemento</li>
            <ul>
                <li>Primer elemento</li>
                <li>Segunda elemento</li>
                <li>Tercer elemento</li> 
            </ul>
            <li>Segunda elemento</li>
            <ol>
                <li>Primer elemento</li>
                <li>Segunda elemento</li>
                <li>Tercer elemento</li> 
            </ol>
            <li>Tercer elemento</li>
        </ol>

        <ul>Es una lista desordenada
            <li>Primer elemento</li>
            <li>Segunda elemento</li>
            <li>Tercer elemento</li>
        </ul>
    
```

 
Hay dos formas de introducir imágenes,  una es sola y otra con una url para que te lleve a otra página web:

Solo imagen: Ahora pasamos a insertar imágenes que tenemos guardadas en nuestro ordenador con esta etiqueta   ```<img src="" alt="" height ="">```, ponemos la ubicación de la imágen entre comillas, como dice en la guía "./", en (alt="ponemos un texto alternativo") y si queremos ajustar un tamaño a la imagen ponemos height o weight y enter comillas en tamaño a disponer.

Enlace de una página web en imagen: La etiqueta se llama a```<a href="https://www.google.com" alt="" target="blank">```, en el href entre comillas va la direción de la página web, "alt" el texto alternativo y importante para que esa dirección web se habrá en otra página web se pone **(target="blank")**.

Enlace de otro archivo html: Se hace el mismo procedimiento que el anterior solo que en ves de poner la ubicacion del archivo.
```<a title="" href="./Apuntes.html" alt="" target="_blank"></a>)```

**Tablas**
Las tablas sirven para empaquetar datos que nosotros queremos

*Encabezado*: Dentro comenzamos con la parte del head con la etiqueta *```<thead>```* y para un fila en la tabla se utiliza *```<tr>```* y dentro de ella pondremos otra más *```<th>```*.

*Cuerpo* : Ahora decimos lo que va dentro de la tabla con la etiqueta *```<tbody>```*, y procedmos a abrir fila filas con  *```<tr>```*, ponemos informacion dentro ella con la etiqueta *```<td>```*.

*Pie*: Por último decimos el pie de la tabla, comenzamos con la etiqueta  *```<tfood>```* para inicar con las celdas utilizamos las etiquetas *```<tr>```* y dentro ella por cada fila abrimos con *```<th>```*

```
    <table border="1">
        <thead>
            <tr
                style="color: red;text-align: center;">
                <th>Puesto</th>
                <th>Atleta</th>
                <th>Tiempo</th>
            </tr>
        </thead>
        <tbody style="background-color: blueviolet;text-align: center; color: aliceblue;">
            <tr id="primerafila">
                <td>1r</td>
                <td>Paco Martinez</td>
                <td>14:25</td>
            </tr>
            <tr class="textoazul">
                <td>2r</td>
                <td>Pau Lopez</td>
                <td>14:50</td>
            </tr>
            <tr class="textoazul">
                <td>3r</td>
                <td>Joel Gallego</td>
                <td>15:30</td>
            </tr>
        </tbody>
        <tfoot>
            <tr>
                <th>Puesto</th>
                <th>Atleta</th>
                <th>Tiempo</th>
            </tr>
        </tfoot>
    </table>
```
## Tercer capítulo: CSS
El CSS es un lenguaje de programación que se utiliza para ordenar las intrucciones referentes a la apariencia de un archivo html y presentar su contenidos de forma atractiva.

El CSS se puede poner en el head de un html o en un archivo externo y hacer un link en el html del archivo CSS.
Estructura:

```<link rel="stylesheet" href="./styles.css" type="text/css"/>```

Tenemos una etiqueta que puede afectar a toda la pagina web que es ```*```.
Ejemplo:
```
    *{
    margin: 0%;
    }
```

Cada selector, id, clase, etiqueta, h1, h2 etc... tiene un montón de opciones para poder dar estilos.
También puede afectar al contenido de la página como margenes, tamño, fondo y mas cosas.


## Cuarto Capitulo: DISEÑO RESPONSIVE

El diseño responsive es una técnica de diseño web que permite que un sitio web se ajuste automáticamente al tamaño y la resolución de la pantalla del dispositivo desde el cual se está viendo. 
Por eso la página web se mostrará de manera clara, legible y fácil de navegar.

En el diseño responsive utiliza CSS y HTML para redimensionar, ocultar, encoger o ampliar estos elementos HTML para que se adapte a la pantalla de cualquier dispositivo.

**Comandos de Diseño de Pagina Web Responsive:**

Mayormente el diseño responsive se usa con la etiqueta ```div```, que también puede ser ```section``` o ```article```. 

El primer comando a mostrar es muy importante debido que lleva a la implementación y construccion de bloques, es el ```display```.

```
    h1{
        display: flex;
    }
```

Otro importante es el ```float```, este elemento coloca en el lado izquierdo o derecho de su contenedor, lo que permite que el texto y los elementos en línea se ajustan a su alrededor.

```
    #left{
        float: left;
    }
```


Tambien el ```box-sizing``` sirve para recalcular la medida del borde y el padding con respecto al tamaño de la informacion.

```
    *{
        box-sizing: border-box;     
        font-weight: 600;
        font-style: normal;
    }
```

**Propiedades de la alineación:**

Hay diferentes comandos para realizar la alineación de la página web, uno va ser el ```aling-items``` que controla la alineación de todos los elementos.

```
    h2 {
        align-items: left;
    }
```

Ahora vamos a la parte del ```flex-direction```, esto significa que el eje principal corre a lo largo de fila horizontalmente y nuestra alineación del eje transversal mueve los elementos hacia arriba y hacia abajo.
```
.ejemplo {
  display: flex;
  flex-direction: column;
  align-items: flex-start;
  width: 500px;
}
```


Otro comando que nos puede ayuda en lo que viene hacer el justificado de página web, siendo algo simiñar a lo visto anteriormente, pero ```justify-content```, se define como el navegador distribuye el espacio entre y alrededor de los elementos de contenido a lo largo del eje principal de un contenedor felxible y el eje en línea de un contenedor cuadrícula. Además este puede tener varias opciones, por ejemplo;

```
.box{
    justify-content: start;
}
```

El ```start```, sirve para empaquetar al ras entre sí hacia el borde inicial del contenedor de alineación en el eje principal. También el "start" puede ser cambiado por otras opciones como la de ```end```, empaqueta a ras hacia el borde final del contenedor de alineación en el eje principal, etc.

**Utilización para imágenes:**

Para hacer una imagen sea responsive se le pueda diferentes formatos y estilos, se le puede dar un valor a su propiedad de anchura. La altura de la imagen se ajustará automáticamete. Lo importante es saber que siempre debes utilizar unidades relativas para la propiedad de anchura, como porcentaje, en lugar de las absolutas, como los píxeles.

```
header{
    height: 100vh;
    background-image: url(../img/brandon-burridge-4o7f9_Z73a4-unsplash.jpg);
    background-size: cover;
    background-position: center;
    background-attachment: fixed;
}
```

En esta parte vemos los principales que se usa para implementación de las imágenes, en primer lugar esta un ```background-image: url(./xxxx/xxxxx.png)```, establece una o más imágenes de fondo en un elemento como en el fondo de l página, podiendo poner de forma predeterminada. En segundo lugar, acompañado de una url que mostra la ubicación de la imagen. El ```background-size: cover```, hace que la imagen se pueda dejar de tamaño natural al momento de estirarla par que se ajuste al espacio disponible, con el ```cover```, ayuda en la escala de la imagen, al tamaño más pequeño posible de llenar el contenedor, sin dejar espacios vacios.

El ```background-position:center```, establece la posición relativa a la capa de posición establecida, junto al ```center```, pone la posición de la imagen hacia el centro del contenedor o de la páginas. El ```background-attachment: fixed```, pone la posición de una imagen de fondo que es fija dentro de la ventana gráfica o se desplaza con su bloque contenedor, con el ```fixed```, pone el fondo fijo en relación con la página web, hasta con un mecanismo de movimiento, haciendo que el fondo no se mueva con el elemento.


**Media:**

Las Media queries permiten aplicar esrilos CSS según el tipo general de un dispositivo, lo cúal va por el tamaño de pantalla u otras características como la resolución de la pantalla o del ancho del viewport del navegador. Tomando el siguiente ejemplo:

```
@media only screen and (max-width: 700px){
/* REGLAS */
.column-3{
    width: 100%;
}
.column-4{
    width: 50%;
}
}
```
