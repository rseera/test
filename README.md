# Crud Api with Node.js
A restful API in Node.js with token-based authentication. This project uses a blog-like CRUD system.

## Install

``` bash
# clone the repository
git clone https://github.com/samuelguebo/crud-api-nodejs.git

# install dependencies
npm install
```
## Configure
Global variables such as server port or token secret can be set in `app/utils/config.js`

## Start the app

``` bash
# start the server
node server

# instead, you can start the server with nodemon
nodemon server
```
## Features
### Initial data seed
On first run the app is populated with some initial data: posts, users, categories

### Restful API
An api with the following routes
* /posts
* /categories
* /users

### Token authentication
An authentication system is included using the [jsonwebtoken](https://github.com/auth0/node-jsonwebtoken) library. 
* `/authentication` generates a token if valid `username` and `password` are provided via Post
* `/users` is protected by the token authentication system

## Branch 2 updates


### Branch1 update


