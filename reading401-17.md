# TCP Servers
- Given the examples of front-end events such as button click, window resize, form submit, etc, what are some examples of back-end events?
  > Requests, event handlers.
- Why are events sometimes better than asynchronous actions with callbacks?
  > Because an event enables certain features/ functions to be added to the call stack as necessary.
- What does an EventEmitter instance do?
  > Keeps track of the listeners
- When is a program’s call stack, event queue, and event loop active?
  > As soon as you're running said program.
  
  
### Term
- Observer Pattern: mainly used to implement distributed event handling systems, in "event driven" software (wikipedia)
- Listener: listens for an action and responds
- Event Handler: the responce of a listener so like a function will be run IF needed
- Event Driven Programming: it's like if you were letting the user contol what's happening within boundaries that you have predetermined 
- Event Loop: responsible for executing the code, collecting and processing events, and executing queued sub-tasks (MDN)
- Event Queue: when an event is needed its added to a "list" to then be used
- Call Stack: The "order" that features/functions are being run this order can get a little confusing when you're using awaits
- Emit/Raise/Trigger: triggers events to be executed 
- Subscribe:the ability to get the right responce based on topic
- database: holds data in certain ways depending on the use, able to "ask" for data as well

#### Preparation Materials
  [OSI Model Explained](https://www.youtube.com/watch?v=vv4y_uOneC0)
  
  [TCP Handshakes Explained](https://www.youtube.com/watch?v=xMtP5ZB3wSk)
  
  [OSI Model](https://www.cloudflare.com/learning/ddos/glossary/open-systems-interconnection-model-osi/)
  
  [What is TCP](https://searchnetworking.techtarget.com/definition/TCP)
  
  [Build a TCP Server (code only)](https://techbrij.com/node-js-tcp-server-client-promisify)
  
  [Node docs: net module](https://nodejs.org/api/net.html)
