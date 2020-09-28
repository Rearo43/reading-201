# Message Queues
- What does it mean that web sockets are bidirectional? Why is this useful?
  > Means that it is communicating in two different directions (back and forth), this is useful because data can be shared between instead of one way.
- Does socket.io use HTTP? Why?
  > Yes so that it's own client can still be served.
- What happens when a client emits an event?
  > An object (or anything I guess) is sent to be used by the Emitter.
- What happens when a server emits an event?
  > A listener triggers a handler.
- What happens if a client “misses” an event?
  > Nothing.
- How can we mitigate this?
  > Handlers solve this problem.
### Term
- Web Socket: communication protocol 
- Socket.io: a JS lib for realtime web apps 
- Client: requests be it data, permission, access to a route
- Server: fulfill requests and save data given/ asked by client
#### Preparation Materials
[Socket.io Chat Example](https://socket.io/get-started/chat/)

[Rooms and Namespaces](https://socket.io/docs/rooms-and-namespaces/)

[Socket.io Emit Cheatsheet](https://socket.io/docs/emit-cheatsheet/)
