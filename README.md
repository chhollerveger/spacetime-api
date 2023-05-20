# Spacetime API

## 💻 Project

Memory recall application, where the user can add texts, photos and videos of important events in his life to a timeline, organized by month and year.

Project developed at [Rocketseat Education](https://github.com/rocketseat-education) 💜

## 🚀 Technologies

This project was developed with the following technologies:

- [Node.js](https://nodejs.org/en/)
- [TypeScript](https://www.typescriptlang.org/)
- [Prisma](https://www.prisma.io/)
- [Fastify](https://www.fastify.io/)
- [Zod](https://zod.dev/)
- [Axios](https://axios-http.com/)

## Getting Started

### Configuration:

Create `.env` file in the root of the project based on:

````
# Database
DATABASE_URL="file:./dev.db"

# Github
GITHUB_AUTH_URL="https://github.com/login/oauth"
GITHUB_API_URL="https://api.github.com"
GITHUB_CLIENT_ID=
GITHUB_CLIENT_SECRET=
````

### Running Project:

Targets on the command line:

- `npm install`
- `npx prisma migrate dev`
- `npm run dev`

### Other information:

- Use the `npx prisma studio` command to start Prisma Studio
get code github;
- Use the `npx prisma migrate reset` command after modifying tables;
- Go to [GitHub](https://github.com/settings/developers) to create a new OAuth App and get the credentials for the environment variables;
- Access `https://github.com/login/oauth/authorize?client_id=${GITHUB_CLIENT_ID}` to get user code for authentication;