# Repositorio-SO-Fabiola-Cruz

| Comando | Descripción | Imagen |
| --- | --- | --- |
| Ip addr | Muestra las direcciones IP | <img width="468" alt="image" src="https://user-images.githubusercontent.com/102490992/185538799-f1880aa7-8c91-45ef-b5ef-f909e83e2048.png"> |
| ping 8.8.8.8(direccion) | Acceso a internet | <img width="468" alt="image" src="https://user-images.githubusercontent.com/102490992/185539328-18a8faa4-da06-4781-b4d1-3ece53a9c6bb.png"> |
| sudo apt install openssh-server | Habilitar el protocolo SSH en el equipo | <img width="468" alt="image" src="https://user-images.githubusercontent.com/102490992/185539179-1857f229-df7e-443b-a24d-78dc17536ba6.png">|
| ls | Mostrar los archivos y carpetas de un directorio | <img width="468" alt="image" src="https://user-images.githubusercontent.com/102490992/185539214-7f8a6199-58aa-42d0-9165-16e85021a7c6.png">|
| ls -l | Visualizar los permisos y dueño de la carpeta | <img width="460" alt="image" src="https://user-images.githubusercontent.com/102490992/185539397-b6fdf867-2a65-4a9b-a2f0-7d247ee55e53.png">|
| mkdir | Crear carpetas | <img width="304" alt="image" src="https://user-images.githubusercontent.com/102490992/185539435-61ad3fe0-27bb-4de1-ac83-572ec8d42ea1.png"> |
| pwd | Visualizar la ubicación del directorio actual | <img width="279" alt="image" src="https://user-images.githubusercontent.com/102490992/185539471-b4709523-e520-457e-9321-033e25b66ef8.png">|
| cd | Ingresar a una carpeta | <img width="468" alt="image" src="https://user-images.githubusercontent.com/102490992/185539500-b3e75f58-3397-433e-b66f-46dcfbd112ba.png"> |
| cd .. | Salir de una carpeta | <img width="348" alt="image" src="https://user-images.githubusercontent.com/102490992/185539525-69b4f8fc-c3b0-4ec4-aaac-c8e4f2952e04.png">|
| sudo adduser test | Añadir un usuario | <img width="468" alt="image" src="https://user-images.githubusercontent.com/102490992/185539560-c0142097-d93b-48ff-88e7-4c835f95def6.png">|
| sudo passwd user | Cambiar la contraseña de un usuario | <img width="468" alt="image" src="https://user-images.githubusercontent.com/102490992/185539594-9528be5b-0207-4830-934d-36a94b7c3fd5.png"> |
| su user | Cambiar de usuario desde la terminal | <img width="324" alt="image" src="https://user-images.githubusercontent.com/102490992/185539691-da22dcaa-31f3-4e1d-a927-a097cb931ba2.png"> |
| whoami | Conocer cuál es el usuario actual | <img width="297" alt="image" src="https://user-images.githubusercontent.com/102490992/185539722-371146d4-5e54-40a7-9a87-eb0a15ac165c.png"> |
| sudo su | Ingresar como usuario administrador | <img width="397" alt="image" src="https://user-images.githubusercontent.com/102490992/185539760-7035d008-1af6-4d72-ac39-2b6be4205fe9.png"> |
| nano archivo.txt | Editar el contenido de un archivo | <img width="333" alt="image" src="https://user-images.githubusercontent.com/102490992/185539791-8f3082be-acd9-4f8a-9fae-092a54fceee4.png"> |
| cat archivo.txt | Visualizar el contenido de un archivo | <img width="307" alt="image" src="https://user-images.githubusercontent.com/102490992/185539830-903da37e-1103-4594-82c9-9c25c722614e.png"> |
| history > archivo.txt | Guardar el historial de comandos de la terminal | <img width="468" alt="image" src="https://user-images.githubusercontent.com/102490992/185539869-feae8af0-3b52-45f4-91f1-3c009e50fcf6.png"> |
| head -n 3 archivo.txt | Visualizar las líneas de un archivo | <img width="439" alt="image" src="https://user-images.githubusercontent.com/102490992/185539911-c134b606-e918-41cd-8683-737111baa6a0.png"> |

| history > archivo.txt | Guardar el historial de comandos de la terminal | <img width="468" alt="image" src="https://user-images.githubusercontent.com/102490992/185539869-feae8af0-3b52-45f4-91f1-3c009e50fcf6.png"> |
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
