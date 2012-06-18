# connect-sts (Strict Transport Security)

This middleware add the *Strict-Transport-Security* header.

## Usage

```javascript
var connect = require('connect');
var sts = require('connect-sts');

var maxAge = 3600000 * 24 * 30; // 1 month
var includeSubdomains = false;

var server = connect.createServer(sts(maxAge, includeSubdomains));

server.listen(3030);
```

## Reference

* http://tools.ietf.org/html/draft-hodges-strict-transport-sec-02
* http://en.wikipedia.org/wiki/Strict_Transport_Security

## License

BSD
