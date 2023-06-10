# An introduction to NodeJS and Express

### 1- Explain middleware, answer as though I were a non-technical recruiter.
Middleware is a concept used in software development, particularly in web applications. It acts as a bridge between the incoming requests from users and the server that processes those requests. It's like a helpful intermediary that performs various tasks to enhance the functionality and security of the application.

### 2- Express the most popular web framework for Node.js.
### 3- Express is “unopinionated.” What does that mean?
When we say Express is "unopinionated," it means that the framework does not enforce any strict rules or conventions on how you should structure or organize your code. It provides a minimalistic and flexible foundation, allowing developers to make their own choices and customize their applications according to their specific needs and preferences.

### 3- What is a module and why is modularity useful to us as developers?
a module is a self-contained unit of code that performs a specific function or provides a particular feature
Modular programming usually makes your code easier to read because it means separating it into functions that each only deal with one aspect of the overall functionality

# What is NPM?
### 1- What version of npm are you running on your machine?
9.5.0
### 2- What command would you type to install a library/package called ‘jshint’ into your node project?
npm install jshint

# What is TDD?
### 1- Explain why tests are important. Please explain as though I were your non technical elder.
Tests are important because they help ensure that software works correctly.They help catch potential issues and prevent problems from reaching end users. By running tests, we can identify and fix errors early on, reducing the chances of encountering unexpected behavior or crashes.
### 2- What are three expected benefits of testing
- Increased software reliability
- Faster development process
- Improved code quality
### 3- Name at lest 2 individual pitfalls and at least 2 team pitfalls commonly encountered while writing tests.
- If tests are not run regularly, it becomes difficult to catch issues early
- developers might write tests that are too simple and do not cover enough scenarios
- When only a few team members embrace testing while others do not, it can lead to inconsistency in test coverage and quality
- If the test suite is not properly maintained, it can become bloated, slow, and difficult to manage

# CI/CD
### 1- What are three benefits of Continuous Integration?
- any conflicts or integration issues can be detected early
- With CI, developers receive immediate feedback on the impact of their changes, allowing them to iterate and improve the code quickly
-  CI ensures that the software remains stable and reliable

### 2- What is the difference between Continuos Delivery and Continuous Deployment?
Continuous Delivery ensures that software is always ready for release, but the actual release to production is a manual decision. Continuous Deployment automates the release process, automatically deploying changes to production once they pass all tests, without requiring manual intervention.

### 3- Explain how GitHub fits into this process assuming the listener comes from a non-technical background
GitHub serves as a collaboration platform and version control system that integrates with CI/CD tools. It helps developers work together, maintain code history, and automate the building, testing, and deployment of software. It simplifies the development process and ensures that the code is continuously tested and ready for release


