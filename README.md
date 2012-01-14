# CoffeeScript (JS) wrapper for SocketStream 0.3

Allows you to use CoffeeScript files (.coffee) in your SocketStream project.


### Instructions

Add `ss-coffee` to your application's `package.json` file and then add this line to app.js:

    ss.client.formatters.add(require('ss-coffee'));