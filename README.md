# 🧱 Data-Structures
### (Fundamental Data Structure Implementations in C)

A curated collection of fundamental data structure implementations written in C. This repository serves as a hands-on reference and practice log for core computer science concepts.

## 📚 Table of Contents
- [About the Project](#about-the-project)
- [Data Structures Included](#data-structures-included)
- [Tech Stack](#tech-stack)
- [Getting Started](#getting-started)
- [Project Structure](#project-structure)
- [Contributing](#contributing)
- [Contact](#contact)
- [License](#license)

---

## About the Project
This project was built to practice and demonstrate how classic data structures work under the hood in C, with clean and self-contained examples.

- **Developer:** Haluk Can Sarıöz
- **Language:** C
- **Purpose:** Learning, practice, and reference

---

## Data Structures Included

| Category | Description | File(s) |
|---|---|---|
| **Linked List** | Singly linked list, appending, and bidirectional (doubly) linked list implementations | [`Appending List.c`](./Appending%20List.c), [`Bidirectional Linkedlist.c`](./Bidirectional%20Linkedlist.c), [`Linkedlist.c`](./Linkedlist.c), [`Linkedlist2.c`](./Linkedlist2.c) |
| **Stack** | Array-based and linked-list-based stack implementations (LIFO) | [`Stack.c`](./Stack.c), [`Linkedlist stack.c`](./Linkedlist%20stack.c) |
| **Queue** | Queue implementations (FIFO) | [`Queue.c`](./Queue.c), [`Queue2.c`](./Queue2.c) |
| **Binary Search Tree** | Binary Search Tree (BST) operations | [`Binary search tree.c`](./Binary%20search%20tree.c) |
| **Sort** | Data sorting implementation | [`Sort data.c`](./Sort%20data.c) |

---

## Tech Stack

- **Language:** C
- **Compiler:** GCC (`gcc`)
- **Version Control:** Git & GitHub

---

## Getting Started

To compile and run any of the C implementations locally:

### Prerequisites
- GCC (or any standard C compiler)
- Git

### Steps
1. **Clone the repository**
   ```bash
   git clone https://github.com/halukcansarioz/Data-Structures
   cd Data-Structures
   ```

2. **Compile and run a C file**
   ```bash
   # Example: Linked List
   gcc "Linkedlist.c" -o linkedlist
   ./linkedlist

   # Example: Stack
   gcc "Stack.c" -o stack
   ./stack

   # Example: Queue
   gcc "Queue.c" -o queue
   ./queue

   # Example: Binary Search Tree
   gcc "Binary search tree.c" -o bst
   ./bst

   # Example: Sort
   gcc "Sort data.c" -o sort
   ./sort
   ```

---

## Project Structure

```
Data-Structures/
│
├── .gitattributes
├── Appending List.c
├── Bidirectional Linkedlist.c
├── Binary search tree.c
├── LICENSE
├── Linkedlist stack.c
├── Linkedlist.c
├── Linkedlist2.c
├── Queue.c
├── Queue2.c
├── README.md
├── Sort data.c
└── Stack.c
```

---

## Contributing
Contributions that add new data structures, improve code readability, or fix issues are welcome!

1. **Fork** the repository.
2. Create a **Branch** (`git checkout -b feature/NewStructure`).
3. Make your changes and **Commit** (`git commit -m "Add new data structure"`).
4. **Push** your branch (`git push origin feature/NewStructure`).
5. Open a **Pull Request**.

---

## Contact
**Haluk Can Sarıöz**
- GitHub: [@halukcansarioz](https://github.com/halukcansarioz)
- Email: halukcansarioz19@gmail.com

---

## License
Distributed under the MIT License. See [`LICENSE`](./LICENSE) for more information.
