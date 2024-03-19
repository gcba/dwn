# Descripción

DWN consiste en un nodo de red diseñado para la mensajería. Utiliza servicios de API REST como interfaz para interactuar con
aplicaciones descentralizadas. Emplea JWS para autorizar el acceso a los mensajes y JWE para asegurar que solo el receptor o el creador del mensaje pueda leer su contenido. Además,
se basa en redes de identificación descentralizada para verificar ambas claves públicas y replica los mensajes en otros nodos de la red de mensajería.
Se implementan protocolos TLS/SSL para garantizar la seguridad de la base de datos, y se utiliza HTTPS para el servicio de APIs, asegurando así la confidencialidad y la integridad de
la información transmitida en ambos casos.

## Tecnologías

La aplicación cuenta con las siguientes técnologias:

NodeJs
TypeScript

Local server install
nvm install 14.19
nvm use 14.19
npm install
node server.mjs

## Arquitectura
[Diagrama](https://docs.quarkid.org/Arquitectura/arquitectura)

## Documentación
[Link](https://docs.quarkid.org/Arquitectura/componentes)

## Variables de Entorno

### Generales

N/A

## Logs

N/A

## Requerimientos de red

La aplicación debe tener conectividad a internet y ser accesible por el Message manager. 

## Ruta de acceso

N/A

