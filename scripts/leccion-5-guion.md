# Desarrollo Web: Estilo Simple con CSS

## 1. Presentación y objetivos del video

¡Hola a todos! Bienvenidos de nuevo al curso. 

Hoy vamos a aprender algo que le va a dar VIDA a nuestras páginas web, porque hasta ahora todo lo que hemos hecho está en blanco y negro, ¡literal! 

Hoy vamos a meterle colores, bordes, espacios... vamos a hacer que nuestra página deje de verse como un documento de Word aburrido y empiece a verse como una página de verdad.

Esto se llama CSS, y hoy nos vamos a enfocar en algo que llamamos **"Estilo Simple"**: técnicas fáciles pero súper efectivas para mejorar visualmente cualquier página.

---

## 2. Repasando las bases de CSS

Antes de meternos a los colores y todo lo cool, repasemos rapidísimo cómo se escribe CSS, porque todo lo que vamos a ver hoy se basa en esto.

CSS funciona bajo una estructura simple:

1. **Selector:** Le decimos a la página a qué elemento le vamos a hablar (por ejemplo, un título `<h1>`).
2. **Llaves (`{ }`):** Abrimos llaves para contener las modificaciones.
3. **Propiedad y Valor:** Dentro de las llaves definimos qué queremos cambiar y qué nuevo aspecto tendrá, separados por dos puntos y terminando en punto y coma.

Esta es la base de absolutamente todo lo que vamos a configurar el día de hoy.

---

## 3. Centrar el contenido

Imagínate que tienes el título de tu página y quieres que resalte, que se note que es lo más importante. 

Una forma súper fácil de lograr eso es centrándolo, porque así se diferencia visualmente del resto del texto que normalmente va pegado a la izquierda.

* **Propiedad clave:** `text-align`
* **Valor principal:** `center`

Más adelante, en la sección de código, vamos a ver cómo se ve esto aplicado directamente a un título principal.

---

## 4. Colores en CSS

Ahora vamos a lo que todos estaban esperando: ¡colores! Aquí es importante que no se confundan, porque hay tres aplicaciones distintas de color y cada una hace algo diferente:

* **Color del texto:** Cambia el tono de las letras de un elemento.
* **Color de fondo de la página:** Modifica el lienzo completo de la pantalla.
* **Color de fondo de un elemento:** Afecta únicamente el fondo de un bloque o párrafo específico, sin alterar el resto.

Además, estos colores los podemos escribir y declarar de 3 maneras distintas en nuestro código:

1. **Nombre en inglés:** Palabras directas como `red`, `blue` o `purple`.
2. **Código Hexadecimal:** Combinaciones alfanuméricas que inician con hash (por ejemplo, `#FF0000`).
3. **Código RGB:** Definición por canales de color (por ejemplo, `rgb(255, 0, 0)`).

Por ahora nos quedaremos con los nombres en inglés por su facilidad, pero es crucial saber que las otras opciones existen para lograr millones de combinaciones en el futuro.

---

## 5. Anatomía y diseño de Bordes

Ahora vamos a aprender sobre bordes, es decir, esas líneas que rodean perimetralmente a un elemento.

Un borde se define configurando 3 propiedades esenciales:

* **El ancho:** Qué tan gruesa es la línea (usualmente medido en píxeles, como `2px`).
* **El estilo:** El tipo de trazo que tendrá la línea. Los 3 principales son:
    * `solid`: Una línea recta y continua.
    * `dashed`: Una línea compuesta por guiones.
    * `dotted`: Una línea formada por puntitos.
* **El color:** El tono visual del trazo.

### Bordes redondeados

Si no quieres esquinas filudas y buscas un diseño más suave, existe una propiedad para redondear bordes llamada `border-radius`. 

Lo interesante es que puedes asignarle un valor distinto a cada una de las cuatro esquinas; no tienen que ser todas iguales obligatoriamente.

---

## 6. Espaciado: Padding vs Margin

Por último, vamos a hablar de espacios, porque una página sin espacio bien distribuido se ve toda apretada, saturada y fea.

Hay dos tipos de espaciado y mucha gente los confunde a menudo, así que presta mucha atención:

* **Padding (Espacio Interno):** Es el espacio que se genera entre el borde de un elemento y su contenido real (las letras o imágenes de adentro).
* **Margin (Espacio Externo):** Es el espacio que se genera hacia afuera del borde, separando a ese elemento de los demás bloques que están a su alrededor.

> **Regla de oro para recordar:**
> * **Padding** es para adentro.
> * **Margin** es para afuera.

Bueno, ya vimos toda la teoría: bases de CSS, centrado, colores, bordes y espaciado. Ahora sí, vamos a compartir pantalla y verlo todo en acción.

---

## 7. Práctica en Vivo (Pantalla Compartida)

A continuación, aplicaremos uno por uno todos los conceptos teóricos directamente sobre nuestro editor de código.

### Caso 1: Centrado de texto

Partimos de una estructura HTML base sin estilos:

```html
<h1>Mi página web</h1>
<p>Este es un texto normal.</p>