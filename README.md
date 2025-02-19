_`NodeJs Starter Template`_

## Configurations:

1. ESLint plugin for TypeScript
2. Prettier plugin for TypeScript
3. Commitizen to enforce a consistent commit message format
4. Husky for git hooks
5. Realease for automated versioning and publishing with change logs
6. Staged linting with ESLint and Prettier
7. Branch name validation for feature branches
8. Some useful VSCode extensions

## Formating

Prittier is already integrated with ESLint. To format yourfiles, run:

```bash
npm run format
# or
yarn format
# or
pnpm format
```

## Linting

ESLint is already integrated with Prettier. To lint your files, run:

```bash
npm run lint
# or
yarn lint
# or
pnpm lint
```

## Commit

Conventional commit commands follow the [Conventional Commits specification](https://www.conventionalcommits.org/en/v1.0.0/).

```bash
cz
# or
git cz
```

Run this command to create a commit with the selected type, scope, and message.

## Release & CHANGELOG.md

Release-it will create a new tag, update the `CHANGELOG.md`, and push the changes to Github, run:

```bash
npm run release
# or
yarn release
# or
pnpm release
```
