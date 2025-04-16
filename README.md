Python ORM with SQLAlchemy – Beginner Project
Welcome to this beginner-friendly Python ORM (Object-Relational Mapping) project using SQLAlchemy! This repo is designed to help you learn how to build and interact with databases in Python without writing raw SQL.

🎥 Watch the full video tutorial here
👉 YouTube Video Link (Replace with your actual video link)

📚 What You'll Learn
- ✅ What Python ORM is and how it works
- ✅ The difference between SQLAlchemy Core and SQLAlchemy ORM
- ✅ What a one-to-many relationship looks like in code
- ✅ How foreign keys connect tables
- ✅ How to structure an ORM project using clean, modular Python files
- ✅ How to:
-   --Create a database (SQLite)
-   --Define models using classes
-   --Insert, filter, update, and delete records
-   --Query relationships using .filter() and .join()
-   --Test everything step-by-step with main.py

🛠 Project Overview
This project simulates a mini inventory system involving:
- Suppliers
- Products

Each product belongs to one supplier, while a supplier can provide many products – this is a classic one-to-many relationship.

📁 Folder Structure

📦 Python-ORM-SQLAlchemy-Tutorial/
- ├── database.py           # Sets up SQLite database connection
- ├── models.py             # Defines tables and one-to-many relationships
- ├── create_tables.py      # Creates the actual tables from models
- ├── insert_records.py     # Inserts sample suppliers and products
- ├── join.py               # Displays products and their suppliers
- ├── filter.py             # Filters products with low stock
- ├── update.py             # Updates product prices
- ├── delete.py             # Deletes a product from inventory
- ├── main.py               # Runs all tasks in sequence for testing
▶️ How to Run
1. Clone the Repo
- git clone https://github.com/your-username/python-orm-sqlalchemy-tutorial.git
- cd python-orm-sqlalchemy-tutorial
2. (Optional) Create a Virtual Environment
- python -m venv venv
- source venv/bin/activate  # On Windows: venv\Scripts\activate
3. Install Requirements
- pip install sqlalchemy
4. Run the Main Script
- python main.py
- --Each step (create, insert, query, filter, update, delete) will run in sequence with helpful printouts.

💡 Bonus Tips
You can also run each script independently to test parts one at a time.

Open inventory.db in PyCharm’s Database Tool to view tables and records.

Every script includes an if __name__ == '__main__' block for modular execution.

📺 Related Resources
🎥 Watch the full tutorial on YouTube

📖 Read the companion blog post

📬 Feedback & Contributions
If you found this useful, feel free to star the repo and share it with others.
Pull requests and feedback are welcome!

🏷️ Tags
- python
- sqlalchemy
- orm
- sqlite
- beginner
- tutorial
- inventory-system
- one-to-many
- foreign-key
- crud

