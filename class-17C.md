# Read 04c: Asynchronous JavaScript, Promises, and fetch


* Callbacks

1. Asynchronous means that things can happen independently of the main program flow.
2. Programs internally use interrupts, a signal that’s emitted to the processor 
   to gain the attention of the system.
3. JavaScript is synchronous by default and is single threaded. 
   This means that code cannot create new threads and run in parallel.
4. A callback is a simple function that’s passed as a value to another function, 
   and will only be executed when the event happens.
5. However every callback adds a level of nesting, and when you have lots of callbacks, 
   the code starts to be complicated very quickly


* Promises

1. Promises are one way to deal with asynchronous code in JavaScript, 
   without writing too many callbacks in your code.
2. A promise can be returned to another promise, creating a chain of promises.
