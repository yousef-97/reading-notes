# Node JS
### what is Node JS:
Node.js is an event-based, non-blocking, asynchronous I/O runtime that uses Google’s V8 JavaScript engine and libuv library.
### node js is built on Google chrome's V8 java script engine 
**V8 engine:**is the open-source JavaScript engine that runs in Google Chrome and other Chromium-based web browsers,t was designed with performance in mind and is responsible for compiling JavaScript directly to native machine code that your computer can execute.
### Introducing npm
**the JavaScript Package Manager**<br />
- npm install -g (package name)(to install the package globally)
- npm init -y (to initiate the package locally)
### What Is Node.js Used For?
if you want to start developing apps with any modern JavaScript framework (for example, React or Angular), you’ll be expected to have a working knowledge of Node and npm. This isn’t because you need a Node back end to run these frameworks . it’s because these frameworks (and many, many related packages) are all available via npm and rely on Node to create a sensible development environment in which they can run.
### The Node Execution Model
Node.js is single-threaded It’s also event-driven which means that everything that happens in Node is in reaction to an event. For example, when a new request comes in (one kind of event) the server will start processing it. If it then encounters a blocking I/O operation, instead of waiting for this to complete, it will register a callback before continuing to process the next event. When the I/O operation has finished (another kind of event), the server will execute the callback and continue working on the original request. Under the hood, Node uses the libuv library to implement this asynchronous (that is, non-blocking) behavior.
### Pros of using Node.js
- Server-Side Solution
- Single Language
- Flexible
- Complexity. Node.js is not too complex to use
- Using JSON
- Execution Speed
### Cons of using Node.js
- Not efficient in handling CPU-intensive apps.
- Not mature enough.
### What Kind of Apps Is Node.js Suited To
- chat sites
- sites involving data streaming