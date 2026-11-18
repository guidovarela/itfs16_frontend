# Tienda de Vino

Proyecto de cursada de **Desarrollo de Sistemas Web (Front End), 2.º cuatrimestre de 2026**.

Sitio web institucional para una tienda de vinos. Presenta el catálogo y contenido sobre vinos, platos, locales, tutoriales, franquicias, contacto y oportunidades de trabajo.
Esta clonada de la página de [Tienda de Cafe](https://tiendadecafe.com.ar/), que es un proyecto de ejemplo para aprender desarrollo web.

**Sitio publicado (Deploy):** [tiendadevino.vercel.app](https://tiendadevino.vercel.app/)

## Página de inicio

La página principal (`index.html`) está organizada en estas secciones:

- **Navegación:** acceso a las distintas páginas del sitio.
- **Portada:** presentación de vinos recomendados y enlace a los productos.
- **Productos:** selección de vinos con imágenes.
- **Promoción:** acceso a la página del menú.
- **Información sobre vinos:** descripciones de variedades y estilos.
- **Locales:** mapa de Buenos Aires integrado desde OpenStreetMap.
- **Pie de página:** enlaces de navegación, formulario de suscripción y redes sociales.

## Tecnologías

- **HTML5:** estructura semántica y contenido de las páginas.
- **CSS3:** estilos, diseño adaptable a distintos tamaños de pantalla y preferencias de movimiento reducido.
- **Google Fonts:** tipografía Oswald, cargada desde Google Fonts.
- **Font Awesome:** icono del menú, cargado desde cdnjs.
- **OpenStreetMap:** mapa integrado mediante un `iframe`.
- **Vercel:** alojamiento y publicación del sitio estático.

## Estructura del proyecto

```text
.
├── index.html
├── vinos.html
├── tutoriales.html
├── locales.html
├── nuestros-platos.html
├── trabaja-con-nosotros.html
├── franquicias.html
├── contacto.html
├── css/
│   └── styles.css
└── assets/
    └── images/
```

Las páginas HTML comparten la hoja de estilos `css/styles.css`. Las imágenes del sitio se guardan en `assets/images/`;

## Ejecutar localmente

No hace falta instalar dependencias. Se puede abrir `index.html` directamente en un navegador o servir la carpeta raíz con un servidor HTTP local, por ejemplo:

## Deploy en Vercel

El sitio publicado está disponible en [https://tiendadevino.vercel.app/](https://tiendadevino.vercel.app/). Al ser un sitio estático, no requiere una etapa de build.


## Recursos externos

La visualización de algunas partes depende de servicios externos: Google Fonts, cdnjs (Font Awesome) y OpenStreetMap. Si alguno de esos servicios no está disponible, las páginas siguen usando sus estilos y contenidos locales, aunque la tipografía, el icono o el mapa integrado podrían no cargarse.
