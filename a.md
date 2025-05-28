/* Rojo intenso (#D32F2F):

Botones principales (CTA)

Encabezados importantes

Íconos o detalles destacados

Enlaces y elementos interactivos


Marrón oscuro (#5D4037):

Texto principal (párrafos, descripciones)

Bordes o sombras suaves en tarjetas o secciones

Fondo de pie de página (footer)


Blanco hueso (#FFF8E1):

Fondo general de la página

Fondos de secciones principales para que luzcan limpias y frescas

Fondos de tarjetas o bloques de contenido


Naranja cálido (#F57C00):

Hover o estados activos de botones y enlaces

Pequeños acentos decorativos (líneas, iconos secundarios)


Amarillo mostaza (#FBC02D):

Etiquetas o badges de promociones o novedades

Destacar precios o elementos especiales


Negro carbón (#212121):

Texto secundario o menos importante

Íconos y elementos gráficos contrastantes */



/* 1. Usa box-sizing más predecible */
*,
*::before,
::after {
  box-sizing: border-box;
}

/* 2. Elimina márgenes y paddings innecesarios  */
body,
h1, h2, h3, h4, h5, h6,
p, figure, blockquote,
dl, dd {
  margin: 0;
  padding: 0;
}

/* / 3. Mejora el rendering del texto / */
body {
  line-height: 1.5;
  -webkit-font-smoothing: antialiased;
  text-rendering: optimizeLegibility;
  font-family: system-ui, sans-serif;
}

/* / 4. Quita la decoración de enlaces / */
a {
  text-decoration: none;
  color: inherit;
}

/* / 5. Imágenes adaptables / */
img,
picture {
  max-width: 100%;
  display: block;
}

/* / 6. Formularios coherentes / */
input,
button,
textarea,
select {
  font: inherit;
}

/* / 7. Elimina listas decorativas / */
ul[role='list'],
ol[role='list'] {
  list-style: none;
}

/* / 8. Mejora del scroll */ */
html:focus-within {
  scroll-behavior: smooth;
}