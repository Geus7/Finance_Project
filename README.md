# 💰 Personal Finance Tracker

A full-stack personal finance tracker built using Java for the backend (console version) and a modern responsive web interface using HTML, CSS, and JavaScript. Track income, expenses, savings, and get insights into your financial health.

---

## 🚀 Features

- 📥 Add income and expense entries
- 📊 Monthly expense graphs (UI)
- 🔁 Category-wise spending breakdown
- 📈 Income vs Expense comparison
- 💾 Save/load transactions using CSV
- 📆 Auto date-stamping for transactions
- 💸 Rupee (₹) currency support
- 🎨 Color-coded output and modern UI
- 🧠 Modular Java OOP design

---

## 🧱 Project Structure
<pre><code> Finance_Project/ │ ├── src/ │ ├── model/ │ │ ├── Transaction.java │ │ └── TransactionType.java │ │ │ ├── service/ │ │ └── TransactionManager.java │ │ │ ├── storage/ │ │ └── StorageManager.java │ │ │ ├── web-ui/ │ │ ├── index.html │ │ ├── style.css │ │ └── script.js │ │ │ ├── Main.java │ └── transactions.csv │ ├── README.md └── .gitignore </code></pre>

---

## 🛠️ Prerequisites

- Java 8 or higher
- Any modern browser (Chrome, Firefox, etc.)
- A code editor (VS Code recommended)

---

## 🖥️ Running the Console Version

1. **Navigate to `src/` directory**
   ```bash
   cd src

2. **Compile all Java files**

```
javac model/*.java service/*.java storage/*.java Main.java
```
3. **Run the program**

```
java Main
```
4.**Transactions will be saved to transactions.csv .**

<img width="1919" height="859" alt="image" src="https://github.com/user-attachments/assets/4e34a009-8fe8-41a4-b118-544534931f35" />

5.**Testing with input.**

<img width="802" height="861" alt="image" src="https://github.com/user-attachments/assets/79cf76ce-c8a7-49cb-b241-7721abb38994" />

