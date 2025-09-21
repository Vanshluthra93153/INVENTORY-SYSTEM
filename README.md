📌 Overview

This project is a C++ console-based Inventory Management System that allows users to manage a collection of items efficiently.
It supports operations such as insertion, deletion, searching, and different ways of displaying inventory data (row-major, column-major, and sparse representation).

The system demonstrates array-based data structures, time/space complexity analysis, and basic inventory operations.

🚀 Features

Add new items (ID, name, quantity, price).

Delete items by ID.

Search items by ID or name.

Display all items in inventory.

View Price-Quantity table in:

Row-major order

Column-major order

Sparse representation for rarely restocked items (quantity ≤ 5).

🛠️ Technologies Used

Language: C++ (C++11 and above compatible)

Compiler: g++ / MSVC / Clang

📂 Project Structure
inventory_system.cpp   # Main program (all logic + driver code)
README.md              # Documentation

⚙️ Compilation & Execution

Open a terminal and navigate to the project directory.

Compile the program:

g++ inventory_system.cpp -o inventory


Run the executable:

./inventory
