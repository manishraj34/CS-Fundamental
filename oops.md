# Object Oriented Programming Interview Question
  - To solve real world probem we use OOPS



## 1) What is oops?
- OOP stands for Object-Oriented Programming.

- object-oriented programming is about creating objects that contain both data and functions.

- Object-oriented programming has several advantages over procedural programming:

    - OOP provides a clear structure for the programs
    - OOP helps to keep the JAVA code DRY "Don't Repeat Yourself", and makes the code easier to maintain, modify and debug
    - It lowers the overall cost of development.

## 2)How Object Oriented Programming is relates to Real world ?

- Basically why we are write coding ,to solve our real world problem right.
- In OOP a logic is right base on the object with this features
  1. abstraction
  2. encapsulation
  3. inheritance
  4. polymorphism
- There are a lot of Car,bike,ATM and coffee machine.and there brands and name also different.
In OOP those are called object .
- Objects logic are done by classes for example ,by phone we can call,Bluetooth ,take photo etc. those every logic
will be divide as classes.

## 3)Why to study OOP (OR) Why we need OOPs in Programming language?

- OOP helps to keep the JAVA code DRY "Don't Repeat Yourself"
- OOPs provides code reusability which reduce the duplication of code because once you have duplicate code, you have make changes everywhere which leads to performance.
- Code can be changed anytime as per our requirement  in the application, OOPs makes it easier.

## 4)Disadvanteges of OOPs?
- ***Larger program size:*** Object-oriented programs typically involve more lines of code than procedural programs. 
- ***Slower programs:*** Object-oriented programs are typically slower than procedure-based programs, as they typically require more instructions to be executed.
- ***Not suitable for all types of problems:*** The problems like functional-programming style, logic-programming style, or procedure-based
programming style, and applying object-oriented programming in those situations will not result in efficient programs. 

## 5)When we say a language is object-oriented What does it mean?

- If a language is designed with the facilities specifically to support object-oriented programming having 4 features that is abstraction, encapsulation, inheritance,
polymorphism then it is an Object-oriented programming language.
-  It's the code that is object-oriented not the language.

## 6)What is class?

- It is a basic concept of Object-Oriented Programming.
- Class is a blueprint of an object.
- A class is a user defined datatype which define its properties and function.

## 7) Structure vs class

![image](https://user-images.githubusercontent.com/102239780/212487317-07f32a5a-e786-4d35-aa46-e56c5290af58.png)

![image](https://user-images.githubusercontent.com/102239780/212488236-54aa8a5b-a9af-49b5-ab0a-8f45ccbf5ab0.png)

## 8) Similarity between structure and class?

- Both are container types, meaning that they contain other types as members.

- Both have members, which can include constructors, methods, properties, fields, constants, enumerations, events, and event handlers.
- Both can implement interfaces.

## 9)when to use structure over class?
- If the size of the instance is below 16 bytes.
- Structures are preferred for object design for data storage like array.

## 10) What is Access Modifier?
- There are two types of modifiers in Java: access modifiers and non-access modifiers.
- The access modifiers in Java specifies the accessibility or scope of a field, method, constructor, or class.
- We can change the access level of fields, constructors, methods, and class by applying the access modifier on it.
1. Private: The access level of a private modifier is **only within the class**. It cannot be accessed from outside the class.
2. Default: The access level of a default modifier is **only within the package**. It cannot be accessed from outside the package. If you don't use any modifier, it is treated as default by default.
3. Protected: The access level of a protected modifier is **within the package and outside the package through child class**. If you do not make the child class, it cannot be accessed from outside the package.
4. Public: The access level of a public modifier is **everywhere**. It can be accessed from within the class, outside the class, within the package and outside the package.

![image](https://user-images.githubusercontent.com/102239780/213178448-16be1d35-0548-4b13-9a4d-652ac9776799.png)

## 11) Member Functions
- Member functions are the functions, which have their declaration inside the class definition and works on the data members of the class.
- The definition of member functions can be inside or outside the definition of class.
- If the member function is defined inside the class definition it can be defined directly, but if its defined outside the class, then we have to use the scope resolution  operator (::) along with class name alng with function name.

# CONSTRUCTORS

## 12) Constroctors in java
- Constructor is a type of method which is created at the time of object creation.
- Every time an object is created using the new() keyword, at least one constructor is called.
- It calls a default constructor if there is no constructor available in the class. In such case, Java compiler provides a default constructor by default.
- There are two types of constructors in Java: no-arg constructor, and parameterized constructor.
- It is called constructor because it constructs the values at the time of object creation.
- https://www.javatpoint.com/java-constructor

## 13) What is the purpose of a default constructor?
- The default constructor is used to provide the default values to the object like 0, null, etc., depending on the type.
## 14) Why use the parameterized constructor?
- The parameterized constructor is used to provide different values to distinct objects. However, you can provide the same values also.

## 15) Constructor Overloading in Java?
- Same name but different parameter.
- Constructor overloading in Java is a technique of having more than one constructor with different parameter lists. 
- They are arranged in a way that each constructor performs a different task. 
-   They are differentiated by the compiler by the number of parameters in the list and their types.

# How constructors are different from a normal member function?

- A constructor is different from normal functions in following ways:

- Constructor has same name as the class itself

- Constructors don???t have return type

- A constructor is automatically called when an object is created.

- If we do not specify a constructor, C++ compiler generates a default constructor for us (expects no parameters and has an empty body).

<img width="536" alt="image" src="https://user-images.githubusercontent.com/78966839/213197340-cdb9f691-9f9a-4706-9fe5-ae607d5f1bbc.png">

# Java Copy Constructor
- There is no copy constructor in Java. However, we can copy the values from one object to another like copy constructor in C++.

- There are many ways to copy the values of one object into another in Java. They are:

     - By constructor
     - By assigning the values of one object into another
     - By clone() method of Object class


## 16) can we have more than one constructor in a class
- Yes, a class can have multiple constructors. These constructors can have different parameters, allowing for multiple ways to initialize an object of the class. They are often called "overloaded constructors."

## 17) Destroctor
- It is a special method that automatically gets called when an object is no longer used.
- In Java, when we create an object of the class it occupies some space in the memory (heap). If we do not delete these objects, it remains in the memory and occupies unnecessary space. To resolve this problem, we use the destructor.
- The destructor is the opposite of the constructor.
- there is no concept of destructor in Java. In place of the destructor, Java provides the garbage collector that works the same as the destructor.
- The Java Object class provides the finalize() method that works the same as the destructor
- https://www.javatpoint.com/java-destructor

## 18) OBJECT vs CLASS
![image](https://user-images.githubusercontent.com/102239780/213229913-2b984cc0-94da-4d4a-b1fb-720301f902e3.png)


## 19) Real World analog of object and class
- https://www.c-sharpcorner.com/blogs/real-life-examples-of-object-oriented-programming1

# Different Keywords

## 20) Static Keyword
- The static keyword belongs to the class than an instance of the class.
- The static keyword in Java is used for memory management mainly.
- The static can be:
    1) Variable (also known as a class variable)
    2) Method (also known as a class method)
    3) Block
    4) Nested class
- static methods can be called without creating an object of the class.
- A static variable is one that's associated with a class, not instance (object) of that class.
- They are initialized only once , at the start of the execution . 
- https://www.javatpoint.com/static-keyword-in-java

# 21)What are virtual keywords?

- The virtual keyword is used to modify a method, property, indexer, or event declaration and allow for it to be overridden in a derived class.

- The virtual keyword is not used in Java.

# [why virtual keyword is used](https://www.codeproject.com/Questions/270054/why-virtual-keyword-is-used)

- Marking a method as virtual means you can override it in derived classes, but you don't have to.
-  If you mark a method as abstract, you are subsequently forced by the compiler to override it in any derived classes.

## 22) Abstract Keyword
- The abstract keyword is used to achieve abstraction in Java. 
- 'abstract' keyword is used to declare the method or a class as abstract.
- - Abstract classes may or may not contain abstract methods, i.e., methods without a body ( public void get(); )
- But, if a class has at least one abstract method, then the class must be declared abstract.
- *If a class is declared abstract, it cannot be instantiated.*
- To use an abstract class, you have to inherit it from another class, provide implementations for the abstract methods in it.
- If you inherit an abstract class, you have to provide implementations to all the abstract methods in it.

- https://www.javatpoint.com/abstract-keyword-in-java
- https://www.tutorialspoint.com/abstract-keyword-in-Java

## 23) Final keyword
- The final keyword in java is used to restrict the user.
- Final can be:
    - variable
    - method
    - class
- If we declare a variable as final then we can not change the value of it.
- If we declare a method as final then we can not override it.
- If we declare a class as final then we can not inherit it.

- https://www.javatpoint.com/final-keyword

## 24) explicit keyword

- Explicit Keyword in C++ is used to mark constructors to not implicitly convert types in C++. It is optional for constructors that take exactly one argument and work on constructors(with a single argument) since those are the only constructors that can be used in typecasting.

## 25) this keyword
- In Java, this is a reference variable that refers to the current object.
- ![image](https://user-images.githubusercontent.com/102239780/214580873-dd806ee6-a3c4-42c3-b2d5-29cac265464f.png)


- https://www.javatpoint.com/this-keyword

## 26) new keyword
- It is used to create the object.
- It allocates the memory at runtime.
- All objects occupy memory in the heap area.
- https://www.javatpoint.com/new-keyword-in-java

## 27) const keyword
- there is no concept of const keyword in java.
- **why**     Java allows us to declare constants by using final keyword.

## 28) super keyword
- ![image](https://user-images.githubusercontent.com/102239780/214587213-2d51e623-d924-4304-8650-ac65b22ff352.png)

# Polymorphism

## 1) What is Polymorphism 
- it is a combinaton of 2 towd Poly and morphism 
- Poly means :- many  and morphism :- forms = manyforms
- whose meaning is **Same object having different behavior**
- example- let us consider i am an object. In my home, office and friend circle i act as different. Here object is same that is I but behaviour is different. This is a real time example of polymerphysm.

- **NEED** (allows us to reuse code by creating one function that's usable for multiple uses.)
- https://www.javatpoint.com/runtime-polymorphism-in-java


## 2) Overloading
- https://www.javatpoint.com/method-overloading-in-java
- Method overloading is used for compiletime polymorphism
- If a class has multiple methods having same name but different in parameters, it is known as Method Overloading.

## 3) Overriding
- https://www.javatpoint.com/method-overriding-in-java
- If subclass (child class) has the same method as declared in the parent class, it is known as method overriding in Java.
- Method overriding is used to provide the specific implementation of a method which is already provided by its superclass.
- Method overriding is used for runtime polymorphism
## 4) Compile time polymerphism
- Compile-time polymorphism is obtained through method overloading. The term method overloading allows us to have more than one method with the same name. Since this process is executed during compile time, that's why it is known as Compile-Time Polymorphism.
- https://www.dineshonjava.com/compile-time-polymorphism-in-java/

## Runtime polymorphism
Runtime polymorphism, also known as the Dynamic Method Dispatch, is a process that resolves a call to an overridden method at runtime. The process involves the use of the reference variable of a superclass to call for an overridden method

## 5) Operators that cannot be overloaded in C++
- In C++ we can overload some operators like +, -, [], -> etc. But we cannot overload any operators in it. Some of the operators cannot be overloaded. These operators are like below

    - ? ???.??? Member access or dot operator
    - ? ???? : ??? Ternary or conditional operator
    - ? ???::??? Scope resolution operator
    - ? ???.*??? Pointer to member operator
    - ? ???sizeof??? The object size operator
    - ? ???typeid??? Object type operator
- These operators cannot be overloaded because if we overload them it will make serious programming issues.

- For an example the sizeof operator returns the size of the object or datatype as an operand. This is evaluated by the compiler. It cannot be evaluated during runtime. So we cannot overload it.


## 6)Functions that cannot be overloaded in C++
1) Function declarations that differ only in the return type.
2) Member function declarations with the same name and the name parameter-type-list cannot be overloaded if any of them is a static member function declaration.
3) Parameter declarations that differ only in a pointer * versus an array [] are equivalent.
4) Parameter declarations that differ only in that one is a function type and the other is a pointer to the same function type are equivalent. 
5) Parameter declarations that differ only in the presence or absence of const and/or volatile are equivalent. That is, the const and volatile type-specifiers for each parameter type are ignored when determining which function is being declared, defined, or called. 

## 7) virtual function
- A C++ virtual function is a member function in the base class that you redefine in a derived class. It is declared using the virtual keyword.
- It is used to tell the compiler to perform dynamic linkage or late binding on the function.
- There is a necessity to use the single pointer to refer to all the objects of the different classes. So, we create the pointer to the base class that refers to all the derived objects. But, when base class pointer contains the address of the derived class object, always executes the base class function. This issue can only be resolved by using the 'virtual' function.
- A 'virtual' is a keyword preceding the normal declaration of a function.
- When the function is made virtual, C++ determines which function is to be invoked at the runtime based on the type of the object pointed by the base class pointer.

## 8) Virtual base class

- Virtual base classes are used in virtual inheritance in a way of preventing multiple ???instances??? of a given class appearing in an inheritance hierarchy when using multiple inheritances. 
- Need for Virtual Base Classes: Consider the situation where we have one class A . This class A is inherited by two other classes B and C. Both these class are inherited into another in a new class D as shown in figure below. 

## 9) What Does Derived Class Mean?
- A derived class is a class created or derived from another existing class. The existing class from which the derived class is created through the process of inheritance is known as a base class or superclass.

- Derived classes are used for augmenting the functionality of base class by adding or modifying the properties and methods to suit the requirements of the specialization necessary for derived class. This allows for defining virtual methods that form the means to implement polymorphism, which allows a group of objects to work in uniform manner. Thus, the inherent advantages of inheritance and polymorphism like code reuse, faster development, easy maintenance, etc., are realized.

- A derived class is also known as subclass or child class.
## 10) Can Virtual Functions be Private in C++?
- A virtual function can be private as C++ has access control, but not visibility control. As mentioned virtual functions can be overridden by the derived class but under all circumstances will only be called within the base class.

## 11)inline virtual functions

- https://stackoverflow.com/questions/733737/are-inline-virtual-functions-really-a-non-sense

## 12)Abstraction
- A class which is declared with the abstract keyword is known as an abstract class in Java. It can have abstract and non-abstract methods.
- Abstraction in Java
- Abstraction is a process of hiding the implementation details and showing only functionality to the user.
- Another way, it shows only essential things to the user and hides the internal details, for example, sending SMS where you type the text and send the message. You don't know the internal processing about the message delivery.

## 13)Pure Virtual Functions
- A pure virtual function (or abstract function) in C++ is a virtual function for which we can have implementation, But we must override that function in the derived class, otherwise the derived class will also become abstract class.
- https://www.geeksforgeeks.org/pure-virtual-functions-and-abstract-classes/

## 14)pure virtual destructor
- https://stackoverflow.com/questions/1219607/why-do-we-need-a-pure-virtual-destructor-in-c


## Why/ need of inheritance?
- For Method Overriding (so runtime polymorphism can be achieved).
- For Code Reusability.
- Inheritance is used to declare characteristics of classes inheriting it,without giving its implementation.
- It is one of the most important concept of OOPS.

## can oop exist without inheritance?(NOT DONE)


# [Inheritence](https://www.javatpoint.com/inheritance-in-java)

- Inheritance in Java is a mechanism in which *one object acquires all the properties and behaviors of a parent object.*

- The idea behind inheritance in Java is that you can create *new classes that are built upon existing classes.*

- Inheritance represents the *IS-A relationship* which is also known as a *parent-child relationship.*

   - subclass (child) - the class that inherits from another class
   - superclass (parent) - the class being inherited from


## Sub Class/Child Class:
- Subclass is a class which inherits the other class. 
- It is also called a derived class, extended class, or child class.


## Super Class/Parent Class:
- Superclass is the class from where a subclass inherits the features. It is also called a base class or a parent class.

## Reusability:
- As the name specifies, reusability is a mechanism which facilitates you to reuse the fields and methods of the existing class when you create a new class. You can use the same fields and methods already defined in the previous class.
...

# [Type of Inheritence](https://www.javatpoint.com/inheritance-in-java)

## Single Inheritance

- When a class inherits another class, it is known as a single inheritance.

## Multilevel Inheritance

- *includes the involvement of at least two or more than two classes*

- When there is a chain of inheritance, it is known as multilevel inheritance. 

## Hierarchical Inheritance

- When *two or more classes inherits a single class,* it is known as hierarchical inheritance

- Single Base class multiple Derive class.

## Hybrid Inheritance

- *hybrid inheritance is the composition of two or more types of inheritance.*

## Multiple inheritence

- In this type of inheritance a single sub class may inherit from two or more than two super classes.

- *java dose not have Multiple inheritence.it have Interfaces.*

## The Real world example of multiple inheritance
- Imagine a Classes called as ???MARUTI??? and ???SUZUKI??? 
- when both collab made a Child Car called as ???Ertiga??? .So Ertiga have characterstic of Maruti as well as Suzuki .
- Child Class (Ertiga) acquared Properties of 2 Parent Classes / Or can say Inherit Properties from Multiple Parents so Its a Multiple Inheritance 

## Limitation of inheritance?
- The inheritance relationship is a, tightly coupled relationship , there will be tight bonding between parent and child. If we change code of parent class it will get affects to the all the child classes which is inheriting the parent code.

## What is sealed modifier?
- sealed is a keyword which is used to seal a class or function and prevent it to get inherited from any other classes.
- In other words, a sealed class cannot be inherited. similarly function can't be used by the other class.

## [How can we call a base/PARENT method without creating instance](https://stackoverflow.com/questions/10173827/how-to-invoke-parent-class-method-without-creating-object-of-it)

## [DIFFERENCE BETWEEN NEW AND OVERRIDE](https://stackoverflow.com/questions/6576206/what-is-the-difference-between-the-override-and-new-keywords-in-c)
- The difference between override and new is that override extend the method of base class with new definition but new hides the method of base class.

## Why multiple inheritance is not supported in java?

- To reduce the complexity and simplify the language, multiple inheritance is not supported in java
- But we can achive multiple inheritance by useing Interfaces.
- <img width="563" alt="image" src="https://user-images.githubusercontent.com/78966839/214851829-60f36a54-5de2-44cc-b1a3-bf189acbe561.png">

## [What all is inherited from parent class](https://www.geeksforgeeks.org/g-fact-4/)

Following are the things that a derived class inherits from its parent. 
1) Every data member that is defined in the parent class  such members may not always be accessible in the child class.
2) Every ordinary member function of the parent class such members may not always be accessible in the derived class.
3) The same initial data layout as of the base class. 

Following are the properties which a derived class doesn???t inherit from its parent class : 
1) The base class???s constructors and destructor. 
2) The base class???s friend functions.
3) Overloaded operators of the base class.

## Inline function
- C++ provides an inline functions to reduce the function call overhead.
- Inline function is a function that is expanded in line when it is called. 
- 
## friend class
- A friend class can access private and protected members of other classes in which it is declared as a friend. 

## Friend Function
- Like a friend class, a friend function can be granted special access to private and protected members of a class in C++.
- 
## Nested class 
- Writing a class within another is allowed in Java. 
- The class written within is called the nested class

## Local class
- Local classes are classes that are defined in a block, which is a group of zero or more statements between balanced braces. 

## Does overloading work with Inheritance?
- Overloading doesn???t work for derived class in the C++ programming language. There is no overload resolution between Base and Derived. 

## [Difference between Inheritance and Polymorphism](https://www.geeksforgeeks.org/difference-between-inheritance-and-polymorphism/)

<img width="491" alt="image" src="https://user-images.githubusercontent.com/78966839/214883002-9592ce84-376b-44f7-8680-b821ff0d9bd5.png">

## [Aggregation, Composition, Generalization](https://javapapers.com/oops/association-aggregation-composition-abstraction-generalization-realization-dependency/)

## [Encapsulation in Java](https://www.javatpoint.com/encapsulation)

- Encapsulation in Java is a process of wrapping code and data together into a single unit.

- for example, a capsule which is mixed of several medicines.

- The Java Bean class is the example of a fully encapsulated class.

## Need  

- In Java, encapsulation helps us to *keep related fields and methods together, which makes our code cleaner and easy to read.*

- The encapsulate class is *easy to test.* So, it is better for unit testing.

## Advantage

- It is a way to achieve *data hiding* in Java because other class will not be able to access the data through the private data members.

- The class will maintain its data members and methods as read-only.

- Data hiding prevents the user from the complex implementations in the code.


- The variables of the class can be read-only or write-only as per the programmer's requirement.

## Encapsulation in Java can be achieved by:
- Encapsulation is achieved in java language by class concept.
- Declaring the variables of a class as private.

## [Encapsulation code/implimentation example](https://beginnersbook.com/2013/05/encapsulation-in-java/)


## [Real world example of encapsulation](https://www.sitesbay.com/java/java-encapsulation)

## Abstraction

- hiding the Internal details and shows only the required one to user

- We cannot create an instance of Abstract Class.

- It reduces the duplication of code.

## [how to achieve abstration using abstract class and interface](https://www.javatpoint.com/how-to-achieve-abstraction-in-java)

## Abstration vs Encapsulation
- ![image](https://user-images.githubusercontent.com/102239780/214894598-52d3ea1e-095e-4539-8b06-5aa92400f794.png)

## difference between Abstract class and interface

- ![image](https://user-images.githubusercontent.com/102239780/214895627-ffdda30a-4bcd-4981-812b-57ec8c8e6678.png)

## Static Binding and Dynamic Binding
- ![image](https://user-images.githubusercontent.com/102239780/214897130-f02a9d26-4a34-41fa-b87a-0d328fb8ef4d.png)

## Message Passing
- Object-oriented programming as a programming paradigm is based on objects. Objects are a representation of real-world and objects communicate with each other via messages.

- When two or more objects communicate with each other that means that those objects are sending and receiving messages. This is often called method calling.

- Sending object (Object A) knows which method of receiving object (Object B) is being called, so it knows more details than needed. With this, we create code which is not loosely coupled. Changes in one object will lead to changes in others too.


# MISC

# [c vs c++ vs java](https://www.javatpoint.com/c-vs-cpp-vs-java)

<img width="577" alt="image" src="https://user-images.githubusercontent.com/78966839/221225660-f15f129a-f24a-4d43-b4fa-103f6b0e797d.png">


# [Differences between Procedural and Object Oriented Programming](https://www.geeksforgeeks.org/differences-between-procedural-and-object-oriented-programming/)


- *Procedural programming* is a programming  that focuses on defining a series of procedures  to be *executed in a specific order*. to solve a problem.

- *Object-oriented programming (OOP)* is about crating objects that contain both data and function.

<img width="485" alt="image" src="https://user-images.githubusercontent.com/78966839/221229332-1e657390-35af-40d2-a1fc-36637f1cac9c.png">


# Why Java is not a purely Object-Oriented Language?

- Pure Object Oriented Language  are Fully Object Oriented Language which supports or have features *which treats everything inside program as objects.*

- However, it is not a purely object-oriented language because it also *includes primitive types, such as int, double, and boolean, which are not objects.*


# [Is an array a primitive type or an object in Java?](https://www.geeksforgeeks.org/array-primitive-type-object-java/)

- *An array in Java is an object*

- *How* :- In Java, we can create arrays by using new operator and we know that every object is created using new operator. Hence we can say that array is also an object.


# what is early and late binding ?

- *early* (or static) binding refers to *compile time binding* and *late* (or dynamic) binding refers to *runtime binding* (for example when you use reflection).

# What is the default access modifier of a class?

- In Java, if no access modifier is specified for a class, it has a default access modifier, which means it can be accessed *only within the same package*.

# [Can we create instance to abstract class?](https://www.quora.com/Can-we-create-instance-to-abstract-class)

- abstract class *cannot be instantiated directly. This means that you **cannot create an object of an abstract class.*

- Because it's abstract and an object is concrete.

- Instead, you must create a concrete subclass that extends the abstract class and provides implementations for any abstract methods defined in the abstract class.

- Once you have created a concrete subclass that extends the abstract class, you can create as many instances of that subclass as you need

# [What is Java Garbage Collection? How It Works](https://stackify.com/what-is-java-garbage-collection/)

- Garbage collection is the process by which a programming language runtime environment automatically *frees up memory that is no longer being used by a program.*

- In Java, when we create an object of the class it occupies some space in the memory (heap). If we do not delete these objects, it remains in the memory and occupies unnecessary space. To resolve this problem, we use the destructor.

- When an object completes its life-cycle the garbage collector deletes that object and deallocates or releases the memory occupied by the object.

# [Defin Manipulators](https://www.geeksforgeeks.org/manipulators-in-c-with-examples/)

- Manipulators are helping functions that can modify the input/output stream.

-  It does not mean that we change the value of a variable, it only modifies the I/O stream using insertion (<<) and extraction (>>) operators. 

- Manipulators are operators that are used to format the data display.

# [What is the final keyword in Java?](https://www.javatpoint.com/final-keyword)

- The "final" keyword in Java is used to indicate that a variable, method, or class cannot be modified.

- If we declare a variable as final then we can not change it value.

- If we declare a method as final then we can not override it.

- If we declare a class as final then we can not inherit it.

# [What Is an Exception?](http://www.iitk.ac.in/esc101/05Aug/tutorial/essential/exceptions/definition.html)

- An exception is an event that occurs during the execution of a program that *disrupts the normal flow* of instructions during the execution of a program.

- When an exception occurs, the program's normal execution is interrupted and the control is transferred to an exception handler that can handle the exception.


#  Exception handling 

- Exception handling is a mechanism in Java that allows you to handle errors or exceptional situations that may occur during the execution of a program.
-  In Java, an exception is an event that occurs during the execution of a program that disrupts the normal flow of the program's instructions.

Exception handling in Java involves three main components:

- *Try:* A try block contains the code that may throw an exception. You enclose the code that may throw an exception in a try block.

- *Catch:* A catch block contains the code that handles the exception. If an exception occurs in the try block, the catch block is executed to handle the exception. 

- *Finally:* A finally block contains code that is always executed.


# is an error is basiccaly same as an exception

- No, an error is not basically the same as an exception.

- while both errors and exceptions are types of abnormal events.
-  An error is a *serious system-level problem* that is usually fatal.
-  while an exception is a type of error that occurs within the program's code and can be caught and handled within the program's code.

- if error occer program will stop.if exception accer program will run but it may not give the expected O/P.






# [Java Object finalize() Method](https://www.javatpoint.com/java-object-finalize-method)
- Finalize() is the method of Object class. This method is called just before an object is garbage collected. finalize() method overrides to dispose system resources, perform clean-up activities and minimize memory leaks.

# [What is a token?](https://www.geeksforgeeks.org/cc-tokens/)
- A token is the smallest element of a program that is meaningful to the compiler.

# [3 arguments of ternary operator](https://www.freecodecamp.org/news/c-ternary-operator/)

- The ternary operator take three arguments:
    - The first is a comparison argument
    - The second is the result upon a true comparison
    - The third is the result upon a false comparison

# [concept of enum](https://www.geeksforgeeks.org/enumeration-enum-c/)
- Enumeration (or enum) is a user defined data type in C. It is mainly used to assign names to integral constants, the names make a program easy to read and maintain.

# [Singleton design pattern in Java](https://www.javatpoint.com/singleton-design-pattern-in-java)

- Singleton Pattern says that just"define a class that has only one instance and provides a global point of access to it".
- In other words, a class must ensure that only single instance should be created and single object can be used by all other classes.

- There are two forms of singleton design pattern

    - Early Instantiation: creation of instance at load time.
    - Lazy Instantiation: creation of instance when required.



# [When should I use a struct instead of a class?](https://stackoverflow.com/questions/85553/when-should-i-use-a-struct-instead-of-a-class)

- MSDN says that you should use structs when you need *lightweight objects*. Are there any other scenarios when a struct is preferable over a class?

- Some people might have forgotten that:

    - structs can have methods.
    - structs cannot be inherited.

# Difference Between Cohesion and Coupling
![image](https://user-images.githubusercontent.com/102239780/221342254-8112cdd5-d611-4651-9085-8190b052e67b.png)

# is it possible for a class to inherit the constructor of its base class
- Yes, it is possible for a class to inherit the constructor of its base class. In object-oriented programming, when a subclass is derived from a base class, it automatically inherits all the members of the base class, including constructors.


