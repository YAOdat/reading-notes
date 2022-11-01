## OSI Mode
Open Systems Interconnection (OSI) is a standard model that describes seven layers that computer systems use to communicate over a network.
the seven layers are:

1. Physical Layer
2. Data Link Layer
3. Network Layer
4. Transport Layer
5. Session Layer
6. Presentation Layer
7. Application Layer

## Socket.io

Socket.io is a library that provides a live communication channel between a client and a server. (Built with WebSocket protocol)

To establish a socket io server:

```
import { createServer } from "http";
import { Server } from "socket.io";

const httpServer = createServer();
const io = new Server(httpServer, {
  // options
});

io.on("connection", (socket) => {
  // ...
});

httpServer.listen(3000);
```
at the client side:
```
import { io } from "socket.io-client";

// CommonJS
const { io } = require("socket.io-client");
```
