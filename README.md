# Example Single Page Application using the XcooBee Cookie Kit web

This is an example of a single page application showing the use of the XcooBee Cookie Kit (XCK).

The XCK is a framework you can plug in to manage the creation and removal of cookies on your site after user gives or removes consent.

Please see the cookie kit for detailed documentation.

[XcooBee Cookie Kit](https://www.npmjs.com/package/xcoobee-cookie-kit-web)


## This example

The example has only one code file `index.html`. Please review the comments inside it to see how the XCK is started and managed.

Inside code, look for a tag of `<!-- COOKIE KIT SCRIPT START -->` to see the example implementation.

## The assumptions

- You are setting all cookies in JS or via `<xbee-cookie>` / `<xbee-script>` tags
- Your are loading and unloading 3rd party scrips like Google Analytics via the `<xbee-script>` tag.


## Use / Install

You should be able to open the `index.html` in browser directly, but most likely it will work better if you move the file to a webserver and serve the files from there. 

You can use a local-web-server with nodejs like `https://www.npmjs.com/package/local-web-server` which makes it trivial to serve this file.





