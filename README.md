# React Webpack Typescript Boilerplate

- **[React](https://facebook.github.io/react/)** (17.x)
- **[Webpack](https://webpack.js.org/)** (5.x)
- **[Typescript](https://www.typescriptlang.org/)** (4.x)
- **[Hot Module Replacement (HMR)](https://webpack.js.org/concepts/hot-module-replacement/)** ([React Hot Loader](https://github.com/gaearon/react-hot-loader))
- Production build script (Webpack)
- Image loading/minification ([Image Webpack Loader](https://github.com/tcoopman/image-webpack-loader))
- [SASS](http://sass-lang.com/) support
- Code linting ([ESLint](https://github.com/eslint/eslint)) and formatting ([Prettier](https://github.com/prettier/prettier))

## Installation

1. Clone/download repo
2. `yarn install` (or `npm install` for npm)
3. `yarn add packagename --dev` (for installing packages in the dev dependency)

## Usage

**Development**

`yarn run start-dev`

- Build app continuously (HMR enabled)
- App served @ `http://localhost:8080`

**Production**

`yarn run start-prod`

- Build app once (HMR disabled) to `/build/`
- App served @ `http://localhost:3000`

---

**All commands**

| Command               | Description                                                                    |
| --------------------- | ------------------------------------------------------------------------------ |
| `yarn run start-dev`  | Build app continuously (HMR enabled) and serve @ `http://localhost:8080`       |
| `yarn run start-prod` | Build app once (HMR disabled) to `/build/` and serve @ `http://localhost:3000` |
| `yarn run build`      | Build app to `/build/`                                                         |
| `yarn run lint`       | Run linter                                                                     |
| `yarn run lint --fix` | Run linter and fix issues                                                      |
| `yarn run start`      | (alias of `yarn run start-dev`)                                                |

**Note**: replace `yarn` with `npm` in `package.json` if you use npm.

## Reference

- [React Webpack Typescript Starter](https://github.com/vikpe/react-webpack-typescript-starter)
- [Create React App](https://github.com/facebook/create-react-app)
