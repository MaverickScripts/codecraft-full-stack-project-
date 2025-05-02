# codecraft-full-stack-project-

# 🚀 CodeCraft Crew – Student Team Members Management Application

Welcome to the **CodeCraft Crew**'s official full-stack web application! This project was developed as part of our Full Stack Development (FSD) coursework to manage team members using React, Node.js, Express, and MongoDB.

---

## 📌 Project Overview

A web application designed to:
- Add new team members with role-specific details and images
- View all members via an organized card layout
- Access detailed information for each member
- Highlight team structure with role-based UI interaction

---

## 👥 Team Members

| Name                  | Reg No.              | Role             |
|-----------------------|----------------------|------------------|
| Shreyas Chowdhury     | RA2211027010028      | 👨‍💻 Developer     |
| Sachin Rajesh Pal     | RA2211027010061      | 🧠 Scrum Master   |
| Mufeeda O             | RA2211027010028      | 📝 Content Coordinator |

---

## 🛠️ Tech Stack

- **Frontend:** React.js
- **Backend:** Node.js + Express
- **Database:** MongoDB (with MongoDB Compass)
- **HTTP Client:** Axios
- **Dev Tools:** Visual Studio Code

---

## 🌐 Features

### ✅ Home Page
- Team intro and welcome message
- Navigation to Add Member and View Members

### ✅ Add Member
- Input: Name, Role, Email, Contact, Image Upload
- POST request to `/api/members`
- Image stored in `uploads/` folder

### ✅ View Members
- Display all team members in a responsive card layout
- “View Details” button on each card
- Cards dynamically show:
  - Profile image
  - Name
  - Role
- Special UI behavior for:
  - **Shreyas** – Emphasized as Developer
  - **Sachin** – Highlighted as Scrum Master
  - **Mufeeda** – Displayed with supporting role

### ✅ Member Details Page
- GET request to `/api/members/:id`
- Shows full profile including image and contact info

---

## 📂 Folder Structure

project-root/
│
├── backend/
│ ├── uploads/ # Stores uploaded profile images
│ ├── models/ # MongoDB schema for members
│ ├── routes/ # Express API routes
│ ├── server.js # Entry point for backend
│
├── frontend/
│ ├── src/
│ │ ├── components/
│ │ ├── pages/
│ │ ├── App.js
│ │ └── index.js
│ └── public/
│
├── .gitignore
├── README.md
└── package.json

yaml
Copy
Edit

---

## 🔌 API Endpoints

| Method | Endpoint              | Description                    |
|--------|------------------------|--------------------------------|
| GET    | `/api/members`         | Fetch all team members         |
| GET    | `/api/members/:id`     | Get details of a single member |
| POST   | `/api/members`         | Add a new team member          |

---

## ⚙️ Installation & Running the App

### Backend
```bash
cd backend
npm install
node server.js
Frontend
bash
Copy
Edit
cd frontend
npm install
npm start
📸 Screenshots (Optional)
Include UI screenshots here for bonus readability.

📝 Notes
Ensure MongoDB is running locally or via Atlas connection.

Use Postman or your browser to test GET endpoints.

🧾 License
MIT License – free to use for academic purposes.

yaml
Copy
Edit

---

Let me know if you'd like this customized further with deployment instructions or image placeholder
