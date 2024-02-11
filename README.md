# NLW Expert | Node | Votes API

![banner](.github/banner.png)

## About ℹ️

This is a voting API to help you with voting process in real time.

<p align="right"><a href="#readme-top">🔝 Return</a></p>

## About NLW 🚀

NLW (Next Level Week) is an event organized by Rocketseat, dedicated to exploring cutting-edge technologies and empowering programmers to build high-quality projects quickly.

This project was created during NLW to embrace and master the latest technologies, resulting in an application powered by multiple advanced technologies.

<p align="right"><a href="#readme-top">🔝 Return</a></p>

## Technologies Used ⚙️

The technologies utilized in this project include:

* [Fastify](https://fastify.dev/)
* [Typescript](https://www.typescriptlang.org/)
* [NodeJS](https://nodejs.org/en)
* [Prisma](https://www.prisma.io/)
* [WebSocket](https://developer.mozilla.org/pt-BR/docs/Web/API/WebSockets_API)

<p align="right"><a href="#readme-top">🔝 Return</a></p>

## Features ✅

- [X] Create HTTP Routes
- [X] Add Prima DB
- [X] Create WS Route
- [X] Set Real time voting

<p align="right"><a href="#readme-top">🔝 Return</a></p>

## Package Dependencies ⬇️

Here is a list of the project's package dependencies:

```json
"devDependencies": {
    "@types/node": "^20.11.16",
    "prisma": "^5.9.1",
    "tsx": "^4.7.0",
    "typescript": "^5.3.3"
},
"dependencies": {
    "@fastify/cookie": "^9.3.1",
    "@fastify/websocket": "^8.3.1",
    "@prisma/client": "^5.9.1",
    "fastify": "^4.26.0",
    "ioredis": "^5.3.2",
    "zod": "^3.22.4"
}
```

<p align="right"><a href="#readme-top">🔝 Return</a></p>

## Running the Project 🏃

1. Install the project dependencies:

```shell
pnpm i
```

2. Create Prisma Database

```shell
pnpm prisma migrate dev --name init
```

3. Create dataset

```shell
pnpm prisma db seed
```

4. Access prisma studio

```
pnpm prisma studio
```

5. Configure enviroment variables. 

```env
DATABASE_URL="postgresql://docker:docker@localhost:5432/polls?schema=public"
```

6. Execute the following command in your terminal to run the project:

```
pnpm run dev
```

## Acknowledge ☺️

A special thanks to Rocketseat and their dedicated instructors who provide incredible content to the React community, making projects like this possible. Your guidance and support are greatly appreciated.

<p align="right"><a href="#readme-top">🔝 Return</a></p>

## License 📖

This project is open-source and is distributed under the MIT License. Feel free to explore, modify, and utilize the codebase according to the terms outlined in the license.

<p align="right"><a href="#readme-top">🔝 Return</a></p>