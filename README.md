# 💰 AI Personal Finance Tracker & Advisor

An AI-assisted expense tracking system designed for students to monitor spending, analyze financial behavior, and receive actionable savings recommendations.

---

## 🚀 Problem Statement

Students often overspend due to lack of structured expense tracking and delayed feedback on their financial habits. Most existing tools are either too complex or not tailored for student needs.

This project aims to provide a **simple, automated, and intelligent financial tracking system**.

---

## 🎯 Project Objective

To build a system that:

* Tracks daily expenses
* Automatically categorizes spending using AI
* Analyzes spending patterns
* Detects overspending behavior
* Provides personalized financial recommendations
* Visualizes data through dashboards and reports

---

## 📌 System Scope

### ✅ In Scope:

* Expense input via custom frontend
* AI-based expense categorization
* Rule-based spending analysis
* Budget tracking and alerts
* Dashboard visualization
* Monthly financial report generation

### ❌ Out of Scope:

* Bank account integration
* Real-time transaction tracking
* Predictive financial modeling
* Investment advisory

---

## 🧾 Expense Categories

The system uses predefined categories for structured analysis:

* Food
* Transport
* Entertainment
* Utilities
* Education
* Shopping

---

## 📊 Budget Thresholds

Each category has a predefined spending limit:

| Category      | Threshold |
| ------------- | --------- |
| Food          | ≤ 35%     |
| Transport     | ≤ 20%     |
| Entertainment | ≤ 15%     |
| Shopping      | ≤ 15%     |
| Utilities     | ≤ 10%     |

If these thresholds are exceeded, the system flags overspending.

---

## 💰 Savings Target Logic

* Target savings: **10–15% of monthly income**

### Rules:

* If total spending > 90% → Alert
* If savings < 10% → Recommendation triggered

---

## 📈 Spending Pattern Detection Rules

The system uses rule-based logic to identify patterns:

### 1. Weekly Spike Detection

* If current week spending > previous week by **20%**

### 2. Category Overspending

* If any category exceeds its threshold percentage

### 3. Frequent Transactions

* Multiple small transactions indicating impulse spending

---

## 🤖 AI-Based Categorization

Expenses are automatically categorized using a free LLM API.

### Example:

**Input:**
₹250 Zomato lunch

**Output:**
Food

---

## 🔄 System Workflow

User Input (Web App)
↓
Backend API
↓
AI Categorization (Free API)
↓
Database (Google Sheets / Firebase)
↓
Analysis (Rules & Calculations)
↓
Dashboard (Charts & Alerts)
↓
Report Generation (Canva PDF)

---

## 🏗️ System Architecture

The system follows a modular architecture:

* **Frontend Layer:** Custom web interface (React)
* **Backend Layer:** Node.js API for processing and integration
* **AI Layer:** Free LLM API for categorization
* **Data Layer:** Google Sheets / Firebase
* **Analysis Layer:** Rule-based logic
* **Visualization Layer:** Charts and reports

---

## 🛠️ Tech Stack

* **Frontend:** React (built using Cursor / Antigravity)
* **Backend:** Node.js (planned)
* **Database:** Google Sheets / Firebase
* **AI API:** OpenRouter / Gemini (free tier)
* **Visualization:** Chart.js / Recharts
* **Automation:** n8n / Google Apps Script (optional)
* **Reporting:** Canva

---

## 📂 Project Structure

/frontend → UI for expense input and dashboard
/backend → API and processing logic (planned)
/docs → Architecture diagrams and documentation

---

## 📊 Sample Data Structure

| Date     | Amount | Description  | Category  | Week | Month |
| -------- | ------ | ------------ | --------- | ---- | ----- |
| 01-04-26 | 250    | Zomato lunch | Food      | 1    | April |
| 02-04-26 | 100    | Bus fare     | Transport | 1    | April |

---

## ⚠️ Limitations

* Uses rule-based analysis (not predictive ML)
* Depends on input accuracy
* AI categorization may require manual override
* Free API may have rate limits

---

## 🔮 Future Enhancements

* Bank API integration
* Predictive spending analysis
* Mobile app version
* Real-time notifications
* Advanced AI financial advisor

---

## 📌 Status

🚧 Milestone 1 Completed:

* Problem definition
* System design
* Rules and thresholds
* Architecture planning
* Initial repository setup

---
