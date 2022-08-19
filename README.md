# Repositorio-SO-Fabiola-Cruz

| Comando | Descripción | Imagen |
| --- | --- | --- |
| Ip addr | Muestra las direcciones IP | 
| ping 8.8.8.8(direccion) | Acceso a internet |
| sudo apt install openssh-server | Habilitar el protocolo SSH en el equipo | 
| ls | Mostrar los archivos y carpetas de un directorio | 
| ls -l | Visualizar los permisos y dueño de la carpeta | 
| mkdir | Crear carpetas |
| pwd | Visualizar la ubicación del directorio actual |
| cd | Ingresar a una carpeta |
| cd .. | Salir de una carpeta |
| sudo adduser test | Añadir un usuario |
| sudo passwd user | Cambiar la contraseña de un usuario |
| su user | Cambiar de usuario desde la terminal |
| whoami | Conocer cuál es el usuario actual |
| sudo su | Ingresar como usuario administrador |
| nano archivo.txt | Editar el contenido de un archivo |
| cat archivo.txt | Visualizar el contenido de un archivo |
| history > archivo.txt | Guardar el historial de comandos de la terminal |
| head -n 3 archivo.txt | Visualizar las líneas de un archivo |
| cp | Copiar un archivo |
| mv | Mover un archivo |
| rm | Borrar un archivo |
| Dpgk -l | Instalar un paquete que se haya descargado |
| sudo apt install neofetch | Instalación del neofetch |
| neofetch | Ejecuta el Neofetch |
| sudo apt | Para instalar paquetes |
| clear | Limpia la terminal |
| sudo apt update && sudo apt upgrade | Para las nuevas instalaciones realizarles una actualización |
| sudo apt install cmatrix | Instalar matrix |
| man | Muestra el manual |
| exit | Sale del porgrama |
| Touch archivo | Crea archivo dentro de directorio |
| Scp archivo usuario@direccionip:/ruta | Para transferir archivos entre hosts a través del protocolo SSH |
| git clone URL | Para clonar |
| wc /var/log/syslog | Cuenta la cantidad de líneas |
| tail | Mostrar las últimas líneas de cualquier fichero |
| Reboot | Renicia el equipo |
| Shutdown | Apaga el equipo |
| Pdfunite “nombres de los pdf a unir” / “nombre.pdf” ”nuevo nombre” | Une archivos PDF |
| -------------- | ----------- | ------ |
| Comando Docker | Descripción | Imagen |
| -------------- | ----------- | ------ |
| curso docker images | Para ver las imagenes con las que cuenta |
| curso docker ps -a | Para ver el estado de los contenedores |
| curso docker history nginx | Historial de capas |
| curso docker info | Muestra los drivers |
| curse uname -a | Para ver el kernel |
| ~ docker network ls | Para ver las redes de Docker |
| sudo ifconfig docker0 | Para ver la interface Docker Cero |
| ~ docker network create --driver (nombre de la red) | Crear un driver |
| ~ sudo ifconfig -s | Para ver las interfaces |
| ~sudo ifconfig (red) | Para ver los contenedores de una red |
| docker pull | Se trae del repositorio o registro que nosotros le digamos la imagen adecuada|
| docker ps -a | Para ver los contenedores que estan en ejecucion y los que no |
| ~ docker run -ti --rm ubuntu bash = entry point | Para activar comandos Unix |
| ~ docker rmi (imagen) | Para borrar imagenes |
| producer curso vim Dockerfile | Hacer variables |
| docker find ./ | Muestra ficheros |
| producer nginx docker built -t (imagen y version) (carpeta) | Crear imagenes |
| -------------- | ----------- | ------ |
| Comando Manjaro | Descripción | Imagen |
| -------------- | ----------- | ------ |
| sudo pacman -Syuu | actualizar los paquetes disponibles del sistema operativo |
| sudo pacman -S unrar zip unzip p7zip gzip bzip2 | Instalar nuevos paquetes para comprimir y descomprimir archivos |
| sudo pacman -S yay sudo yay -S --needed base-devel | Instalar el Repositorio AUR (Arch User Repository) |
| yay -S google-chrome | Instalar google-chrome por medio del instalador de paquetes yay |
| sudo pacman -S apache | Instalar apache en Manjaro |
| uname -a | Visualizar el uso de los kernel |
| sudo useradd -m nombredeusuario -G wheel -p passworddelusuario | Comando para agregar un nuevo usuario |
| Chown | Otorgar permisos a una carpeta |
| Grep | Realizar búsquedas de un texto dentro de un archivo de texto |
|
