### Indecision App

### Installing Indecision App
```
npm install -g yarn
yarn add global live-server or npm install -g live-server
live-server public

yarn global add babel-cli@6.24.1 or npm install -g babel-cli@6.24.1
yarn init or npm init
yarn add babel-preset-react@6.24.1 babel-preset-env@1.5.2

babel src/app.js --out-file=public/scripts/app.js --presets=env,react

Terminal 1
=========
babel src/app.js --out-file=public/scripts/app.js --presets=env,react --watch

Terminal 2
==========
live-server public
```
