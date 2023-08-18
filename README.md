# VercelliniJulia_Comis43685
Entrega final del curso Python - CoderHouse

MY CONTENT´S LIBRARY

explicar de que se trata la web

la información relevante del proyecto, nombre del proyecto, objetivo funcional, descripción de modelos, etc.
Usuario administrador y su contraseña para acceder al panel de administración

Al ingresar a la web sin estar logueado se podrán visualizar las siguientes opciones:

1. Home
2. Registro: al ingresar el usuario podrá realizar su registración incial para luego acceder a la app, en donde se requerirá que se completen los siguientes campos:
        - Nombre de usuario
        - Email Usuario
        - contraseña
        - confirmación de contraseña

Finalizada la carga, se vuelve a la página principal para poder proceder al login con el usuario creado.

Usuarios y claves de acceso creadas:
Usuario (superuser): JuVer 
Clave: 12345

Usuario: Maria
Clave: *M02468*

Usuario: PedroP
Clave: #P013579#

Usuario: TomasG
Clave: &012345&


3. Login: se debe ingresar con el usuario y contraseña creados:
En caso de que alguno de los valores no coincidan el sistema arrojará el siguiente mensaje:
En caso de ser existoso el ingreso se accede a la pantalla principalde la aplicación en donde se podrá visualizar en el menu superior la bienvenida del usuario logueado y mas campos a los cuales podrá acceder, con las diferentes funcionalidades:

4. Editar Perfil: se creo la funcionalidad para editar el perfil  del  usuario ingresando desde este link.http://127.0.0.1:8000/miaplicacion/editar_perfil/. En este apartado el usuario podrá  modificar o actualizar cualquiera de sus datos segun se detalla:
    - Modificar email
    - contraseña
    - repetir contraseña
    - Nombre/s
    - Apellido/

5. About me: es una pequeña descripcion sobre quien soy y de que se trata la apliación con que fin fue creada a partir de una necesidad detectada.
* Usuarios: podrán visualizarse distintos usuarios de la app con sus respectivos email.
* Logout: este botón permite desloguearse de la página y luego se redirecciona a la página principal.
* Administración: este botón es el acceso al  módulo administración.

Seguidamente podemos visualizar la seccion posteos en donde podemos identificar distinta categorías:

* Turismo
* Manualidades
* Recetas

En cada una de estas categerías se podrá realizar las siguientes funcionalidades:

* Crear una nuevo ítem:  dentro de la categoría haciendo click en el  boton que se visualiza como un mas. Finalizada la carga al presiona el  boton actualizar el registro se graba, se vuelve a la página principal de la categoría donde pueded visualizarse que la misma ha sido creada.
* Editar uno de los items: dentro de la categoría se pueded moficar algunos de los datos existentes, en caso de que existiera una foto nos podremos eliminarla y reemplzarla por otra. Una vez que se actualizan los datos se vuelve a la pagina principal de la categoría y podra vizualizarse el campo modificado.
* Eliiar: en caso de querer eliminar una de las lineas de la categorías se selecciona el boton elinar y automáticamente se elimina, seguidamente se vuelve a la página principal de la categoría y se puede verificar que el registro ya no existe.


6. Búsqueda: se relizó un búsqueda a partir de email, para que el sistema nos traiga la información del usuario: para acceder a la búsqueda hay que ingresar a:
http://127.0.0.1:8000/miaplicacion/buscar_email/
Colocando un email de la base de usuarios se podrá visualizar el resultado de la búsqueda. Probar con: jb@gmail.com
En el resultado de la búsqueda se puede visualizar la herencia del template de la página de inicio.  
En caso de no ingresar un mail en la búsqueda el sistema arrojará el siguiente mensaje: "No se ingresaron datos para buscar!"

7: Restricciones de acceso: se definio que para acceder a la visualización de la sección Posteos, Usuarios, Aboutme , el  usuario deba estar logueado de manera tal no pueda acceder a los mismos sin loguearse.


8. Admistración: en caso de que quien quiera acceder a este módulo sin ser superuser el sistema arrojará un alerta sobre la imposibilidad de realizarlo por un tema de permisos, dando como opcion loguearse con otro usuario. En caso de que se trate del superuser permitirá acceder a esta sección.
a. Se creo el suepruser: JuVer y la contraseña 12345, el sistema nos alertó acerca de lo frágil de la contraseña pero para este ejercicio se dejó esa clave.
b. Dentro de administración se podrán visualizar las siguientes secciones:
    Autenticación y autorización: allí se podrá ver al usuario admin a quien se le asignó y nombre, apellido e email. y se selecionaron los Permisos que se requerian para el mismo.
        Usuarios: se puede visualizar los distintos usuarios y asignarse los permisos que se consideren.

    MiAplicación: en esta sección se pueden visualizar las distintas categorías de la aplicación: ingresando en cada una se podrá observar:
        Usuarios: ingresando se visualiza el nombre de los usuarios, e ingresando en alguno de los usuarios podremos acceder a la información completa del mismo, pudiendo realizar algún cambio guardarlo y que este luego se actualice en nuestra tabla.
        Posteos: ingresando se visualiza el nombre de los posteos, e ingresando en alguno de los posteos  podremos acceder a la informacción completa del posteo, pudiendo realizar algun cambio, guardarlo y que este luego se actualice en nuestra tabla.
        Categorias: ingresando se visualiza el nombre de las categorías, e ingresando en alguno de ellas podremos acceder a la informacción completa de la misma, pudiendo realizar algun cambio, guardarlo y que este luego se actualice en nuestra tabla.
    Para cada una de estas categorías se  podrá:
    Añadir: una nueva desde allí a partir de los datos asociada a cada una. Finalizada la carga se podrá ver que la misma ha sido agregada correctamente.
    Modificar: permite modificar alguno de los datos que contiene la categoría.
    Eliminar datos: en caso de querer eliminar algun registro de Usuarios, Posteos o Categorías, el sistema preguna previo a eliminarlo si deseamos hacerlo, en caso de estar seguros de hacerlo se procede a su elminación.
    
 9- Se puede visualizar en todos los accesos desde el click a páginas en donde se ha realizado la herencia de template.
 10- Avatar: para aquellos usuarios que estando ya creados no tuvieran avatar, estando logueados podrán subir su Avatar y luego modificar la foto en caso de requerirlo, accediendo al siguiente link:
    http://127.0.0.1:8000/miaplicacion/agregar_avatar/
 Una vez cargada la foto se podrá visualizar al lado del Bienvenido {usuario}

11- video: https://drive.google.com/file/d/1c69Nt8QEm_UNAvQq2Xj3GygxUuOKLwv5/view?usp=sharing

