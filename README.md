# Snappy - Chat Application 
Snappy is chat application build with the power of MERN Stack. You can find the tutorial [here](https://www.youtube.com/watch?v=otaQKODEUFs)

<img width="1440" alt="Screenshot 2023-07-26 at 3 15 36 PM" src="https://github.com/aniasusual/snappy/assets/82938725/879e573d-cab0-475e-897b-c9c9ab4ff137">
<img width="1440" alt="Screenshot 2023-07-26 at 3 15 40 PM" src="https://github.com/aniasusual/snappy/assets/82938725/2dba41a0-e9a6-4725-af61-0a543052f4be">
<img width="1440" alt="Screenshot 2023-07-26 at 3 15 23 PM" src="https://github.com/aniasusual/snappy/assets/82938725/1abfa1ef-87d9-455b-94ef-7ae8c3e44973">

<img width="1440" alt="Screenshot 2023-07-26 at 3 18 36 PM" src="https://github.com/aniasusual/snappy/assets/82938725/347b6692-7252-4834-abf9-a0eaad3474ca">





## Installation Guide

### Requirements
- [Nodejs](https://nodejs.org/en/download)
- [Mongodb](https://www.mongodb.com/docs/manual/administration/install-community/)

Both should be installed and make sure mongodb is running.

```shell
git clone https://github.com/koolkishan/chat-app-react-nodejs
cd chat-app-react-nodejs
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
yarn start
```
For Backend.

Open another terminal in folder, Also make sure mongodb is running in background.
```shell
cd server
yarn start
```

Done! Now open localhost:3000 in your browser.
