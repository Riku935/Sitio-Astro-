---
setup: |
  import Layout from '../../layouts/BlogPost.astro'
  import Cool from '../../components/Author.astro'
title: Sitio de Riku!
publishDate: 28 Abril 2022
name: Ricardo Calderon
value: 128
description: Mi primer sitio en Astro!
---

## Aqui va mi primer post!

<Cool name={frontmatter.name} href="https://www.youtube.com/watch?v=dQw4w9WgXcQ" client:load />

----

Luis Ricardo Calderon Rios

Correo GitHub: exodo302.richy@gmail.com

Correo academico: cdmx2001@amerike.edu.mx

![Foto de perfil](/public/assets/blog/Perfil.jpg)

```
// Comandos para iniciar Astro

mkdir carpeta-proyecto
cd carpeta-proyecto
npm create astro@latest
# en el asistente de instalación escribir:
#   y
#   .
#   elegir un template
npm install

// Comenzar la aplicación en local
npm start
// Construir el sitio para producción
npm run build

```
