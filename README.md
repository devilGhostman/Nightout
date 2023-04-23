# Nightout
## Demo - [LIVE](https://nightout-eta.vercel.app/)
```shell
https://nightout-eta.vercel.app/
```

## Getting started
### Prerequisites

**Node version 14.x**

### Cloning the repository

```shell
https://github.com/devilGhostman/Nightout.git
```

### Install packages

```shell
cd Nightout/
npm i
```

### Setup .env file


```js
DATABASE_URL=
GOOGLE_CLIENT_ID=
GOOGLE_CLIENT_SECRET=
GITHUB_ID=
GITHUB_SECRET=
NEXTAUTH_SECRET=
```


### Setup Prisma

```shell
npx prisma db push

```

### Start the app

```shell
npm run dev
```

## Available commands

Running commands with npm `npm run [command]` and `npm [command]`

| command         | description                                        |
| :-------------- | :------------------------------------------------- |
| `i` or `install`| Install all the dev dependency to run app          |
| `dev`           | Starts a development instance of the app in nextjs |
