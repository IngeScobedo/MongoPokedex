<p align="center">
  <a href="http://nestjs.com/" target="blank"><img src="https://nestjs.com/img/logo-small.svg" width="200" alt="Nest Logo" /></a>
</p>


# Ejecutar en desarrollo

1. Clonar el repositorio
2. Ejecutar
```
npm i
```

3. Tener Nest CLI instalado
```
npm i -g @nestjs/cli
```

4. Levantar base de datos
```
docker-compose up -d
```
5. Clonar el archivo ```.env.example``` y renombrar la copia a ```.env```

6. Llenar las variables de entorno definidas en el ```.env```

7. Ejecutar la aplicación en dev:
```
npm run start:dev
```

# Ejecutar en desarrollo

1. Crear el archivo ```.env.prod```
2. Llenar las variables de entorno definidas en el ```.env.prod```
3. Crear la nueva imagen
```
docker-compose -f docker-compose.prod.yaml --env-file .env.prod up --build
```

## Stack usado
* MongoDB
* NestJS


---
Author: Alan Escobedo
---