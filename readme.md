# Portfolio Personal - Lorenzo Rojic

## Sobre el proyecto

Portfolio web personal desarrollado con HTML y CSS para la materia Laboratorio de Algoritmos y Estructuras de Datos. Incluye las secciones Sobre mi, Proyectos, Habilidades tecnicas y Contacto, pensado como base para sumarle un blog mas adelante.

Tecnologias usadas: HTML5, CSS3 (Flexbox y Grid, variables CSS), Google Fonts (Poppins), FontAwesome y un script simple en JavaScript para el modo oscuro/claro.

## Bitacora de investigacion

- Etiquetas semanticas de HTML: uso de header, main, section y footer en vez de div genericos.
- CSS Grid vs Flexbox: Grid para la grilla de proyectos (se adapta sola al ancho de pantalla), Flexbox para navbar, habilidades y contacto.
- Variables CSS en :root: centralizar la paleta de colores para reutilizarla y cambiarla facil, incluido el modo oscuro.
- Modo oscuro/claro: clase dark-mode en el body togglada con JavaScript, combinada con variables CSS que cambian de valor.
- Google Fonts: como importar Poppins con un link en el head y aplicarla con font-family.
- FontAwesome: como linkear la libreria por CDN y usar iconos para redes y habilidades.
- Imagenes circulares con doble borde: efecto medalla combinando border-radius 50%, padding, background y box-shadow.
- Navbar fija con scroll suave: position sticky y scroll-behavior smooth para los links del menu.
- Formulario de contacto: envio por mail con action mailto, method post y enctype text/plain, sin backend.