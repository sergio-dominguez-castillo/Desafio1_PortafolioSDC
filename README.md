# README

This README would normally document whatever steps are necessary to get the
application up and running.

Things you may want to cover:

* Ruby version

* System dependencies

* Configuration

* Database creation

* Database initialization

* How to run the test suite

* Services (job queues, cache servers, search engines, etc.)

* Deployment instructions

Requerimientos
1. La aplicación deberá contener 3 rutas, una para /home, /projects y /contact. La ruta
raíz de la aplicación será el /home.
(1 Punto)
Nota: Recuerda que en el archivo routes.rb puedes definirlo como:
root ‘nombre_controlador#nombre_método’.
2. Cada ruta deberá tener su correspondiente vista HTML asociada.
(1.5 Puntos)
3. Deberá existir un controlador que gestione la visualización de cada vista con sus
respectivos métodos.
(2 Puntos)
4. En la vista de /projects deberás agregar al menos 3 imágenes de proyectos
realizados hasta el momento, podrás utilizar el componente Card de Bootstrap y
modificar el botón de “ver más” con estilos personalizados desde CSS.
(3 Puntos)
Nota: El CSS que personaliza los estilos del botón “ver más” debe ser llamado desde
la estructura de assets de Rails.
5. Agregar un menú de navegación bien sea personalizado o con la ayuda de Bootstrap
mediante CDN. Este menú debe verse en todas las vistas de la aplicación y redirigir
según corresponda en cada interacción utilizando el helper link_to.
(2 Puntos)
Nota: Puedes asignarle la clase container de bootstrap al yield para modificar los
márgenes izquierdo y derecho de la app.
6. Gestionar las versiones en github haciendo al menos 3 commits que detallan el
avance progresivo de la aplicación.
(0.5 Puntos)
* ...
