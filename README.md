

# Library Management Application

A scalable library management system built with **Python (Tkinter)** and **MySQL**.  
This application handles a catalogue of **10,000+ book records**, providing efficient search, purchase, and review functionality with indexing for fast queries and input validation to ensure data integrity under concurrent use.

---

## Features

- **Book Catalogue**
  - Add, update, delete, and search books by reference number, title, genre, language, or author.
  - Display book summaries, ratings, and previews.
  - Indexing applied to key fields for faster query response.

- **Customer Management**
  - Add, view, update, and delete customer records.
  - Track customer preferences and purchase history.

- **Staff Management**
  - Add, view, update, and delete staff records.
  - Maintain staff details such as position, salary, and contact information.

- **Purchase System**
  - Customers can buy books through a GUI interface.
  - Generates bills with purchased items and total cost.
  - Input validation ensures consistent records under concurrent transactions.

- **Review System**
  - Add and manage book reviews with ratings.
  - Reviews linked to external charitable sites for awareness campaigns.

---

## Tech Stack

- **Frontend:** Python Tkinter  
- **Backend:** MySQL  
- **Libraries Used:**  
  - `mysql.connector` – Database connectivity  
  - `tkinter` – GUI framework  
  - `webbrowser` – External link handling  
  - `colorama` – Console text formatting  
  - `PIL` – Image handling  
  - `fitz`, `PyPDF2` – PDF viewing and manipulation  

---

## Modules Overview

- **BUY Table**
  - Create, add, and manage purchase records.
  - Generate bills and handle transactions.

- **CUSTOMER Table**
  - CRUD operations for customer records.
  - Display customer details and preferences.

- **STAFF Table**
  - CRUD operations for staff records.
  - Update staff details including salary and position.

- **BOOK Table**
  - CRUD operations for book records.
  - Search by multiple attributes with indexed queries.

- **REVIEW Table**
  - Add, update, and delete reviews.
  - Display reviews with ratings and link to awareness campaigns.

---

## Setup Instructions

1. Install required libraries:
   ```bash
   pip install mysql-connector-python colorama pillow PyMuPDF PyPDF2
   ```
2. Ensure MySQL is installed and running.
3. Create databases:
   - `RECORDS` for customer and staff tables.
   - `LIBRARY` for books, buy, and review tables.
4. Run the Python scripts to initialize tables and launch the application.

---

## Sample Output

- Bookstore interface with titles and prices displayed.  
- Customer and staff records shown in tabular format.  
- Bills generated after purchases.  
- Reviews stored and displayed with ratings.  

---

## Project Highlights

- Built a **MySQL‑backed system** with Python connectivity to manage a catalogue of **10,000+ book records**.  
- Implemented **indexing strategies** to improve query response time.  
- Designed **input validation mechanisms** to maintain data integrity under concurrent use.  
- Developed modular CRUD operations for books, customers, staff, purchases, and reviews.  
- Integrated a **Tkinter GUI** for user interaction, including book previews, billing, and review submission.  
- Added a **social impact feature** linking reviews to charitable sites.  
