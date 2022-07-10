# C++ interview-prep
C++ is a powerful and all-purpose programming tool developed by Bjarne Stroustrup at Bell Labs. This language is an extension of C and is by far one of the fastest object-oriented programming languages. C++ is super popular because of its high speed and compatibility.

It is widely used in the development of games and servers while some of the real-world applications of C++ are as follows

Operating systems
GUI based applications
Distributed systems
Database software
Banking applications
Advanced computations and graphics
Embedded systems
So, today, well understand the different C++ questions asked in an interview at a basic, intermediate and advanced level.

C++ Interview Questions For Freshers
1. What are the different data types present in C++?
The 4 data types in C++ are given below:

Primitive Datatype(basic datatype). Example- char, short, int, float, long, double, bool, etc.
Derived datatype. Example- array, pointer, etc.
Enumeration. Example- enum
User-defined data types. Example- structure, class, etc.
2. What is the difference between C and C++?
The main difference between C and C++ are provided in the table below:
![image](https://user-images.githubusercontent.com/59536110/178155817-f514e09c-d714-4553-b83e-0e2886f4c605.png)

3. What are class and object in C++?
A class is a user-defined data type that has data members and member functions. Data members are the data variables and member functions are the functions that are used to perform operations on these variables.

An object is an instance of a class. Since a class is a user-defined data type so an object can also be called a variable of that data type.

A class is defined as-
![image](https://user-images.githubusercontent.com/59536110/178155848-139dbe35-0786-4237-9b2c-8a5e4a7b0e07.png)
![image](https://user-images.githubusercontent.com/59536110/178155885-87197b52-17f7-4190-a42e-f52b202540c8.png)
![image](https://user-images.githubusercontent.com/59536110/178155899-a016aece-e039-443f-9f5f-0ce7641cf550.png)
6. What is polymorphism in C++?
Polymorphism in simple means having many forms. Its behavior is different in different situations. And this occurs when we have multiple classes that are related to each other by inheritance.

For example, think of a base class called a car that has a method called car brand(). Derived classes of cars could be Mercedes, BMW, Audi - And they also have their own implementation of a cars

The two types of polymorphism in c++ are:

Compile Time Polymorphism
Runtime Polymorphism
![image](https://user-images.githubusercontent.com/59536110/178155921-9ec36373-8b0f-48b8-a586-87ba28ff78e7.png)

7. Explain constructor in C++
The constructor is a member function that is executed automatically whenever an object is created. Constructors have the same name as the class of which they are members so that compiler knows that the member function is a constructor. And no return type is used for constructors.

![image](https://user-images.githubusercontent.com/59536110/178155937-a09f66c3-687a-469f-9a01-4031e85fbd5a.png)

8. Tell me about virtual function
Virtual function is a member function in the base class that you redefine in a derived class. A virtual function is declared using the virtual keyword. When the function is made virtual, C++ determines which function is to be invoked at the runtime based on the type of the object pointed by the base class pointer.

9. Compare compile time polymorphism and Runtime polymorphism
The main difference between compile-time and runtime polymorphism is provided below:
![image](https://user-images.githubusercontent.com/59536110/178155970-39970087-d408-4ce1-94eb-3bc57b38e7d7.png)

10. What do you know about friend class and friend function?
A friend class can access private, protected, and public members of other classes in which it is declared as friends.

Like friend class, friend function can also access private, protected, and public members. But, Friend functions are not member functions.

For example -

![image](https://user-images.githubusercontent.com/59536110/178155993-f702c21a-3298-460c-892e-3427f01c9c88.png)

