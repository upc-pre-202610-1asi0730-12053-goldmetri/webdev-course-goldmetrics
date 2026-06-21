# 🎙️ Guion de clase: ¡Dándole vida a nuestra página web!

## Parte 1: Introducción (El plano y la pintura)
**Tiempo estimado: 2 minutos**

*(Muestra en la pantalla la página web ya terminada con sus colores y la foto)*

**Tú (Carolina):** "¡Miren esto, chicos! Esta es la página web que vamos a construir hoy. Se ve genial, ¿verdad? Tiene colores, una tarjeta flotante, una foto de un perrito y todo bien ordenado.

Para lograr esto, necesitamos dos archivos trabajando en equipo. Imaginen que vamos a construir una casa: HTML es el plano que dice dónde van las paredes y las ventanas, y CSS es el pintor que viene con las brochas a darle color y estilo. ¡Si no los conectamos, nuestra página se vería muy aburrida, toda gris y blanca!

Vamos a ver cómo funciona el código por dentro."

---

## Parte 2: Explicando el código HTML (La estructura)
**Tiempo estimado: 5 minutos**

*(Abres el archivo index.html en el editor de código)*

**Tú (Carolina):** "Empecemos por el esqueleto, nuestro archivo HTML. Como ven, el código se escribe usando unas palabritas entre llaves llamadas etiquetas (o 'tags'). Casi todas tienen una de apertura y una de cierre con una rayita (/). Es como abrir y cerrar una caja.

- **Línea 1 a 6 (`<head>`)**: Esta es la 'cabeza' de nuestra página. Aquí no va lo que vemos en la pantalla, sino la configuración del cerebro de la web.

- **Línea 7 (`<link rel="stylesheet"...`)**: ¡Ojo aquí, chicos! Esta línea es la más importante de todas. Es el 'puente' o el 'cable' que conecta nuestro HTML con los colores de CSS. Si borramos esto, los colores desaparecen.

- **Línea 10 (`<body>`)**: ¡Aquí empieza la magia! El Body es el cuerpo de la página, todo lo que sí va a ver la gente en su pantalla.

- **Línea 12 (`<header>`)**: Es el encabezado, el título grande que va arriba. Usamos `<h1>` para el título principal y `<p>` para un párrafo corto con mi nombre.

- **Línea 18 (`<main>`)**: Es el contenido principal. Dentro pusimos una `<section class="tarjeta">`. Esa palabra 'class' es como ponerle una etiqueta con nombre a una caja para que luego el CSS sepa a cuál caja pintarle bordes redondos.

- **Línea 23 (`<img>`)**: ¿Ven este código largo? Es la dirección de internet de la foto del perrito. Si cambiamos ese enlace por el de un gatito, ¡la foto cambia automáticamente!

- **Línea 27 y 28 (`<ul>` y `<li>`)**: La `<ul>` significa 'lista desordenada' (unordered list) y cada `<li>` es un elemento de la lista. Son esos puntitos donde pusimos lo que les gusta hacer a los perros.

- **Línea 35 (`<footer>`)**: El pie de página. Es la parte de abajo del todo donde los programadores ponemos los derechos de autor o el año."

---

## Parte 3: Explicando el código CSS (El diseño)
**Tiempo estimado: 5 minutos**

*(Cambias de pantalla al archivo estilos.css)*

**Tú (Carolina):** "¡Ahora viene lo divertido! Vamos a ver cómo el pintor (CSS) hace su trabajo. En CSS no usamos flechitas, usamos llaves `{ }`. Primero le decimos a quién queremos cambiarle el estilo, y dentro de las llaves le decimos qué queremos cambiarle.

- **Sección 1 (body)**: Le cambiamos el tipo de letra a toda la página para que no se vea vieja, y con `background-color` le pusimos un color de fondo gris azulado muy suave, para que no nos duelan los ojos al leer.

- **Sección 2 (header)**: Al título de arriba le pusimos `background-color: #1e90ff`. Ese código raro con un hashtag es un color azul brillante en el idioma de las computadoras. Y con `color: white` hicimos que las letras se vuelvan blancas para que resalten.

- **Sección 3 (.tarjeta)**: ¿Se acuerdan que en el HTML le pusimos el nombre 'tarjeta' a una caja? ¡Aquí la llamamos usando un puntito al inicio: `.tarjeta`! Le dimos un fondo blanco, la centramos y usamos un truco de magia: `border-radius: 15px`. Esto hace que las esquinas de la tarjeta ya no sean puntiagudas, ¡sino redondeadas y modernas! Y con `box-shadow` le pusimos una sombrita abajo para que parezca que está flotando.

- **Sección 4 (.foto-mascota)**: Con `width: 100%` le ordenamos a la foto que se estire exactamente al tamaño de la tarjeta, para que no se salga de la pantalla."

---

## Parte 4: ¡Tu turno del Reto Hackers! (Práctica)
**Tiempo estimado: Resto de la clase**

**Tú (Carolina):** "¡Listo, equipo! Ahora que ya sabemos cómo funciona el plano y la pintura, es su turno de ser los ingenieros web.

Van a copiar este código en sus archivos, pero les tengo un **Reto Hacker**:

> Una vez que vean al perro en su pantalla, quiero que entren al CSS y cambien el color del header por su color favorito en inglés (pueden probar con `red`, `purple`, `orange` o `green`). Y en el HTML, cambien la información para que la página sea de su propia mascota o animal favorito: ¡un gato, un dinosaurio, un hámster o un dragón!

¡Manos a la obra, si necesitan ayuda me avisan!"