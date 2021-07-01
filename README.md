# Repositorio de la app descentralizada del INE

------------

**Instalación:**
- Se necesita agregar la libreria de flask una vez clonado el repositorio.
- Se necesita agregar la libreria de waitress para hacer uso de serve, esto se realiza mediante el comando:
		pip install waitress

------------

**Descripcion del funcionamiento:**
- La aplicacion conciste de una base de datos descentralizada, por lo que todos los nodos de la app contienen un registro de toda la informacion que se ha trabajado y esta misma se mantiene igual en cada uno de los nodos.
- Se trabaja con blockchain por lo que la cadena mas larga sera siempre la que se mantenga en cada uno de los nodos.
- La informacion añadida a la aplicacion se actualiza en cada uno de los nodos despues de realizar la actualizacion de la pagina.
- Los metodos de minado de bloque y recibir la cadena son realizados desde una aplicacion externa Postman, estos se reciben y se muestran mediante un archivo json.
- La aplicacion se corre desde el host 127.0.0.1 en el puerto 5000, 5001, 5002 y el puerto 5003 respectivamente.
- Para realizar la ejecucion del programa se deben tener corriendo todos los nodos de la aplicación.

------------

**Descripcion de la idea de la app:**
La idea que se tiene respecto a la aplicacion, es que pueda funcionar para que el personal del Instituto Nacional Electoral pueda añadir a la base de datos de forma mas sencilla a las personas del pais, asi mismo, que sea mas intuitiva para las personas que se dedican a esta accion, el uso de esta aplicacion provocaria que la informacion de las personas no estuviese en un solo servidor, ya que esto traeria con sigo problemas si este mismo llegase a fallar por alguna razo, con ayuda de la descentralizacion todos los nodos de la aplicacion tendrian la informacion y esta asi mismo seria exactamente la misma debido a que se trabaja con blockchain y la cadena mas larga es la que se mantiene en uso.

En la aplicacion se tiene pensado agregar tambien herramientas para que los trabajadores puedan obtener ayuda, en caso de que estos lo requieran, asi como obtener la informacion completa de algun usuario o varios si se llegase a necesitar, asi mismo, si es posible conectar con la base de datos actual del INE para extraccion de datos de las personas ya registradas hasta la fecha.

------------

# Programas utilizados para la aplicación
##Pycharm

![](https://resources.jetbrains.com/storage/products/pycharm/img/meta/pycharm_logo_300x300.png)

> Entorno de desarrollo para la realizacion de la app. Se puede obtener dando click [Aqui](https://www.jetbrains.com/es-es/pycharm/download/#section=windows "Aqui").

##Postman

![](https://dashboard.snapcraft.io/site_media/appmedia/2018/11/logo-mark.png)

> Permite crear peticiones sobre APIs de una forma muy sencilla. Se puede obtener dando click [Aqui](https://www.postman.com/downloads/ "Aqui").

##Visual Studio Code

![](https://i1.wp.com/blog.330ohms.com/wp-content/uploads/2021/02/thumbnail_visualstudiocode_01.png?fit=1200%2C675&ssl=1)

> Entorno de desarrollo que tambien esta soportado para realizacion de la aplicacion. Se puede obtener dando click [Aqui](https://code.visualstudio.com/download "Aqui").