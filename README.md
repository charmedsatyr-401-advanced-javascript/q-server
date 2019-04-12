![CF](http://i.imgur.com/7v5ASc8.png) LAB
=================================================

## Lab 20: Q Server

### Author: Joseph Wolfe

### Links and Resources
* [GitHub](https://github.com/charmedsatyr-401-advanced-javascript/q-server)
* [![Build Status](https://travis-ci.org/charmedsatyr-401-advanced-javascript/q-server.svg?branch=master)](https://travis-ci.org/charmedsatyr-401-advanced-javascript/q-server)

#### Documentation
See [Simple Node Message Queue (@nmq)](https://www.npmjs.com/package/@nmq/q)

### Modules
#### `server.js`
* Monitors `save` and `error` events in the `files` namespace.
* Monitors `create`, `read`, `update`, and `delete` events in the `database` namespace.

### Setup
#### `.env` requirements
* `PORT` - Port number

#### Running the app
* `npm run start`

#### Tests
N/A

#### UML
N/A
