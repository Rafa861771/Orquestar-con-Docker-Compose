# Orquestar-con-Docker-Compose
1. Como primer paso debemos de tener instalado de manera correctar el Docker y el Docker Compose
   Lo verificamos con los comandos
   - docker --version
   - docker-compose --version
2. Luego debemos crear el archivo docker-compose.yml
3. Posteriormente debemos de levantar los servicios con el comando docker-compose up -d
   - -d lo ejecutamos en segundo plano
4. Despues verificamos los contenedores que se encuentran en ejecucion con el comando
   - docker ps
5. Luego debemos gestionar los contenedores con los siguientes comandos:
   - docker-compose down (para detener los servicios)
   - docker-compose restart (para reiniciarlos)
   - docker-compose logs -f (que nos permite ver los logs)
6. Y como ultimo paso opcional, podemos escalar los servicios con el comando:
   - docker-compose up --scale web=3 -d
