# Product Microservice

## Dev

1. Clone rep
2. Install dependencies
3. Create `.env` file based on `env.example`
4. Exec prisma migration `npx prisma migrate dev`
5. Have launched NATS server

```
docker run -d --name nats-server -p 4222:4222 -p 8222:8222 nats
```

6. Exec `npm run start:dev`
