# Comandos
| Comando | Descripcion | Ejemplo |
| ------- | ------------ | -------- |
| `ls` | revisa documentos en el directorio | `ls` dentro en la terminal para ver los archivos del directorio en el que esta |
| `sudo apt update && sudo apt upgrade`| actualiza los paquetes | `sudo apt update && sudo apt upgrade` va a actualizar todos los paquetes de la maquina |
| `pwd` | revisa en que parte del sistema se esta trabajando | `pwd` dentro de una zona determianda de la terminal |
| `sudo ./VBoxLinuxAdditions.run` | sirve para insertar los Guest additions | Se ingresa a la termianal del disco para poder agregarlos |
| `sudo nano `nombre`.txt` | crea un archivo de texto en el directorio en el que se encuentre | `sudo nano prueba.txt` para crear un archivo de texto que se llame "prueba" |
| `rm` | borra archivos | `rm prueba` va a borrar el archivo que se llama prueba |
| `rm -R` | elimina directorios | `rm -R home` va a eliminar la carpeta que se llama home |
| `clear` | resetea la terminal | se agrega el comando `clear` para borrar todo lo que esta en la termianl |
| `top` `ps -aux` `htop` `pstree` | muestra los IDs y procesos de la maquina virtual | se puede ingresar cualquiera en cualquier momento para que los muestre |
| `kill -9` numeroID | mata el proceso de la maquina virtual | `kill -9 8329` va a matar el proceso 8329 de la maquina |
| `telnet towel.blinkenlights.nl` | se presenta el episodio de star wars IV | se puede poner en la terminal para que se presente el episodio |
| `ip a` `ip addr` | muestra el IP de la maquina | al digitar este comando se presentan las direcciones de IP | 
| whoami | muestra el usuario que se esta utilizando | se digita en la terminal y va a presentar el nombre el usuario que se esta usando |
| `cd` nombre | cambia de directorio | `cd /home` va a ponerse en el directrorio de home |
| `ls -l` | va a mostrar archivos ocultos | `ls -l` en la terminal para poder verificar los archivos ocultos de la maquina |
| `cat` | muestra contenido de un archivo | `cat prueba.txt` muestra el texto que viene en el archivo prueba|
| `mkdir` nombre | crea carpetas nuevas | `mkdir xpj` crea una carpeta nueva con el nombre xpj |
| `sudo su` | cambia a usuario root| `sudo su` va a permitir hacer acciones de super usuario|
| `exit` | sale de usuario root |`exit` en la terminal va a hacer que vuelva a el usuario normal|
| `tail` nombre | muestra parte final de un archivo | `tail prueba` muestra el final de ese archivo |
| `head` nombre | muestra el inicio de un archivo | `head prueba` muestra el inicio de ese archivo |
| `cp` nombre direccion | copiar un archivo | `cp prueba /home/` hace una copia del archivo que se encuentra en el directorio y lo pega en otra direccion |
| `mv` | mueve archivos | mv prueba /home/ mueve ese archivo a la carpeta home |
| `sudo adduser` | crea usuario nuevo | `sudo adduser xime` crea un usuario con el nombre xime |
| `sudo passwd` usuario | cambia la contrasena de un usuario| `sudo passwd xime` va a cambiar la contrasena del usuario xime|
| `history` | muestra el historial de los comando utilizados | `history` va mostrar una lista de los comandos utilizados en la maquina virtual|
| `df - h` | muestra el espacio del disco duro | se va a presentar el espacio disponible del disco de la maquina virtual|
| `sudo mount`tipo direccion| montaje de dispositivos en el sistema de archivos | `sudo mount /dec/sdb2/` va a montar este disco en el lugar indicado|
| `gnome-disk-utility` | muestra informacion sobre el disco | va a presentar la informacion del disco |

///////////////////



| `docker build` | crea una imagen del dockerfile | |
| `docker images` | lista todas la siamgenes del docker host | |
| `docker run` | corre una imagen | |
| `docker ps` | lista todas las instacias que esta corriendo y detenidas | |
| `docker stop` | detiene todas las instancias que estan corriendo | |
| `docker rm` | elimina una instancia | |
| `docker rmi` | elimina una imagen | |
| `docker container ls -a` | lista los contenedores | |
| `docker ps -a` | lista los contenedores | |
| `docker start -a` | iniciar y detener un contenedor | |
| `docker container rm CONTAINER` | elimina un contenedor con su nombre o id| |
|`docker run -it ubuntu`| iniciar un contenedor en modo interactivo | |
| ` docker sun -d ubuntu`| iniciar un contenedor en modo detached | |
| ` docker container exec ls`| ejecuta un comando en un contenedor | |
| ` docker run -d --name ubuntu-test ubuntu`| le asigna un nombre personalizado a un contenedor | |
| `docker attach CONTAINER`| entra a la terminal de un contenedor en ejecucion | |
| `docker container stop $ (docker container ls -q)`| detiene todos los contenedores | |
