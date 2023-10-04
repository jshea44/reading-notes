# Message Queues

## Socket.io Chat Example

> 1. This example is showing instantanious messaging between parties.
> 2. Proof of life is being shown by the backend while it connects to all parties using 'broadcast.'
> 3. The flag that you would use is socket.broadcast.emit().

## Rooms

> 1. "A room is an arbitrary channel that sockets can join and leave. It can be used to broadcast events to a subset of clients."
> 2. You use socket.join() to join a room, passing in the room name.
> 3. You can use socket.leave() to leave a room, passing in the same room name you are trying to leave.

## Namespaces

> 1. "A namespace is a communication channel that allows you to split the logic of your application over a single shared connection."
> 2. Each namespace has its own event handlers, rooms, and middlewares.
> 3. A possible usecase for seperate namespaces is it can "allow you to create isolated communication channels within a single server, enabling different parts of an application to exchange data independently over WebSocket connections."

## Things I want to know more about

## Resources

- ChatGPT
- [Link](https://socket.io/docs/v4/rooms)
- [Link2](https://socket.io/docs/v4/namespaces/)
