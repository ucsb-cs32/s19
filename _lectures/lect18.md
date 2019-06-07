---
num: "Lecture 18"
desc: "Final Review"
ready: true
lecture_date: 2019-06-06 12:30:00.00-7:00
---

```
Logistics
- Bring studentID and writing utensil
    - ink or dark led
- Please write LEGIBLY
- No electronic devices
- No book, no notes
- 30% of your final grade
- Monday 6/10 @ 12pm (CHEM 1171)

Format of the exam
- Similar to the midterms, but designed to take two hours (~ twice as long)
- Mix of questions
    - Short answer
    - Briefly describe / define / state /...
    - Write code
    - Fill in the blank / complete the table (or diagram)
    - True / False, if false explain why
    - Given code, what is the output

Topics
- Will cover everything from the start of the quarter up to Tuesday's lecture (6/4) on Threads
- Covers lecture, labs, homeworks, and readings
    - Use lecture notes as breadth of topics (except OS, use lecture notes for depth), and all other course material (lecture, hw, labs, reading) as depth.

- Makefiles
- STL (vector, map, unordered_map, string, iostream, thread, ...)
- Class Design
    - Abstract Data Types
    - Build process
        - .cpp / .h linking
    - Big Three (copy constructor, destructor, assignment operator)
    - Scope resolution operators (::)
        - Used in class method definitions and namespaces
    - Templates
- Structs and classes
    - Differences
    - Memory storage (hexidecimal notation)
    - Syntax
- Memory Padding
- Namespaces
    - Naming collisions (and how to avoid them)
    - Global namespace
- Quadratic Sorting
    - Bubblesort, selectionsort, insertionsort
    - Optimizations
    - Running times
- Hash Tables
    - Performance and functionality
    - Open-address, double-hashing, chained-hashing (pros / cons)
    - std::map, std::unordered_map, std::set, std::unordered_set (under-the-hood implentation and concepts and runtime)
- Mergesort and Quicksort
    - Algorithm
    - Running times
    - Pros / cons
- Inheritance
    - Understand concepts and behavior
    - Understand memory allocation of base / sub classes
    - Hierarchy (types)
- Polymorphism
    - Understand concpets and behavior
    - Virtual vs. non-virtual
    - Abstract classes and pure virtual functions
    - Virtual destructors
- Exceptions
    - Try / catch / throw mechanisms and flow control
    - Inheritence and how catches work with types
- Function Pointers
    - Syntax of function Pointers
        - How to declare, assign, call functions via function Pointers
    - Using function pointers with Threads
    - write code utiliznig function pointers
- Testing
    - Understand main ideas and terminology
    - tddFuncs' way of Testing
    - TDD (test driven development)
- Operating System concepts
    - Role of the OS
    - OS Kernel
    - Relationship to software / hardware
    - Processes
    - Threads
    - Basic Unix commands from lecture notes
        - ps, ps -e, top, jobs, ^C, ^Z, kill, ...
    - Foreground vs background Processes
        - How they relate to the terminal
    - Fork / Exec
        - Examples with terminal behavior when executing command lines and unistd.h functions in a C++ application
- Heap
    - MinHeap and MaxHeap
    - Conceptual tree structure
    - Implementation
    - Array representation and index of children / parent of node
    - Insertion and maintenance
        - Deletion (of root)
        - Runtime analysis
- Threads
    - Threads and hardware (threads running on cores)
        - Concurrency
    - Using <thread> library to create threads
    - .join, .detach - what they do and why is this important
    - Race conditions
        - Mutex (locks) and supporting atomic operations
```
