# 💰 Expense Tracker App (Android Project)

A simple and clean Android application to manage daily expenses using **Java, XML, and SQLite**.

---

## 📱 Features

- ➕ Add Expense (Title, Category, Amount, Date)
- 📋 View all expenses in RecyclerView
- 💰 Auto total calculation
- 🗑️ Delete expense (Long press)
- 💾 Local SQLite database storage
- 🎨 Simple and clean UI

---

## 🛠️ Tech Stack

- Java (Android)
- XML (UI Design)
- SQLite Database
- RecyclerView
- AlertDialog

---

## 📂 Project Structure

com.example.expensetracker  
├── MainActivity.java  
├── AddFragment.java  
├── ViewFragment.java  
├── Expense.java  
├── ExpenseAdapter.java  
├── DatabaseHelper.java  
│  
├── activity_main.xml  
├── fragment_add.xml  
├── fragment_view.xml  
├── expense_item.xml  
├── bottom_nav_menu.xml  

---

## 🚀 How It Works

### ➕ Add Expense
- Enter Title, Category, Amount, Date
- Click Save
- Data stored in SQLite database

---

### 📋 View Expense
- Shows all saved expenses in list format
- Displays Title, Amount, Date

---

### 💰 Total Calculation
```sql
SELECT SUM(amount) FROM expense
```

---

### 🗑️ Delete Expense
- Long press item
- Confirmation dialog appears
- On Yes → item deleted

---

## 🎨 UI Design

- Pink theme accent (#E91E63)
- Card-style expense items
- Clean spacing and simple layout
- Bottom Navigation for easy switching

---

<img width="365" height="800" alt="SS1" src="https://github.com/user-attachments/assets/22166682-1094-40f9-b6e3-c9475fa770cc" />

<img width="365" height="800" alt="SS2" src="https://github.com/user-attachments/assets/f4fe540f-84ae-44ad-95a1-54f450373891" />

---

## 🔮 Future Improvements

- Edit expense feature
- Monthly reports
- Charts/graphs
- Firebase backup
- Login system

---

## 👩‍💻 Developer

Made by **Dikshita Mittal** ✨
