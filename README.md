# Next Expense Tracker AI

A smart, modern expense tracking app built with **Next.js**, **Prisma**, and **AI-powered features**, designed to help you manage your finances more intuitively.

---

## 🚀 Features

- **Track expenses & incomes** with user-friendly forms
- **AI categorization & insights** — automatically classify transactions, detect spending habits
- **User authentication & profiles** — secure sign-in, individual dashboards
- **Responsive design** — works smoothly across desktop & mobile
- **SQL database support** (PostgreSQL) with Prisma ORM for reliable data management

---

## 💡 Why This Project

This project aims to simplify personal finance management using modern stack and AI. Whether you're tracking daily coffee, rent, or bills, Expense Tracker lets you:

- See where your money is going
- Set budgets and financial goals
- Get recommendations to save or cut unnecessary spend

---

## 🛠️ Tech Stack

- **Frontend**: Next.js (React)
- **Backend / API**: Next.js API routes or server actions
- **Database**: PostgreSQL, Prisma ORM
- **AI / Logic**: (your AI model / API if used)
- **Deployment**: (e.g. Vercel / Netlify / your choice)

---

## 📦 Getting Started

1. Clone this repo
2. Install dependencies: `npm install`
3. Set up `.env` with DB credentials etc.
4. Run migrations & generate Prisma client:
   ```bash
   npx prisma migrate dev --name init
   npx prisma generate
   ```
