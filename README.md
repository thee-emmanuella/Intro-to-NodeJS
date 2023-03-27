# INTRODUCTION TO NodeJS

## QUESTION 1

### • Define Monolithic architecture

A monolithic architecture is a traditional model of a software program, which is built as a unified unit that is self-contained and independent from other applications. A monolithic architecture is a singular, large computing network with one code base that couples all of the business concerns together.

A monolithic application is built as a single unit. Enterprise applications are built in three parts:

    1. A database — consisting of many tables usually in a relational database management system

    2. A client-side user interface — consisting of HTML pages and/or JavaScript running in a browser

    3. A server-side application — which will handle HTTP requests, execute domain-specific logic, retrieve and update data from the database, and populate the HTML views to be sent to the browser.

This is what makes a monolith architecture monolith — it is a single logical executable. To make any changes to the system, a developer must build and deploy an updated version of the server-side application.

Monoliths can be convenient early on in a project's life for ease of code management, cognitive overhead, and deployment. This allows everything in the monolith to be released at once.

## QUESTION 2

### • Explain microservices in your own understanding

A microservices architecture is a type of application architecture where the application is developed as a collection of services. It provides the framework to develop, deploy, and maintain microservices architecture diagrams and services independently.

Microservices are small, independent, and loosely coupled. A single small team of developers can write and maintain a service. Within a microservices architecture, each microservice is a single service built to accommodate an application feature and handle discrete tasks. Each microservice communicates with other services through simple interfaces by using well-defined APIs to solve business problems. Internal implementation details of each service are hidden from other services.

Each service is a separate codebase, which can be managed by a small development team. Services can be deployed independently. A team can update an existing service without rebuilding and redeploying the entire application.

Microservices also supports polyglot programming. For example, services don't need to share the same technology stack, libraries, or frameworks.

## QUESTION 3

### • Which of the backend architecture appeals to you and why?

The microservices architecture. This is because it allows for separation of concerns and therefore would be easier to manage as the application grows larger. Because microservices are deployed independently, it's easier to manage bug fixes and feature releases. You can update a service without redeploying the entire application, and roll back an update if something goes wrong.

## QUESTION 4

### • Is NodeJS a multithreaded language?

NodeJS runs JavaScript code in a single thread, which means that your code can only do one task at a time. However, NodeJS itself is multithreaded and provides hidden threads through the libuv library, which handles I/O operations like reading files from a disk or network requests. Through the use of hidden threads, NodeJS provides asynchronous methods that allow your code to make I/O requests without blocking the main thread.

## QUESTION 5

### • What does REPL stand for?

Read-Eval-Print Loop.
It is a computer environment where user inputs are read and evaluated, and then the results are returned to the user. REPLs provide an interactive environment to explore tools available in specific environments or programming languages.
