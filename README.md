# Setup React app (TS)

## Technology used

- **[React](https://facebook.github.io/react/)** (18.x)
- **[Webpack](https://webpack.js.org/)** (5.x)
- **[Typescript](https://www.typescriptlang.org/)** (4.x)
- Test frameworks **[Cypress](https://docs.cypress.io/)** (10.x)
- Code linting ([ESLint](https://github.com/eslint/eslint)) and formatting ([Prettier](https://github.com/prettier/prettier))

## Installation

1. Clone/download repo
2. `npm install` (or `yarn install` for yarn)

## Usage

**Development**

`npm run start`

- App served @ `http://localhost:8080`

**Production**

`npm run build`

- Build app once to `/dist/`

---

| Command            | Description                     |
| ------------------ | ------------------------------- |
| `npm start`        | Serve @ `http://localhost:8080` |
| `npm run build`    | Build app to `/dist/`           |
| `npm run test`     | Run tests                       |
| `npm run lint`     | Run linter                      |
| `npm run lint:fix` | Run linter and fix issues       |
| `npm run format`   | Run prettier                    |

**Note**: replace `npm` with `yarn` in `package.json` if you use npm.
