# react-workshop-starter

## quickstart

```shell
git clone https://github.com/bartw/react-workshop-starter
cd react-workshop-starter
npm install
npm start
```

browse to http://localhost:8080/

## slowstart

```shell
mkdir react-workshop-starter
cd react-workshop-starter
npm init -y
npm install --save-dev webpack webpack-dev-server babel-core babel-loader babel-preset-es2015 babel-preset-react jest babel-jest
npm install --save react react-dom
touch webpack.config.js webpack.config.prod.js .babelrc 
mkdir public
touch public/index.html
mkdir src
touch src/index.js
code .
```

## commands

```shell
npm start
npm test
npm run test:once
npm run build
npm run build:debug
```