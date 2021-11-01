## Introduction to Objects
>All programming languages provide abstraction.  
What really matters is the kind and quality of abstraction. Kind implies "What is it that is being abstracted".<br/>
The Object-oriented approach allows the programmer to model the solution based on the problem space. The elemets of the problem state are known as "Objects" in the solution space.<br/>
As the book puts it: 
> The idea is that the program is allowed to adapt itself to the lingo of the problem by adding new types of objects, so when you read the code describing the solution, you're reading words that also express the problem.<br/>
Features of Object-oriented programming 
1. Everything is an object 
2. A program is a bunch of objects telling each other what to do by sending messages
3. Each object has its own memory made up of other objects
4. Every object has a type
5. All object of a particular type can receive the same messages

### An object has an interface 
A class describes a set of objects that have identical characteristics and behaviours, a class is really a data type because a floating point number, for example, also has a set of characteristics and behaviours. 
To do useful things with objects you need to access the objects properties and functions. The interface establishes what requests you cann make for a particular object. 

### Hidden Implementation 
General Principal: While creating classes the programmer should expose only what is necessary to the consumer. 
C++ uses three explicit keywords to set boundaries in a class. 
1. **Public:** Access is available to everyone
2. **Private:** Access is available only to the creator. Accessing a private member will lead to a compile-time error.
3. **Protected:** Acts like private, but, an inheriting class has access to protected members, but not private members.
These are known as *access specifiers* <br/>
