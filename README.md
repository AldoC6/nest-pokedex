<p align="center">
  <a href="http://nestjs.com/" target="blank"><img src="https://nestjs.com/img/logo-small.svg" width="120" alt="Nest Logo" /></a>
</p>

# Ejecute in dev

1. Clone repository
2. Execute this command
```
npm install
```
3. Have NEST CLI installed
```
npm i -g @nestjs/cli
```
4. Build the database
```
docker-compose up -d
```

5. Clone archive __.env.template__ and rename copy to __.env__

6. fill the defined environment variables on __.env__

7. Ejecute the app in dev mode:
```
npm run start:dev
```

8. Get data from db with seed
```
http://localhost:3000/api/v2/seed
```


# Stack
* MongoDB
* NestJS
