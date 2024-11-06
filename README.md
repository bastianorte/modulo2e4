# Modulo 2 Ejercicio 4 

## :pencil2: Autores


Bastian Ortega Fuenzalida

## 📖 Descripción
En esta fase del proyecto, el enfoque estará en la implementación del preprocesador SASS
para gestionar los estilos de forma más eficiente, modularizando correctamente el código y
utilizando metodologías como BEM para organizar los estilos. Además, se integrará el
framework Bootstrap para mejorar la estructura visual y la responsividad del sitio web del
hospital.

Para este proyecto use el patron de organizacion 7-1 dividiendo una carpeta scss(sass) en 7 carpetas(Abtracts, Component, Core, layout, pages, themes, vendor) y el archivo styles.scss

Para la responsividad de este proyecto use Media Queries y Bootstrap

Este es un proyecto web que utiliza Webpack, Bootstrap, y SASS para crear un sitio responsivo con un sistema de navegación. El proyecto incluye páginas como "Inicio", "Equipo Médico" y "Contacto".



## Tecnologías Usadas

- **Webpack**: Para la gestión de módulos y la optimización de los activos.
- **Bootstrap**: Para estilos responsivos y componentes predefinidos.
- **SASS**: Para la escritura de estilos en CSS con características adicionales como variables y anidamiento.
- **JavaScript (ES6)**: Para la lógica del cliente.

## Estructura del Proyecto


- **/src/html**: Contiene las páginas HTML del proyecto.
- **/src/js**: Contiene los archivos JavaScript.
- **/src/scss**: Contiene los archivos SASS para estilos.
- **/src/images**: Contiene las imágenes utilizadas en el proyecto.
- **/dist**: Carpeta generada automáticamente que contiene los archivos listos para producción.

## Instalación

1. Clona este repositorio:
   ```bash
   git clone https://github.com/FabianPena/proyecto-base.git
   cd tu-repo

2. Instala las dependencias:
   ```bash
   npm install
3. Para iniciar el servidor de desarrollo, ejecuta:
   ```bash
   npm start

Esto abrirá el proyecto en http://localhost:8080.

4.- Para compilar el proyecto para producción, ejecuta:
   ```bash
   npm run build

Esto generará los archivos optimizados en la carpeta dist.


