# annotation-example
annotation/ text-highlights

Download Plugin : https://github.com/openannotation/annotator/downloads

For server side response object as follows:
var data = {"ranges":[{"start":"","startOffset":25,"end":"","endOffset":31}],
      "quote":"fished","text":"rtyrtyr","uri":"http://this/document/only",
      "user":  {id: 6, name: "Alice"},
      "created": "2016-09-06T11:34:59.389047+00:00",
      "permissions": {
        "update": [1],
        "admin": [1],
        "read": [1],
        "delete": [1]
      }
    };
    res.send({rows: [data], total: 1});



