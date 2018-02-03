# testingDocker-Compose

Pasos para crear la maquina en azure y desplegar el docker compose del repositorio: 
 - az login
 - lanzar el script "setup.sh". No introducir ninguna letra mayuscula ni caracter extraño. La contraseña debe tener mas de 6 caracteres con: mayusculas, minusculas y numeros.
 - anotamos el DNS que nos proporciona como ultima linea el script.
 - conectarnos por ssh:
``` bash
ssh azureuser@mypublicdns.eastus.cloudapp.azure.com
docker-compose --version
```
 - 

Apuntes: [enlace.](http://jj.github.io/CC/documentos/temas/Contenedores)
Guia node: [enlace.](https://nodejs.org/en/docs/guides/nodejs-docker-webapp)
Guia docker-compose: [enlace.](https://jsitech1.gitbooks.io/meet-docker/content/docker_compose.html)
Guia docker-compose en azure: [enlace.](https://docs.microsoft.com/es-es/azure/virtual-machines/linux/docker-compose-quickstart)
