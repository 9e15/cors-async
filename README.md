# cors-async

Like [cors](https://www.npmjs.com/package/cors) but async.

## API

Same as cors but returns promise instead of invoking callback.

Examples:

```javascript
  const corsAsync = require('cors-async')(/* options here */);

  ...

  return corsAsync(req, res)
    .then(() => {
      // next handler
    });
```

## License

MIT
