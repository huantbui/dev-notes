COMPUTER SCIENCE OF NODE:

https://medium.com/platformer-blog/node-js-concurrency-with-async-await-and-promises-b4c4ae8f4510

Concurrency vs Parallelism
— Concurrency in very simple terms means that two or more processes (or threads) run together, but not at the same time. Only one process executes at once.
— Parallelism on the other hand means that the processes (or threads) run in parallel (surprise surprise); meaning they start at the same time and execute alongside each other at the same time.

￼

Because Node.js is a single-threaded event loop and async; therefore, it needs to use a callback function to do a task AFTER the async task is completed.

In order to create synchronicity, Promise is used to put structure and predictability.
