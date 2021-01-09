# Learn TWITTER OAuth using ExpressJS

This example demonstrates how to use [Express](http://expressjs.com/) 4.x and
[Passport](http://passportjs.org/) to authenticate users using Twitter.  
Use this example as a starting point for your own web applications.

Modified from : https://github.com/passport/express-4.x-twitter-example

## Instructions

To install this example on your computer, clone the repository and install
dependencies.

```bash
$ git clone git@github.com:nsvirk/learn-express-twitter-oauth1.git
$ cd learn-express-twitter-oauth1
$ npm install
```

### Setup Twitter Consumer Key & Secret
#### Create .env file in the root folder
```bash
touch .env

TWITTER_CONSUMER_KEY="xxxxxx" 
TWITTER_CONSUMER_SECRET="xxxxxx"
```

### Run Server
```bash
$ node server.js
```

Open a web browser and navigate to [http://127.0.0.1:8080/](http://127.0.0.1:8080/)
to see the example in action.

