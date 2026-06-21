# Lección 3: Elementos HTML Comunes

## Datos del módulo

- **Duración estimada**: 6:45 - 7:30 minutos
- **Público objetivo**: Estudiantes de secundaria de 12 a 17 años sin conocimientos previos de programación
- **Herramientas en pantalla**: Navegador web con CodePen.io en pantalla completa y zoom aumentado (Ctrl +)

## 1. Introducción y la estructura de un Elemento (0:00 - 1:00)

- Repaso del módulo anterior: siempre se inicia desde el esqueleto estándar
- Un elemento HTML completo se compone de: etiqueta de apertura, contenido y etiqueta de cierre
- Objetivo del módulo: dar orden y jerarquía visual a los datos

```html
<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <title>Mis Libros Favoritos</title>
</head>
<body>

</body>
</html>
```

## 2. Demostración de la Jerarquía de Encabezados (1:00 - 2:30)

- Seis niveles de encabezados: `<h1>` a `<h6>` (h = heading = encabezado)
- `<h1>` es el más importante, solo uno por documento como buena práctica
- Conforme aumenta el número, el tamaño disminuye automáticamente
- No se usan solo para cambiar tamaño de letra, sino para dar estructura y jerarquía lógica
- Importancia para buscadores (Google) y lectores de pantalla (accesibilidad)

```html
<h1>Título Principal (Nivel h1)</h1>
<h2>Subtítulo Importante (Nivel h2)</h2>
<h3>Sección del Módulo (Nivel h3)</h3>
<h4>Subsección Temática (Nivel h4)</h4>
<h5>Detalle de la Lección (Nivel h5)</h5>
<h6>Nota al pie o aclaración (Nivel h6)</h6>
```

## 3. Listas Ordenadas y Desordenadas (2:30 - 4:30)

### Lista desordenada

- `<ul>`: Unordered List (Lista Desordenada), muestra viñetas (puntos)
- `<li>`: List Item (Elemento de Lista)
- Se usa cuando el orden no es relevante

```html
<p>Lista de Compras del Hogar (Sin orden específico):</p>
<ul>
    <li>Manzanas</li>
    <li>Leche entera</li>
    <li>Pan integral</li>
</ul>
```

### Lista ordenada

- `<ol>`: Ordered List (Lista Ordenada), enumera automáticamente
- Se usa para procesos secuenciales, recetas o clasificaciones

```html
<p>Pasos para preparar un Sándwich (Con orden estricto):</p>
<ol>
    <li>Cortar el pan a la mitad</li>
    <li>Colocar el jamón y queso</li>
    <li>Tostar el pan por dos minutos</li>
</ol>
```

## 4. Práctica Integradora: "Libros que te Gusten" (4:30 - 7:00)

Maquetación de una biblioteca digital del libro *La Ciudad y los Perros* integrando todos los elementos aprendidos:

- Imagen decorativa con `<img>` centrada usando `<div>` con estilo inline
- Jerarquía completa de encabezados: `<h1>` (título del portal), `<h2>` (nombre del libro), `<h3>` (autor), `<h4>` (sección de resumen), `<h5>` (ficha técnica), `<h6>` (personajes)
- Párrafo `<p>` con resumen de la obra
- Lista ordenada `<ol>` para ficha técnica (año, editorial, género)
- `<strong>` para resaltar texto en negrita dentro de los elementos de lista
- Lista desordenada `<ul>` para personajes destacados
- Enlace `<a>` a Google Books

## 5. Cierre técnico (7:00 - 7:30)

- Recomendación: verificar siempre que cada etiqueta abierta tenga su cierre correspondiente
- Adelanto de la siguiente lección: "Introducción a CSS" (colores, estilos, fuentes)
