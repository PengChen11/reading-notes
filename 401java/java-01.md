# Class-01 Readings: Java Basics

[Table of Contents](../README.md)  

## Difference between Java and Javascript

As a javascript developer, I'd like to start with this topic:

Java and JavaScript were developed to serve entirely different purposes. Java was designed as a general purpose programming language for building standalone applications, whereas JavaScript is a scripting language built specifically to interface with web technologies, namely HTML.

1. Compiled vs. Interpreted. Java is considered a compiled programming language. JavaScript is considered an interpreted scripting language. The difference is in the implementation: Java is compiled into bytecode and run on a virtual machine, whereas JavaScript can be interpreted directly by a browser in the syntax it is written (although it is usually minified in practice).
2. Static vs Dynamic Type Checking. Java uses static type checking, where the type of a variable is checked at compile-time. The programmer must specify the type (integer, double, string, etc.) of any variable they create. JavaScript, like most scripting languages, uses dynamic typing, where type safety is verified at runtime. It is not required for a programmer to specify the type of any variable they create. There are many pros and cons for these two paradigms, but the primary advantage of static type checking is that type errors are caught early in development, and because the compiler knows exactly what data types are being used, code typically executes faster or uses less memory. The primary advantage of dynamic type checking is programmer productivity—you are free to assign types at your leisure.
3. Concurrency. The ability to handle the execution of several instruction sequences at the same time is handled very differently between Java and JavaScript. Java makes use of multiple threads to perform tasks in parallel. JavaScript, particularly as it exists as Node.js in server-side applications, handles concurrency on one main thread of execution via a queue system called the event loop, and a forking system called Node Clustering. For most use-cases, both methods work just fine, but Java is generally faster because thread to thread memory sharing much faster than interprocess communication (IPC).
4. Class Based vs Prototype Based. Java follows class based inheritance—a top down, hierarchical, class-based relationship whereby properties are defined in a class and inherited by an instance of that class (one of its members). In JavaScript, inheritance is prototypal—all objects can inherit directly from other objects. Hierarchy is accomplished in JavaScript by assigning an object as a prototype with a constructor function.
