# 💰 Expense Tracker

A simple, clean expense tracker built with React that helps you keep track of your income and expenses in real time.

## ✨ Features

- Add new transactions (income or expense)
- Automatically calculates and displays your current balance
- See a breakdown of total income vs. total expenses
- View a list of all transactions
- Delete any transaction with one click
- Built using React's Context API and `useReducer` for state management (no external state library needed)

## 🛠️ Built With

- **React** – UI library
- **Context API + useReducer** – global state management
- **CSS** – styling

## 📂 Project Structure
src/
├── App.js # Root component
├── AppReducer.js # Reducer logic for state updates
├── GlobalState.js # Context provider for app-wide state
├── Header.js # App header
├── Balance.js # Displays current balance
├── IncomeExpenses.js # Displays income and expense totals
├── TransactionList.js # Renders list of transactions
├── Transaction.js # Single transaction item
├── AddTransaction.js # Form to add a new transaction
└── App.css # Styles


## 🚀 Getting Started

### 1. Clone the repository
```bash
git clone https://github.com/dikshaverma469/Expense-Tracker.git
cd Expense-Tracker
```

### 2. Install dependencies
```bash
npm install
```

### 3. Run the app
```bash
npm start
```
Open [http://localhost:3000](http://localhost:3000) to view it in your browser.

## 📝 How It Works

1. Enter a transaction description and amount.
2. Use a **positive** number for income and a **negative** number for an expense.
3. Click **Add transaction** — the balance, income total, and expense total update instantly.
4. Click the **x** next to any transaction to remove it.

## 📌 Future Improvements

- Persist transactions with local storage or a backend/database
- Add categories/tags for transactions
- Add charts for spending trends
- Add date filters

## 👤 Author

**Diksha Verma**
- GitHub: [@dikshaverma469](https://github.com/dikshaverma469)
- LinkedIn: [diksha-verma-b890ab294](https://www.linkedin.com/in/diksha-verma-b890ab294)

## 📄 License

This project is open source and available under the [MIT License](LICENSE).
