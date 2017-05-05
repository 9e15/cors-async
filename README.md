# cors-async

Like [cors](https://www.npmjs.com/package/cors) but async.

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
