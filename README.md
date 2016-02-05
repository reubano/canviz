# canviz
Automatically exported from code.google.com/p/canviz

Canviz is a JavaScript library for drawing Graphviz graphs to a web browser canvas. More technically, Canviz is a JavaScript xdot renderer. It works in most modern browsers.

Using Canviz has advantages for your web application over generating and sending bitmapped images and imagemaps to the browser:

- The server only needs to have Graphviz generate xdot text; this is faster than generating bitmapped images.
- Only the xdot text needs to be transferred to the browser; this is smaller than binary image data, and, if the browser supports it (which most do), the text can be gzip- or bzip2-compressed.
- The web browser performs the drawing, not the server; this reduces server load.
- The user can resize the graph without needing to involve the server; this is faster than having the server draw and send the graph in a different size.
