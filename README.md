# connect-sts (Strict Transport Security)

This middleware add *Strict-Transport-Security* header.

## Usage

     var connect = require('connect');
     var sts = require('connect-sts');
     var server = connect.createServer(sts(max_age, includeSubdomains);
     server.listen(3030);

## Reference

* http://tools.ietf.org/html/draft-hodges-strict-transport-sec-02
* http://en.wikipedia.org/wiki/Strict_Transport_Security

## License

BSD
