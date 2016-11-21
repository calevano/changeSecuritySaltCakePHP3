# changeSecuritySaltCakePHP3
Creación de un comando en Shell para crear un SECURITY_SALT o modificarlos con el hash256 predeterminado de CakePHP3

Sigue los siguientes pasos:

* En la terminal entras a tu proyecto "cd [NOMBRE_PROYECTO]"
* En la terminal ejecutas: bin/cake bake shell Salt
* Abre el archivo generado en la carpeta src/Shell
* Una vez dentro del archivo copias el contenido del archivo de este repositorio
* Eso es todo.

En la terminal ahora tienes estás dos opciones

* bin/cake salt ( Lo que hace es generar un salt en caso no exista )
* bin/cake salt reset ( Lo que hace es reemplazar el salt que tiene a otro nuevo )

Espero sea de suma ayuda para ustedes que como yo en CakePHP no encontramos algo como lo hace Laravel "php artisan key:generate".