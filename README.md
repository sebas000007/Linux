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