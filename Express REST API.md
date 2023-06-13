# Express REST API

## ES6 Classes

1- Classes are a template for creating objects.

2- No, a class declaration cannot be hoisted. Unlike function declarations, which are hoisted to the top of their scope.

3- A constructor is like a blueprint or a set of instructions that helps create an object, while the "this" keyword is like a reference to the object itself. It allows the object to know and work with its own data and behavior.

## Using Express Routing

1- Routing refers to the process of determining how an application responds to client requests at specific URLs (route paths) and with specific HTTP methods.

2-The route path defines the URL pattern or structure that a request must match, while the route method determines the type of operation or action to be performed on that specific route. Together, the combination of a route path and a route method defines the unique endpoint or URL of an application's API and specifies how it should handle client requests.

3- In Express, the next parameter is used to pass control from one middleware function to the next in the middleware chain. Adding next as a parameter to a route handler indicates that the current middleware has completed its task and Express should move on to the next middleware or route handler. If next has been passed to your middleware, make sure to call next() within your middleware to pass control to the next function in the chain. Not calling next() will prevent subsequent middleware or route handlers from being executed.

## Express Routing

1- an Express Router provides a way to structure your routes in a more organized and maintainable manner, promoting code reusability and separation of concerns.

2- use the express.Router() method. This method returns an instance of a router that you can then use to define routes and middleware specific to that router.

3- By using route middleware, you can modularize your application's logic, keep your route handlers focused on their main functionality, and reuse common functionality across multiple routes. It enhances the flexibility, maintainability, and extensibility of your Express application.

