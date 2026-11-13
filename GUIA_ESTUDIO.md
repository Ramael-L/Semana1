# Guía breve de términos en  Rueda Libre

**HTML** organiza el contenido; **CSS** define su apariencia; **Tailwind** ofrece clases listas para combinar.

- `header`: cabecera de una página o sección;
 `nav`: grupo de enlaces de navegación; 
 `main`: contenido principal; 
 `footer`: pie de página.
- `section`: agrupa contenido de un tema con encabezado; 
`article`: tarjeta independiente (un servicio o una bicicleta); 
`div`: contenedor sin significado propio, útil para Grid.
- `h1`, `h2`, `h3`: jerarquía de títulos; 
`p`: párrafo; `a` + 
`href`: enlace; `img` + `alt`: imagen y texto alternativo.
- `ul` / `li`: lista sin orden; 
`dl` / `dt` / `dd`: términos y descripciones (días y horarios).
- `table`: datos tabulares; 
`caption`: título de tabla; 
`thead`, `tbody`: grupos de filas; 
`th scope="col"` y `scope="row"`: encabezados de columna y fila.
- `form`: formulario; 
`label for` + `input id`: asocian texto con campo; 
`fieldset` y `legend`: agrupan entradas; `required`, `min`, `max`, `pattern`: validación del navegador.
- `:root`: lugar para declarar variables CSS; `var(--nombre)`: usar una variable ya declarada; reutilizar evita copiar colores y tamaños.
- `display: flex`: organiza elementos en una dirección; `gap`: espacio entre ellos; `display: grid`: filas y columnas; `@media`: cambia reglas según pantalla.
- Tailwind `p-6` agrega relleno; `grid`, `sm:grid-cols-2`, `lg:grid-cols-3` organizan tarjetas con enfoque mobile-first; `hover:` y `focus-visible:` expresan estados.

