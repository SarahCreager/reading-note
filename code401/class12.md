# Socket.io

## Review, Research, and Discussion

**What is the benefit of transforming data into packets?**

It splits the data into smaller pieces while it is being sent. 

**UDP is often refereed to as a connectionless protocol. Why is this?**

"There is no handshaking required before sending a message; hence, UDP is referred to as a connection-less protocol."

**Can a socket server application have multiple socket connections?**

Yes a socket server can handle multiple clients simultaneously. 

**Can a socket connection application be connected to multiple socket servers?**

Yes a socket can connect to multiple servers. 

**Can an application be both a socket server and a socket connection?**

I don't believe so and I'm not sure why you would want to do that. 

## Vocabulary Terms

| Term      | Definition |
| ----------- | ----------- |
| Observer Pattern     | "the subject, maintains a list of its dependents, called observers, and notifies them automatically of any state changes" |
| Listener   | Listens for the event    |
| Event Handler      | callback function called when an event is triggered |
| Event Driven Programming     | "the flow of the program is determined by events"  |
| Event Loop   | allows JS to run asynchronous programming despite being on a single thread  |
| Event Queue      | "sends new functions to the track for processing" |
| Call Stack     | "keeps track of all the operations in line to be executed"  |
| Emit/Raise/Trigger   | triggers or begins an event after some action takes place    |
| Subscribe      | the process of signing up to receive something regularly |
| database     | collection of data in an organized manner |

## Preview

**Which 3 things had you heard about previously and now have better clarity on?**

1). Socket.io

2). Applying more advanced implementation for event driven programming

3). Error Events

**Which 3 things are you hoping to learn more about in the upcoming lecture/demo?**

1). WebSocket Protocol

2). TCP Handshakes

3). PSI Model

**What are you most excited about trying to implement or see how it works?**

Implementing Socket.io.  

### Sources

[Event-Driven Programming in Node.js](https://www.digitalocean.com/community/tutorials/nodejs-event-driven-programming)

[Observer pattern](https://en.wikipedia.org/wiki/Observer_pattern)

[Event-driven programming](https://en.wikipedia.org/wiki/Event-driven_programming)

[What is an event loop in JavaScript?](https://www.educative.io/edpresso/what-is-an-event-loop-in-javascript)

[UDP](https://www.educative.io/edpresso/what-is-udp)

[Back to Homepage](../README.md)