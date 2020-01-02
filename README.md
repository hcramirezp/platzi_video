# platzi_video
Sitio de consulta de videos escuela JavaScript

## Versión 1.0
Construcción de la página principal y del menú de acceso al sitio.

Incluye lo siguiente:
* Se crea la sección Header del sitio y al encabezado de la página se incluye el logo de Platzi Video. 
* Se asigna la clase header y se crea el menú de ingreso a la aplicación, el cual incluye una imagen, el texto *"Perfil"* y las opciones *"Cuenta"* y *"Cerrar Sesión"*.  
* El menú debe mostrarse cuando el usuario pasa el puntero del mouse sobre la imagen de usuario o la palabra Perfil.
* Se configuran los estilos para cada uno de los elementos creados en esta versión en el archivo *estilos.css*.

---------------------------
## Versión 1.1
Construcción de un input para realizar busquedas.

Incluye lo siguiente:
* Se crea una sección en la cual contiene un campo que se utilizará para hacer las búsquedas en el sitio. 
* Se asigna la clase main a esta sección, la cual incluye un título y un input con la etiqueta *"Buscar..."* 
* Al campo de búsqueda se asigna la clase input.
* Se configuran los estilos para cada uno de los elementos creados en esta versión en el archivo *estilos.css*.

---------------------------
## Versión 1.2
Construcción del carrusel de imágenes donde se va a hacer la selección de los videos.

Incluye lo siguiente:
* Se crea una sección la cual contiene una serie de items que cada uno corresponde a un video.
* Cada ítem contiene una imágen descriptiva del video a seleccionar.
* Para cada ítem del carrusel, se incluyen dos botones y un texto descriptivo. 
* Se asigna la clase carousel a esta sección, la cual incluye un ítem para cada video. 
* Se configuran los estilos para cada uno de los elementos creados en esta versión en el archivo *estilos.css*.


Creación de la página de inicio de sesión de la aplicación (archivo *login.html*).

Incluye lo siguiente:
* Se crea la sección Header del sitio y al encabezado de la página se incluye el logo de Platzi Video.
* Se crea una sección en donde se incluye el formulario de inicio de sesión, se asigna la clase login.
* El formulario de inicio de sesión, incluye dos campos llamados *"Correo"* y *"Contraseña"* y el botón 
  *"Iniciar sesión"*.
* En el formulario también aparece un checkbox con la etiqueta *"Recuerdame"* y un enlace con el texto 
  *"Olvidé mi contraseña"*.
* Se crea la sección footer para la página, que incluye tres enlaces correspondientes a *"Términos de uso"*,   *"Declaración de privacidad"* y *"Centro de ayuda"*. Se asigna la clase footer a esta sección.
* Se configuran los estilos para cada uno de los elementos creados en esta página en el archivo *styles.css*.

---------------------------
## Versión 1.3
Creación de la página de registro de usuario nuevo de la aplicación (archivo *register.html*).

Incluye lo siguiente:
* Se crea la sección Header del sitio y al encabezado de la página se incluye el logo de Platzi Video.
* Se crea una sección para el formulario de registro de usuario, se asigna la clase register.
* El formulario de registro de usuario incluye tres campos llamados *"Nombre"*, *"Correo"* y *"Contraseña"* y el botón *"Registrarme"*. 
* En el formulario también aparece un enlace con el texto *"Iniciar sesión"*.
* Se crea la sección footer para la página, que incluye tres enlaces correspondientes a *"Términos de uso"*,   *"Declaración de privacidad"* y *"Centro de ayuda"*. Se asigna la clase footer a esta sección.
* Se configuran los estilos para cada uno de los elementos creados en esta página en el archivo *styles.css*.

---------------------------
## Versión 1.4
Se agregan media queries.

Incluye lo siguiente:
* Se crea media query en el archivo *styles.css* que impacta las clases *login__container* y *footer* para generar diseño responsive en la página de inicio de sesión.
* Se crea media query en el archivo *styles.css* que impacta las clases *register__container* y *footer* para generar diseño responsive en la página de registro de usuarios.

---------------------------
## Versión 1.5
Afinamiento de estilos de la página principal.

Incluye lo siguiente:
* Se agregan las secciones *"Tendencias"* y *"Originales de Platzi Video"* , en las que cada una de ellas contiene un carrusel con una serie de items que cada uno corresponde a un video.
* Cada ítem contiene una imágen descriptiva del video a seleccionar.
* Para cada ítem del carrusel, se incluyen dos botones y un texto descriptivo. 
* Se asigna la clase carousel a estas secciones. 
* Se configuran los estilos para cada uno de los elementos creados en esta versión en el archivo *estilos.css*.

---------------------------
## Versión 1.6
Creación de la página para el mensaje de error 404 (archivo *errorpage.html*).

Incluye lo siguiente:
* Se crea la sección Header del sitio y al encabezado de la página se incluye el logo de Platzi Video.
* Se crea una sección para el mensaje de error, se asigna la clase errormessage.
* Se crea la sección footer para la página, que incluye tres enlaces correspondientes a *"Términos de uso"*,   *"Declaración de privacidad"* y *"Centro de ayuda"*. Se asigna la clase footer a esta sección.
* Se configuran los estilos para cada uno de los elementos creados en esta página en el archivo *styles.css*.

---------------------------
## Versión 1.7
Afinamiento de estilos de las páginas del sitio utilizando preprocesador Sass.

Incluye lo siguiente:
* Creacion de carpeta SASS en la aplicación, en la cual se incluyen los archivos *"estilos.scss"* y *"styles.scss"*.
* Se incluyen las variables para color de fondo, tipo de fuente y color de texto en los archivos de estilos *"estilos.scss"* y *"styles.scss"* que son aplicados a las páginas *"index.html"*, *"login.html"*, *"register.html"* y *"errorpage.html"*.
* Se crea la clase .flex en los archivos de estilos *"estilos.scss"* y *"styles.scss"*, la cual es utilizada dentro de los estilos aplicados a las páginas *"index.html"*, *"login.html"*, *"register.html"* y *"errorpage.html"*.

---------------------------
## Versión 1.8
Inclusión de propiedades para mejorar la accesibilidad del sitio.

Incluye lo siguiente:
* Se agrega el atributo **"tabindex"** a los diferentes elementos que lo requieren para mejorar la accesibilidad a las páginas cuando se utilicen herramientas de lectura de páginas a usuarios invidentes. 
* Se agrega el atributo **"aria-label"** a todos los elementos de tipo *"input"* habilitando las características de accesibilidad por cuanto estos campos tienen asignado un placeholder y no etiqueta (label) para nombrarlos en las páginas.
* Los anteriores cambios se aplican a los archivos *"index.html"*, *"login.html"*, *"register.html"* y *"errorpage.html"*.