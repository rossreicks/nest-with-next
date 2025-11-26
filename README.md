# NestJS application with a NextJS frontend

* PNPM mono repo with a server, client and shared packages
* Server is a NestJS application
* Client is a NextJS application
* Shared packages are shared between the server and client

## Setup

```bash
pnpm install
```

## Run the server

```bash
pnpm run start:server
```

/api route will be served by nestjs controllers and all other routes will be served by nextjs.


