# FASTAPI_WEBSOCKET_TEST
Example of chat between 2 (or more) users. 
WebSocket is a realtime technology that enables bidirectional, full-duplex communication between client and server over a persistent, single-socket connection.

# References
- https://www.youtube.com/watch?v=ADVsjLHevtY
- https://github.com/codingwithroby/Youtube/tree/main/2023/fastapi-websockets

# Render
to run on `Render`
```commandline
uvicorn main:app --host 0.0.0.0 --port 10000 --reload
```

# Version 2
- using:
    - `main2.py`
    - `static/ws.js`
    - `templates/socket.html`
- reference: https://www.tutorialspoint.com/fastapi/fastapi_websockets.htm
- same as version 1 but breaks down the `html` and the `js` files