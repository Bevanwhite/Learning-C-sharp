# Markdown File

# difference between class and struct 

struct
* it's typically stored in the stack and it is value type
* structs are allocated inline where they are declared
* Structs have a default constructir that initializes all the fields to their defult values(zero or null)
* struct are usually immutable. their fields cannot be modified after the struct instance is created.
* struct are typically used for small data structures that have value semantics

class
* refrence type and  whereas classes are stored on the heap
* require heap allocation and garbage collection


Aspect | Class | Struct
| :--- | :--- | :---
Type | Reference type | Value type
Memory Allocation | Heap | Stack or Inline
Mutability | Mutable | Typically immutable
Default Constructor | Yes (if not explicitly defined) | Always provided
Inheritance| Supports | Does not support
Usage Scenarios| complex objects, shared state | Lightweight data, value semantics
Performance | Overhead due to heap allocation | Faster due to stack allocation


### Value Types
* Value types store their data directly where the variable is allocated.
* Value types are allocated and managed directly by the complier.
* They do not require heap allocation and are not subject to garbage collection
* When passing a value type as an argument to method or assigning it to another variable,
  a copy of the data is passed or assigned. 
* Changes to the copy do not affect the original variable unless explicitly returned.
* value types are automatically initialized to thier default values if not explicitly initialized
* Value types in C# are - int, float, double, char, bool, struct types, enum types and nullable value types 


### stack 
* The stack is fixed length location in memory allocated to each of the threads in an application
* Fixed length value types are stored one top of other on the stack while a sequence of instructions is executed 
for a thread.
* These values are processed on a LIFO or last in first out basis.

### Thread
* A thread of excution is the smallest sequence of programmed instructions.
* In a simple you might require only one thread but a more complex application could invoke multiple threads.
* Each of these threads can run in parallel asynchronously,
* which can greatly increase the performance of the application

### Inherit
* Inheritance is a fundermental principal of object oriented programming.
* Inheritance allows for eg: on class to be based upon another class.

### class
* A class is group of related types, methods and events.
* it servers as a blue print for an object.
* A class is a reference type
* the new keyword is used to create an object from a class

### Reference Type 
* Reference types inherit directly from the 'System.Object' class (which is itself a reference type).
* A variable defined as a reference type stores a pointer or memory location to where the actual data resides.
* The memory location information is stored as a numeric value on the stack and this value points to a portion 
of memory where the data resides in a memory location as the heap. 

### heap 
* The heap is a location in memory that is not constrained by a fixed length
* it is used for the stroage of object data.
* Data is stored in a more haphazed way on the heap when compared to the orderly way that data is stored on 
the stack.
* As a result memory management applied to heap is more complex and therefore less efficient than memory 
management applied to the stack.
* unlike data stored on the stack, the data stored on the heap is not constrained by a fixed length.
* The size of the object data stored on the heap is only constrained by the physical resources of the 
computer on which it resides.
