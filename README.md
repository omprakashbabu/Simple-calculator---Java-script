# Simple Calculator (Frontend + Backend)

A basic calculator project with a **frontend (HTML, CSS, JavaScript)** and a **backend (Node.js + Express)**.  
The frontend provides the user interface, while the backend performs the calculations.

---

## 📂 Project Structure
calculator-project/
│── frontend/
│ ├── index.html # UI for the calculator
│ ├── script.js # Handles user interaction & fetches result
│ └── style.css # Styling
│
│── backend/
│ └── server.js # Node.js + Express backend for calculations
│
│── package.json # Dependencies (express, cors, body-parser)

---

## 🚀 How to Run (Local)

### 1. Clone the repository
```bash
git clone https://github.com/your-username/calculator-project.git
cd calculator-project

### 2. Setup and run backend
cd backend
npm install express cors body-parser
node server.js

Server will run at: http://localhost:5000

### Open frontend
Go to the frontend/ folder.
Open index.html in your browser.
Enter two numbers, select an operator, and click Calculate.
