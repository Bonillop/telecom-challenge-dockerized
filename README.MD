# Clima app - Dockerizado

Esta es la aplicacion Clima app, desarrollada como challenge para Telecom y dockerizada
***
## Instalación
Antes que nada deberá utilizarse el siguiente comando para la instalación de dependencias que utiliza la aplicación
>`npm install`

Esto debe realizarse en ambos directorios `/back` y `/front`

## Uso
Para utilizarla será necesario tener instalado docker, luego en el directorio `/docker` deberá ejecutar el siguiente comando 
>`docker-compose up`

Una vez hecho esto podrá dirigirse a http://localhost:3000/ en el navegador para comenzar a utilizarla

## Descripción
Se utilizó una imagen oficial de node tanto para el front como para el back y a su vez se utilizo una imagen oficial de nginx para ser utilizado como proxy para manejar independientemente las peticiones al front y al back

### Mas informacion en los README ubicados en los directorios `/back` y `/front`