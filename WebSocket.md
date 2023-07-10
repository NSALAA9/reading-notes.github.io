# Web Socket
 Web Socket is a protocol that enables full-duplex communication channels between a client and a server over a single TCP connection. The handshake process involves an HTTP-based request from the client, and once the connection is established, bidirectional communication can occur.

Proof of life or code functionality can be demonstrated through console/log messages, real-time updates on the client interface, and network traffic inspection.

socket.emit() is used in Socket.IO to send custom events from the client to the server or from the server to a specific client.

The difference between WebSocket and Socket.IO is that WebSocket is a standardized low-level protocol, while Socket.IO is a library built on top of WebSockets, offering additional features and transport options.

Socket.IO is used when real-time bidirectional communication with fallback mechanisms and cross-platform compatibility is required.

WebSockets are suitable when low-level, efficient full-duplex communication is needed, and there is control over the client and server implementation.
