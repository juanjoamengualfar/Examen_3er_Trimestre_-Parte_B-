# Examen_3er_Trimestre_-Parte_B-


# APARTADO 1


### 1. Lo primero de todo, hacer el log in:

![login](https://user-images.githubusercontent.com/91874635/173301170-1c8c9d9e-4844-4e64-902a-aaa11395e613.png)

<br>

### 2. Ahora podemos proceder con el ejercicio 1, en el que descargaremos una imagen nueva utilizando "docker pull ubuntu:18.04" y crearemos un contenedor teniendo acceso a un shell en el utilizando "docker run -it ubuntu:18.04 /bin/bash":

![Ejercicio 1](https://user-images.githubusercontent.com/91874635/173301804-4e76c38f-016a-48ea-b0fa-77120ccaa2be.PNG)

<br>

### 2. Continuamos con el ejercicio 2, en el que crearemos un contenedor y listaremos el contenido de la carpeta con el comando "docker run centos ls/":

![Ejercicio 2](https://user-images.githubusercontent.com/91874635/173305092-e006c096-b6a7-4bdf-b14b-9d7377efe3b0.PNG)

<br>

### 3. Continuamos con el ejercicio 3, en el que crearemos un contenedor de httpd (Servidor Apache) utilizando el comando docker run httpd:

![Ejercicio 3](https://user-images.githubusercontent.com/91874635/173305642-32746a0e-5f64-4836-9fd2-dc098e8b0b56.PNG)

<br>

### 4. Continuamos con el ejercicio 4, en el que crearemos un contenedor de debian 9 y mostraremos el contenido de una carpeta establecida con el parámetro -w (docker run -it -w /etc debian:9 ls):

![Ejercicio 4](https://user-images.githubusercontent.com/91874635/173306556-e5d9c670-69fb-46ed-b10a-bc736fb8d521.PNG)

<br>

### Para ver todo lo que hemos realizado hasta el momento utilizaremos el comando docker ps:
![Contenedores realizados](https://user-images.githubusercontent.com/91874635/173307233-ad223793-d0c9-49d6-bb7e-c330992bb914.PNG)

<br>
<br>

# APARTADO 2


### 1. Lo primero de todo será crear una imagen tomcat con el código siguiente:

![Crear una imagen tomcat](https://user-images.githubusercontent.com/91874635/173310773-ed915bb4-7fab-45db-9ddc-b829e8bc9a9a.PNG)

![Crear una imagen tomcat](https://user-images.githubusercontent.com/91874635/173315643-ae823d7e-4c81-49e0-95f9-59c057678880.PNG)

<br>

### 2. Lo siguiente será cambiar el nombre de la imagen al que queramos con el siguiente código:

![cambiar el nombre](https://user-images.githubusercontent.com/91874635/173314628-af439b35-a650-48eb-8bcc-59fd8c9f0540.PNG)

<br>

### 3. Por último, lo que deberemos hacer es un push para que se suba a docker hub:

![push a docker hub](https://user-images.githubusercontent.com/91874635/173316266-f63c6e32-5d3e-4119-968c-e4c44fd176ae.PNG)

<br>

### 4. Para comprobar que todo se ha subido correctamente podemos acceder a docker hub, al apartado de nuestros repositorios, en el caso de que no nos aparezca lo que deberemos hacer es refrescar la página:

![repositorio de docker hub](https://user-images.githubusercontent.com/91874635/173316762-c2b3ebd7-0670-435f-a187-a0f6138381b7.png)





