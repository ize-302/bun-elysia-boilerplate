<h1 align="center">bun-elysia-boilerplate</h1>

<div align="center">
  <a href="https://bun.sh"><img src="https://user-images.githubusercontent.com/709451/182802334-d9c42afe-f35d-4a7b-86ea-9985f73f20c3.png" alt="Logo" height=100></a>
<span>🩶</span>
   <a href="https://elysiajs.com/"><img src="https://elysiajs.com/assets/elysia.svg" alt="Logo" height=100></a>
</div>

<br/>
<p align="center">
Boilerplate to easily get you started with <a href="https://bun.sh">Bun</a> and <a href="https://elysiajs.com">Elysia framework</a>
</p>

---

#### Usage

1. Clone this repository
2. Install dependencies: `bun install`

#### Commands

###### Build project

```bash
bun run build
```

###### Serve build

```bash
bun start
```

###### Run in development mode

```bash
bun start:dev
```

🦊 Elysia is running at localhost:3000

> PS: Bun uses `3000` as default port

#### Run app in Docker

###### Build docker image

```bash
docker build -t <TAG_NAME> .
```

###### Running container

```bash
docker run -p <PORT>:<PORT> <TAG_NAME>
```

### OR

###### Run with docker-compose

```bash
docker compose up --build -d
```

> PS: You have to define PORT in your .env file
