# Doubly-Linked-List-DLL-
A custom implementation of a Doubly Linked List in Java, supporting insertion, deletion, bidirectional traversal, and dynamic memory management using Node&lt;T>. Includes methods for adding, removing, searching, printing, and clearing elements. Designed for academic use and technical interviews.
# Doubly Linked List Implementation in Java

## Overview
This project implements a **Doubly Linked List (DLL)** in Java, featuring a dynamic data structure with bidirectional traversal. The implementation provides efficient methods for insertion, deletion, searching, and list traversal, adhering to the List interface.

## Features
- **Insertion & Deletion**: Add and remove elements at the beginning or end of the list.
- **Bidirectional Traversal**: Navigate the list in both forward and backward directions.
- **Efficient Memory Management**: Uses `Node<T>` objects for dynamic allocation.
- **Utility Methods**: Check for emptiness, retrieve size, search for elements, clear the list, and print contents.
- **Console-based Interaction**: A `Menu` system facilitates testing via user input.

## Project Structure
```
DoublyLinkedList/
│── DoublyLinkedList.java   # Implementation of the doubly linked list
│── List.java               # Interface defining list operations
│── Node.java               # Node structure for DLL
│── Menu.java               # Enum for menu-driven operations
│── Main.java               # Entry point to interact with the linked list
```

## Installation & Usage
### Compilation
Compile all Java files:
```sh
javac doublyLinkedList/*.java
```

### Execution
Run the `Main` class to interact with the list via console:
```sh
java doublyLinkedList.Main
```

### Interactive Menu Options
When executed, the program provides a menu where users can:
- Add or remove elements
- Print the list forward or backward
- Check if the list is empty
- Retrieve the list size
- Search for elements

## Example Usage
**Adding Elements:**
```
Choose the method you want to apply:
2: ADDFIRST
Which input would you like to insert?
10
```

**Printing Elements:**
```
7: PRINTFORWARD
10 20 30
```

## Potential Enhancements
- Implement **iterator-based traversal** for better flexibility.
- Extend functionality with **sorting algorithms**.
- Convert into a **thread-safe implementation** using synchronization.

## Author
**Or Adar**  
GitHub: [github.com/Dauban](https://github.com/Dauban)  

---
This project serves as an academic demonstration of linked list data structures and their applications in Java.

