# 💰 AI Personal Finance Tracker & Advisor

An AI-assisted expense tracking system designed for students to monitor spending, analyze financial behavior, and receive actionable savings recommendations.

---

## 🚀 Problem Statement

Students often overspend due to lack of structured expense tracking and delayed feedback on their financial habits. Most existing tools are either too complex or not tailored for student needs.

This project aims to provide a **simple, automated, and intelligent financial tracking system**.

---

## 🎯 Project Objective

To build a system that:
- Tracks daily expenses
- Automatically categorizes spending using AI
- Analyzes spending patterns
- Detects overspending behavior
- Provides personalized financial recommendations
- Visualizes data through dashboards and reports

---

## 📌 System Scope

### ✅ In Scope:
- Expense input via custom frontend
- AI-based expense categorization
- Rule-based spending analysis
- Budget tracking and alerts
- Dashboard visualization
- Monthly financial report generation

### ❌ Out of Scope:
- Bank account integration
- Real-time transaction tracking
- Predictive financial modeling
- Investment advisory

---

## 🧾 Expense Categories

The system uses predefined categories for structured analysis:

- Food  
- Transport  
- Entertainment  
- Utilities  
- Education  
- Shopping  

---

## 📊 Budget Thresholds

Each category has a predefined spending limit:

| Category       | Threshold |
|---------------|----------|
| Food          | ≤ 35%    |
| Transport     | ≤ 20%    |
| Entertainment | ≤ 15%    |
| Shopping      | ≤ 15%    |
| Utilities     | ≤ 10%    |

If these thresholds are exceeded, the system flags overspending.

---

## 💰 Savings Target Logic

- Target savings: **10–15% of monthly income**

### Rules:
- If total spending > 90% → Alert
- If savings < 10% → Recommendation triggered

---

## 📈 Spending Pattern Detection Rules

The system uses rule-based logic to identify patterns:

### 1. Weekly Spike Detection
- If current week spending > previous week by **20%**

### 2. Category Overspending
- If any category exceeds its threshold percentage

### 3. Frequent Transactions
- Multiple small transactions indicating impulse spending

---

## 🤖 AI-Based Categorization

Expenses are automatically categorized using a free LLM API.

### Example:

**Input:**