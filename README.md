# Expense Tracker – Vue

A Vue 3 application for tracking income and expenses, with a running balance and browser-based persistence.

**[Try it!](https://cheery-platypus-086e21.netlify.app)**

<img src="public/screen.png" alt="Expense Tracker" width="500">


---

## Features

- Add and delete transactions
- Running balance with separate income and expense totals
- Data persists in the browser across sessions
- Form validation with toast notifications
- Component-based architecture

---

## Tech Stack

- **Vue 3** with the Composition API
- **Vite** for development and bundling
- **vue-toastification** for notifications
- **localStorage** for persistence

---

## How It Works

Transactions are stored in the browser's local storage, so the app runs entirely client-side with no server required. Positive amounts count as income, negative amounts as expenses, and the balance updates reactively as transactions change.

---

## Project Structure

```
├── src/
│     ├── components/
│     │     ├── Header.vue
│     │     ├── Balance.vue
│     │     ├── IncomeExpenses.vue
│     │     ├── TransactionList.vue
│     │     └── AddTransaction.vue
│     ├── assets/
│     ├── App.vue
│     └── main.js
├── public/
├── index.html
├── vite.config.js
└── package.json
```

---

## Setup

### Install dependencies

```bash
npm install
```

### Start the development server

```bash
npm run dev
```

The app runs at `http://localhost:5173/`.

### Build for production

```bash
npm run build
```

---

## Related

The same concept was later rebuilt as a full-stack Django application with a REST API, database, and authentication: [ExpenseTracker-Django](https://github.com/ShahadAlkamli/ExpenseTracker-Django).

---

## License

This repository is provided for academic and learning purposes.
