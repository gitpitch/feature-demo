## Code Presenting
## Repo Source Files
@css[tip](Press the Space or Down key for a live demo.)

@fa[arrow-down]

@snap[south doclink]
See the [GitPitch Code Presenting Docs](https://gitpitch.com/docs/code-features) for further details.
@snapend

+++?code=src/go/server.go&lang=golang&title=Source: Golang File

@[1,3-6](Present code found within any repo source file.)
@[8-18](Without ever leaving your slideshow.)
@[19-28](Using GitPitch code-presenting with (optional) annotations.)

---
@title[Present Static Block]

## Code Presenting
## Static Source Blocks
@css[tip](Press the Space or Down key for a live demo.)

@fa[arrow-down]

@snap[south doclink]
See the [GitPitch Code Presenting Docs](https://gitpitch.com/docs/code-features) for further details.
@snapend

+++
@css[menu-title slide-title](Source: JavaScript Block)

```javascript
// Include http module.
var http = require("http");

// Create the server. Function passed as parameter
// is called on every request made.
http.createServer(function (request, response) {
  // Attach listener on end event.  This event is
  // called when client sent, awaiting response.
  request.on("end", function () {
    // Write headers to the response.
    // HTTP 200 status, Content-Type text/plain.
    response.writeHead(200, {
      'Content-Type': 'text/plain'
    });
    // Send data and end response.
    response.end('Hello HTTP!');
  });

// Listen on the 8080 port.
}).listen(8080);
```

@[1,2](You can present code inlined within your slide markdown too.)
@[9-17](Displayed using code-syntax highlighting just like your IDE.)
@[19-20](Again, all of this without ever leaving your slideshow.)

---
@title[Present GIST]

## Code Presenting
## GitHub GIST
@css[tip](Press the Space or Down key for a live demo.)

@fa[arrow-down]

@snap[south doclink]
See the [GitPitch Code Presenting Docs](https://gitpitch.com/docs/code-features) for further details.
@snapend

+++?gist=onetapbeyond/494e0fecaf0d6a2aa2acadfb8eb9d6e8&lang=Scala&title=Source: Scala GIST

@[23](You can even present code found within any GitHub GIST.)
@[41-53](GIST source code is beautifully rendered on any slide.)
@[57-62](Code-presenting works seamlessly both online and offline.)

