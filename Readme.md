# Don't Panic - The Hitchhiker's Guide to Node

YP.com is the largest Ruby shop in LA. A few months ago we started migrating a large codebase from Ruby to Node.js.

Full-stack JavaScript application opens up new possibilities but it also adds a challenge of making many in-flight decisions, such as the following: Should we use a web framework? Which one? How to organize our client-side codebase? Should we write in Object Oriented or Functional style?

In this talk we won't spend time on fluff and dive right in to a real codebase.
I'll share code and practices that are applicable immediately to any JavaScript developer.

## Topics covered

* Web frameworks Fight! Express vs Hapi vs http.createServer
* Client side code - CommonJS vs AMD
* Code style - OO vs Functional
* Control Flow - Callbacks vs Promises
* Error handling - Domains?

# Building a framework-free Website

This is a hands-on session and attendees will be able to code with me if they want to.

Everyday someone new to Node is asking 'how to create a website' on the IRC and usually she is being directed to express.js, the most popular web framework in Node.
But as you get closer to the core Noder (Isaacs, Substack, Mikeal etc) you noticed that many of them don't use any framework to build their websites or web service. Where is this gap coming from? This session we'll reveal together the 'secrets' of building a website that follows the Unix philosophy - small modules that works nicely with each other. After this session you'll have the foundations to create your own fast and lean website.

## Topics covered

* Routing
* Templates
* Serving static files
* Handling errors