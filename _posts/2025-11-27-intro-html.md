---
layout: post
title: "Introduccion a HTML"
author: "Paul Le"
categories: journal
tags: [documentation,sample]
image: html1.jpg
---

# Introduccion

Si alguna vez te has preguntado cómo se construyen las páginas web que ves todos los días —desde el marcador en vivo de una transmisión de fútbol hasta el análisis táctico interactivo en un blog deportivo— todo comienza con **HTML**.

HTML, o **HyperText Markup Language**, es el lenguaje estándar para crear y estructurar contenido en la web. No es un lenguaje de programación, sino un *lenguaje de marcado*: define la estructura de una página mediante *etiquetas* que indican qué es cada parte del contenido (títulos, párrafos, imágenes, enlaces, etc.).

## ¿Qué significa "HTML"?

- **HyperText**: Texto que contiene enlaces a otros textos (o recursos), permitiendo la navegación no lineal.
- **Markup**: Se "marca" el contenido con etiquetas que describen su función y jerarquía.
- **Language**: Es un lenguaje formal con reglas sintácticas bien definidas.



## 📐 Estructura básica de un documento HTML

Todo documento HTML5 válido comienza con esta estructura mínima:

```html
<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <title>Mi primera página</title>
</head>
<body>
  <h1>¡Hola, mundo del fútbol!</h1>
  <p>Este es un párrafo. ¿Sabías que el primer gol del Clásico en 2025 fue un tiro desde fuera del área?</p>
</body>
</html>
```