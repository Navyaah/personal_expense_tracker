Personal Expense Tracker:
A full-stack MERN application for managing and tracking personal expenses efficiently. Users can add, edit, delete, and view expenses, categorize them, and monitor their spending habits with a modern UI and secure backend.
Features:
✔ User Authentication – Secure signup/login with JWT
✔ Add & Manage Expenses – Create, update, and delete expense records
✔ Expense Categories – Organize expenses by category (Food, Travel, Bills, etc.)
✔ Dashboard & Charts – Visualize spending using graphs
✔ Responsive UI – Modern and mobile-friendly interface
✔ MongoDB Database – Store user and expense data securely
✔ REST API – CRUD operations for expenses and user management
Tech Stack:
Frontend: React.js, Context API / Redux, Axios, Tailwind CSS or Bootstrap
Backend: Node.js, Express.js
Database: MongoDB (with Mongoose)
Authentication: JWT (JSON Web Token)
Deployment:
Frontend: Vercel / Netlify
Backend: Render / Heroku
Database: MongoDB Atlas
Project Structure:
expense-tracker/
expense-tracker/
```
├── backend/
│   ├── db/
│   │   └── connect.js
│   ├── models/
│   │   ├── Expense.js
│   │   └── User.js
│   ├── routes/
│   │   ├── expenses.js
│   │   └── users.js
│   ├── app.js
│   ├── package.json
│   └── .env
│
├── frontend/
│   ├── src/
│   │   ├── components/
│   │   │   ├── Navbar.js
│   │   │   ├── ExpenseForm.js
│   │   │   └── ExpenseList.js
│   │   ├── context/
│   │   │   └── ExpenseContext.js
│   │   ├── pages/
│   │   │   ├── Dashboard.js
│   │   │   └── Login.js
│   │   ├── services/
│   │   │   └── api.js
│   │   └── App.js
│   ├── package.json
│   └── .env
│
└── README.md
```

Installation & Setup:
1. Clone the Repository
   git clone https://github.com/Kumarsai1434/epense_tracker.git
cd personal-expense-tracker
2. Setup Backend
   cd backend
npm install
Create a .env file in the backend folder and add:
PORT=8000
MONGO_URI=mongodb+srv://kumar123:CiqBmHGMaMUyk9IR@myatlasclusteredu.a5hsxz3.mongodb.net/
JWT_SECRET=a3b743890311ff84c0bd03c0d4c039a1f9857357fbee8b2219a35abc35d53fc185854687e734339de4c1c1f8e1c221daf412f92c85d0153a9e6b2be335fcd892
npm run dev
cd ../frontend
npm install
npm run dev
API Endpoints
Auth Routes:
POST /api/users/register – Register a new user
POST /api/users/login – Login user
Expense Routes:
GET /api/expenses – Fetch all expenses for logged-in user
POST /api/expenses – Add new expense
PUT /api/expenses/:id – Update expense
DELETE /api/expenses/:id – Delete expense
Future Enhancements:
✔ Add budget limits & alerts
✔ Export reports as PDF/Excel
✔ Add dark mode UI
✔ Implement voice-based expense entry
Screenshots:
<img width="1909" height="916" alt="image" src="https://github.com/user-attachments/assets/48b3ccfc-b75e-48b6-8e3e-72c2afca4918" />
<img width="1894" height="906" alt="image" src="https://github.com/user-attachments/assets/0df95224-1333-4eed-9c17-0581943b4541" />
<img width="1893" height="895" alt="image" src="https://github.com/user-attachments/assets/12159b5d-137c-4143-b11e-69ac2ca22c14" />



