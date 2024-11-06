# Modulo 2 Ejercicio 4 


## 📖 Descripción
En esta última fase del proyecto, los estudiantes trabajarán en parejas y deberán elegir uno
de los dos proyectos que han desarrollado individualmente (proyecto de uno de los dos
estudiantes). A partir de ese proyecto, deberán trabajar juntos para completar y mejorar las tres
vistas principales: Home, Equipo Médico y Contacto, aplicando las metodologías aprendidas
a lo largo del módulo.

Además de mejorar el diseño y la funcionalidad, deberán usar SASS para modularizar los
estilos, integrar Bootstrap para estructurar el diseño visual, y asegurarse de que el sitio sea
completamente responsivo.

Para este proyecto use el patron de organizacion 7-1 dividiendo una carpeta scss(sass) en 7 carpetas(Abtracts, Component, Core, layout, pages, themes, vendor) y el archivo styles.scss

Para la responsividad de este proyecto use Media Queries y Bootstrap

Este es un proyecto web que utiliza Webpack, Bootstrap, y SASS para crear un sitio responsivo con un sistema de navegación. El proyecto incluye páginas como "Inicio", "Equipo Médico" y "Contacto".

## 📁 Proyecto 
```
├── src     
│   ├── scss (Organización SASS 7-1.)
│   │    ├── abstracts
│   │    │     ├── _mixins.scss
│   │    │     └── _variables.scss
│   │    ├── component
│   │    │     ├── _buttons.scss
│   │    │     ├── _cart.scss
│   │    │     └── _slider.scss
│   │    ├── core
│   │    │     ├── _reset.scss
│   │    │     └── _typography.scss
│   │    ├── layout
│   │    │     ├── _banner.scss
│   │    │     ├── _footer.scss
│   │    │     └── _header.scss
│   │    ├── pages
│   │    │     ├── _contacto.scss
│   │    │     ├── _equipo.scss
│   │    │     └── _home.scss
│   │    ├── themes
│   │    │     └── _dark.scss
│   │    ├── vendors
│   │    │     └── carpeta bootstrap
│   │    │      
│   │    └── styles.scss
│   ├── images
│   │    └── ..images**
│   │── HTML
│   │    ├── contacto.html  
│   │    ├── equipo.html 
│   │    └── index.html 
│   └──  js    
│         └── js**       
│
│── Archivos Webpack y Package
│                
```

- **/src/scss**: Contiene los archivos SASS para estilos.
- **/src/images**: Contiene las imágenes utilizadas en el proyecto.
- **/src/html**: Contiene las páginas HTML del proyecto.
- **/src/js**: Contiene los archivos JavaScript.



## 👁️ Instalación

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

```
## 🔧 Tecnologías Usadas

- **Webpack**: Para la gestión de módulos y la optimización de los activos.
- **Bootstrap**: Para estilos responsivos y componentes predefinidos.
- **BoxIcons**: Para tener una biblioteca de íconos escalables y personalizables.
- **SASS**: Para la escritura de estilos en CSS con características adicionales como variables y anidamiento.
- **JavaScript (ES6)**: Para la lógica del cliente.

## :pencil2: Autores

Natalia Albornoz Parra

Bastian Ortega Fuenzalida

Nadja Villarroel Navarro


