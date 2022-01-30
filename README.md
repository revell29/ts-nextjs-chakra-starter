<div align="center">
  <h1>🔋 ts-nextjs-chakra-starter</h1>
  <p>Next.js + Chakra-UI + TypeScript starter packed with useful development features.</p>
  
  
[![CodeFactor](https://www.codefactor.io/repository/github/revell29/ts-nextjs-chakra-starter/badge)](https://www.codefactor.io/repository/github/revell29/ts-nextjs-chakra-starter)
[![Maintainability Rating](https://sonarcloud.io/api/project_badges/measure?project=revell29_ts-nextjs-chakra-starter&metric=sqale_rating)](https://sonarcloud.io/dashboard?id=revell29_ts-nextjs-chakra-starter)
[![Bugs](https://sonarcloud.io/api/project_badges/measure?project=revell29_ts-nextjs-chakra-starter&metric=bugs)](https://sonarcloud.io/dashboard?id=revell29_ts-nextjs-chakra-starter)
[![Depfu](https://badges.depfu.com/badges/fc6e730632ab9dacaf7df478a08684a7/overview.svg)](https://depfu.com/repos/github/revell29/ts-nextjs-chakra-starter)

</div>

## Features

This repository is 🔋 battery packed with:

- ⚡️ Next.js 12
- ⚛️ React 17
- ✨ TypeScript
- 💨 Chakra-UI
- 🃏 Jest — Configured for unit testing
- 📈 Absolute Import and Path Alias — Import components using `@/` prefix
- 📏 ESLint — Find and fix problems in your code, also will **auto sort** your imports
- 💖 Prettier — Format your code consistently
- 🐶 Husky & Lint Staged — Run scripts on your staged files before they are committed
- 🤖 Conventional Commit Lint — Make sure you & your teammates follow conventional commit
- ⏰ Standard Version Changelog — Generate your changelog using `yarn release`
- 👷 Github Actions — Lint your code on PR
- 🚘 Automatic Branch and Issue Autolink — Branch will be automatically created on issue **assign**, and auto linked on PR
- 🔥 Snippets — A collection of useful snippets

## Getting Started

### 1. Clone this template using one of the three ways:

1. Using `create-next-app`

   ```bash
   npx create-next-app -e https://github.com/revell29/ts-nextjs-chakra-starter project-name
   ```

2. Deploy to Vercel

   [![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new/git/external?repository-url=https%3A%2F%2Fgithub.com%2Ftheodorusclarence%2Fts-nextjs-tailwind-starter)

### 2. Install dependencies

It is encouraged to use **yarn** so the husky hooks can work properly.

```bash
yarn install
```

### 3. Run the development server

You can start the server using this command:

```bash
yarn dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result. You can start editing the page by modifying `src/pages/index.tsx`.

### 4. Change defaults

There are some things you need to change including title, urls, favicons, etc.

Don't forget to change the package name in package.json

### 5. Commit Message Convention

This starter is using [conventional commits](https://www.conventionalcommits.org/en/v1.0.0/), it is mandatory to use it to commit changes.
