# Verifying User Account by email :heavy_check_mark:
> simple user account registering and login with user email verification using nodemailer
> Nodejs App (MVC) and MongoDb

## Prerequisite:
- [x] npm/node latest version (node.js)

## Technologies used:
### 1. Backend
- Nodejs
- ExpressJs
- MongoDb

### 2. Frontend
- Jquery
- Mdbootstrap
- Bootstrap

## Dependency install :heavy_exclamation_mark:
```
npm install --save
```
Dependencies are:
> express, bcrypt, cors, jsonwebtoken, mongoose, cookie-parser, bootstrap, mdbootstrap, jquery, helmet, dotenv, nodemailer

## Dev Dependency install
```
npm install --save-dev
```
Dev Dependency is:
> nodemon

## Add .env file then write down below :heavy_exclamation_mark:
```
SECRET_KEY=?
SECRET_ACCESS=?
SECRET_REFRESH=?
DATABASE_URI=?
PORT=?
// For gmail SMTP authentication (Your gmail email and password)
SECRET_USER=?
SECRET_PASSWORD=?
```

## To generate tokens using CRYPTO write and run in your terminal:
```bash
node
require('crypto').randomBytes(64).toString('hex')
```

## Run Project
```
npm run devStart
```
Or
```
nodemon app.js
```

