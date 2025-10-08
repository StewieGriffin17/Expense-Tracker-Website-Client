## 💰 Expense Tracker

A full-stack Expense Tracker Web Application built using the MERN tech stack — enabling users to track income and expenses, visualize spending trends, and manage financial data securely with authentication.

This is the repository for frontend(cliend side). Here is the link to backend repository-  
[Backend Repository](https://github.com/StewieGriffin17/Expense-Tracker-Website-Server)

---
## 🚀 Features
- 🔐 **User Authentication** (Register / Login using JWT)
- 💸 **Add, Edit, Delete Expenses, and Incomes**
- 📊 **Dashboard with Analytics and Charts**
- 📅 **View Expenses by Date Range (Last 30 Days, Custom Range)**
- ⚙️ **Secure Backend with MongoDB Atlas**
- 🎨 **Responsive, modern UI powered by Tailwind CSS**

---
## 🧩 Tech Stack

**Frontend:**
- React.js (Vite)
- Axios
- Recharts (for charts)
- Context API / Hooks
- Tailwind CSS

**Backend:**
- Node.js
- Express.js
- MongoDB Atlas
- Mongoose
- JSON Web Token (JWT)
- CORS / dotenv
---
## 📦 Project Structure
```
├── client-side/        
│   ├── src/
│   │   ├──assets/
│   │   ├── components/
│   │   ├── context/
│   │   ├── hooks
│   │   ├── pages/
│   │   ├── utils/
│   │   ├── index.css
│   │   ├── App.jsx
│   │   └── main.jsx
│   ├── package.json
│   ├── package-lock.json
│   ├── index.html
│   └── vite.config.js

├── server-side/        (In Another Repo, link below)
│    ├── config/
│    ├── controllers/
│    ├── middlewares/
│    ├── models/
│    ├── routes/
│    ├── server.js
│    ├── .env
│    └── package.json
```
---
## 🖼️ Screenshots

### Login & Signup Page
<table>
 <tr>
   <td> <img src="/src/assets/screenshot/login.PNG"/></td>
   <td> <img src="/src/assets/screenshot/signup.PNG"/></td>
 </tr> 
</table>

### Dashboard Page
<img src="/src/assets/screenshot/1.PNG"/>
<img src="/src/assets/screenshot/2.PNG"/>

### Income Overview
<img src="/src/assets/screenshot/3.PNG"/>

### Expense Overview
<img src="/src/assets/screenshot/5.PNG"/>

### Add Income & Expense Form
<table>
 <tr>
   <td><img src="/src/assets/screenshot/4.PNG"/></td>
   <td><img src="/src/assets/screenshot/4_1.PNG"/></td>
 
 </tr> 
</table>


---
## 🧑‍💻 Getting Started

### Prerequisites

- Node.js (v16+ recommended)
- npm

### Installation (Frontend)

```bash
# Clone this repository
git clone https://github.com/StewieGriffin17/Expense-Tracker-Website-Client

# Install dependencies
npm install
```

### Installation (Backend)

```bash
# Clone this repository
git clone https://github.com/StewieGriffin17/Expense-Tracker-Website-Server

# Install dependencies
npm i
```
#### Create a .env file inside server-side with - 
```bash
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_secret_key
PORT=8000
```

### Running the Application

```bash
# Run this in both server and client side
npm run dev
```

Then open your browser at [http://localhost:5173](http://localhost:5173).

### Live Link 
https://expense-tracker-website-client.onrender.com/

---

## 🧠API Endpoints

| Method | Endpoint                | Description                 |
| ------ | ----------------------- | --------------------------- |
| POST   | `/api/v1/auth/register` | Register a new user         |
| POST   | `/api/v1/auth/login`    | Login and receive JWT token |
| GET    | `/api/v1/dashboard`     | Fetch dashboard overview    |
| POST   | `/api/v1/income`        | Add a new income            |
| GET    | `/api/v1/income`        | Get all incomes             |
| POST   | `/api/v1/expense`       | Add a new expense           |
| GET    | `/api/v1/expense`       | Get all expenses            |

---

## 📝Author

**Anowarul Asif**  
📧 [Reach Me Here](mailto:anowarul.asif@gmail.com)  
🌐 [Portfolio](https://anowarulasif.netlify.app/) | 🔗 [LinkedIn](https://www.linkedin.com/in/anowarul-asif/) | 🐙 [GitHub](https://github.com/StewieGriffin17)

---

## ⭐ Contribute

Contributions are welcome! Follow these steps:
1. Fork the repository  
2. Create a new branch: `git checkout -b feature-name`  
3. Commit your changes: `git commit -m "Add feature"`  
4. Push to your fork: `git push origin feature-name`  
5. Open a Pull Request  

---

## 🛡️ License

This project is licensed under the [MIT License](https://opensource.org/licenses/MIT) — feel free to use and modify it.
