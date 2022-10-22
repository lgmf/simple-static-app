# Simple Static App

## Setup

1. Install nvm https://github.com/nvm-sh/nvm#installing-and-updating

2. Use nvm to install node lts version 
  ```sh
    nvm install --lts`
  ```

3. Verify if it worked by checking the node version
  ```sh
    node --version
    npm --version
  ```

4. On the project folder install de dependencies
  ```sh
    npm install
  ```

## Dev

```sh
 npm run dev
```

> This command will use live-server to start a local server and reload it every time a file changes

## Prod
```sh
 npm start
```
> This command uses serve package to start a server without the live reloading feature