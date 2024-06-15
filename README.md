# Orders MicroService

## Dev

1. Clonar el repositorio
2. Instalar las dependencias
3. Crear el archivo `.env` con las variables de entorno basado en el `.env.template`
4. Ejecutar migración de prisma `npx prisma migrate dev`
5. levantar al servidor de NATS

```
docker run -d --name nats-server -p 4222:4222 -p 8222:8222 nats
```

6. Ejecutar `npm run start:dev`
