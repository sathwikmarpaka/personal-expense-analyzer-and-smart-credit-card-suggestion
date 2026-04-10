# 💳 Personal Expense Analyzer with Smart Credit Card Suggestions

## 📌 Overview
This project is a full-stack web application that analyzes user spending from bank statements and provides intelligent credit card recommendations based on spending habits, age, and CIBIL score.

---

## 🚀 Features

- 📂 Upload bank statement (PDF)
- 📊 Automatic transaction extraction and categorization
- 📈 Pie chart visualization of spending (with percentages)
- 💡 Smart credit card recommendations
- 🔐 Eligibility check (Age & CIBIL score)
- 🎯 Category-wise spending breakdown

---

## 🛠️ Tech Stack

### 🔹 Frontend
- React.js
- HTML5, CSS3
- Chart.js (Data Visualization)

### 🔹 Backend
- FastAPI (Python)
- PDF parsing
- Custom transaction classification logic

---

## 📊 How It Works

1. User uploads bank statement
2. System extracts transactions
3. Categorizes spending (Food, Fuel, Shopping, etc.)
4. Displays:
   - Total spending
   - Pie chart analysis
   - Category breakdown
5. Recommends best credit cards based on spending patterns

---

## 🔐 Eligibility Criteria

- Age ≥ 21
- CIBIL Score ≥ 700

If not eligible, only spending analysis is shown.

---

## ▶️ Run the Project

### Backend
```bash
cd backend
venv\Scripts\activate
uvicorn main:app --reload






