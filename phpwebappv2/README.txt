# Despliegue simple actividad 3.1

## Requisitos

Docker, docker-compose

##Cómo utilizarlo

-- Construir y lanzar el contenedor

docker-compose up -d

-- En caso de error 503, ejecute el siguiente comando

docker-compose restart haproxy

-- Ver logs

docker-compose logs -f

-- Comprobar el estado del contenedor

docker stats

-- Acceder a la aplicación 

http://localhost/

-- Compruebe los estados proporcionados por haproxy

http://localhost/stats
