# RepositoryComands
Repositorio de los comandos que se iran viendo en el curso de Sistemas operativos

| Comando | Descripcion |
| ------------- | ------------- |
| sudo apt update && sudo apt upgrade | Sirve para buscar por actualizaciones y actualizar el sistema  |
| sudo apt install | sirve para instalar algun programa en repositorio. |
| reboot | Reiniciar el sistema |
| echo $Shell | me permite ver que shells tengo instalados. |
| cat /etc/shells | sirve para ver dnnde esta fish |
| chsh -s/bin/zsh | sirve para cambiar el shell |
| ./.script.sh | ver el script | 
| chmod +x script.sh | Hace el archivo ejecutable | 
| mkdir +nombre | para crear carpetas |
| history | Ver todo el historial de comandos ingresados |
| sudo netstat -plut | Muestra conexiones de red | 
| cp +nombrearchivo | Copia archivos |
| mv "nombre archivo" + ruta | es para mover archivos |
| ls /tmp | grep texto2.txt | Comando compuesto, sirve para decirle que me muestre el contenido de la carpeta tmp y unalo con la cadena de texto en el nombre del txt |
| rm /tmp/nombredelarchivo | lo que hace es borrar el archivo temoral creado |
| rm nombredelarchivo -R | elimina el folder y todos los archivos que estan dentro. |
| rm nombredelarchivo -Rf | elimina la carpeta sin importar q o sea de forma forzadaue, es final |
| rm -Rf / | borrar todo los archivos de raiz. Se hecha el sistema operativo |
| scp | sirve para hacer una copia a traves de la red. O sea par copiar archivos de linux copiarlo a un servidor | 
| "scp nombrearchivo usuario@direcionip:/ruta/ruta/ruta/nombrearchivo o3.txt" | Sirve para copiar archivs. con base en el usuario y la direccoin IP | 
| wget + direccion url | sirve para descargar archivos |
| git clone https://github.com/mortasoft/linux-scripts | sirve para copiar un github en ubuntu| 
| curl | sirve para enviar datos a una pagina web | 
| curl -X GET -L https://script.google.com/macros/s/AKfycby61tcPuNY3dw_3IYqNGFnR6Ei55MrLFPe_PHup_VMnGP07HeoRyIy5W8xlrheMB7vJ/exec?data=$nombre | Metemos nuestro nombre a la aplicacion web que desarrollamos |
| wc | sirve para hacer conteo de palabras |
| wc /var/log/syslog | cantidad de lineas que tiene el archivo y la cantidad de palabras que hay en esas lineas, de ultimo sale la cantidad de carcacteres |
| wc /var/log/syslog -l	 | es una ele y es para ver solo las lineas  |
| wc /var/log/syslog -w	 | Es para ver solo las palabras |
| wc /var/log/syslog -m	 | Es para ver solo la cantidad de caracteres |
| head + ubicacion 	 | enseña la primera parte del texto o sae las primeras lineas  |
| head + ubicacion + -n	 | me enseña una canitdad especifica de lineas de esa ubicación |
| tail + ubicación	 | puedo ver las ultimas lineas de un archivo  |
| more + direccion	 | Puedo ver las lineas del directorio viendo por paginas y lineas un archivo podemos salir con q |
| less + direccion	 | Muestras las lineas del directorio  |
| ls -l / -R	 | imprime en pantalla todos los directorios que tengo guardados |
| ls -l / -R  more  | 	me va mostrando en pantalla los directorios poco a poco  |
| grep -r "palabraporbuscar" directorio | buscar cadenas dde text en todos los archivos que yo establezca |
| grep -r "linux" /var/log | Busco linux en los archivos que estan en la direccion de var/log |
| find /home/mortasoft -name index.html	| sirve para buscar en una ruta especifica un archivo con un nombre que yo le diga  |
| shutdown | sirve para apagar la maquina virtual |
| pdfseparate -f 1 -l 5 salida.pdf resultado_%d.pdf	 | sirve para separar paginas de un PDF |
| libro filetype:pdf	 | Crear PDF |
| ip addr	 | Sirve para ver la direccion IP |
| whoami 	 | Ver que usuario esta en la terminal ejecutando |
| man 	  | me dan un manual del comando |
| sudo	  | corre como si fuera el usuario maestro |
| sudo su	 | conectarse al usuario root |
| exit	 | Salir del motod root |
| su root 	 | conectarse al usuario root |
| sudo user add XXXX(el nombre del nuevo usuario)-m	 | para crear un nuevo usuario |
| userdel – r	 | es para eliminar usuarios. El comando r me sirve para eliminar toda la info relacionada con ese usuario.  |
| cat/etc/passwd	 | sirve para listar los usuarios del sistema |
| clear | 	limpiar |
| nano	 | crear archivos de texto |
| cat XXX(nombre del archivo)	 | me muestra el archivo de txt  |
| cat /var/log/syslog	 | me muestra un registro de todo lo que esta pasando en el virtual box |
| tail /var/log/syslog  -10	 | Me sirve para ver una cantidad especifica de líneas de muestra un registro  |
| cat /var/log/syslog more | 	Para ver mas detalle de esos movimiento |
| grep -r “palabra que quiero buscar en esos datos”/var/log/system  | 	me busca un string en todas las líneas |
| history > historial.txt	 | me permite generar un Txt con todos los comandos creados |
| Downloads $ ls > archivos.txt  |	me permite generar un lista con todos los archivos que tengo en x carpeta. En este caso downloads.  |
| free -h	 | Nos dice cuanto tenemos de memoria usada y cuando de swap |
| Swapon	 | Nos va a decir donde esta el archivo y la prioridad de uso |
| cat /proc/sys/vm/swappiness | 	Que tanta prioridad va a darle al Swap |
| df – h	 | me indica datos del uso de mi memoria |
| sudo mkdir /mnt/ram_disk	 | creo la carpeta donde se guardaran los archivos  para un RAM disk |
| sudo mount -t tmpfs -o size=1024m new_ram_disk /mnt/ram_disk	 | Se crea un archivo de memoria temporal |
| ls	 | Lista de archivos de un determinado directorio |
| ls - l	 | Lista los archivos y carpeta de la carpeta que estoy junto con sus tributos |
| Ls – lh 	 | me muestra mas lindo el tamaño de los archivos que tengo en ese directorio |
| chmod	 | cambio laos permisos de usuario |
| du – h +nombredelarchivo	 | me dice el tamaño del archivo  |
| stat +nombredearchivo	Fecha de creación. Cuando se acceso, cuando fue modificado, y cuando cambio el archivo  |
| touch +nombre del archivo 	Le cambia la hora de ultima modificación por la actual |
| Touch + nombrede archivo que no existe	Crea un archivo vacio |
| file + nombre del arhivo	me da el formato del arhivo |
| ps -aux | 	Busca los procesos abiertos y con |
| Grep  | Me ayuda a buscar el programa |
| Kill – 9 ### num programa | 	Cerrar de golpe un programa |
| cd  | 	Sube un nivel de directorios |
| cd -	 | Vas a la ubicación donde estabas antes |
| cd nombredeldirectorio/o/ruta	 | Va hacia el directorio o ruta indicada  |
| passwd | 	Cambiar contraseña |
| sudo apt-get remove nombredelaaplicacion | 	borrar una aplicaciones |
| ping direccionIp | 	Sirve para hacer ping a una direccion IP y ver si recibimos respuesta de la misma  |
| sudo apt-get install apt-transport-https ca-certificates curl    gnupg-agent software-properties-commonInstalar la clave GPG Oficia	 | Descargar la informacion relacionada a Dokcer  |
| curl -fsSL https://download.docker.com/linux/debian/gpg  sudo apt-key add –	 | Para asegurar al sistema que ese repositorio es bueno y se puede utilizar creamos una llave |
| sudo add-apt-repository "deb [arch=amd64] https://download.docker.com/linux/ubuntu bionic stable"	 | Agregamos el repositorio oficial de Docker  |
| sudo apt-get install docker-ce docker-ce-cli containerd.io docker-compose | 	Para instalar el docker: |
| sudo usermod -aG docker ${USER}	 | Para agregar el usuario al grupo de Docker y que no ocupemos usar sudo |
| su - ${USER} | 	Refresca los permisos y hace que funcione Docker |
| sudo docker run hello-world | 	Para comprobar que Docker esta correctamente instalado |
| sudo systemctl start docker | 	Para iniciar el Docker una vez reiniciado |
| sudo systemctl enable docker | 	Para habilitar que se inicie en automático cada vez que se prende el sistema operativo |
| docker pull ubuntu | 	Instalar el dokcer de ubuntu |
| docker images | 	Ver las imágenes instaladas |
| docker pull nextcloud | Instalar el dokcer de nextcloud |
| docker run -it ubuntu | para correr un nuevo contenedor y entrar a la terminal de este |
| apt install “nombreapp | instalar aplicaciones  |
| exit | 	Salgo del sistema operativo docker |
| docker ps -a | 	Ver los contenedores que están corriendo |
| docker start iddeldocker | 	iniciar un contenedor |
| --name | 	Poner un parámetro de nombre |
| docker run -d -p 8080:80 nextcloud | Iniciar el Docker de nextcloud y los puertos sirven para que mapear el puerto de la app virtual que tenga dentro con los puertos mios de mi maquina |
| docker login -u “usuario” | Iniciar con nombre de usuario  |
| Docker commit “imagen” “nombreque yole quiera poner” | Colocarle un nombre al repositorio |
| docker push “repositorio que quiero hacerle push” | enviar algo a la nube |
| docker pull mortasoft/ubuntu-calc | Descargar la imagen creada |
| docker stop “numeroid” | Detener una instancia |
| docker rm idinstancias | Borrar una instancia |
| docker rmi “nombreinstancia” | borrar una instancia |
| Docker run -ti –rm nomredelainstancia | Borrar en automático al salir del Docker  |
