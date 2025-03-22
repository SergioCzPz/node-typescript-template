# Node.js and Typescript Template

<p align="center">
  <a href="https://skillicons.dev">
    <img src="https://skillicons.dev/icons?i=nodejs,npm,ts,git" />
  </a>
</p>

Node.js and Typescript ready to use.
Work with:

- [Node.js](https://nodejs.org)
- [Typescript](https://www.typescriptlang.org)
- [Prettier](https://prettier.io)
- [Eslint](https://typescript-eslint.io)
- [Husky](https://typicode.github.io/husky)

---

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)

---

1. You can create a new repository based in this repository in `Use this template` label or clone it:

```bash
git clone
```

2. Checkout `.node-version` file and your current version of node.js. See it with: `node -v`

3. Install dependencies:

```bash
npm install
```

4. To work with husky and [conventional commits](https://www.conventionalcommits.org/en/v1.0.0)

```bash
npm run prepare
```

---

## Usage

All the files to be transpile must to be inside `src/` folder and the entry point is `src/app.ts`.

### Extensions

Extensions you should have:

1. Prettier

2. ESLint

### Develope

To work in develope mode:

```bash
npm run dev
```

### Build

To build your project:

```bash
npm run build
```

### Run Compiled Project

```bash
npm start
```

This will execute `dist/app.js`

## Considerations

- Feel free to modify `.prettierrc`, you could also find [more configurations](https://prettier.io/docs/precommit) to format your code and pre-commit hook

- Working with [Express](https://expressjs.com) with Typescript, could make a little hard, consider use [Disable eslint rules](https://eslint.org/docs/latest/use/configure/rules#disabling-inline-comments) just disabling inline comments.

- This project uses [Commilint](https://commitlint.js.org) and pre commit hook with [Husky](https://typicode.github.io/husky)

## Contributing

1. Fork the repository.

2. Create a new branch: `git checkout -b <feature-name>`.

3. Make your changes.

4. Push your branch: `git push origin <feature-name>`.

5. Create a pull request.
