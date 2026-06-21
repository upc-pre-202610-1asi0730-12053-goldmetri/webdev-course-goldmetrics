# Cierre del Curso de Desarrollo Web

## 1. Bienvenida al cierre del curso

Hola y felicidades por haber llegado al final de este curso.

A lo largo de las lecciones aprendimos los fundamentos necesarios para comenzar en el mundo del desarrollo web.

Ahora vamos a repasar lo más importante que hemos aprendido, revisar algunos errores comunes y descubrir cuáles pueden ser tus próximos pasos como desarrollador web.

## 2. ¿Qué he aprendido en este curso?

Durante este curso aprendimos conceptos fundamentales del desarrollo web.

Primero conocimos qué es una página web y cómo funciona Internet de manera básica.

Luego aprendimos a utilizar HTML para crear la estructura de una página.

Con HTML pudimos crear:

* Títulos
* Párrafos
* Imágenes
* Enlaces
* Listas

Después aprendimos CSS para mejorar la apariencia visual de nuestras páginas.

Con CSS pudimos modificar:

* Colores
* Tamaños
* Posiciones
* Diseños

Finalmente combinamos HTML y CSS para crear una página web sencilla y funcional.

Ahora ya conoces las bases sobre las que se construyen millones de sitios web en Internet.

## 3. Errores comunes al programar

Cuando estamos aprendiendo a programar es completamente normal cometer errores.

De hecho, los errores forman parte del proceso de aprendizaje, veamos algunos de los más comunes.

### Error #1: Cierre incorrecto de etiquetas

Uno de los errores más frecuentes ocurre cuando olvidamos cerrar una etiqueta HTML.

Por ejemplo:

```html
<p>Hola mundo
```

Aquí falta la etiqueta de cierre:

```html
<p>Hola mundo</p>
```

Cuando olvidamos cerrar etiquetas, la página puede mostrar resultados inesperados.

Por eso siempre debemos verificar que cada etiqueta tenga su apertura y su cierre correspondiente.

### Error #2: Orden incorrecto de etiquetas

Otro error común ocurre cuando cerramos etiquetas en un orden incorrecto.

Por ejemplo:

```html
<b><i>Texto</b></i>
```

Este orden es incorrecto.

La forma correcta sería:

```html
<b><i>Texto</i></b>
```

Una buena regla es recordar: La última etiqueta que abrimos debe ser la primera que cerramos.

Podemos imaginarlo como apilar cajas: la última caja colocada arriba es la primera que retiramos.

### Error #3: Nombres incorrectos de etiquetas o atributos

A veces escribimos mal una etiqueta o un atributo.

Por ejemplo:

```html
<imgg src="foto.png">
```

La etiqueta correcta es:

```html
<img src="foto.png">
```

O también podemos escribir incorrectamente un atributo:

```html
<img sorce="foto.png">
```

Cuando esto sucede, el navegador no entiende correctamente nuestras instrucciones.

Por eso es importante escribir cuidadosamente y revisar posibles errores de escritura.


### Error #4: El diseño no se aplica

Muchas veces escribimos código CSS pero no vemos cambios en la página.

Esto puede ocurrir por varias razones:

* El archivo CSS no está conectado correctamente.
* El nombre de la clase es diferente en HTML y CSS.
* Existe un error de escritura.
* Se olvidó guardar los cambios.

Por ejemplo:

HTML:

```html
<h1 class="titulo">
```

CSS:

```css
.titlo {
    color: blue;
}
```

Como los nombres son diferentes, el estilo no se aplicará.

Siempre debemos revisar cuidadosamente que los nombres coincidan exactamente.

## 4. Recomendaciones

Ahora que conoces las bases del desarrollo web, aquí tienes algunas recomendaciones:

* Practica constantemente.
* Crea pequeñas páginas web por tu cuenta.
* Experimenta cambiando colores, tamaños y diseños.
* No tengas miedo de equivocarte.
* Aprende a leer los mensajes de error.
* Intenta resolver problemas antes de buscar la solución.

Recuerda que todos los programadores comenzaron siendo principiantes. La práctica constante es la mejor forma de mejorar.

## 5. ¿Qué puedo aprender ahora?

Este curso es solo el comienzo, después de dominar HTML y CSS puedes continuar aprendiendo:

### JavaScript
Para agregar interactividad a tus páginas web.

### Diseño Web Responsivo
Para que tus páginas se adapten a celulares, tablets y computadoras.

### Frameworks y Herramientas Modernas
Explora tecnologias como Angular o Vue

### Desarrollo Backend
También puedes aprender tecnologías para crear la parte interna de los sistemas como bases de datos

## 6. Despedida

¡Felicidades por completar el curso!

Ahora ya conoces los fundamentos del desarrollo web y has dado tus primeros pasos como creador de páginas web.

Recuerda que aprender programación es un proceso continuo.

Cada proyecto que realices te ayudará a mejorar tus habilidades y adquirir más experiencia.

Sigue practicando, sigue creando y sigue aprendiendo.

Muchas gracias por acompañarnos durante este curso.

¡Nos vemos en la próxima aventura de programación!