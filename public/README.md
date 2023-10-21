# Quicky - Chat Application 
Quicky is chat application build with the power of MERN Stack.



## Installation Guide

### Requirements
- [Nodejs](https://nodejs.org/en/download)
- [Mongodb](https://www.mongodb.com/docs/manual/administration/install-community/)

Both should be installed and make sure mongodb is running.

```shell
git clone https://github.com/ericcaptain22/Chat-App
cd CHAT-APP
```
Now rename env files from .env.example to .env
```shell
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
Now just start the development server.

For Frontend.
```shell
cd public
yarn start or npm start
```
For Backend.

Open another terminal in folder, Also make sure mongodb is running in background.
```shell
cd server
yarn start or npm start
```

Done! Now open localhost:3000 in your browser.
"# Chat-App" 

