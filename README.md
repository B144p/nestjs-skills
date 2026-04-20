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

## Install Full Stack

```bash
# 3rd party
npx skills add https://github.com/kadajett/agent-nestjs-skills --skill nestjs-best-practices
npx skills add https://github.com/jeffallan/claude-skills --skill nestjs-expert
npx skills add https://github.com/sickn33/antigravity-awesome-skills --skill prisma-expert
npx skills add https://github.com/prisma/skills --skill prisma-postgres
npx skills add https://github.com/wshobson/agents --skill typescript-advanced-types

# Custom
npx skills add https://github.com/B144p/nestjs-skills --skill nestjs-websocket-gateway
```
