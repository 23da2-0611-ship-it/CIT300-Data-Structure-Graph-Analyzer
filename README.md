# Data Structure & Graph Performance Analyzer

**Module:** CIT300 Data Structures and Algorithms - Graded Practical Assignment 2 (Week 12)
**Language:** Java (console application)

## Project Description
A single integrated console application that demonstrates arrays, stacks, queues, linked lists,
searching algorithms, graphs (BFS/DFS) and a performance/complexity comparison. Every menu validates
input and handles empty / full structures without crashing.

## Team Members

### Member 1
- **Student Name:** Reeha Rafees
- **Student ID:** 23DA2-0614
- **Email:** 23da2-0614@sltc.ac.lk
- **Assigned Responsibility:** Array and Searching
- **Individual Contribution:**
  - Implemented `IntArray` operations and `ArrayMenu`.
  - Implemented linear search and binary search in `SearchAlgorithms`.
  - Built `SearchMenu` and tested search step/time comparisons.
  - Helped integrate and test these features with the main menu.

### Member 2
- **Student Name:** Jesla Nusky
- **Student ID:** 23DA2-0566
- **Email:** 23da2-0566@sltc.ac.lk
- **Assigned Responsibility:** Stack and Queue
- **Individual Contribution:**
  - Implemented `ArrayStack` push, pop, peek and display operations.
  - Implemented `ArrayQueue` enqueue, dequeue, front/peek and display operations.
  - Built `StackMenu` and `QueueMenu`.
  - Tested empty/full conditions and integrated these menus.

### Member 3
- **Student Name:** Nusla Risal
- **Student ID:** 23DA2-0633
- **Email:** 23da2-0633@sltc.ac.lk
- **Assigned Responsibility:** Linked List and Performance Comparison
- **Individual Contribution:**
  - Implemented `SinglyLinkedList` insertion, deletion, searching, reversing and display operations.
  - Built `LinkedListMenu`.
  - Implemented `PerformanceAnalyzer` comparisons for search, insertion and graph traversal.
  - Tested linked-list and performance features.

### Member 4
- **Student Name:** Afqa Aswer
- **Student ID:** 23DA2-0611
- **Email:** 23da2-0611@sltc.ac.lk
- **Assigned Responsibility:** Graph, Main Menu and Integration
- **Individual Contribution:**
  - Implemented `Graph` using an adjacency list, including vertex/edge operations, BFS, DFS and shortest path.
  - Built `GraphMenu` and integrated all components through `Main`.
  - Implemented input validation with `InputHelper` and result display with `ResultLog`.
  - Helped with integration and final testing.

> **Important:** Make sure each responsibility and contribution above matches the work actually completed by that member. Every member should be able to explain and demonstrate their own contribution in the video.

## Technologies Used
- Java 8 or higher (developed with JDK 21)
- Git and GitHub

## Main System Features
| Menu | Feature |
|------|---------|
| 1 | Array: insert, insert at position, delete, search, sort, random fill, display |
| 2 | Stack: push, pop, peek, display (overflow/underflow handled) |
| 3 | Queue: enqueue, dequeue, peek, display (circular queue, overflow/underflow handled) |
| 4 | Linked list: insert head/tail/position, delete, search, reverse, display |
| 5 | Searching: linear, binary, side-by-side comparison with steps and time |
| 6 | Graph: add vertex/edge, display, BFS, DFS, shortest path, sample graph |
| 7 | Performance comparison table (steps, time, complexity) |
| 8 | Display all recorded results |

## Complexity Summary
| Operation | Complexity |
|-----------|-----------|
| Linear search | O(n) |
| Binary search (sorted array) | O(log n) |
| Array insert/delete at position | O(n) |
| Stack push/pop/peek, Queue enqueue/dequeue/peek | O(1) |
| Linked list insert at head | O(1) |
| Linked list search / insert at tail | O(n) |
| Graph BFS / DFS (adjacency list) | O(V + E) |

## How to Run
```bash
# from the project root
mkdir out
javac -d out src/*.java
java -cp out Main
```
On Windows (PowerShell) use `mkdir out` then the same `javac` / `java` commands.
An IDE (IntelliJ IDEA / Eclipse / VS Code) also works: open the folder and run `Main`.

## Project Structure
```
src/
  Main.java                 main menu and integration
  InputHelper.java          validated console input
  ResultLog.java            Display All Results
  IntArray.java             array structure
  SearchAlgorithms.java     linear and binary search
  ArrayMenu.java / SearchMenu.java
  ArrayStack.java / StackMenu.java
  ArrayQueue.java / QueueMenu.java
  SinglyLinkedList.java / LinkedListMenu.java
  Graph.java / GraphMenu.java
  PerformanceAnalyzer.java  performance comparison
```
