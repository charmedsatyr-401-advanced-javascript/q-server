![CF](http://i.imgur.com/7v5ASc8.png) LAB
=================================================

## Lab 20: Q Server

### Author: Joseph Wolfe

### Links and Resources
* [GitHub](https://github.com/charmedsatyr-401-advanced-javascript/q-server)
* [![Build Status](https://travis-ci.org/charmedsatyr-401-advanced-javascript/q-server.svg?branch=master)](https://travis-ci.org/charmedsatyr-401-advanced-javascript/q-server)
* [Back End](http://qserver-env-0.5wcm66q2tu.us-west-2.elasticbeanstalk.com)

#### Documentation
See [Simple Node Message Queue (@nmq)](https://www.npmjs.com/package/@nmq/q)

### Modules
* `./index.js`

* `./server/server.js`

-----

#### `./index.js`
* The entry point to the application. Invokes the Q server's `start` method.

-----

#### `./server/server.js`
* Creates a `files` namespace and monitors `save` and `error` events.
* Creates a `database` namespace and monitors `create`, `read`, `update`, and `delete` events.

-----

### Setup
#### `.env` requirements
* `PORT` - Port number

#### Running the app
* `npm run start`

#### Tests
* `npm run lint`

#### UML
N/A
