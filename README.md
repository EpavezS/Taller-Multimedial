
<img src="https://media.giphy.com/media/F0Y7kjfHRl3a0/giphy.gif" alt="GIF reloj" width="300"><br><br>
### Taller Multimedial De Grado.
#### Bitacora de cultura web y arte digital
##### Elena Pavez

## Índice:

### Semana 1:
``` html
<!DOCTYPE html>
<!-- Indica al navegador que este documento usa HTML5 -->

<html>
<!-- Inicio del documento HTML -->

<head>
<!-- Sección donde van metadatos, título y estilos -->

<meta charset="UTF-8">
<!-- Define la codificación de caracteres para que se vean bien tildes y símbolos -->

<title>Multimedial</title>
<!-- Título de la página que aparece en la pestaña del navegador -->

<style>
/* Aquí comienza la sección de estilos CSS que define la apariencia visual */

body{
/* "body" se refiere a todo el contenido visible de la página */

  background-color: white;
  /* Define que el fondo de toda la página sea blanco */

  color: black;
  /* Define que el color del texto sea negro */

  margin: 0;
  /* Elimina los márgenes que los navegadores agregan por defecto */

  height: 100vh;
  /* Hace que el alto del cuerpo sea igual al 100% de la altura de la pantalla */

  display: flex;
  /* Activa el sistema Flexbox para organizar y centrar elementos */

  justify-content: center;
  /* Centra el contenido horizontalmente */

  align-items: center;
  /* Centra el contenido verticalmente */

  font-family: Arial, sans-serif;
  /* Define la tipografía del texto */

  font-size: 60px;
  /* Define el tamaño grande del texto */

}
/* Fin de las reglas de estilo del body */

</style>
<!-- Fin de la sección de estilos -->

</head>
<!-- Fin de la sección head -->

<body>
<!-- Inicio del contenido visible de la página -->

MULTIMEDIAL
<!-- Texto que aparece en el centro de la pantalla -->

</body>
<!-- Fin del contenido visible -->

</html>
<!-- Fin del documento HTML -->
```
<a href="#top">
  <img src="https://i.giphy.com/media/xn8xD14FtUGQgXxST5/giphy.gif" width="120">
</a>
  
### Semana 2: Enlaces (links)
#### Ejemplo 1 básico:
```html
<a href="pagina2.html">Ir a la página 2</a>
```
#### Explicación:
<a> → etiqueta de enlace.
href → atributo que indica a qué página se va a enlazar.
"pagina2.html" → archivo o dirección a la que se va.
Ir a la página 2 → texto visible del enlace.
</a> → cierre de la etiqueta.

#### Cuando una persona hace clic en “Ir a la página 2”, el navegador abre pagina2.html.

### Ejemplo 2 con dos páginas:
##### index.html

```html
<!DOCTYPE html>
<html>
<head>
<title>Mi sitio</title>
</head>

<body>

<h1>Página principal</h1>

<a href="pagina2.html">Ir a la segunda página</a>

</body>
</html>
```
##### pagina2.html

```html
<!DOCTYPE html>
<html>
<head>
<title>Página 2</title>
</head>

<body>

<h1>Esta es la segunda página</h1>

<a href="index.html">Volver a la página principal</a>

</body>
</html>
```
