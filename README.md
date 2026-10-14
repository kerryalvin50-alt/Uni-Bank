# Uni-Bank
students banking system
🎓 Student Banking System (UniBank)

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Build Status](https://img.shields.io/badge/build-passing-brightgreen.svg)]()
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](http://makeapullrequest.com)

**UniBank** is an open-source, student-focused banking platform designed to empower university students with financial literacy, smart budgeting, low-fee account management, and seamless peer-to-peer campus payments.



## 📌 Project Overview

Navigating personal finance while in college can be overwhelming. Standard banking applications often lack features tailored specifically to student life—such as splitting tuition/housing costs, tracking meal-plan spending, and managing student loans or grants.

**UniBank** bridges this gap by providing an intuitive, fee-transparent banking ecosystem customized for higher education students.

---

## ✨ Key Features

* **📱 Student-Centric Account Dashboard:** Track checking, savings, and campus meal-card allowances in one unified view.
* **💸 Zero-Fee Peer-to-Peer (P2P) Payments:** Instant, zero-fee transfers between students for rent, groceries, study materials, or dining out.
* ** Smart Budgeting & Expense Analytics:** Categorizes spending automatically (e.g., *Books & Supplies*, *Tuition*, *Entertainment*, *Dining*).
* **🎯 Savings Goals ("Pots"):** Create target goals for upcoming semester fees, spring break trips, or emergency funds.
* **🔒 Low-Balance & Overdraft Alerts:** Proactive notifications to help students avoid costly bank overdraft fees.
* **🎓 Financial Literacy Hub:** Built-in micro-courses and quizzes on credit building, budgeting, and managing student loan interest.

---

## 🛠️ Tech Stack

| Layer | Technology |
| :--- | :--- |
| **Frontend** | React / Next.js / Tailwind CSS |
| **Mobile App** | React Native / Flutter |
| **Backend API** | Node.js (Express) / Python (FastAPI) |
| **Database** | PostgreSQL / MongoDB |
| **Authentication** | OAuth 2.0 / JWT / University SSO Integration |
| **Security** | AES-256 Encryption, PCI-DSS compliance mock layer |

---

## 🚀 Quick Start & Installation

Follow these instructions to get a local copy running on your machine for development and testing.

### Prerequisites
* [Node.js](https://nodejs.org/) (v18.0 or higher)
* [Git](https://git-scm.com/)
* [PostgreSQL](https://www.postgresql.org/) or [Docker](https://www.docker.com/)

### 1. Clone the Repository
```bash

## ARCHITECTURE STRUCTURE.

[ University Student ] ---> [ React/Mobile Frontend ]
                                   │
                                   ▼
                         [ API Gateway / Auth ]
                                   │
                ┌──────────────────┴──────────────────┐
                ▼                                     ▼
     [ Core Banking API ]                    [ Analytics Engine ]
                │                                     │
                └──────────────────┬──────────────────┘
                                   ▼
                         [ PostgreSQL Database ]













git clone [https://github.com/your-username/student-banking-app.git](https://github.com/your-username/student-banking-app.git)
cd student-banking-app
