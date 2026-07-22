# Terminal-Based Library Management System

A robust, terminal-based library management system written entirely in C. It provides a complete workflow for managing book inventories, student requests, and user authentication using dynamic data structures and persistent file storage. 

Designed with a focus on memory efficiency and clean architecture, this project demonstrates practical applications of pointers, linked lists, and binary file I/O.

## 🚀 Key Features

*   **Role-Based Access Control:** Secure login system with distinct interfaces and permissions for **Librarians** (admins) and **Students** (users).
*   **Dynamic Data Structures:** Built using **Singly Linked Lists** to manage users and books dynamically, ensuring efficient memory allocation without hardcoded limits.
*   **Data Persistence:** Uses **Binary File I/O** (`.dat` files) to securely save and load the system's state (users, books, and requests) across different executions.
*   **Smart Borrowing Logic:** Automatically validates book availability and restricts students to borrowing only **major-specific** or general books.
*   **Request Management:** Librarians have a dedicated dashboard to **review, accept, or decline** incoming student requests.
*   **Comprehensive Tracking:** Maintains a detailed **borrowing history** for every book, tracking exactly which students have checked it out over time.

## 🛠️ Technical Stack

*   **Language:** C
*   **Core Concepts:** Pointers, Dynamic Memory Allocation (`malloc`/`free`), Structs, Singly Linked Lists
*   **Storage:** Binary & Text File I/O (`fread`, `fwrite`, `fprintf`, `fscanf`)

*Note: On the first run, ensure the librarian authentication file (`librarian.txt`) is configured to access the admin panel.*
