# Rueda Libre — Proyecto académico RIWI

Sitio web de demostración para el alquiler de bicicletas y los recorridos guiados en Medellín. Incluye una sección de experiencias nocturnas y un portafolio de aprendizaje.

**Autor:** Ramael Gonzalez  
**Repositorio:** https://github.com/Ramael-L/Semana1

> Este es un proyecto académico. Los formularios **no envían ni almacenan** información personal ni confirman reservas. Utiliza datos ficticios para probarlos.

## Páginas

| Archivo | Contenido |
| --- | --- |
| `index.html` | Inicio, servicios, rutas, flota y beneficios |
| `paginas/tarifas.html` | Tablas de tarifas y recorridos |
| `paginas/reservas.html` | Horarios y formulario validado en el navegador |
| `nocturna/index.html` | Rutas nocturnas y formulario de inscripción |
| `nocturna/prototipo.html` | Primera propuesta visual de la campaña |
| `nocturna/componentes.html` | Ejemplos de botones, tarjeta, alertas y campos |
| `Portafolio/Portafolio.html` | Portafolio personal con proyectos |
| `css/styles.css` | Estilos compartidos del sitio principal |
| `bitacora.txt` | Conceptos, decisiones y registro de trabajo |
| `GUIA_ESTUDIO.md` | Resumen para explicar el código |

## Tecnologías y decisiones

- **HTML semántico:** `header`, `nav`, `main`, `section`, `article`, `aside` y `footer`.
- **CSS:** una hoja compartida, variables en `:root`, Grid, Flexbox y media queries `min-width` (mobile-first).
- **Tailwind CSS:** enlazado por CDN en Rueda Nocturna y el portafolio, siguiendo la indicación del profesor.
- **Bootstrap:** un ejemplo *opcional y mínimo* para aprender: un aviso `alert` en `nocturna/index.html` y un distintivo `badge` en el portafolio. Se carga el CSS por CDN, **sin** añadir JavaScript de Bootstrap ni trasladar el proyecto a Bootstrap.
- **JavaScript:** únicamente validación nativa de HTML y un aviso de demostración con `alert()` y `preventDefault()`. No hay backend.

La práctica con Tailwind CLI y la implementación extensa de Bootstrap **no se realizan** porque el profesor permitió usar Tailwind por CDN e ignorar los ejercicios amplios de Bootstrap.

## Cómo abrir el proyecto

1. Descomprime el ZIP y abre la carpeta `Semana1` en VS Code.
2. Abre `index.html` con Live Server.
3. Desde el menú visita Tarifas, Reservas y Rueda Nocturna.
4. Abre `Portafolio/Portafolio.html` para ver el portafolio.
5. Conéctate a internet para que carguen Tailwind, Bootstrap y las fuentes externas.

## Comprobaciones realizadas sobre los archivos

- Los siete documentos HTML incluyen un `h1` cada uno.
- Las rutas **locales** a imágenes, páginas y estilos se revisaron y no se detectaron archivos ausentes.
- Se revisaron los enlaces internos con fragmentos `#id` y los identificadores duplicados.
- Se corrigió el anidamiento de las tres tarjetas de proyectos del portafolio.
- Se agregaron diseños responsive para las rutas nocturnas y los cuatro pasos.
- La flota de bicicletas usa `auto-fit` para reorganizar tarjetas sin reglas particulares por tamaño de pantalla.
- Reservas incluye una fila de dos campos relacionados y un límite de 300 caracteres en comentarios.

Estas son **comprobaciones estáticas**, no sustituyen la revisión real del navegador.

## Pendiente de comprobar en tu ordenador

- [ ] Probar con Live Server a 360, 768, 1024 y 1280 píxeles. Revisar que no haya scroll horizontal y que se vean las tablas.
- [ ] Comprobar que Nocturna mantenga sus colores oscuros en móviles y escritorio.
- [ ] En DevTools → Network, comprobar que no haya errores 404 ni fallos al cargar los recursos CDN.
- [ ] Probar el formulario vacío, datos erróneos, datos válidos y recorrido con la tecla Tab.
- [ ] Validar `paginas/reservas.html` y `nocturna/index.html` en https://validator.w3.org/ y corregir errores si aparecen.
- [ ] Publicar el proyecto en GitHub Pages y anotar su URL aquí.
- [ ] Guardar capturas de escritorio, móvil y Rueda Nocturna de la publicación final.
- [ ] Ensayar la presentación de tres minutos y registrar la opinión de un compañero.
- [ ] Sustituir el número pendiente de WhatsApp por uno autorizado antes de habilitar el enlace. El correo `.example` también es demostrativo.

**URL publicada:** pendiente de confirmar por el autor.

## Cómo defender las decisiones ante el profesor

- **¿Por qué Grid para tarjetas?** Porque organiza filas y columnas a la vez.
- **¿Por qué Flexbox dentro de las tarjetas?** Porque alinea su contenido verticalmente y deja el botón al final.
- **¿Por qué `div`?** Porque algunos contenedores solo organizan el diseño y no representan una sección independiente.
- **¿Por qué Tailwind?** Porque sus clases permiten ajustar el diseño sin crear un CSS extra para la landing.
- **¿Para qué sirve el pequeño ejemplo de Bootstrap?** Para mostrar un componente ya preparado: un `alert` o un `badge`.
- **¿Se envía realmente el formulario?** No. El navegador valida los campos y el aviso confirma que es una demostración.
