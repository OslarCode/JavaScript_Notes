# Introducción

# Introducción a JavaScript en el Diseño y Confección de Páginas Web

JavaScript es un lenguaje de programación de alto nivel, interpretado y dinámico, que se utiliza principalmente para crear interactividad en páginas web. Desde su creación en 1995 por Brendan Eich en Netscape, JavaScript ha evolucionado hasta convertirse en uno de los lenguajes de programación más populares y ampliamente utilizados en el desarrollo web. En este documento, exploraremos qué es JavaScript, cómo funciona y cómo se utiliza en el diseño y confección de páginas web.

## ¿Qué es JavaScript?

JavaScript es un lenguaje de programación que se utiliza principalmente en el lado del cliente para agregar interactividad y funcionalidad a las páginas web. A diferencia de HTML y CSS, que se utilizan para definir la estructura y el estilo de una página web, respectivamente, JavaScript permite a los desarrolladores crear aplicaciones web dinámicas y receptivas al interactuar con el usuario y modificar el contenido de la página en tiempo real.

## Funcionamiento de JavaScript en el Diseño Web

JavaScript se ejecuta en el navegador web del usuario, lo que significa que su código se interpreta y ejecuta en el dispositivo del cliente, en lugar de en un servidor remoto. Esto permite una rápida respuesta a las acciones del usuario y una experiencia más fluida y receptiva en la interfaz de usuario.

### Integración con HTML

JavaScript se integra fácilmente con HTML mediante la inclusión de scripts dentro de las etiquetas `<script>` en el documento HTML. Estos scripts pueden ubicarse en el encabezado (`<head>`) o en el cuerpo (`<body>`) de la página web.

```html
<!DOCTYPE html>
<html lang="es">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Ejemplo de JavaScript</title>
    <script>
      // Aquí se coloca el código JavaScript
    </script>
  </head>
  <body>
    <!-- También puede colocarse aqui el script -->
  </body>
</html>

```

### Manipulación del DOM

Una de las características más poderosas de JavaScript es su capacidad para manipular el Document Object Model (DOM) de una página web. El DOM representa la estructura de la página como un árbol de nodos, y JavaScript puede acceder a estos nodos, modificar su contenido, atributos y estilos, y agregar o eliminar elementos según sea necesario.

```html
<!DOCTYPE html>
<html lang="es">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Manipulación del DOM con JavaScript</title>
    <script>
      // Seleccionar un elemento por su ID y cambiar su contenido
      document.getElementById("demo").innerHTML = "¡Hola, Mundo!";
    </script>
  </head>
  <body>
    <!-- Elemento de demostración -->
    <div id="demo"></div>
  </body>
</html>

```

### Interacciones del Usuario

JavaScript permite manejar eventos del usuario, como clics de ratón, pulsaciones de teclas y desplazamientos de la página, para crear interactividad en la página web. Esto se logra utilizando métodos como `addEventListener()` para asociar funciones con eventos específicos.

```html
<!DOCTYPE html>
<html lang="es">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Interacciones del Usuario con JavaScript</title>
  </head>
  <body>
    <!-- Botón de demostración -->
    <button id="boton">Haz clic aquí</button>

    <script>
      // Esperar a que el DOM esté completamente cargado
      document.addEventListener("DOMContentLoaded", function() {
        // Acceder al botón después de que el DOM esté listo
        document.getElementById("boton").addEventListener("click", function () {
          alert("¡Has hecho clic en el botón!");
        });
      });
    </script>
  </body>
</html>

```

## Conclusiones

En resumen, JavaScript es un lenguaje de programación esencial en el diseño y confección de páginas web, que permite agregar interactividad, dinamismo y funcionalidad a las aplicaciones web modernas. Al integrarse con HTML y CSS, JavaScript ofrece a los desarrolladores la capacidad de crear experiencias de usuario ricas e inmersivas, lo que contribuye a una web más dinámica y atractiva para los usuarios finales.

## Referencias

- Flanagan, D. (2011). JavaScript: The Definitive Guide. O'Reilly Media.
- Duckett, J. (2014). JavaScript and jQuery: Interactive Front-End Web Development. Wiley.
- MDN Web Docs. (s.f.). JavaScript. Recuperado de [https://developer.mozilla.org/en-US/docs/Web/JavaScript](https://developer.mozilla.org/en-US/docs/Web/JavaScript)