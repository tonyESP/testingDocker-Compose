# testingDocker-Compose

Pasos para crear la maquina en azure y desplegar el docker compose del repositorio: 
 - az login
 - lanzar el script "setup.sh". No introducir ninguna letra mayuscula ni caracter extraño. La contraseña debe tener mas de 6 caracteres con: mayusculas, minusculas y numeros.

```bash
#!/bin/bash
# setup.sh
```

 - conectarnos por ssh:

``` bash
ssh azureuser@mypublicdns.eastus.cloudapp.azure.com
docker-compose --version
```

Apuntes: http://jj.github.io/CC/documentos/temas/Contenedores
Guia node: https://nodejs.org/en/docs/guides/nodejs-docker-webapp/
Guia docker-compose: https://jsitech1.gitbooks.io/meet-docker/content/docker_compose.html
Guia docker-compose en azure: az group create --name myResourceGroup --location eastus
