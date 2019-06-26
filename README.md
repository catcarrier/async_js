## A few remarks on asynchronous operations in JavaScript

- Many operations in JavaScript are asynchronous (file i/o, web service calls...)
- Callbacks are the basic tool for working with asynchronous operations
- Callbacks are just functions you set up to receive the result of some asynch operation; they wait in a special area called the callback queue until the operation completes
- Callbacks have disadvantages related to complexity, loss of control, and error handling

[Callbacks and the callback queue, part 1](http://catcarrier.github.io/async_js/ex1.html)

[Callbacks and the callback queue, part 2](http://catcarrier.github.io/async_js/ex2.html)

[Callbacks and the callback queue, part 3](http://catcarrier.github.io/async_js/ex3.html)

- Promises wrap around callbacks and make them easer to work with
- Promises are syntactically messy

[Promises](ex4.html)

- _async_ and _await_ make promises easier to deal with

[async and await](ex5.html)

[Edit this page](https://github.com/catcarrier/async_js/edit/master/README.md)
