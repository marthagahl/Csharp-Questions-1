## Csharp Questions 1

[Navigate to README.md](README.md)

1. **Q:** What is a namespace?  
**A:** A namespace is way to organize code by having certain pieces under certain 'headings'. They make code easier to read by defining what different pieces are used for. ["Namespaces are used in C# to organize and provide a level of separation of codes. "](https://www.programiz.com/csharp-programming/namespaces#what-is-namespace)
2. **Q:** What are value types?   
**A:** Value types are variables that are assigned a value. An example of a value type is int. When you assign a value to int, that variable holds the actual value of the variable.
3. **Q:** What are reference types?   
**A:** Reference types are variables that, unlike variable types, do not contain the actual value of the variable. Instead they hold a reference for where the value is held in memory.
4. **Q:** What is an automatic property and how is it useful?   
**A:** Automatic properties allow you to very simply and efficiently make public properties within private objects. We have seen this used in this class when using "get" and "set" and we set a property in a class and then get that property.
5. **Q:** What is the purpose of **using** statement?   
**A:** A **using** statement is used when a code needs to access outside resources. These are called IDisposable objects. The benefit of using a **using** statement is that at the end of the statement, the object is automatically disposed even if an exception occurs. This means it does not have to be done manually, which would require **try** and **finally** statements.
6. **Q:** What are dynamic type variables?    
**A:** Dynamic type variables are variables that can hold any type of value. It is like having a variable for which you do not have to declare a type. ["Type checking for these types of variables takes place at run-time."](https://www.tutorialspoint.com/csharp/csharp_data_types.htm)
7. **Q:** What is the purpose of the **is** operator?  
 **A:** The **is** operator allows two variables or expressions to be compared. It can determine if they can be converted to the same type and then evaluates if the statement is true or false. ["It determines whether an object instance or the result of an expression can be converted to a specified type."](https://docs.microsoft.com/en-us/dotnet/csharp/language-reference/keywords/is)
8. **Q:** What are generics and how is using them useful?   
**A:** Generics allow classes to be defined without specifying a type. The type is a parameter that is determined when the class is instantiated. They are useful because algorithms can be reused because they are not specific to one type.
9. **Q:** What is the scope of a public member of a class?   
**A:** A public member of a class can be accessed by any code within the assembly or assemblies that reference it.
10. **Q:** Can you create a function that can accept a varying number of arguments?   
**A:** You can using the 'params' keyword. Params is like an array and can take a variable number of arguments. Those arguments are all passed to the function.
11. **Q:** How do you sort an array?   
**A:** You can sort an array using Array.Sort() and then including the array to be sorted within the parentheses. This can sort arrays of different types and allows for different ways of sorting.
12. **Q:** What is a nullable type and what purpose does it serve?   
**A:** Nullables allow you to assign either a value or a null to the variable.
13. **Q:** What is an enumeration?   
**A:** Enumeration is used to define a set of constants within a variable that will not change. For example, you can set an array of strings that contains the days of the week. These are constants that will not change and can be pre-defined.
14. **Q:** What is inheritance?   
**A:** Inheritance occurs when there are base classes and derived classes. When a class has a base class, it will inherit any members from that base class. A derived class can have additional members that were not in the base class, but it will have all members included in the base class. These inherited members can be overridden.
15. **Q:** Is multiple inheritance supported?   
**A:** Multiple inheritance is not supported in C#.
16. **Q:** What is the purpose of as operator   
**A:** Operators are used to preform functions, like mathematical operations, within the program. They can have basic mathematical functions, like addition or subtraction, or they can preform things like incrementation or condition checking.
17. **Q:** What is an object?  
**A:** An object is an instance of a class. A class can be the basis for many objects. In that way, all objects of the same class have the same members. If a class was 'animal', objects would be instantiations of 'animal', like 'dog' or 'cat'. There are properties that both dogs and cats share, and these shared members could be defined in a class.
18. **Q:** What is the difference between a struct and a class?   
**A:** Classes are reference types, can inherit from another class, and can have null values. Structs are value types, cannot inherit from another struct, and cannot have null values.
19. **Q:** What is the difference between **continue** and **break** statements?   
**A:** Both **break** and **continue** are used in loops. A **break** statement will cause execution to leave the loop whereas a **continue** statement allows execution to continue within the loop but skips to the next iteration of the loop.
20. **Q:** What is **this** and how is it used?   
**A:** **This** is used when using a member in a class. If there are multiple instances of a class, and each class has a variable 'name', the program can't distinguish one from another. When within an instance of a class, using this.name specifies that it is its own variable and that only the 'name' variable within this instance is being referenced.
21. **Q:** What is **try** and **catch** and when are they used?   
**A:** **Try** and **catch** are blocks that catch and throw exceptions, stopping execution so that errors don't occur later in the code and often giving feedback to the user about why execution was stopped. When a block of code has a potential to throw an exception, like if the code may attempt to access something out of its range, it can be placed in a **try/catch** block. This will prevent code from improperly executing and protect anything the program is trying to access.
22. **Q:** How is exception handling done?   
**A:** Exception handling is done using a **catch** block. This block catches an exception that occurs in the block of code within a **try** block, and handles it. This can be by prompting the user for different inputs, writing out a message to inform a user of exceptions, or stopping execution of the program. There are exceptions defined in C#, like the 'IndexOutOfRangeException', but exceptions can also be defined by the user.
23. **Q:** What is **finally** and what is its purpose?   
**A:** **Finally** is often used after **try** and **catch**. The **finally** block will execute no matter if an exception is thrown or not. This is useful because it can be sure to close or dispose of anything it was attempting to access. ["The main purpose of finally block is to release the system resources."](https://www.geeksforgeeks.org/c-sharp-finally-keyword/)
24. **Q:** List the differences between Array and ArrayList.   
**A:** Arrays are less dynamic. They can't change sizes and require that all items in the array be the same type. ArrayLists can have items in the ArrayList of different types and it is more dynamic in that it can change sizes.
25. **Q:** What is an object?   
**A:** An object is an instance of a class. A class can be the basis for many objects. In that way, all objects of the same class have the same members. If a class was 'animal', objects would be instantiations of 'animal', like 'dog' or 'cat'. There are properties that both dogs and cats share, and these shared members could be defined in a class.
26. **Q:** Define **constructor**.   
**A:** A constructor is used when creating classes and structs. They help define constants or default values for the class or the struct.
27. **Q:** When can **var** be used to declare a variable and how is the type for the variable determined?   
**A:** **Var** is a type that can be declared for a variable within a method. ["An implicitly typed local variable is strongly typed just as if you had declared the type yourself, but the compiler determines the type."](https://docs.microsoft.com/en-us/dotnet/csharp/language-reference/keywords/var) Var can be used as a local variable and cannot have a null value. The type is determined by the complier.
28. **Q:** What is an abstract class?   
**A:** Abstract classes define base classes. They have abstract methods in them that are inherited by all classes that use them as a base class. They can have implementation in them. In addition, a class can only inherit from one abstract class.
29. **Q:** What is an interface?   
**A:** An interface is used to define a set of methods or properties that will be in all subclasses, but it cannot have implementation within it. A class can inherit from more than one interface.
30. **Q:** What is a method?   
**A:** A method is a member of a class. It is a block of code that contains implementation. It will execute code and perform different actions when it is called.
31. **Q:** What is a property?   
**A:** A property is a member of a class that holds values. These can be accessed, often using methods.
32. **Q:** What is an access specifier?   
**A:** An access specifier is a keyword that determines how the member can be accessed, by what code it can be accessed, and if it can be overridden.
33. **Q:** What access specifiers are supported and what do they mean?   
**A:** Public: can be accessed by any other code within the assembly or assemblies that reference it. Private: can only be accessed by code within the class or struct. Protected: can only be accessed by code within the class or a derived class. Internal: can be accessed by any other code within the assembly. Protected internal: can be accessed by code within the same assembly, or a derived class of the class it is in that is in a different assembly. Private protected: can only be accessed by code that is in both in the same assembly, and in the same class or a derived class. [Access modifiers](https://docs.microsoft.com/en-us/dotnet/csharp/programming-guide/classes-and-structs/access-modifiers)
34. **Q:** What is a collection?  
**A:** A collection is a type of class that holds data, like a stack or an ArrayList. This data can be accessed and retrieved. They are dynamic.
35. **Q:** What is a Hash Table?  
**A:** A hash table is like a collection in that it holds data. It organizes this data in such a way as to assign a key to each piece of data. This key allows the data accessed.
