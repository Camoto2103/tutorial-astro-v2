---
layout: ../../layouts/MarkdownPostLayout.astro
title: Mi cuarta entrada en el blog
author: Alumno de Astro
description: "Usando Markdown en Astro"
image:
  url: "https://docs.astro.build/default-og-image.png"
  alt: "La palabra 'astro' contra una ilustración de planetas y estrellas."
pubDate: 2025-08-17
tags: ["astro", "éxitos"]
---
Astro facilita la creación de blogs y sitios web modernos gracias a su soporte para Markdown y plantillas anidadas. En esta publicación, te cuento cómo se estructura una página de blog usando estas herramientas.

## 1. Plantilla principal

La plantilla principal define la estructura general de tu sitio: incluye los estilos globales, la navegación y el pie de página con enlaces sociales. Así, todas las páginas mantienen una apariencia consistente.

## 2. Plantilla de publicación de blog

Cada entrada del blog utiliza una plantilla específica, como `MarkdownPostLayout.astro`. Esta plantilla lee las propiedades del *frontmatter* (la sección entre líneas `---` al inicio del archivo), como el título, la descripción, la fecha y la imagen destacada. Así, puedes personalizar cada publicación fácilmente.

## 3. Contenido en Markdown

El contenido de cada publicación se escribe en Markdown, lo que permite enfocarte en el texto y la estructura sin preocuparte por el HTML. Puedes usar títulos, listas, enlaces, imágenes y mucho más de forma sencilla.

---

**En resumen:**  
Astro te permite separar la estructura (plantillas) del contenido (Markdown), haciendo que tu flujo de trabajo sea más ordenado y eficiente. ¡Explora y experimenta con tus
