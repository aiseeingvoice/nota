Features of Node.js are:

- Single-threaded
- Non-Blocking, Asynchronous I/O
- Cross-platform
- Fast Execution (V8 Engine)
- Real-Time Data Handling.



While both are used to export modules, module.exports is the actual object that gets exported. exports is just a reference to module.exports.


Get your JS fundamentals down, what are closures, object prototype, event loop, etc.

Then get your web fundamentals down, HTTP (headers, methods, cookie, body, status code), what is DNS, what is a CDN, how to do caching (and cache invalidation), OSI layers (probably don’t need to know too much, but you should be able to explain UDP/TCP vs HTTP).

If you’re doing full stack, SQL, architecture (load balancing, high availability)

These are what I ask when I interviewing a mid to senior role. Good luck!

You gotta know a bit of everything, even tho nodejs is backend, they can plot twist you with a frontend type questions but at a high level:

Core concepts

how does the event loop work in node.js, and how is it different from the browser?

explain the difference between process.nexttick, setimmediate, and settimeout.

what are worker threads, and when would you use them?

how does node.js handle asynchronous operations under the hood?

explain how garbage collection works in node.js.

how do streams work in node.js, and when would you use them?

what is the purpose of the cluster module, and how does it handle scaling?

Performance and optimization

how would you handle a memory leak in a node.js application?

how do you optimize a high-throughput api built with node.js?

what are the trade-offs between child processes, worker threads, and clustering?

how would you monitor and profile a node.js application in production?

what are some ways to prevent blocking the event loop?

Security

how do you prevent prototype pollution in a node.js application?

what security risks does eval() pose in a node.js app?

how do you handle jwt authentication securely in a node.js backend?

how does csrf protection work in an api, and do you need it in a restful service?

what are the best practices for handling sensitive data (e.g., env variables, secrets management)?

Code challenges / hands-on exercises

implement a custom promise class from scratch.

write a function that limits the number of concurrent asynchronous tasks running at a time.

build a simple rate limiter middleware in express.

implement an lru cache using javascript.

create an async queue that processes tasks with a given concurrency limit.

Bonus Tips

Consider free and paid alternatives with a more structured approach to prepping for frontend interviews. Full disclosure, I am the creator of FrontendLead (dot) com, which offers a structured approach to preparing for front-end specific interviews at top tech companies, with company particular questions. (30-day money-back guarantee)

Use other platforms (free and paid) to also help you prepare.

JavaScript doesn’t know classes;
the object model of JavaScript is based on prototypes.

As you probably know, JavaScript doesn’t know classes;
the object model of JavaScript is based on prototypes. In
class-based languages such as Java or PHP, classes
represent the blueprint of objects. These classes can’t
be changed at runtime. Prototypes in JavaScript, on the
other hand, are dynamic, which means that properties
and methods can be added and removed at runtime. As
with all other languages that implement the objectoriented
programming paradigm, objects are
represented by their properties and methods, where
properties represent the state of an object, and methods
are used to interact with the object. In an application, you
usually access the properties of the various objects very
frequently. In addition, methods in JavaScript are also
properties of objects that are stored with a function. In
JavaScript, you work almost exclusively with properties
and methods, so access to them must be very fast.

In classical
languages, the object structure doesn’t change at
application runtime; the properties of objects are always
located in the same place, which significantly speeds up
accessing them.

