PyCart: Python Console E-commerce CLI

 Problem Statement

The challenge is to build a functional, self-contained application using only fundamental Python programming concepts (dictionaries, lists, functions, and standard I/O). The goal is to successfully simulate the core business logic of an e-commerce platform, specifically focusing on product display, cart management, and inventory integrity, without relying on complex external libraries or frameworks.

 Scope of the Project

The scope of the PyCart project is limited to a command-line interface (CLI) application.

Included:

Core Logic: Inventory management, cart state, total calculation, and input validation.

Environment: Pure Python 3 environment (no external libraries required).

Persistence: Data (catalog) is stored as global dictionaries (in-memory) for the duration of the session.

Excluded:

Graphical User Interface (GUI) or Web Interface.

Database integration (e.g., SQLite, PostgreSQL).

User Authentication or complex order history features.

 Target Users

This project primarily targets:

First-Semester Computer Science Students: Individuals learning fundamental data structures (dictionaries, lists) and procedural/modular programming.

Beginner Python Developers: Those seeking a practical, self-contained project to solidify their grasp of Python basics and simple application development flow.

 High-Level Features

Catalog Management: Displays a complete list of available products, IDs, prices, and current stock.

Cart and Order Processing: Provides functionality to add, remove, and review items in the current shopping cart.

Inventory Control: Implements checks to prevent overselling and correctly reduces stock levels upon successful checkout.

Financial Summary: Calculates real-time subtotals and the final order total.

Robust Input: Uses error handling (try-except) to gracefully manage invalid user input.

 How to Run the Application

Since this project uses only standard Python libraries (sys), no external installations are required.

Save the file: Save the code as shopping_app.py.

Open Terminal: Navigate to the directory where you saved the file.

Execute: Run the application using the Python interpreter:

python shopping_app.py


Interaction: Follow the on-screen menu prompts (1-6) to interact with the system.
