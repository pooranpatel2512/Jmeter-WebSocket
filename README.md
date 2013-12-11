ApacheJmeter-WebSocket
================

This is a Websocket sample for Jmeter. It is extended from the websocket sampler from this project.

https://github.com/kawasima/jmeter-websocket

Prerequisites :

* Bacis Jmeter and how to set up a test plan with samplers, as i am using some of the terminology used in the documentation provided by Jmeter website. 
* You also need to read about how to use an external plugin in Jmeter.
* Basic knowledge about how websockets are working.

I have modified the plug-in in such a way that it will use only one wesocket connection for one user thread. example: If you will create 50 user thread (with one thread having 50 websocket sampler request), then only 50 websocket connections will be used for 50 user threads.

Please feel free to ask for any questions or suggestions.

