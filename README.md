Personal Expense Tracker: A full-stack MERN application for managing and tracking personal expenses efficiently. Users can add, edit, delete, and view expenses, categorize them, and monitor their spending habits with a modern UI and secure backend. Features: ✔ User Authentication – Secure signup/login with JWT ✔ Add & Manage Expenses – Create, update, and delete expense records ✔ Expense Categories – Organize expenses by category (Food, Travel, Bills, etc.) ✔ Dashboard & Charts – Visualize spending using graphs ✔ Responsive UI – Modern and mobile-friendly interface ✔ MongoDB Database – Store user and expense data securely ✔ REST API – CRUD operations for expenses and user management Tech Stack: Frontend: React.js, Context API / Redux, Axios, Tailwind CSS or Bootstrap Backend: Node.js, Express.js Database: MongoDB (with Mongoose) Authentication: JWT (JSON Web Token) Deployment: Frontend: Vercel / Netlify Backend: Render / Heroku Database: MongoDB Atlas Project Structure: expense-tracker/ expense-tracker/
```├── backend/
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

Clone the Repository git clone https://github.com/Navyaah/personal_expense_tracker.git cd personal-expense-tracker
Setup Backend cd backend npm install Create a .env file in the backend folder and add: MONGO_URI=mongodb+srv://navya123:navya123@cluster0.ypmkrrz.mongodb.net/
JWT_SECRET=a3b743890311ff84c0bd03c0d4c039a1f9857357fbee8b2219a35abc35d53fc185854687e734339de4c1c1f8e1c221daf412f92c85d0153a9e6b2be335fcd892
PORT=8000 npm run dev cd ../frontend npm install npm run dev API Endpoints Auth Routes: POST /api/users/register – Register a new user POST /api/users/login – Login user Expense Routes: GET /api/expenses – Fetch all expenses for logged-in user POST /api/expenses – Add new expense PUT /api/expenses/:id – Update expense DELETE /api/expenses/:id – Delete expense Future Enhancements: ✔ Add budget limits & alerts ✔ Export reports as PDF/Excel ✔ Add dark mode UI ✔ Implement voice-based expense entry Screenshots:
<img width="515" height="750" alt="image" src="https://github.com/user-attachments/assets/4f9d2453-87c1-4a94-b564-6719256eb666" />
