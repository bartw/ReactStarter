# React-workshop-starter

## Prerequisites

* [Node.js](https://nodejs.org/)
* Basic javascript, html and css skills
* An editor, for example [Visual Studio Code](https://code.visualstudio.com/)

## Quickstart

```shell
git clone https://github.com/bartw/react-workshop-starter
cd react-workshop-starter
npm install
npm start
```

Browse to http://localhost:8080/.

## Slowstart

```shell
mkdir react-workshop-starter
cd react-workshop-starter
npm init -y
npm install --save-dev webpack webpack-dev-server babel-core babel-loader babel-preset-es2015 babel-preset-react jest babel-jest eslint eslint-plugin-react
npm install --save react react-dom showdown
touch webpack.config.js webpack.config.prod.js .babelrc .eslintrc
mkdir public
touch public/index.html
mkdir src
touch src/index.js
code .
```

## Commands

```shell
npm start
npm test
npm run test:once
npm run build
npm run build:debug
npm run lint
```

## License

React-workshop-starter is licensed under the [MIT License](http://www.opensource.org/licenses/mit-license.php).