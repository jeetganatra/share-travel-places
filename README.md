<h1 align="center">
Share Travel Places
</h1>
<p align="center">
MongoDB, Expressjs, React, Nodejs
</p>

> Share Travel Places is a Website where users can share the places they travelled to, add their photos and describe the place for others to have a look at.

## Clone or Download

```terminal
$ git clone https://github.com/jeetganatra/share-travel-places.git
$ npm i
```

## Project structure

```terminal
LICENSE
package.json
Frontend/
   package.json
Backend/
   package.json
   .env (to create .env, check [prepare your secret session])
...
```

# Usage (run fullstack app on your machine)

## Prerequirements

- [MongoDB](https://gist.github.com/nrollr/9f523ae17ecdbb50311980503409aeb3)
- [Node](https://nodejs.org/en/download/) ^10.0.0
- [npm](https://nodejs.org/en/download/package-manager/)

Notice: You need client and server runs concurrently in different terminal sessions, in order to make them talk to each other

## Client-side usage(PORT: 3000)

```terminal
$ cd Frontend   // go to the Frontend folder
$ npm i       // npm install pacakges
$ npm start // run it locally
```

## Server-side usage(PORT: 5000)

### Start

```terminal
$ cd Backend   // go to the Backend folder
$ npm i       // npm install pacakges
$ nodemon app.js // run it locally
```

# Dependencies(tech-stacks)

| Client-side              | Server-side               |
| ------------------------ | ------------------------- |
| react: ^16.11.0          | bcryptjs: ^2.4.3          |
| react-dom: ^16.11.0      | body-parser: ^1.19.0      |
| react-router-dom: ^5.2.0 | express-validator:^6.10.0 |
|                          | dotenv: ^8.2.0            |
|                          | express: ^4.17.1          |
|                          | jsonwebtoken: ^0.5.1      |
|                          | mongoose: ^5.12.3         |
|                          | multer: ^1.4.2            |
|                          | nodemon: ^2.0.7           |
|                          | uuid: ^8.3.2              |

# Screenshots of this project

## Home page

![Home page displaying all the users](https://i.imgur.com/aNJwOVal.jpg)

## User Login/SignUp page

![User can sign in or sign up](https://i.imgur.com/OVkI0bTl.jpg)

## LoggedIn user can add their own place

![LoggedIn user can add the place and describe it](https://i.imgur.com/7lobo9rl.jpg)

## After adding the place

![Preview after adding adding the place](https://i.imgur.com/mGB5FfUl.jpg)

## Location can be seen on Google Maps

![Location on Goolge maps](https://i.imgur.com/1LmZHmvl.jpg)

## Standard

[![JavaScript Style Guide](https://cdn.rawgit.com/standard/standard/master/badge.svg)](https://github.com/standard/standard)

## BUGs or Comments

[Create new Issues](https://github.com/jeetganatra/share-travel-places/issues)

Email Me: jeetganatra138@gmail.com

## Author

[jeetganatra](https://github.com/jeetganatra)

### License

[MIT](https://github.com/jeetganatra/share-travel-places/blob/main/LICENSE)
