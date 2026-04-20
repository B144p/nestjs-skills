# nestjs-skills

Custom skill pack for my NestJS stack.
These skills are opinionated and written specifically for this stack —
they may work for similar setups but are not intended to be generic.

## Stack

- **NestJS 11** — `@nestjs/common`, `@nestjs/core`, `@nestjs/config`
- **Auth** — `@nestjs/passport`, `passport-jwt`, `passport-google-oauth20`, `@nestjs/jwt`
- **WebSocket** — `@nestjs/websockets`, `@nestjs/platform-socket.io`, `socket.io`
- **ORM** — Prisma 6
- **Validation** — `class-validator`, `class-transformer`
- **Docs** — `@nestjs/swagger`

## Skills

### `nestjs-websocket-gateway`
NestJS WebSocket gateway using Socket.IO — lifecycle hooks, rooms, namespaces,
broadcasting, WsException handling, ValidationPipe on events, Redis adapter scaling.

> Auth and ORM are intentionally excluded — handled by `nestjs-expert` and `prisma-expert`.


## Installation

```bash
npx skills add https://github.com/B144p/nestjs-skills --skill nestjs-websocket-gateway
```
