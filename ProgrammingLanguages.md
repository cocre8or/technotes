# Programming Languages and Ecosystems
<details>
  <summary>
    C-Sharp
  </summary>

  ## Language Summary
  C# is an Object oriented, type-safe programming language that runs on .NET framework and .NET Core for platform independence.
  
  ## Features
  1. Automatic Garbage collection
  2. Generics which allows parameterized types, it enables programmers to create classes,interfaces,and methods that work with different data types without having to define the data type **explicitly**.
  3. LINQ - Lambda expressions for Language Integrated Queries
  4. Synchronization and Asynchronization
  5. Classes, Objects, Primitive Types, Generics, user-defined reference and value types.

  ## Data Types
  14 Primitive types and blank Non-primitive types
  |Primitive Type | Details | 
  |-|-|
  |Boolean | true/false data type 1 byte i.e. 8 bits.|
  
  |Non-primitive Types | Details |
  |-|-|
  |Class | Reference type and blueprint for an object, defining properties and behaviors|
  |Struct | Value type and more of a lightweight class, no inheritance, but interfaces allowed |
  |Enum | Are **sets** of named integer constants that are grouped together.|
  |Arrays | Arrays are one of the ways to store a fixed size collection of elements of the same data type.|
  |Strings | A string is a collection of characters stored in a sequential order to form text.|
  
  ## Ecosystem

  
</details>

<details>
  <summary>
    Java
  </summary>

  ## Language Summary
  Java is a **mostly** Object oriented programming language that runs on JVM (Java Virtual Machine) for platform independence.
  
  ## Features
  1. Automatic Garbage collection
  2. Generics which allows parameterized types, it enables programmers to create classes,interfaces,and methods that work with different data types without having to define the data type **explicitly**. i.e. List<T>().
  3. Stream is the Java equivalent to LINQ in C#
  4. Synchronization and Asynchronization
  5. Classes, Objects, Primitive Types, Generics, user-defined reference and value types.

  ## Data Types
  8 Primitive types and 5 Non-primitive types
  |Primitive Type | Details | Immutable Wrapper Class | 
  |-|-|-|
  |char | 1 bit | Char |
  |boolean | true/false data type 1 byte i.e. 8 bits.| Boolean |
  |byte |8 bit signed number | Byte |
  |short |16 bit signed number | Short |
  |int | 32 bit signed number | Integer |
  |long |64 bit signed number | Long |
  |float |32 bit signed floating point number | Float |
  |double |64 bit signed floating point number | Double |
  
  |Non-primitive Types | Details |
  |-|-|
  |Class | Reference type and blueprint for an object, defining properties and behaviors|
  |Object | A general type that includes any non-primitive or reference type |
  |Interface | A reference type that holds a collection of abstract methods |
  |Arrays | Arrays are one of the ways to store a fixed size collection of elements of the same data type.|
  |Strings | A string is a collection of characters stored in a sequential order to form text.|

  |Data Structure | Runtime Complexity | Details |
  |-|-|-|
  |HashSet | O(n) | Set data structure i.e. { 1, 5, 6 }. No duplicates allowed. 1 null element allowed. Uses hashMap for sorting. |
  |HashMap | O(1) | Map data structure i.e. (key, value) pair. Not Thread safe. No duplicate keys allowed. 1 null key, any # of null values allowed. Uses hashing which includes a key, hash function and a HashTable. |
  |HashTable | O(1) | Legacy Table data structure i.e. (index, value). No duplicates allowed. Thread safe. No nulls at all allowed. |
  |ConcurrentHashMap | O(1) | A thread safe HashMap. It allows for multiple threads to access the same HashMap. |
  |Array | O(n) | fixed size and can be multi-dimensional |
  |ArrayList | O(n) | variable size and single-dimensional. It can store multiple different types. |
  |LinkedList | O(n)| variable size and tree structure with nodes and address pointers. Doubly linked list to store elements.|
  
  ## Ecosystem

  |Term | Information |
  |-|-|
  |JDK: Java Development Kit | Development platform including dev tools, JRE, javac, and JVM |
  |JRE: Java Runtime Environment |JRE executes Java Programs, includes JIT and JVM. |
  |JVM: Java Virtual Machine |JVM is the foundation, or the heart of Java programming language, and ensures the program’s Java source code will be platform-agnostic. JVM is *included* in **both** JDK and JRE – Java programs won’t run without it.|
  |JIT: Just In Time Compiler | It is part of JVM and optimizes the conversion of bytecode to machine code.|
  |Javac | Another complementary tool, is a compiler that reads Java definitions and translates them into bytecode that can run on JVM|
  | Javadoc | Converts API documentation from Java source code to HTML. This is useful when creating standard documentation in HTML|
  |JDBC | Responsible for database connections and query activities within Java. |
  |Hibernate |Preferred Object Relational Mapping Tool|
  |Spring Framework | Similar to C-Sharps ASP.NET framework, it simplifies many configurations for developers. It can be considered as a collection of sub-frameworks|
  |Spring Boot | Built on top of Spring, and easier to use. It is mostly used for REST API development. It also includes an instance of Tomcat server. |
  |Spring Web MVC | Part of Spring that helps faciliate rapid Web Application development in Java using the Model-View-Controller pattern.|
  | Spring JDBC | It belongs to the Spring Data family. Basically, it provides abstractions for the JDBC-based Data Access Layer. It provides easy to use Object Relational Mapping (ORM) framework to work with databases. |
  |Gradle | Gradle is a build automation tool known for its flexibility to build software. A build automation tool is used to automate the creation of applications. |
  |Maven |Maven is chiefly used for Java-based projects, helping to download dependencies, which refers to the libraries or JAR files. The tool helps get the right JAR files for each project as there may be different versions of separate packages.|
  |Tomcat | Typical web server |
  |JUnit | A unit testing open-source framework for the Java programming language. Uses @Test annotation and Asserts. |

</details>

<details>
  <summary>
    Python
  </summary>
</details>

<details>
  <summary>
    JavaScript
  </summary>
</details>

<details>
  <summary>
    TypeScript
  </summary>
</details>

<details>
  <summary>
    C Language
  </summary>
</details>
