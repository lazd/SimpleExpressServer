# SimpleExpressServer
> A Node.js + express server for static files and Stylus CSS

Like Python's SimpleHTTPServer, but with support for Stylus CSS.


## Starting the server

First, install the requried modules with NPM:

```
npm install
```

Then, start the server:

```
node server.js
```


## Using Stylus

Using Stylus with SimpleExpressServer is easy. To get started, simply edit the files inside of `public/styles`.

The server will compile `public/styles/index.styl` to `public/styles/index.css`. Your HTML pages can then include `index.css` with a link tag:

```html
<link rel="stylesheet" href="/styles/index.css">
```


## Changing the server port

Set the `PORT` environment variable, then launch the server:

```
PORT=8000 node server.js
```


## License

This software is public domain.
