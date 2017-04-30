# ws-reconnect-js: a Node.js WebSocket Client 

## Usage

```
const WSCLINET = require('ws-reconnect-es6');
var wsclient = new WSCLIENT("localhost:1010",{
	retryCount:1, // default is 2
	reconnectInterval: 1 // default is 5
},{
onMessageHandler: handlerFunction
});
wsclient.start();

```
