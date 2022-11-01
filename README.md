# NLW Copa

<p align="center">
  <img alt="Developer" src="https://img.shields.io/badge/developer-jfilipedias-blue">
  <img alt="GitHub" src="https://img.shields.io/github/license/jfilipedias/nlw-copa">
</p>
<br>

## Technologies

- [Typescript](https://typescriptlang.org/)
- [ReactJS](https://reactjs.org/)
- [React Native](https://reactnative.dev/)
- [NodeJS](https://nodejs.org/)
- [Next.js](https://nextjs.org/)
- [Tailwind](https://tailwindcss.com/)
- [Fastify](https://fastify.io/)
- [Prisma](https://prisma.io/)
- [Mermaid](https://mermaid-js.github.io/)
- [Expo](https://expo.dev/)

## Getting Started

### Back-end

Install the dependencies:

```shell
npm i
```

Setup the `.env` file:

```env
DATABASE_URL="./dev.db"
```

If you ar running the project on [WSL](https://learn.microsoft.com/windows/wsl/install), the you will need to install the Google Chrome to generate the Entity Relationship Diagram (ERD) with [Mermaid](https://mermaid-js.github.io/).:

```shell
sudo apt update && sudo apt -y upgrade && sudo apt -y autoremove
wget https://dl.google.com/linux/direct/google-chrome-stable_current_amd64.deb
sudo apt -y install ./google-chrome-stable_current_amd64.deb
```

Generate the Prisma client and ERD:

```shell
npx prisma generate
```

## License

This project is licensed under the MIT. Consult the [LICENSE](LICENSE) for more information.
