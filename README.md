# CIT300 Data Structure and Graph Performance Analyzer

## Project Title

**Data Structure and Graph Performance Analyzer**

## Module

**CIT300 – Data Structures and Algorithms**

## Assignment

**Graded Practical Assignment 2**

## Application Type

Java Console-Based Application

---

# 1. Project Description

The **Data Structure and Graph Performance Analyzer** is a Java console-based application developed for the CIT300 Data Structures and Algorithms module.

The purpose of this project is to demonstrate the practical implementation and use of common data structures, searching algorithms, graph representations, graph traversal algorithms, and algorithm performance analysis.

The application provides a menu-driven console interface where users can perform different operations using:

- Arrays
- Stacks
- Queues
- Linked Lists
- Linear Search
- Binary Search
- Graphs
- Breadth First Search (BFS)
- Depth First Search (DFS)
- Performance and complexity comparison

The program also includes input validation, error handling, operation tracking, execution-time measurement, and complexity information.

---

# 2. Team Members

| Student ID | Student Name | Role |
|---|---|---|
| 23DA2-0477 | Mohammed Aswin | Group Leader |
| 23DA2-0476 | Mohammed Haazeem | Member |
| 23DA2-0539 | Sumaas Ahamed | Member |
| 23DA2-0517 | Arsath Hasan | Member |

---

# 3. Team Responsibilities and Individual Contributions

## Member 1 – Mohammed Aswin

**Student ID:** 23DA2-0477  
**Role:** Group Leader  

### Assigned Responsibility

- Array Implementation
- Searching Algorithms
- Performance Analysis
- Main System Integration
- Final Testing
- README Documentation

### Individual Contribution

- Implemented the `ArrayManager` class.
- Implemented Array insertion at the end.
- Implemented Array insertion at a specific position.
- Implemented Array deletion by value.
- Implemented Array searching.
- Implemented Array display functionality.
- Implemented Linear Search.
- Implemented Binary Search.
- Implemented search result tracking.
- Implemented performance comparison between Linear Search and Binary Search.
- Implemented performance comparison between BFS and DFS.
- Integrated all data structure modules into the main application.
- Developed the main menu and submenus.
- Added the complexity reference section.
- Added the display-all-results functionality.
- Performed final integration and system testing.
- Prepared and updated project documentation.

### Main Files

```text
ArrayManager.java
SearchAlgorithms.java
SearchResult.java
PerformanceAnalyzer.java
Main.java
README.md
```

---

## Member 2 – Mohammed Haazeem

**Student ID:** 23DA2-0476

### Assigned Responsibility

- Stack Implementation
- Queue Implementation
- Stack and Queue Testing

### Individual Contribution

- Implemented the `StackManager` class.
- Implemented Stack Push operation.
- Implemented Stack Pop operation.
- Implemented Stack Peek operation.
- Implemented Stack display functionality.
- Implemented Stack overflow handling.
- Implemented Stack underflow handling.
- Implemented the `QueueManager` class.
- Implemented Queue Enqueue operation.
- Implemented Queue Dequeue operation.
- Implemented Queue Peek/Front operation.
- Implemented Queue display functionality.
- Implemented Circular Queue logic.
- Implemented Queue overflow handling.
- Implemented Queue underflow handling.
- Tested Stack and Queue operations.

### Main Files

```text
StackManager.java
QueueManager.java
```

---

## Member 3 – Sumaas Ahamed

**Student ID:** 23DA2-0539

### Assigned Responsibility

- Linked List Implementation
- Input Validation
- Error Handling

### Individual Contribution

- Implemented the `LinkedListManager` class.
- Implemented a custom Node structure.
- Implemented Linked List insertion at the beginning.
- Implemented Linked List insertion at the end.
- Implemented deletion by value.
- Implemented Linked List searching.
- Implemented Linked List display functionality.
- Implemented search step counting.
- Implemented search execution-time measurement.
- Implemented the reusable `InputHelper` class.
- Implemented integer input validation.
- Prevented invalid user input from terminating the application.
- Tested empty Linked List conditions.
- Tested invalid input handling.

### Main Files

```text
LinkedListManager.java
InputHelper.java
```

---

## Member 4 – Arsath Hasan

**Student ID:** 23DA2-0517

### Assigned Responsibility

- Graph Implementation
- Breadth First Search
- Depth First Search
- Graph Searching
- Graph Traversal Testing

### Individual Contribution

- Implemented the `Graph` class.
- Implemented Graph representation using an Adjacency List.
- Implemented Add Vertex functionality.
- Implemented Add Edge functionality.
- Implemented Graph display functionality.
- Implemented Breadth First Search traversal.
- Implemented Depth First Search traversal.
- Implemented BFS-based Graph searching.
- Implemented traversal step counting.
- Implemented traversal execution-time measurement.
- Implemented traversal result storage.
- Implemented Graph search result storage.
- Tested Graph operations.
- Tested BFS and DFS traversal.

### Main Files

```text
Graph.java
TraversalResult.java
GraphSearchResult.java
```

---

# 4. Technologies Used

- Java
- Java Development Kit (JDK)
- Git
- GitHub
- Visual Studio Code

---

# 5. Main System Features

The system provides the following functionality.

## Array Operations

- Insert value at end
- Insert value at a specific position
- Delete value
- Search value
- Display Array
- Array capacity validation

---

## Stack Operations

- Push
- Pop
- Peek
- Display
- Overflow handling
- Underflow handling

The Stack follows the:

**LIFO – Last In, First Out**

principle.

---

## Queue Operations

- Enqueue
- Dequeue
- Peek / Front
- Display
- Overflow handling
- Underflow handling

The Queue follows the:

**FIFO – First In, First Out**

principle.

A Circular Queue implementation is used to efficiently reuse available positions.

---

## Linked List Operations

- Insert at beginning
- Insert at end
- Delete by value
- Search
- Display

A custom Node structure is used to implement the Linked List.

---


# 11. Project Structure

```text
CIT300-Data-Structure-Graph-Analyzer/
│
├── README.md
│
└── src/
    │
    ├── Main.java
    ├── InputHelper.java
    │
    ├── ArrayManager.java
    ├── StackManager.java
    ├── QueueManager.java
    ├── LinkedListManager.java
    │
    ├── SearchAlgorithms.java
    ├── SearchResult.java
    │
    ├── Graph.java
    ├── TraversalResult.java
    ├── GraphSearchResult.java
    │
    └── PerformanceAnalyzer.java
```

---

# 12. Java File Description

## `Main.java`

Controls the entire application.

Responsibilities:

- Main menu
- Array menu
- Stack menu
- Queue menu
- Linked List menu
- Searching menu
- Graph menu
- Performance menu
- Display all results
- Complexity reference
- System integration

---

## `ArrayManager.java`

Handles all Array operations.

```text
Insert
Delete
Search
Display
```

---

## `StackManager.java`

Handles all Stack operations.

```text
Push
Pop
Peek
Display
Overflow Handling
Underflow Handling
```

---

## `QueueManager.java`

Handles all Queue operations.

```text
Enqueue
Dequeue
Peek
Display
Circular Queue Management
```

---

## `LinkedListManager.java`

Handles all Linked List operations.

```text
Insert at Beginning
Insert at End
Delete
Search
Display
```

---

## `SearchAlgorithms.java`

Contains:

```text
Linear Search
Binary Search
```

---

## `SearchResult.java`

Stores searching results including:

```text
Found / Not Found
Index
Number of Steps
Execution Time
```

---

## `Graph.java`

Handles the Graph implementation.

Features:

```text
Adjacency List
Add Vertex
Add Edge
Display
BFS
DFS
BFS Graph Search
```

---

## `TraversalResult.java`

Stores BFS and DFS traversal results.

```text
Traversal Order
Steps
Execution Time
```

---

## `GraphSearchResult.java`

Stores Graph searching results.

```text
Found / Not Found
Visited Order
Steps
Execution Time
```

---

## `PerformanceAnalyzer.java`

Handles algorithm performance comparison.

```text
Linear Search vs Binary Search
BFS vs DFS
Steps
Execution Time
Complexity
```

---

## `InputHelper.java`

Handles user input validation.

It prevents the program from crashing when invalid non-numeric values are entered.

---

# 13. Main Application Menu

The application contains the following main menu.

```text
==================================================
 DATA STRUCTURE & GRAPH ANALYZER
==================================================

1. Array Operations
2. Stack Operations
3. Queue Operations
4. Linked List Operations
5. Searching Operations
6. Graph Operations
7. Performance Comparison
8. Display All Results
9. Complexity Reference
0. Exit

Enter your choice:
```

---


## Step 5 – Compile All Java Files

```bash
javac *.java
```

If the project compiles successfully, no error message should be displayed.

---

## Step 6 – Run the Application

```bash
java Main
```

The main menu will then be displayed.

# 16. Input Validation

The program validates user input.

For example, if the user enters:

```text
abc
```

instead of a number, the application displays:

```text
Invalid input. Please enter a whole number.
```

The user can then enter a valid value without restarting the application.

---

# 17. Error Handling

The system handles invalid data structure operations.

Examples include:

### Empty Stack

```text
Stack underflow. Cannot pop from an empty stack.
```

### Empty Queue

```text
Queue underflow. Cannot dequeue from an empty queue.
```

### Invalid Array Position

```text
Invalid position.
```

### Duplicate Graph Vertex

```text
Vertex already exists.
```

### Invalid Graph Edge

Both vertices must exist before an edge can be created.

# 27. Final Team

| Student ID | Name | Main Responsibility |
|---|---|---|
| 23DA2-0477 | Mohammed Aswin | Array, Searching, Performance and Integration |
| 23DA2-0476 | Mohammed Haazeem | Stack and Queue |
| 23DA2-0539 | Sumaas Ahamed | Linked List and Input Validation |
| 23DA2-0517 | Arsath Hasan | Graph, BFS and DFS |

---

# 28. Conclusion

The **Data Structure and Graph Performance Analyzer** integrates multiple data structures and algorithms into a single Java console application.

The system demonstrates practical implementations of Array, Stack, Queue, Linked List, Searching, and Graph concepts while also showing algorithm steps, execution time, and time complexity.

The project was developed collaboratively using GitHub branches, meaningful commits, Pull Requests, integration, and testing.

---

**CIT300 – Data Structures and Algorithms**  
**Graded Practical Assignment 2**  
**Data Structure and Graph Performance Analyzer**
