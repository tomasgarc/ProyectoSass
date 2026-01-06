Proyecto SASS - Mini web corporativa

Descripción:
Este proyecto es una práctica de la asignatura Diseño de Interfaces Web del IES Mar de Cádiz. La web tiene tres páginas: Inicio, Servicios y Contacto. Todo se ha desarrollado usando SASS para manejar los estilos de forma más organizada, con variables, mixins, funciones y anidamiento. Además, se ha implementado un footer que siempre se mantiene abajo y el contenido ocupa toda la altura de la pantalla.

Tecnologías:
HTML5, SASS como preprocesador CSS, CSS generado automáticamente a partir de SASS, y Visual Studio Code con la extensión Live Sass Compiler.

Estructura del proyecto:
La carpeta principal contiene los archivos HTML de cada página. Los estilos están en la carpeta scss, divididos en subcarpetas: abstracts (variables, mixins, funciones), base (reset y tipografía), layout (header, footer, main), components (botones, cards) y pages (estilos específicos de cada página). El archivo main.scss importa todos los parciales y genera el main.css dentro de la carpeta css, que es el que carga el navegador.

Cómo usarlo:
Abrir la carpeta del proyecto en VS Code, activar Live Sass Compiler y Watch Sass sobre main.scss para generar automáticamente el main.css. Luego abrir cualquiera de las páginas en el navegador o usar Live Server. No hay que modificar main.css manualmente, ya que se genera automáticamente desde SASS.

Qué incluye este proyecto:

Variables globales para colores, tipografía y espaciado.

Mixins para centrar contenido y reutilizar estilos.

Funciones para tamaños relativos, usando rem.

Anidamiento para un CSS más limpio y organizado.

Footer que siempre se queda abajo aunque el contenido sea pequeño.

Layout adaptable a diferentes tamaños de pantalla.

Cambiar colores o tamaños:
Para cambiar colores o tipografía basta con editar las variables en scss/abstracts/_variables.scss. Por ejemplo, cambiando $primary-color, $secondary-color o $text-color, los cambios se aplicarán automáticamente a toda la web al guardar.

Integrantes del grupo:

Tomás García Chaves

Hugo Gil Bailón

Adulis Esteban López Tirado

Hector Ramos Fernández
