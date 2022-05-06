# Chain of responsabilitty

It's a behavioral design pattern that lets you pass requests along a chain of handlers. 
Upon receiving a request, each handler decides to process the request or pass it on to the next handler in the chain.

## Applicability

- Use the pattern when it is essential to run multiple handlers in a specific order.

- Use the Chain of Responsibility pattern when your program is expected to process different types of requests in various ways, but the exact types of requests and their sequence are unknown in advance.

- The pattern allows you to link multiple handlers into a chain and, upon receiving a request, ask each handler whether or not it can process it. That way all handlers have a chance to process the request.