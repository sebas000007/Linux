# <img src="images/518713.png" alt="Imagen de ejemplo" width="45" height="45" style="position: relative; top: 10px;"> APUNTES CURSO CIBERSEGURIDAD LINUX 

## Comandos nuevos aprendidos

| Comando | Descripción | Ejemplo |
| --- | --- | --- |
| `sudo apt install` | Instalar apps | `sudo apt install app` |
| `sudo apt remove` | Desinstalar apps | `sudo apt remove app` |
| `apt list --installed` | Listar apps | `apt list --installed` |
| `echo` | Imprimir por consola | `echo "hola"` |
| `expr` | Operaciones por consola | `expr 3500 * 12` |
| `man hier` | Información sobre directorios de Linux | `man hier` |
| `ls -la` | Ver permisos y archivos ocultos | `ls -la` |
| `grep` | Buscar cadena específica en un archivo | `grep string archivo.txt` |
| `pipe` | Combinar comandos con `linea vertical |  `ls home grep users` |
| `find` | Buscar archivos en directorios | `find /home -name archivo.txt`|
|  `chmod`|Cambiar permisos a un archivo o directorio| `chmod g+w,o-r archivo.txt`|
| `sudo useradd user_name` | Crear un nuevo usuario | `sudo useradd sebaz` |
| `sudo userdel user_name` | Borrar un usuario | `sudo userdel sebaz` |
| `sudo usermod -aG grupo user_name` | Agregar un usuario a un grupo | `sudo usermod -aG sudo sebaz` |
| `sudo chown user_name:grupo archivo` | Cambiar propietario de un archivo | `sudo chown sebaz:sudo archivo.txt` |
| `sudo chmod u+x archivo` | Dar permiso de ejecución al propietario | `sudo chmod u+x script.sh` |
| `sudo chmod g+w archivo` | Dar permiso de escritura al grupo | `sudo chmod g+w archivo.txt` |
| `sudo chmod o-r archivo` | Quitar permiso de lectura a otros | `sudo chmod o-r archivo.txt` |
| `sudo passwd user_name` | Cambiar la contraseña de un usuario | `sudo passwd sebaz` |
| `sudo usermod -L user_name` | Bloquear la cuenta de un usuario | `sudo usermod -L sebaz` |
| `sudo usermod -U user_name` | Desbloquear la cuenta de un usuario | `sudo usermod -U sebaz` |


### Anotaciones
- Al cambiar permisos hay que recordar los tres items `(user,group,other)`
## Directorios estandar del FHS

`/home:`

- Cada usuario del sistema obtiene su propio directorio de inicio.

`/bin:` 

- Este directorio significa “binario” y contiene archivos binarios y otros archivos ejecutables. Los archivos ejecutables contienen una serie de comandos que una computadora debe seguir para ejecutar programas y llevar a cabo otras funciones.

`/etc:` 

- Este directorio almacena los archivos de configuración del sistema.

`/tmp:` 

- Este directorio almacena varios archivos temporales. Las/los atacantes suelen usar el directorio /tmp porque cualquier persona en el sistema puede modificar datos en estos archivos.

`/mnt:`

- Este directorio significa “montaje” y almacena medios, como unidades USB y discos duros.