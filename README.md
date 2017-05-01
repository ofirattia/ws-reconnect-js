# ws-reconnect-js: a Node.js WebSocket Client 
> This lib designed for web applications and compatible with webpack bundling. 


## Usage

```
const WSCLINET = require('ws-reconnect-js');
var wsclient = new WSCLIENT("localhost:1010",{
	retryCount:1, // default is 2
	reconnectInterval: 1 // default is 5
},{
onMessageHandler: handlerFunction
});
wsclient.start();

```
