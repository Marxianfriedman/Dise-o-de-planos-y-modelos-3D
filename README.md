# Diseño de Planos y Modelos 3D

Página web para servicios de diseño de planos arquitectónicos y modelos tridimensionales.

## Tecnologías

- Vue.js 3
- Vite

## Instalación

1. Clona el repositorio
2. Instala dependencias: `npm install`
3. Ejecuta el servidor de desarrollo: `npm run dev`
4. Construye para producción: `npm run build`

## Despliegue

Para alojar gratuitamente en GitHub Pages:

1. Crea un repositorio en GitHub
2. Sube el código: `git remote add origin <url>` `git push -u origin master`
3. Habilita GitHub Pages en la configuración del repositorio, seleccionando la rama master y carpeta root.

Nota: Para despliegue automático, instala gh-pages: `npm install --save-dev gh-pages` y añade script "deploy": "npm run build && gh-pages -d dist" en package.json, luego `npm run deploy`
