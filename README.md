# Despliegue

## INTRODUCCION
### ESTE DESPLIEGUE SE REALIZARA CON LA PLATAFORMA DIGITAL OCEAN MEDIANTE UN DOCKER PREVIAMENTE INSTALADO EN UN UBUNTU 20.0.4

## 1. ACCESO A LA MAQUINA
#### PRIMERAMENTE NOS DIRIGIMOS A LA WEB DE https://cloud.digitalocean.com/ Y CREAMOS UN DROPLET
![image](https://user-images.githubusercontent.com/91564342/172449141-557bf829-62b5-4189-9c83-1fe23420c9b9.png)

#### A CONTINUACIOÓN, NOS CONECTAMOS POR SSH
<code>user@ip</code>

![image](https://user-images.githubusercontent.com/91564342/172449344-d331749c-a3ea-430d-898e-d9e6208bf749.png)

## 2.0 .yml

#### EN MI CASO, SOLO NECESITO EMPLEAR MYSQL Y TOMCAT PARA EL CORRECTO DESPLIEGUE DE LA APLICACION
![image](https://user-images.githubusercontent.com/91564342/172461128-6f93c89c-f78b-499f-b076-f9a62a82f691.png)

#### PODEMOS APRECIAR QUE EL ARCHIVO SE HA CREADO
![image](https://user-images.githubusercontent.com/91564342/172461784-76954582-2974-4578-940c-5466c6913185.png)

## 2.1 SUBIR LA IMAGEN

#### PRIMERAMENTE NOS LOGUEAMOS CON <code>dcoker login</code>

![image](https://user-images.githubusercontent.com/91564342/172463326-72956535-aab3-4276-952f-5e5f8e7240c0.png)

#### AÑADIMOS LOS TAGS 

![image](https://user-images.githubusercontent.com/91564342/172465005-aa63b39b-e978-4eaf-88f3-575ca6c6546a.png)


## 3.0 TECNOLOGIAS

### LAS TECONOLOGIAS OPTADAS PARA EL LANZAMIENTO DEL PROYECTO SON LAS SIGUIENTES:

#### TOMCAT : EN ESTA IMAGEN NOS ENCARGAMOS DE LA  VISTA HTML +  LA PARTE LOGICA DE JAVA

![image](https://user-images.githubusercontent.com/91564342/172461917-5c3653b5-35f4-4d50-99c9-6a79d5d51a1e.png)


#### MYSQL: BASE DE DATOS, CONECTADDA MEDIANTE PETICIONES REALIZADAS EN EL BACKEND

## 4.0 CONCLUSIONES

#### Al principio he tenido algún fallo con el formato .yml pues había un carácter especial que no podía pareciar pero finalmente todo ha salido como tendría que ser
excepto el subir la imagen pues me muestra el siguiente error

![image](https://user-images.githubusercontent.com/91564342/172466201-a91a9f6d-e8db-41d1-a897-6fcae54785bd.png)

#### HE REALIZADO VARIAS PRUEBAS PERO TODO APUNTA A ALGUN ARCHIVO CORRUPTO DEL SISTEMA, LA APLICACION ES 100% FUNCIONAL Y EL USUARIO ESTA LOGUEADO


## 5.0 ANEXOS

https://hub.docker.com/u/rafa380



