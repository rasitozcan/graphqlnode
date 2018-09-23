docker-compose up -d

Your Prisma server is now running on http://localhost:4466 which means you can now start deploying Prisma services to it using the Prisma CLI.

https://www.prisma.io/docs/tutorials/setup-prisma/create-new-db/mysql-gui4peul2u

If you get error "Your token is invalid. It might have expired or you might be using a token from a different project."

Generate prisma token

```sh
prisma token
```

and use it on request header.
