# Object Oriented Programming Interview Question
  - To solve real world probem we use OOPS

## Polymorphism 
- it is a combinaton of 2 towd Poly and morphism 
- Poly means :- many  and morphism :- forms = manyforms
- whose meaning is **Same object having different behavior**


## 1) What is oops?
- OOP stands for Object-Oriented Programming.

- Procedural programming is about writing procedures or functions that perform operations on the data, while object-oriented programming is about creating objects that contain both data and functions.

- Object-oriented programming has several advantages over procedural programming:

    - OOP is faster and easier to execute
    - OOP provides a clear structure for the programs
    - OOP helps to keep the JAVA code DRY "Don't Repeat Yourself", and makes the code easier to maintain, modify and debug
    - OOP makes it possible to create full reusable applications with less code and shorter development time
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
- If the member function is defined inside the class definition it can be defined directly, but if its defined outside the class, then we have to use the scope resolution :: operator along with class name alng with function name.

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
