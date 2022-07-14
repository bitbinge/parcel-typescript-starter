# Parcel Typescript Starter

A simple starter project that uses [Parcel](https://parceljs.org), [TypeScript](https://www.typescriptlang.org/), [ESlint](https://eslint.org/), and [Prettier](https://prettier.io/).

## Dev Server

To start the development server, run `npm start`.

## Build for Production

To build a minified, tree shaken, code-split'n production build, run `npm run build`.

The build output will be in the `dist/` directory.

### [browserlist](https://github.com/browserslist/browserslist)

Build output will target compatibility with the browsers specified in the `browserlist` property of [package.json](./package.json)

## Development Dependencies

THe following libaries, plugins and projects are used for development.

### [@tsconfig/recommended](https://www.npmjs.com/package/@tsconfig/recommended)

Provides the base settings extended in [tsconfig.json](./tsconfig.json).

### [@typescript-eslint](https://github.com/typescript-eslint/typescript-eslint)

Provides the eslint rules for Typescript used in [.eslintrc.json](./.eslintrc.json).

### [husky](https://github.com/typicode/husky) & [lint-staged](https://github.com/okonet/lint-staged)

Installs the
[pre-commit](./.husky/pre-commit) git hook during the `prepare` step of `npm install`.

This hook executes the tasks specified in the `lint-staged` property of [package.json](./package.json).

### [shx](https://github.com/shelljs/shx) (ShellJS)

Allows executing Unix shell commands in [package.json](./package.json) scripts.
