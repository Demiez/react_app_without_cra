# react_app_without_cra

### Implementing starter skeleton without create-react-app in order to avoid lots of boilerplate code

### Steps:

yarn init -y <br>
touch tsconfig.json <br>
yarn add react react-dom <br>
yarn add -D @types/react @types/react-dom <br>
mkdir public src ./src/components <br>
touch ./public/index.html ./src/index.tsx ./src/App.tsx <br>
mkdir ./src/components/Default && touch ./src/components/Default/Default.tsx <br>

#### Webpack block

yarn add -D webpack webpack-cli webpack-dev-server ts-node tsconfig-paths-webpack-plugin @types/node @types/webpack @types/webpack-dev-server <br>
yarn add -D ts-loader fork-ts-checker-webpack-plugin html-webpack-plugin <br>
touch webpack.config.ts

#### ESlint block

yarn add -D eslint eslint-plugin-react eslint-plugin-react-hooks eslint-plugin-prettier eslint-config-prettier eslint-plugin-import @typescript-eslint/eslint-plugin @typescript-eslint/parser <br>
touch .eslintrc.json <br>
touch .eslintignore
