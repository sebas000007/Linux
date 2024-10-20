# APUNTES CURSO CIBERSEGURIDAD LINUX

## Comandos nuevos aprendidos

- Instalar apps 
```
sudo apt install app
```
- desinstalar apps 
```
sudo apt remove app 
```
- Listar apps 
```
apt list --installed
```
- Imprimir por consola 
```
Echo "hola"
``` 
- Operaciones por consola
 ```
 expr 3500 * 12
 ```
- Informacion sobre directorios de linux 
```
man hier
```
- Ver permisos que tienen los archivos y ver files ocultos 
```
ls -la
```
- busqueda de una cadena especifica dentro de un file 
```
grep string archivo.txt
```
- pipe se utiliza para combinar comandos con | 
```
ls home | grep users
```
----
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