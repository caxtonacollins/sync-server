---
<p align="center">
  <a href="http://nestjs.com/" target="blank"><img src="https://nestjs.com/img/logo-small.svg" width="120" alt="Nest Logo" /></a>
</p>

<p align="center">
  A progressive <a href="http://nodejs.org" target="_blank">Node.js</a> framework for building efficient and scalable server-side applications.
</p>

<p align="center">
  <a href="https://www.npmjs.com/~nestjscore" target="_blank"><img src="https://img.shields.io/npm/v/@nestjs/core.svg" alt="NPM Version" /></a>
  <a href="https://www.npmjs.com/~nestjscore" target="_blank"><img src="https://img.shields.io/npm/l/@nestjs/core.svg" alt="Package License" /></a>
  <a href="https://www.npmjs.com/~nestjscore" target="_blank"><img src="https://img.shields.io/npm/dm/@nestjs/common.svg" alt="NPM Downloads" /></a>
  <a href="https://circleci.com/gh/nestjs/nest" target="_blank"><img src="https://img.shields.io/circleci/build/github/nestjs/nest/master" alt="CircleCI" /></a>
  <a href="https://discord.gg/G7Qnnhy" target="_blank"><img src="https://img.shields.io/badge/discord-online-brightgreen.svg" alt="Discord"/></a>
</p>

---

## 📦 Description

This project is a NestJS-based backend server, initialized inside the `app/` directory and managed with **Yarn v4.9.1** using `node_modules` for dependency resolution.

---

## 🚀 Project Setup

### 1. Clone the repository

```bash
git clone https://github.com/caxtonacollins/sync-server.git
cd sync-server/app
````

### 2. Install Yarn (v4.9.1)

```bash
corepack enable
corepack prepare yarn@4.9.1 --activate
```

### 3. Configure `.yarnrc.yml` in `app/` folder

Make sure it contains:

```yaml
nodeLinker: node-modules
```

### 4. Install dependencies

```bash
yarn install
```

---

## 🧪 Running the Application

```bash
# Start in development mode
yarn start:dev

# Start in watch mode
yarn start:debug

# Start in production mode
yarn start:prod
```

---

## 🧪 Testing

```bash
# Unit tests
yarn test

# End-to-end (e2e) tests
yarn test:e2e

# Test coverage
yarn test:cov
```

---

## 📁 Directory Structure

```
sync-server/
├── .github/
├── app/               # NestJS project root
│   ├── src/
│   ├── .yarn/
│   ├── .yarnrc.yml
│   ├── package.json
│   ├── yarn.lock
│   └── ...
├── LICENSE
└── README.md
```

---

## 📚 Resources

* [NestJS Documentation](https://docs.nestjs.com)
* [Yarn v4 Docs](https://yarnpkg.com)
* [Deployment guide](https://docs.nestjs.com/deployment)
* [NestJS Devtools](https://devtools.nestjs.com)

---

## 🛡 License

NestJS is [MIT licensed](https://github.com/nestjs/nest/blob/master/LICENSE).


---

