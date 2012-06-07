iso8601
=======

![build status](https://secure.travis-ci.org/calmh/node-iso8601.png)](http://travis-ci.org/calmh/node-iso8601)

    var iso8601 = require('iso8601');
    var fromIso8601 = iso8601.fromIso8601;
    var toIso8601 = iso8601.toIso8601;
    
    var d = new Date(1325471624000);
    toIso8601(d); // => 2012-01-02T02:33:44Z
    
    fromIso8601('2012-01-02T02:33:44Z'); // => new Date(1325471624000)

