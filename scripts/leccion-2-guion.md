# Lección 2: Estructura HTML Básica

## Datos del módulo

- **Duración estimada**: 6:45 - 7:30 minutos
- **Público objetivo**: Estudiantes de secundaria de 12 a 17 años sin conocimientos previos de programación
- **Herramientas en pantalla**: Navegador web con CodePen.io en pantalla completa y zoom aumentado (Ctrl +)

## 1. Introducción y la analogía del esqueleto (0:00 - 1:00)

- Analogía: una página web es como el cuerpo humano, necesita un esqueleto para mantenerse en pie
- HTML = HyperText Markup Language (Lenguaje de Marcado de Hipertexto)
- Presentación de CodePen como editor en línea gratuito

## 2. Escribiendo la estructura base desde cero (1:00 - 2:45)

- Declaración `<!DOCTYPE html>`: aviso al navegador de que el documento es HTML5
- Etiqueta contenedora `<html lang="es">`: todo el código vive dentro de ella
- Atributo `lang="es"`: define el idioma del sitio (language = idioma)
- Concepto de etiquetas de apertura y cierre

```html
<!DOCTYPE html>
<html lang="es">

</html>
```

## 3. El `<head>` vs el `<body>` (2:45 - 4:15)

- `<head>`: configuración oculta, invisible para el usuario
- `<meta charset="UTF-8">`: charset = character set (juego de caracteres), permite ñ, tildes y emojis
- `<title>`: texto que aparece en la pestaña del navegador
- `<body>`: contenido visible, todo lo que se dibuja en pantalla

```html
<head>
    <meta charset="UTF-8">
    <title>Mi Primera Página Web</title>
</head>
<body>

</body>
```

## 4. Conceptos Clave: Etiquetas y Atributos (4:15 - 5:15)

- `<p>`: paragraph (párrafo), bloque de texto común
- `<br>`: break (ruptura de línea), etiqueta sin cierre
- Atributos: información adicional dentro de la etiqueta de apertura (nombre, signo igual, valor entre comillas)

```html
<p>¡Hola! Estamos aprendiendo las bases del HTML.<br>Este es un salto de línea.</p>
```

## 5. Práctica Dirigida: "Animales del Hogar" (5:15 - 6:45)

Maquetación de fichas informativas para tres animales domésticos utilizando:

- `<p>`: descripción del animal
- `<img>`: imagen con atributos `src` (source = fuente) y `alt` (alternative text = texto alternativo para accesibilidad)
- `<br>`: salto de línea
- `<a>`: anchor (ancla), hipervínculo con atributo `href` (hypertext reference = referencia de hipertexto)

Animales incluidos: Perros, Tortugas, Aves. Cada ficha sigue la misma estructura: párrafo, imagen, salto de línea, enlace a National Geographic.

## 6. Cierre (6:45 - 7:15)

- Repaso de lo aprendido: etiquetas, atributos, enlaces e imágenes
- Adelanto de la siguiente lección: "Elementos HTML Comunes" (encabezados y listas)
