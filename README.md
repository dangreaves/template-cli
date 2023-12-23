# Template for building Node.js CLI projects with TypeScript

![GitHub License](https://img.shields.io/github/license/dangreaves/template-cli)

This template is a starting point for building Node.js CLI projects with TypeScript.

- Uses [commander](https://github.com/tj/commander.js) to manage the entrypoint in [src/index.ts](./src/index.ts)
- Commands are added to the [src/commands](./src/commands) directory
- See [src/commands/hello-world.ts](./src/commands/hello-world.ts) for an example command.

## Usage

Run the CLI with the following command.

```sh
npm start -- hello-world
```

## Included tools

This template has the following tools configured.

- [tsx](https://github.com/privatenumber/tsx)
- [husky](https://github.com/typicode/husky)
- [prettier](https://prettier.io)
- [commander](https://github.com/tj/commander.js)
- [typescript](https://www.typescriptlang.org)
- [lint-staged](https://github.com/lint-staged/lint-staged)
