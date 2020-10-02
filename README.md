# Fork of node-firebird

- [node-firebird](https://www.npmjs.com/package/node-firebird)


## Installation

```bash
npm install node-firebird-os
```

## Usage

```js
var Firebird = require('node-firebird-os');
```

### Methods

- `Firebird.escape(value) -> return {String}` - prevent for SQL Injections
- `Firebird.attach(options, function(err, db))` attach a database
- `Firebird.create(options, function(err, db))` create a database
- `Firebird.attachOrCreate(options, function(err, db))` attach or create database
- `Firebird.pool(max, options) -> return {Object}` create a connection pooling

### See more

- [node-firebird](https://www.npmjs.com/package/node-firebird)