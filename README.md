# electron-react-app

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app), [Electron](https://github.com/electron/electron), and [Electron packager](https://github.com/electron/electron-packager).

![Screenshot](/docs/img/electron-react-app.jpg)

## Install

Clone the project

```bash
  git clone https://github.com/megahoma/electron-react-app.git
```

Go to the project directory

```bash
  cd electron-react-app
```

Install dependencies

```bash
  npm install
```


## Usage

Both processes have to be started simultaneously in different console tabs

```bash
  npm run react:start
  npm run electron:start
```
This will start the application with hot-reload so you can instantly start developing your application.

## Pakckaging

We use [Electron packager](https://github.com/electron/electron-packager) to build and package the application. By default you can run the following to package for your current platform

```bash
  npm run react:build
  npx electron-packager . --no-prune --ignore=/node_modules --ignore=/e2e --overwrite --ignore=/src 
--ignore=/public
```

## Contribute
Feel free to submit an issue or pull request anytime. If a change is made to the codebase with your PR, you'll be listed as a contributor.

## Coded by [megahoma](https://github.com/megahoma)
