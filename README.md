# Request Has Param

Easily check for params directly using a middleware.

# Install

```shell
$ npm install --save git+https://git@github.com/matteocrippa/request-has-param.git
```

# Usage

```nodejs
var hasParam = require('request-has-param');

// setup routes
app.use('/', hasParam(['test']), rootRoute);
```

This will check for all the request to have `req.param.test`.
