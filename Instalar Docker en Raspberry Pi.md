Primero actualizar la raspberry

~~~bash
sudo apt-get update
~~~

~~~bash
sudo apt-get upgrade
~~~

Descargar el script para instalar Docker en Raspberry Pi

~~~bash
curl -fsSL https://get.docker.com -o get-docker.sh
~~~

Ejecutar el script usando el siguiente comando

~~~bash
sudo sh get-docker.sh
~~~

Agregar el usuario Pi usa el comando

~~~bash
sudo usermod -aG docker Pi
~~~

Revisar la versión de Docker

~~~bash
docker version
~~~

Para obtener información de docker 

~~~bash
docker info
~~~

