# Dokerizar-PiZhop

Aplicacion multicapa con Docker-Compose

Si somos usuarios de MAC y Windows no tendremos que instalar nada ya que docker-compose es una de las herramientas que por defecto se incluyen dentro de Docker Desktop

Lo primero es escojer una imagen de DockerHub y hacer un Pull para posteriormente poder trabajar con ella.

Vamos a utilizar la imagen de Tomcat.


![image](https://user-images.githubusercontent.com/91556752/171196915-cdb0834d-1c19-4e1c-995a-da8abb687716.png)


    docker pull tomcat


![image](https://user-images.githubusercontent.com/91556752/171200982-ee431408-eee3-40d9-a030-637c79fabb87.png)

Como se puede ver en Docker desktop ya aparece nuestra imagen de Tomcat.


![image](https://user-images.githubusercontent.com/91556752/171201239-cfd4008a-eccb-46d1-98ab-0613b05f5fa7.png)


        docker run -d --name PiZhop -p 80:8080 tomcat

En Desktop 

![image](https://user-images.githubusercontent.com/91556752/171203694-00f40240-5d53-4786-adbe-250be3a772f4.png)

En este caso lo ejecutaremos por terminal.

![image](https://user-images.githubusercontent.com/91556752/171204505-bb24d069-8f68-4a1f-aeb7-ca9763dc18b4.png)
Ya lo tenemos creado y arrancado.

![image](https://user-images.githubusercontent.com/91556752/171205299-4fdddd68-6794-4219-886e-2febf4359704.png)

