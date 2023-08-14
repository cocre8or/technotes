# Data Structures

## Structs
A **struct** simply is a container for data and it has no behavior. It cannot be instantiated (new) or inherited.
Also a struct is a value type.

## Node
A **node** is the fundamental building block of many data structures.
It fulfills 2 functions:
	1. Contains a value
	2. And an object reference to another node typically named Next

## Array
An **array** is an ordered collection of items in one container.

Each item in the array has an index. Usually a 0 based index, except COBOL

Immutable - you cannot add or remove items because they are a fixed size.

Restricted to a specific type of data, such as an array of strings or int. Fixed size( fast ), efficient and predictable. The compiler can easily know how much memory to allocate.

Allows for direct fast access to objects in the array. Searching is better when the array is ordered already.

## List or Array Lists
A list is basically a linked list which include sequential access.

Each item in the list has one connecting node to another item in the list and the last item connects to a sentinel node.

Also, typically the list would be a doubly Linked List - a list where the nodes have both a reference to the prev node and the next node.

## Stack
A **stack** is a data structure that is LIFO - last in first out just like a stack of paper or dishes, last item is removed.

Stacks are to be very simple, there is no necessary order or index like arrays or lists. 

The 3 main functions of a  stack structure is push, pop, peek

Push - adds an item to the top of the data
Pop - removes the item from the top of the data AND returns the item that was removed.
Peek - returns the top item value without removing it.

## Queue
A structure that is FIFO first in first out structure

Enqueue - add object to beginning of data
Dequeue remove object from beginning of the data.

## Heap
A heap is basically a sorted queue with a tree structure, see tree below.

## Hash Structures
Basically associate arrays meaning the index is a meaningful key for a certain value.

For what it's worth, a Dictionary is a hash table.

Dictionary is a generic type, Hash table is not. That means you get type safety with Dictionary, because you can't insert any random object into it, and you don't have to cast the values you take out.

## Sets
- Unordered collection of objects - no index and no key
- Rules - they do not allow duplicates
- They allow very fast look up
-- Only Reason to use is to check for membership

## Graph
A **graph** is a specified set of nodes(vertices) V and edges E between select pairs of vertices.<br>
 `G = (V, E)` <br>
 `V = {1,2,3}` <br>
 `E = {1,2}, {3,4}` undirected graph bidirectional vs `E = (1,2)` directed graph

## Tree
A **tree** is a connected acylic graph. Trees are ordered. Any connected graph with |V|-1 edges is a tree.

## Binary Tree
Binary trees can only have up to 2 linking child nodes .i.e. left and right nodes.

## Integers
### Based on Microsoft C#
- The sbyte type represents signed 8-bit integers with values between –128 and 127.
- The byte type represents unsigned 8-bit integers with values between 0 and 255.
- The short type represents signed 16-bit integers with values between –32768 and 32767.
- The ushort type represents unsigned 16-bit integers with values between 0 and 65535.
- The int type represents signed 32-bit integers with values between –2147483648 and 2147483647.
- The uint type represents unsigned 32-bit integers with values between 0 and 4294967295.
- The long type represents signed 64-bit integers with values between –9223372036854775808 and 9223372036854775807.
- The ulong type represents unsigned 64-bit integers with values between 0 and 18446744073709551615.
- The char type represents unsigned 16-bit integers with values between 0 and 65535. The set of possible values for the char type corresponds to the Unicode character set. Although char has the same representation as ushort, not all operations permitted on one type are permitted on the other.

## Floats, Double, Decimal

**Float** is a binary (base 2)  float type 0000.1010 with a precision of 7 digits ( 32 bits ) 4 bytes
**Double** is also a binary(base 2) float type but with a higher precision of 15-16 digits (64 bits) 8 bytes
**Decimal** is based 10 with a precision of 28-29 digits 128 bit 

### NOTE ABOUT BASE 10 AND COMPUTERS
**Base 10** is also called the decimal system or denary system. In base 10, each digit in a position of a number can have an integer value ranging from 0 to 9 (10 possibilities).

Although computers use binary and other systems, they use the decimal system or base 10 to perform arithmetic. This is important because it allows exact computation, which is not possible using binary fractional representations.

## Value vs Reference Type
### Value types
A variable holds actual values. These value types are stored in “stack” memory and these value types are fixed in size. If you assign a value of a variable to another variable it will create two copies.
Ex: byte, short, int, float, double, long ,char, bool, DateTime.
	- Primitive data types are value types except string, object.
	- Object type is superior to all types. It can store any type or any size of data. It helps in inheritance process.
	- Struct, enum are value types.

### Reference types
A variable holds a reference to the value, then that type of data types are reference types. These reference types are stored in “heap” memory and these types are not fixed in size.  They are maintained in system managed heap but it also uses stack to store reference of the heap. Two primitive types (string and object) and non-primitive data types (class, interface & delegate) are examples of reference type.
Ex:   class, interface, delegate, string, object and array
Let us learn couple of data types and its uses with example

## Boxing and Unboxing in C#
Boxing is the process of converting a value type to the type object or to any interface type implemented by this value type. 

When the CLR boxes a value type, it wraps the value inside a System.Object and stores it on the managed heap. Unboxing extracts the value type from the object. Boxing is implicit; unboxing is explicit. The concept of boxing and unboxing underlies the C# unified view of the type system in which a value of any type can be treated as an object.
