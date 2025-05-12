# 💸 Expense Tracker

**Authors:** Adithya Devarapally & Satwik Rao Balguri  
**Technologies:** Python, Tkinter, OpenPyXL, Pandas, Matplotlib

<br />

---

## 📝 Overview

Expense Tracker is a simple yet powerful desktop application designed to help individuals and small businesses monitor and manage their expenses. Built with a user-friendly interface and seamless Excel integration, it enables users to record, categorize, and analyze transactions effectively.

<br />

---

## 🎯 Project Goals

- Help users track their spending habits
- Promote better budgeting and financial planning
- Provide real-time insights through charts and summaries
- Offer a simple, intuitive interface for all levels of users

<br />

---

## 🔧 Features

- 📅 **Add and Edit Transactions:** Input details such as date, description, category, and amount
- 📁 **Excel Integration:** Uses OpenPyXL for persistent data storage
- 📊 **Visual Analytics:** Displays category-wise spending with pie charts using Matplotlib
- 📋 **Data Validation:** Ensures accuracy and consistency
- 🧩 **Category Management:** Dropdown menu for predefined categories
- 💡 **Editable UI:** Easily edit entries directly through the interface

<br />

---

## 🗂️ Dataset

Each transaction includes the following fields:

- **Date**
- **Description**
- **Amount**
- **Category**

The data is stored in an Excel workbook (`expenses.xlsx`) and manipulated using Pandas DataFrames.

<br />

---

## 🖼️ UI Preview

![image](https://github.com/user-attachments/assets/e79ad6e1-203c-4619-bfc2-40ceddbce579)
![image](https://github.com/user-attachments/assets/4ab4b9e8-7b04-4525-8979-2f6018b6732f)


<br />

---

## 🔄 Operational Flow

1. **User Input:** Enter transaction data via the Tkinter GUI  
2. **Validation:** Ensures completeness and correctness  
3. **Storage:** Saved in an Excel sheet using `openpyxl`  
4. **Display:** Rendered in a Treeview widget  
5. **Edit:** Modify selected entries and update Excel  
6. **Visualization:** Generate pie charts of expenses by category  

<br />

---

## 🛠️ Technologies Used

| Library     | Purpose                                       |
|-------------|-----------------------------------------------|
| `tkinter`   | GUI interface for user interaction            |
| `openpyxl`  | Read/write Excel files for data persistence   |
| `pandas`    | Data management and analysis                  |
| `matplotlib`| Generate charts for expense visualization     |

<br />

---


## ⚙️ Setup Instructions

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/ExpenseTracker.git
   cd ExpenseTracker
   ```

2. **Install dependencies**
   ```bash
   pip install -r requirements.txt
   ```

3. **Run the application**
   ```bash
   python main.py
   ```

<br />

---


## ✅ Future Enhancements

- Add user authentication
- Add Proper Database System instead of Excel file
- Enable monthly/weekly reports
- Export to PDF or CSV
- Cloud-based syncing

<br />

---
