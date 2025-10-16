# 💰 FinPilot – Personal Finance Tracker

FinPilot is a **full-stack personal finance tracker** built with **React.js** (frontend) and **Spring Boot** (backend).  
It empowers users to **track income, categorize earnings with emoji icons, filter by category**, and manage records with **secure CRUD operations**.  
Designed as a **modern fintech project**, WealthWise ensures **data accuracy, real-time feedback, and a seamless user experience**.

---

## 🚀 Features

- 📌 **Add Income Records** – with category selection and emoji-based icons.  
- 🔐 **Secure CRUD Operations** – confirmation modal for deletion, JWT authentication for backend APIs.  
- ⚡ **Real-Time Feedback** – toast notifications powered by `react-hot-toast`.  
- 🗂️ **Category Filtering** – quickly view specific income streams.  
- ✅ **Input Validation** – prevents invalid or incomplete data submissions.  
- ⏳ **Loading States** – Lucide React spinners ensure smooth UX.  
- ☁️ **Full Stack Integration** – Spring Boot APIs + React frontend for end-to-end finance tracking.  

---

## 🛠️ Tech Stack

**Frontend**
- React.js (Hooks + Context API / Redux)
- Lucide React Icons
- react-hot-toast
- TailwindCSS

**Backend**
- Spring Boot (Java 17+)
- Spring Security (JWT-based Authentication)
- MongoDB (NoSQL Database)
- REST APIs

**DevOps**
- Docker
- GitHub Actions (CI/CD)
- Deployed on AWS EC2 / S3 / Vercel  

---

## 📂 Project Structure

```bash
finpilot/
│── backend/           # Spring Boot APIs, Security, MongoDB models
│── frontend/          # React.js app with components, pages, services
│── docker-compose.yml # Containerization setup
│── README.md          # Project documentation
```

---

## ⚙️ Installation & Setup

### 1️⃣ Clone the repository
```bash
git clone https://github.com/your-username/WealthWise.git
cd WealthWise
```

### 2️⃣ Backend (Spring Boot)
```bash
cd backend
./mvnw spring-boot:run
```
Backend will run at: `http://localhost:8080`

### 3️⃣ Frontend (React.js)
```bash
cd frontend
npm install
npm start
```
Frontend will run at: `http://localhost:3000`

---

## 🔐 Environment Variables

Create a `.env` file in the **backend** and **frontend** folders:

**Backend (`backend/.env`)**
```
MONGO_URI=mongodb://localhost:27017/wealthwise
JWT_SECRET=your_jwt_secret
```

**Frontend (`frontend/.env`)**
```
REACT_APP_API_URL=http://localhost:8080/api
```

---

## 📊 Screenshots

### Dashboard  
![Dashboard Screenshot](assets/dashboard.png)

### Add Income Modal  
![Add Income Screenshot](assets/add_income.png)

### Category Filter  
![Category Filter Screenshot](assets/filter.png)

---

## ✅ Future Enhancements
- 📉 Expense Tracking  
- 📊 Analytics & Reports (Monthly / Yearly trends)  
- 🌍 Multi-language Support  
- 💳 Bank Account Integration (OpenBanking APIs)  

---

## 🤝 Contributing

1. Fork the repo  
2. Create a new branch (`feature/xyz`)  
3. Commit changes  
4. Push and create a Pull Request  

---

## 📜 License
This project is licensed under the **MIT License**.  

---

## 👨‍💻 Author
**Rishabh Aggarwal**  
- [LinkedIn](https://linkedin.com/in/your-profile)  
- [GitHub](https://github.com/your-username)  
