This python script can be placed between traditional web penetration testing tools and WebSocket connections, which does translation from HTTP to WebSocket and back. Think of it like a fuzzing harness that is used for native code.

Example: python websocket-harness.py -p 8000 -u ws://dvws.local:8080/authenticate-user

In the example above, the WebSocket harness will listen on local loopback, and forward any HTTP POST requests to the target WebSocket endpoint (ws://dvws.local:8080/authenticate-user).

Happy bug hunting!
