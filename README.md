# Fundamentos de Desarrollo Web

Curso de **Fundamentos de Desarrollo Web** creado por el equipo **GoldMetrics** como parte de su curso de Aplicaciones Web. Dirigido a estudiantes de secundaria (12–17 años) sin experiencia previa en programación.

**Duración:** ~60 minutos &nbsp;|&nbsp; **Herramientas:** Solo tu navegador web (Chrome, Firefox, Safari, Edge) &nbsp;|&nbsp; **Prerrequisitos:** Ninguno

---

## 📂 Estructura del repositorio

```
webdev-course-goldmetrics/
├── starter-files/       # Archivos HTML de inicio para cada lección
├── completed-examples/  # Ejemplos terminados y errores comunes
├── scripts/             # Guiones de cada lección (texto del video)
├── course-plan.md       # Plan completo del curso con enlaces a videos y CodePens
└── README.md
```

**Repositorio completo:** [github.com/upc-pre-202610-1asi0730-12053-goldmetri/webdev-course-goldmetrics](https://github.com/upc-pre-202610-1asi0730-12053-goldmetri/webdev-course-goldmetrics.git)

---

## ▶️ Cómo usar este repositorio

1. Mira el video de la lección correspondiente (enlaces en la tabla de abajo).
2. Abre el archivo starter de `starter-files/` como punto de partida, o usa el enlace de CodePen para programar directamente en línea.
3. Sigue el guion en `scripts/` si quieres leer el contenido de la lección.
4. Compara con el ejemplo terminado en `completed-examples/` cuando acabes.

No necesitas instalar nada. Abre los archivos `.html` directamente en tu navegador (doble clic) o usa CodePen en línea — **sin descargas ni registros**.

---

## 📚 Lecciones

| # | Tema | Duración | Video | Práctica |
|---|------|----------|-------|----------|
| 1 | ¿Qué es el desarrollo web? | 5 min | [Ver](https://youtu.be/7rcnYVt0u8c) | [CodePen](https://codepen.io/Course-Gm/pen/NPdpOwE) |
| 2 | Introducción a HTML | 10 min | [Ver](https://www.youtube.com/watch?v=example-link2) | [CodePen](https://codepen.io/Course-Gm/pen/azpJRQB) |
| 3 | Añadir más elementos HTML | 8 min | [Ver](https://www.youtube.com/watch?v=example-link3) | [CodePen](https://codepen.io/Course-Gm/pen/VYPpEVr) |
| 4 | Introducción a CSS | 10 min | [Ver](https://youtu.be/KuApcleVRDM) | [CodePen](https://codepen.io/Course-Gm/pen/RNKpYLr) |
| 5 | Estilo Simple | 8 min | [Ver](https://youtu.be/7rcnYVt0u8c) | [CodePen](https://codepen.io/Course-Gm/pen/myRWGBP) |
| 6 | Crear una página web sencilla | 15 min | [Ver](https://www.youtube.com/watch?v=example-link5) | [Replit](https://replit.com/@your-final-project) |
| 7 | Consejos y próximos pasos | 5 min | [Ver](https://youtu.be/gHqPT2egiDY) | [CodePen](https://codepen.io/Course-Gm/pen/NPdpOMo) |

---

### 1️⃣ ¿Qué es el desarrollo web?

¡Bienvenidos al inicio de este curso! Exploraremos qué es realmente una página web y cómo tecnologías como HTML y CSS trabajan juntas para crear todo lo que ves en internet, desde tus redes sociales favoritas hasta grandes tiendas virtuales. Descubriremos que el navegador funciona como un "cocinero" que interpreta una "receta" de código para entregarnos el sitio terminado.

**Consejos clave:**
- **Contenido vs. Estilo:** un sitio web es la combinación perfecta de estructura (HTML) y diseño visual (CSS).
- **La analogía del cuerpo:** HTML es el esqueleto que sostiene todo, mientras que CSS es la ropa y decoración que le da color y personalidad.
- **Frontend vs. Backend:** el Frontend es la fachada o el comedor que los clientes ven; el Backend es la cocina interna donde se procesan los datos y las reglas del sitio.
- **Sin instalaciones:** no necesitas programas complejos; los navegadores son las únicas herramientas necesarias.

---

### 2️⃣ Introducción a HTML

Aprende la estructura base de un documento HTML desde cero. Construye tu primera página web con párrafos, imágenes y enlaces usando la práctica **"Animales del Hogar"**.

**Consejos clave:** Usa `<!DOCTYPE html>`, `<html>`, `<head>`, `<body>`, `<p>`, `<img>`, `<a>`, `<br>`.

---

### 3️⃣ Añadir más elementos HTML

Domina los encabezados (`<h1>` a `<h6>`), listas ordenadas y desordenadas. Integra todos los elementos en la práctica **"Libros que te Gusten"**, creando una biblioteca digital.

**Consejos clave:** Usa `<h1>`–`<h6>`, `<ul>`, `<ol>`, `<li>`, `<strong>`, `<div>`.

---

### 4️⃣ Introducción a CSS

¿Cansado de que tus páginas web parezcan un esqueleto aburrido? Aprenderás a usar CSS (Cascading Style Sheets), el lenguaje de diseño que permite controlar el aspecto visual de tus sitios: cómo conectar tu código, la anatomía de una línea de CSS y la diferencia entre seleccionar por etiqueta o por clase. Práctica: **"El Mundo de las Témperas"**.

**Consejos clave:**
- **CSS es el guardarropa:** si HTML es el esqueleto (estructura), CSS es la ropa y el estilo que le das a tu página.
- **La anatomía perfecta:** una regla de CSS siempre tiene un selector (a quién cambiamos), una propiedad (qué característica cambiamos) y un valor (cómo se verá el cambio).
- **El punto es la clave:** para aplicar estilos a una clase específica en CSS, siempre debes empezar el nombre con un punto (`.`).
- **Orden profesional:** aunque existen varias formas de agregar estilos, la manera más limpia es referenciar un archivo externo.

---

### 5️⃣ Estilo Simple

¿Ya conoces las bases de CSS pero quieres llevar tu página al siguiente nivel? Aprenderás técnicas simples pero súper efectivas: centrar contenido, las distintas formas de aplicar color, estilo de bordes (rectos y redondeados) y manejo del espaciado con `padding` y `margin`. Práctica: **"Mis Bandas Favoritas"**.

**Consejos clave:**
- **El centrado destaca:** `text-align: center` no es solo decoración, es una forma de decirle al usuario "esto es lo más importante de la página".
- **3 colores, 3 propósitos:** `color` cambia el texto, `background-color` en el `body` cambia toda la página, y `background-color` en un elemento cambia solo esa parte.
- **La fórmula del borde:** todo borde se arma igual: ancho | estilo | color. Cambia esos 3 valores y dominarás `solid`, `dashed` y `dotted`.
- **Adentro vs. afuera:** padding es para adentro, margin es para afuera.

---

### 6️⃣ Crear una página web sencilla

Pon en práctica todo lo aprendido construyendo tu propio proyecto final desde cero.

**Proyecto final:** [Crea tu Perfil](https://replit.com/@your-final-project) — ¡guarda y comparte!

---

### 7️⃣ Consejos y próximos pasos

¡Felicidades por llegar al final! Repasamos los conceptos fundamentales de HTML y CSS explorados durante el curso. Analizaremos los "bugs" o errores más comunes que cometen los principiantes y te daremos recomendaciones para que sigas mejorando tus habilidades digitales.

**Consejos clave:**
- **La regla de las cajas:** la última etiqueta que abres debe ser la primera que cierres; piensa en ello como apilar cajas donde la de arriba se retira primero.
- **Revisa tu ortografía técnica:** un error de escritura en un atributo (como poner `imge` en lugar de `img`) hará que el navegador no entienda tu instrucción.
- **Sincronización de nombres:** si tu diseño de CSS no se aplica, verifica que el nombre de la clase en tu HTML coincida exactamente con el de tu CSS.
- **Práctica constante:** no tengas miedo de equivocarte. Intenta resolver los problemas por tu cuenta antes de buscar la solución.

---

## 🧰 Recursos adicionales

- **Código fuente completo:** [Repositorio de GitHub](https://github.com/upc-pre-202610-1asi0730-12053-goldmetri/webdev-course-goldmetrics.git)
- **Cuestionario:** [Pon a prueba tus conocimientos](https://forms.gle/your-quiz)
- **Comparte:** `#WebDevBeginners`

**¡Gracias por completar el curso!**

---

## 👥 Equipo

Proyecto desarrollado en la **Universidad Peruana de Ciencias Aplicadas** · Ingeniería de Software · Período 202610 · 1ASI0730 Aplicaciones Web · NRC 12053

**Equipo:** GoldMetrics &nbsp;|&nbsp; **Líder del equipo:** Katty Yolanda Philco Mota

| Integrante |
|---|
| Adrián Andres Armestar Felipa |
| Victor Manuel García Paredes |
| Carolina Celeste Navarro Aldoradin |
| Katty Yolanda Philco Mota |
| Kiara Lucia Tuesta Girón |

**Fecha de entrega:** 21 de junio del 2026