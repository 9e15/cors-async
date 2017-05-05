[![Build Status](https://travis-ci.org/kownacki/cors-async.svg?branch=master)](https://travis-ci.org/kownacki/cors-async)
# cors-async

Like [cors](https://www.npmjs.com/package/cors) but async.

## Installation

$ npm install cors-async

## API

Same as cors but returns promise instead of invoking callback.

Examples:

```javascript
  return corsAsync(req, res)
    .then(() => {
      // next handler
    });
```

## License

MIT
