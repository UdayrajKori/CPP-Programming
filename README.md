# C++ Programming

<pre>
|
|-- Fundamentals
| |-- Basics of Programming
| | |-- Introduction to C++
| | |-- Setting Up Development Environment (IDE: Code::Blocks, Visual Studio, etc.)
| | |-- Compiling and Running C++ Programs
| |
| |-- Syntax and Structure
| | |-- Basic Syntax
| | |-- Variables and Data Types
| | |-- Operators (Arithmetic, Relational, Logical, Bitwise)
|
|-- Control Structures
| |-- Conditional Statements
| | |-- If-Else Statements
| | |-- Switch Case
| |
| |-- Loops
| | |-- For Loop
| | |-- While Loop
| | |-- Do-While Loop
| |
| |-- Jump Statements
| | |-- Break, Continue
| | |-- Goto Statement
|
|-- Functions and Scope
| |-- Defining Functions
| | |-- Function Syntax
| | |-- Parameters and Arguments (Pass by Value, Pass by Reference)
| | |-- Return Statement
| |
| |-- Function Overloading
| | |-- Overloading Functions with Different Parameters
| |
| |-- Scope and Lifetime
| | |-- Local and Global Scope
| | |-- Static Variables
|
|-- Object-Oriented Programming (OOP)
| |-- Basics of OOP
| | |-- Classes and Objects
| | |-- Member Functions and Data Members
| |
| |-- Constructors and Destructors
| | |-- Constructor Types (Default, Parameterized, Copy)
| | |-- Destructor Basics
| |
| |-- Inheritance
| | |-- Single and Multiple Inheritance
| | |-- Protected Access Specifier
| | |-- Virtual Base Class
| |
| |-- Polymorphism
| | |-- Function Overriding
| | |-- Virtual Functions and Pure Virtual Functions
| | |-- Abstract Classes
| |
| |-- Encapsulation and Abstraction
| | |-- Access Specifiers (Public, Private, Protected)
| | |-- Getters and Setters
| |
| |-- Operator Overloading
| | |-- Overloading Operators (Arithmetic, Relational, etc.)
| | |-- Friend Functions
|
|-- Advanced C++
| |-- Pointers and Dynamic Memory
| | |-- Pointer Basics
| | |-- Dynamic Memory Allocation (new, delete)
| | |-- Pointer Arithmetic
| |
| |-- References
| | |-- Reference Variables
| | |-- Passing by Reference
| |
| |-- Templates
| | |-- Function Templates
| | |-- Class Templates
| |
| |-- Exception Handling
| | |-- Try-Catch Blocks
| | |-- Throwing Exceptions
| | |-- Standard Exceptions
|
|-- Data Structures
| |-- Arrays and Strings
| | |-- One-Dimensional and Multi-Dimensional Arrays
| | |-- String Handling
| |
| |-- Linked Lists
| | |-- Singly and Doubly Linked Lists
| |
| |-- Stacks and Queues
| | |-- Stack Operations (Push, Pop, Peek)
| | |-- Queue Operations (Enqueue, Dequeue)
| |
| |-- Trees and Graphs
| | |-- Binary Trees, Binary Search Trees
| | |-- Graph Representation and Traversal (DFS, BFS)
|
|-- Standard Template Library (STL)
| |-- Containers
| | |-- Vectors, Lists, Deques
| | |-- Stacks, Queues, Priority Queues
| | |-- Sets, Maps, Unordered Maps
| |
| |-- Iterators
| | |-- Input and Output Iterators
| | |-- Forward, Bidirectional, and Random Access Iterators
| |
| |-- Algorithms
| | |-- Sorting, Searching, and Manipulation
| | |-- Numeric Algorithms
|
|-- File Handling
| |-- Streams and File I/O
| | |-- ifstream, ofstream, fstream
| | |-- Reading and Writing Files
| | |-- Binary File Handling
|
|-- Testing and Debugging
| |-- Debugging Tools
| | |-- gdb (GNU Debugger)
| | |-- Valgrind for Memory Leak Detection
| |
| |-- Unit Testing
| | |-- Google Test (gtest)
| | |-- Writing and Running Tests
|
|-- Deployment and DevOps
| |-- Version Control with Git
| | |-- Integrating C++ Projects with GitHub
| |-- Continuous Integration/Continuous Deployment (CI/CD)
| | |-- Using Jenkins or GitHub
| |
</pre>

# 🖥️ What is a Computer?

A **computer** is an **electronic device** that takes **input**, processes it using a **set of instructions (called programs)**, and gives an **output**. It can also **store data** for future use.


## 🔄 Basic Functions of a Computer

1. **Input** – Getting data from the user (e.g., using a keyboard or mouse)
2. **Processing** – Working on the data (inside the CPU)
3. **Output** – Showing the result (on screen or printer)
4. **Storage** – Saving the data (in hard disk, pen drive, etc.)


## 📝 In Simple Words

A computer is a **machine** that helps us do tasks like:

- Typing documents
- Drawing pictures
- Solving calculations
- Playing games
- Browsing the internet


## 💻 Examples of Computers

- Desktop
- Laptop
- Tablet
- Smartphone


# 💻 Hardware and Software

## 🧠 What is Hardware?
**Hardware** refers to the **physical components** of a computer system that can be **seen and touched**.

### 🔧 Types of Hardware
1. **Input Devices** – Keyboard, Mouse, Scanner
2. **Output Devices** – Monitor, Printer, Speaker
3. **Processing Devices** – CPU
4. **Storage Devices** – Hard Disk, SSD, RAM


## 💾 What is Software?
**Software** is a **collection of instructions** that tells the hardware what to do. It is **not physical** and cannot be touched.

### 🧩 Types of Software
1. **System Software** – Windows, Linux, Device Drivers
2. **Application Software** – MS Word, Chrome, Photoshop
3. **Programming Software** – VS Code, Compiler, Debugger


## 🆚 Difference Between Hardware and Software

| Hardware               | Software                       |
|------------------------|--------------------------------|
| Physical components     | Instruction/code               |
| Can be touched          | Cannot be touched              |
| Examples: CPU, Mouse    | Examples: Windows, Chrome      |


# 💡 Programming Language Levels

## 🔵 1. High-Level Language (HLL)

### 📘 Definition
A high-level language is close to human language and easy to write, read, and understand.

### ✅ Advantages
- Easy to learn and use
- Portable across systems
- Easier to debug and maintain

### ❌ Disadvantages
- Slower execution
- Needs a compiler/interpreter

### 🧾 Examples
- Python, Java, C++, JavaScript


## 🟡 2. Low-Level Language (LLL)

### 📘 Definition
A low-level language is closer to hardware and gives more control to the programmer.

### ✅ Advantages
- Faster execution
- Better control over hardware

### ❌ Disadvantages
- Hard to understand and write
- Not portable

### 🧾 Example
- Assembly Language


## 🔴 3. Machine-Level Language (MLL)

### 📘 Definition
Machine language is the binary code (0s and 1s) that is directly understood by the CPU.

### ✅ Advantages
- Fastest execution
- No need for translation

### ❌ Disadvantages
- Very difficult to write
- Not readable or portable

### 🧾 Example
- `10110000 01100001` (binary instruction)

# 🧠 Compiler

## 📘 What is a Compiler?

A **compiler** is a program that **translates high-level language code** into **machine language** (binary) **before execution**. It converts the entire program at once and produces an executable file.


## ✅ Advantages of Compiler

- 🔹 Fast execution of compiled programs
- 🔹 Code optimization for better performance
- 🔹 Detects syntax errors before execution


## ❌ Disadvantages of Compiler

- 🔸 Slower compilation (takes time to compile whole code)
- 🔸 Shows all errors at once – harder for beginners to debug
- 🔸 Compiled code is often platform dependent


## 🧾 Examples of Compilers

- **GCC** – for C/C++
- **javac** – for Java
- **Turbo C** – for C/C++ (Windows)
- **Intel Compiler** – for high-performance C/C++ programs


## Introduction to C++

C++ is a special language that we use to talk to computers. Just like we speak English or Nepali, computers understand C++ when we give them instructions. With C++, we can create fun things like games and apps or solve problems using a computer. It was made by a smart person named Bjarne Stroustrup. When we write C++ code, the computer reads it and does what we ask, like showing a message on the screen. Learning C++ helps us understand how computers think and work, and many big companies use it to build important software. So, by learning C++, you can make your own cool programs and become a computer expert!

## Why C++

C++ is a very popular language because it is powerful and easy to use for many things. We use C++ to make games, apps, and even robots work! It helps us tell the computer exactly what to do, step by step. Many big companies and game makers choose C++ because it is fast and can do a lot of things at once. Also, when you learn C++, it becomes easier to learn other programming languages later. That’s why C++ is a great language to start with if you want to become a computer programmer or build your own projects.

## Features of C++

1. **Fast and Powerful** – C++ can do many tasks quickly.
2. **Works for Small and Big Programs** – You can make simple apps or big games.
3. **Object-Oriented Programming** – Lets you create classes and objects, like organizing toys in boxes.
4. **Uses Functions** – Helps keep your code clean and easy to understand.
5. **Memory Control** – You can tell the computer how to use its memory carefully.
6. **Supports Reusable Code** – You can use the same code again and again.
7. **Works on Many Computers** – C++ runs on Windows, Mac, and Linux.
8. **Used by Many Programmers** – People all over the world use C++ to build software.


## Difference Between C and C++

| Feature | C | C++ |
|------------------------|--------------------------------|-----------------------------------------|
| Age | Older language | Newer language with extra features |
| Programming Style | Procedural (step-by-step) | Procedural + Object-Oriented Programming |
| Code Organization | Simple functions | Uses classes and objects to organize code|
| Complexity | For simple programs | Can handle big and complex programs |
| Toolbox Example | Small toolbox | Bigger toolbox with more tools |
| Usage | Basic tasks | Games, apps, and big software projects |

## Advantages of C++

- **Fast and Efficient** – Programs run quickly because C++ works close to the computer’s hardware.
- **Powerful Language** – Can be used to make games, apps, and big software projects.
- **Object-Oriented Programming** – Helps organize code using classes and objects, making it easier to manage.
- **Portable** – C++ programs can run on different types of computers like Windows, Mac, and Linux.
- **Reusable Code** – You can use the same code many times, saving time and effort.
- **Large Community** – Many programmers use C++, so it’s easy to find help and resources.

## Disadvantages of C++

- **Complex Syntax** – Sometimes C++ code can be hard to write and understand, especially for beginners.
- **Manual Memory Management** – You need to manage computer memory yourself, which can cause errors if not done carefully.
- **Not Easy for Small Projects** – For very simple tasks, C++ might be more complicated than needed.
- **Longer Learning Time** – It can take more time to learn C++ well compared to some other languages.

## Setting Up Development Environment (IDE)

To write and run C++ programs, we need a special software called an **IDE** (Integrated Development Environment). An IDE helps us write code, find mistakes, and run the program all in one place.

Some popular IDEs for C++ are:
- **Code::Blocks** — It is easy to use and good for beginners.
- **Visual Studio** — A powerful tool used by many programmers.
- **Dev-C++** — Simple and lightweight for small programs.

### How to Set Up Code::Blocks (Example)

1. Go to the Code::Blocks website and download the version that includes the **MinGW compiler** (this lets your computer understand C++ code).
2. Install Code::Blocks by following the steps on the screen.
3. Open Code::Blocks and create a new C++ project or file.
4. Write your C++ code and click “Build and Run” to see your program work!

Using an IDE makes learning and coding in C++ easier and more fun!

## Compiling and Running C++ Programs

When we write C++ code, the computer does not understand it right away. We need to **compile** the code first. Compiling means changing the code into a language that the computer can understand.

### Steps to Compile and Run:

1. **Write the code** in your IDE (like Code::Blocks or Visual Studio).
2. **Compile the code** by clicking the “Build” or “Compile” button. This checks your code for mistakes and turns it into a program the computer can run.
3. If there are no mistakes, you will get an **executable file** (a program file).
4. **Run the program** by clicking the “Run” button or opening the executable file. You will see the result of your code on the screen.

If there are errors, the compiler will tell you what needs fixing. Fix the errors and try compiling again.

This process helps you turn your instructions into working programs!


# ❌ Errors in C++

## 📘 What is an Error?

An **error** in C++ is a problem in the code that prevents it from compiling, running, or producing correct results.


## 📚 Types of Errors in C++

### 1. Syntax Error
- Violates the rules of C++ syntax
- Detected at compile-time

**Example:**
```cpp
cout << "Hello" // missing semicolon
```

### 2. Semantic Error
- Code structure is correct, but the logic or meaning is wrong

**Example:**
```cpp
int a = 10;
a = a / 0; // Division by zero
```


### 3. Logical Error
- Code runs, but the result/output is incorrect

**Example:**
```cpp
int a = 5, b = 10;
cout << a - b; // Wrong logic if we want to find the sum
```


### 4. Runtime Error
- Occurs while the program is running

**Example:**
```cpp
int x = 10, y = 0;
cout << x / y; // Division by zero
```


## ✅ Advantages of Understanding Errors

- Better coding skills
- Easier debugging
- Cleaner and more reliable programs


## ❌ Disadvantages of Errors

- Time-consuming to fix
- Can cause crashes
- Debugging may be difficult


## 🧾 Error Types Cheat Sheet

| Error Type     | When it Occurs     | Detected By     | Description                             | Example                          |
|----------------|--------------------|-----------------|---------------------------------------|---------------------------------|
| Syntax Error   | Compile-time       | Compiler        | Rule-breaking in language syntax      | Missing `;`                     |
| Semantic Error | Compile-time       | Compiler/Runtime| Valid syntax but invalid meaning      | Division by zero                |
| Logical Error  | Runtime (No crash) | Programmer      | Output is wrong due to wrong logic    | Adding by mistake uses `-`      |
| Runtime Error  | During execution   | Program         | Error happens while the program runs  | Dividing a number by zero       |


# 📐 Syntax and Structure in Programming (C++)

## What is Syntax?

**Syntax** means the set of rules that define the **correct way** to write programs in a programming language.

Just like grammar rules in English, syntax rules in C++ tell you how to write instructions so the compiler can understand them.


## Why is Syntax Important?

- Ensures the code is **understandable** by the compiler  
- Prevents errors during compilation  
- Helps programmers write **consistent** and **clear** code


## What is Structure?

**Structure** refers to the way different parts of a program are **organized** or **arranged** together to form a working program.

It includes:

- How functions, variables, and statements are grouped  
- How the program flow is controlled using loops, conditionals, etc.


## Basic Structure of a C++ Program

```cpp
#include <iostream>  // Preprocessor directive

using namespace std; // Use standard namespace

int main() {         // Main function - program entry point
    // Your code goes here
    cout << "Hello, World!" << endl; // Output statement
    return 0;       // Exit status
}
```

# 🔢 Variables and Data Types in C++

## What is a Variable?

A **variable** is a named storage location in memory used to hold data that can change during program execution.

Think of it like a box with a label, where you can store and later change the value inside.


## Syntax of Variable Declaration

```cpp
data_type variable_name = value;
```

**Example:**

```cpp
int age = 25;
float price = 99.99;
```


## What are Data Types?

**Data types** specify what kind of data a variable can store.

Different data types reserve different amounts of memory and define what operations can be performed on the data.


## Common Data Types in C++

| Data Type   | Size (approx) | Description                   | Example                  |
|-------------|---------------|------------------------------|--------------------------|
| `int`       | 4 bytes       | Stores whole numbers          | `int age = 25;`          |
| `float`     | 4 bytes       | Stores decimal numbers        | `float price = 99.99;`   |
| `double`    | 8 bytes       | Stores large decimal numbers  | `double pi = 3.14159;`   |
| `char`      | 1 byte        | Stores a single character     | `char grade = 'A';`      |
| `bool`      | 1 byte        | Stores true or false          | `bool isPassed = true;`  |


## Types of Variables in C++

1. **Local Variables**  
   Declared inside a function or block, accessible only within that scope.

2. **Global Variables**  
   Declared outside all functions, accessible throughout the program.

3. **Static Variables**  
   Retain their value between function calls, declared with the `static` keyword.

4. **Constant Variables (`const`)**  
   Variables whose value cannot be changed once initialized.


## Syntax of Different Variable Types

| Variable Type | Syntax Example                 |
|---------------|-------------------------------|
| Local         | `int localVar = 10;`           |
| Global        | Declared outside all functions |
| Static        | `static int count = 0;`        |
| Constant      | `const int MAX = 100;`         |


## Advantages of Variables and Data Types

- **Memory Management:** Reserve appropriate memory for data  
- **Code Clarity:** Makes the program easier to understand  
- **Type Safety:** Helps catch errors early by restricting data types  
- **Reusability:** Variables can store different values over time


## Disadvantages

- **Memory Usage:** Improper choice of data types can waste memory  
- **Type Errors:** Using wrong data types can cause bugs  
- **Complexity:** Managing many variables can complicate code


## Example in C++

```cpp
#include <iostream>
using namespace std;

int globalVar = 100; // Global variable

void demoFunction() {
    static int staticVar = 0;    // Static variable
    int localVar = 10;           // Local variable
    const int constantVar = 50;  // Constant variable

    staticVar++;
    cout << "Static: " << staticVar << ", Local: " << localVar 
         << ", Constant: " << constantVar << endl;
}

int main() {
    int age = 25;
    float price = 99.99;
    char grade = 'A';
    bool isPassed = true;

    cout << "Age: " << age << endl;
    cout << "Price: $" << price << endl;
    cout << "Grade: " << grade << endl;
    cout << "Passed: " << isPassed << endl;

    demoFunction();
    demoFunction();
    demoFunction();

    cout << "Global Variable: " << globalVar << endl;

    return 0;
}
```


# ⚙️ Operators in C++

Operators are symbols that perform operations on variables and values.


## 1. Arithmetic Operators

Used for mathematical calculations like addition, subtraction, multiplication, division, and modulus.

### Syntax

```cpp
result = operand1 operator operand2;
```

### Common Arithmetic Operators

| Operator | Description       | Example        |
|----------|-------------------|----------------|
| `+`      | Addition          | `a + b`        |
| `-`      | Subtraction       | `a - b`        |
| `*`      | Multiplication    | `a * b`        |
| `/`      | Division          | `a / b`        |
| `%`      | Modulus (remainder)| `a % b`       |

### Example

```cpp
int a = 10, b = 3;
cout << a + b; // Output: 13
cout << a % b; // Output: 1
```

### Advantages

- Simple and efficient for arithmetic calculations.
- Easy to understand and use.

### Disadvantages

- Division by zero causes runtime errors.
- Limited to numeric data types.


## 2. Relational Operators

Used to compare two values and return a boolean result (`true` or `false`).

### Syntax

```cpp
operand1 operator operand2;
```

### Common Relational Operators

| Operator | Description            | Example      |
|----------|------------------------|--------------|
| `==`     | Equal to               | `a == b`     |
| `!=`     | Not equal to           | `a != b`     |
| `>`      | Greater than           | `a > b`      |
| `<`      | Less than              | `a < b`      |
| `>=`     | Greater than or equal  | `a >= b`     |
| `<=`     | Less than or equal     | `a <= b`     |

### Example

```cpp
int a = 5, b = 10;
cout << (a < b);  // Output: 1 (true)
cout << (a == b); // Output: 0 (false)
```

### Advantages

- Useful for decision-making and control flow.
- Clear and intuitive syntax.

### Disadvantages

- Only compares values, not data types.
- Can cause confusion if not used carefully (e.g., assignment `=` vs equality `==`).


## 3. Logical Operators

Used to combine multiple boolean expressions.

### Syntax

```cpp
expression1 operator expression2;
```

### Common Logical Operators

| Operator | Description    | Example           |
|----------|----------------|-------------------|
| `&&`     | Logical AND    | `(a > 0 && b > 0)`|
| `||`     | Logical OR     | `(a > 0 || b > 0)`|
| `!`      | Logical NOT    | `!(a > b)`        |

### Example

```cpp
bool x = true, y = false;
cout << (x && y); // Output: 0 (false)
cout << (!x);     // Output: 0 (false)
```

### Advantages

- Powerful for complex conditional statements.
- Improves code readability.

### Disadvantages

- Complex conditions can become hard to debug.
- Logical errors can be tricky to find.


## 4. Bitwise Operators

Operate on bits and perform bit-level operations.

### Syntax

```cpp
operand1 operator operand2;
```

### Common Bitwise Operators

| Operator | Description         | Example       |
|----------|---------------------|---------------|
| `&`      | Bitwise AND         | `a & b`       |
| `|`      | Bitwise OR          | `a | b`       |
| `^`      | Bitwise XOR         | `a ^ b`       |
| `~`      | Bitwise NOT         | `~a`          |
| `<<`     | Left shift          | `a << 2`      |
| `>>`     | Right shift         | `a >> 2`      |

### Example

```cpp
int a = 5;    // binary: 0101
int b = 3;    // binary: 0011
cout << (a & b);  // Output: 1 (0001)
cout << (a << 1); // Output: 10 (1010)
```

### Advantages

- Efficient for low-level programming and performance-critical code.
- Useful for manipulating bits in embedded systems, cryptography, and graphics.

### Disadvantages

- Harder to understand for beginners.
- Can cause unexpected results if not used carefully.


# Summary Table

| Operator Type     | Purpose                  | Result Type        | Usage Example             |
|-------------------|--------------------------|--------------------|---------------------------|
| Arithmetic        | Mathematical operations  | Numeric            | `a + b`                   |
| Relational        | Comparison               | Boolean (`true`/`false`) | `a == b`             |
| Logical           | Combine boolean expressions | Boolean          | `a && b`                  |
| Bitwise           | Bit-level operations     | Numeric (bits)     | `a & b`                   |



