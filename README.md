# Chatly - Chat Application 

![login page](./images/chatly2.png)

![home page](./images/chatly1.png)

## Installation Guide

### Requirements

- [Nodejs](https://nodejs.org/en/download)
- [Mongodb](https://www.mongodb.com/docs/manual/administration/install-community/)

Both should be installed and make sure mongodb is running.

#### First Method
```shell
git clone https://github.com/PLP-MERN-Stack-Development/real-time-communication-with-socket-io-codewin1.git
cd real-time-communication-with-socket-io-codewin1-main
```
Now rename env files from .env.example to .env
```shell
cd public
mv .env.example .env
cd ..
cd server
mv .env.example .env
cd ..
```

Now install the dependencies
```shell
cd server
yarn
cd ..
cd public
yarn
```
We are almost done, Now just start the development server.

For Frontend.
```shell
cd public
yarn add
yarn start
```
For Backend.

Open another terminal in folder, Also make sure mongodb is running in background.
```shell
cd server
yarn add
yarn start
```
Done! Now open localhost:5000 in your browser.
