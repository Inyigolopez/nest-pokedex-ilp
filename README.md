<p align="center">
  <a href="http://nestjs.com/" target="blank"><img src="https://nestjs.com/img/logo-small.svg" width="200" alt="Nest Logo" /></a>
</p>

# Ejecutar en desarrollo

1.- Clonar el repositorio
2.- Ejecutar 
```
yarn install
```
3.- Tener Nest CLI instalado
```
npm i -g @nestjs/cli
```

4.- Levantar la base de datos
```
docker-compose up -d
```
5.- Instalar paquetes de Nest para conexion con MongoDB
```
yarn add @nestjs/mongoose mongoose
```
6.- Clonar el archivo __.env.template__ y renombrar la copia a __.env__
7.- Completar las variables de eentorno definidas en el __.env__

8.- Ejecutar la aplicación en dev:
```
yarn start:dev
```
9.- Instalar Axios para peticiones HTTP
```
yarn add axios
```
10.- Reconstruir la BBDD utilizando la semilla:
```
GET http://localhost:3000/api/v2/seed
```
11.- Instalar paquete de configuración para uso de variables de entorno en .env
```
yarn add @nestjs/config
```




## Stack usado
* MongoDB
* Nest