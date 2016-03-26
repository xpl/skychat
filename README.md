# Skychat
An example of WebRTC chat/paint app with distributed message history saving. You can embed it to HTTP 404 or 500 page, to let users hang around even when server is not working :)

Probably wont work if has too many peers (> 100), because the history synchronization algorithm is awful. To make it working on your own domain, you need to obtain a WebRTC API key at [developer.temasys.com.sg](http://developer.temasys.com.sg/) (they provide peer tracking service, which is required to make WebRTC work).

Does not work in Safari (due to lack of WebRTC support). Actually, it can work, if your disable the `hasNativeRTCSupport ()` check in JS code, but it will ask users to install a third-party plugin (developed by Skylink), and it can be quite disturbing.

## Live demo: [xpl.github.com/skychat](https://xpl.github.com/skychat)

[![img](http://img.leprosorium.com/2508370)](https://xpl.github.com/skychat)
