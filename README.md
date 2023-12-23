# Next.Js-Node.Js-Prisma-Postgres-Docker

![8u5tuvomas4zw37m4g5z](https://github.com/jay75chauhan/Next.Js-Node.Js-Prisma-Postgres-Docker/assets/66429052/a8152c1a-1d58-47c3-b9bf-820cbc3bfda3)

# Backend (Node Js)

```
# npm init -y

# npm i express prisma @prisma/client

```

# Frontend (Next Js)

```
# npx create-next-app@latest --no-git

# npm run dev

# npm i axios

```

# DB (postgres:12) (docker)

```
# docker exec -it db psql -U postgres

# \l (List of database)

# \dt (relations)

```

# ORM (prisma)

```
# npx prisma init

DATABASE_URL="postgresql://postgres:postgres@localhost:5432/postgres?schema=public"

# npx prisma generate (Prisma schema loaded)

(sync database with prisma)
# docker exec -it backend npx prisma migrate dev --name init

(Run Studio)

# npx prisma studio
```

# Docker

```
# docker-compose up -d
```
