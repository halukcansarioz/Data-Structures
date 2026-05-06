# 🔢 Data Structures
### (Fundamental Data Structure Implementations in C, C++, and C#)

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![C](https://img.shields.io/badge/C-00599C?style=flat&logo=c&logoColor=white)](#)
[![C++](https://img.shields.io/badge/C++-00599C?style=flat&logo=c%2B%2B&logoColor=white)](#)
[![C#](https://img.shields.io/badge/C%23-239120?style=flat&logo=c-sharp&logoColor=white)](#)

A collection of fundamental data structure implementations written in C, C++, and C#. This repository serves as both a learning resource and a reference for classic data structures used in computer science.

## 📚 Table of Contents
- [About the Project](#about-the-project)
- [Data Structures Covered](#data-structures-covered)
- [Languages & Tools](#languages--tools)
- [Getting Started](#getting-started)
- [Repository Structure](#repository-structure)
- [Contributing](#contributing)
- [Contact](#contact)
- [License](#license)

---

## About the Project
This project contains simple, well-commented implementations of essential data structures. The code is written in three different languages to highlight syntactical and conceptual differences, making it easier to understand the underlying mechanics regardless of your preferred language.

- **Developer:** Haluk Can SARIÖZ
- **Purpose:** Practice and reference for data structures
- **Languages:** C, C++, C#

---

## Data Structures Covered
While the exact contents may vary, the repository typically includes examples for:

- **Linear Structures**
  - Arrays
  - Linked Lists (Singly, Doubly, Circular)
  - Stacks (Array and Linked List based)
  - Queues (Simple, Circular, Priority)
- **Non‑linear Structures**
  - Trees (Binary Tree, Binary Search Tree)
  - Heaps (Min‑Heap, Max‑Heap)
  - Graphs (Adjacency Matrix / List representations)
- **Other Classic Examples**
  - Hashing
  - Sorting algorithms integrated into structure operations

All implementations include basic operations such as insertion, deletion, traversal, and searching where applicable.

---

## Languages & Tools

| Language | Description |
|----------|-------------|
| **C** | Low‑level, manual memory management with pointers. Focuses on fundamentals. |
| **C++** | Object‑oriented approach, sometimes using templates and the STL for comparison. |
| **C#** | High‑level, managed code with classes and properties. Demonstrates modern language features. |

- **Build/Compile:** GCC (for C/C++), .NET SDK (for C#)
- **Version Control:** Git & GitHub

---

## Getting Started

### Prerequisites
- For C/C++ files: [GCC](https://gcc.gnu.org/) or any C/C++ compiler
- For C# files: [.NET SDK](https://dotnet.microsoft.com/download)

### Running the Examples

**1. Clone the repository:**
```bash
git clone https://github.com/halukcansarioz/Data-Structures.git
cd Data-Structures
```

**2. Compile and run a C/C++ example:**
```bash
gcc linked_list.c -o linked_list
./linked_list
```

**3. Compile and run a C# example:**
```bash
dotnet run   # if a .csproj file exists, or
csc BinarySearchTree.cs && BinarySearchTree.exe  # for Windows
```

> ⚠️ **Note:** Some examples may require manual adjustments depending on your platform (e.g., using `gcc` for C, `g++` for C++, and `dotnet` for C#).

---

## Repository Structure
```text
Data-Structures/
├── C/                         # C language examples
│   ├── linked_list.c
│   ├── stack_array.c
│   ├── binary_tree.c
│   └── ...
├── C++/                       # C++ language examples
│   ├── doubly_linked_list.cpp
│   ├── queue_linked.cpp
│   └── ...
├── CSharp/                    # C# language examples
│   ├── Stack.cs
│   ├── HashTable.cs
│   └── ...
└── README.md
```

*(Note: The actual folder structure may differ; the above is a representative layout.)*

---

## Contributing
Contributions that add new data structures, improve code readability, or fix issues are welcome!

1. **Fork** the repository.
2. Create a **Branch** (`git checkout -b feature/NewStructure`).
3. Make your changes and **Commit** (`git commit -m 'Add: Implementation of AVL tree'`).
4. **Push** your branch (`git push origin feature/NewStructure`).
5. Open a **Pull Request**.

---

<a name="contact"></a>
## Contact
**Haluk Can Sarıöz**
- GitHub: [@halukcansarioz](https://github.com/halukcansarioz)
- Email: [halukcansarioz19@gmail.com](mailto:halukcansarioz19@gmail.com)
- LinkedIn: [Haluk Can Sarıöz](https://www.linkedin.com/in/halukcansarioz)

---

*If this collection helps you, please ⭐ the repository!*

---

## License
This project is licensed under the [MIT License](LICENSE).
