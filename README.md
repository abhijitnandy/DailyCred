# DailyCred
Express 4 example for DailyCred

The [login example](https://github.com/dailycred/passport-dailycred/tree/master/examples/login) in DailyCred doesn't work with newer versions of Express.

To run this version, make the following changes

In 'app.js'

1. Add your Client ID
1. Add your Client Secret

These are available on the Settings page

For your Application in DailyCred, set the Callback to
http://localhost:3000/auth/dc/callback


* Install dependencies

    npm install

* Run

    node app.js

