# typescript-library-boilerplate

[![](https://img.shields.io/npm/v/tlb)](https://www.npmjs.com/package/tlb)
[![Build](https://github.com/ezze/typescript-library-boilerplate/actions/workflows/main.yml/badge.svg)](https://github.com/ezze/typescript-library-boilerplate/actions/workflows/main.yml)
[![Coverage Status](https://coveralls.io/repos/github/ezze/typescript-library-boilerplate/badge.svg)](https://coveralls.io/github/ezze/typescript-library-boilerplate)
[![](https://img.shields.io/github/license/ezze/typescript-library-boilerplate)](https://github.com/ezze/typescript-library-boilerplate/blob/HEAD/LICENSE.md)

Use this repo as [template](https://docs.github.com/en/repositories/creating-and-managing-repositories/creating-a-repository-from-a-template) for new library creation.

## Installation

```
pnpm install tlb -P
```

1. Fix installation command above.
2. Change `name`, `version`, `description`, `keywords`, `author`, `repository` and `bugs` properties in `package.json`.
3. Change library `name` in `vite.config.ts`.
4. Enable library repository on https://coveralls.io/ for test coverage reports.
5. Replace contents of `CHANGELOG.md`.
6. Change library author in `LICENSE.md`.
7. Change `README.md` file: fix title, shields and replace all the rest.

## Build

```
pnpm build
```

## Develop

```
pnpm dev
```

## Test

```
pnpm lint
pnpm test
pnpm test:coverage
```

## Changelog

Changelog is available [here](CHANGELOG.md).

## License

[MIT](LICENSE.md)
