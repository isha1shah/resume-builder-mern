# 🚀 AI Resume Builder (MERN Stack)

A full-stack **Resume Builder** web application built using the **MERN stack** with **AI-powered content enhancement**. Create, edit, and export professional resumes with a modern, responsive interface.

**🌐 Live Demo:**  
- Frontend: [https://resume-builder-client-5ucg.onrender.com](https://resume-builder-client-5ucg.onrender.com)  
- Backend API: [https://resume-builder-backend-luea.onrender.com](https://resume-builder-backend-luea.onrender.com)

---

## 📌 Table of Contents

- [About the Project](#about-the-project)  
- [Features](#features)  
- [Tech Stack](#tech-stack)  
- [Installation](#installation)  
- [Environment Variables](#environment-variables)  
- [Run Locally](#run-locally)  
- [Project Structure](#project-structure)  
- [Future Improvements](#future-improvements)  
- [Author](#author)  

---

## ⭐ About the Project

The **AI Resume Builder** helps users:

- Create professional resumes quickly and easily  
- Generate AI-enhanced content for summaries and job descriptions  
- Manage multiple resumes  
- Export resumes as PDF  
- Preview edits live  

It follows a **clean full-stack architecture**, using **React** for the frontend and **Node/Express** for the backend.

---

## ✨ Features

### 🎨 Frontend
- Modern UI built with **React** and **Tailwind CSS**  
- Fully responsive design  
- Live resume preview  
- Multiple editable sections  

### ⚙ Backend
- RESTful API built with **Express.js**  
- **MongoDB** database integration  
- Secure routes & authentication  
- Full CRUD operations for resumes  

### 🤖 AI Integration
- AI-powered summary enhancement  
- Smart content suggestions  
- Improved job descriptions  

---

## 🧰 Tech Stack

| Layer      | Technology                       |
|-----------|----------------------------------|
| Frontend  | React.js, Tailwind CSS           |
| Backend   | Node.js, Express.js              |
| Database  | MongoDB                          |
| AI        | Gemini API                       |
| Version Control | Git & GitHub                |

---

## 🔧 Installation

Clone the repository:

```bash
git clone https://github.com/isha1shah/resume-builder-mern.git
cd resume-builder-mern
📦 Install Dependencies

Backend:

cd server
npm install

Frontend:

cd ../client
npm install
🔐 Environment Variables

Create a .env file inside the server folder:

MONGO_URI=your_mongodb_connection_string
PORT=3000
GEMINI_API_KEY=your_api_key

Ensure .env is included in .gitignore.

▶ Run Locally

Start Backend:

cd server
npm run dev

Start Frontend:

cd ../client
npm start

Open in browser: http://localhost:5173

📂 Project Structure
Resume-Builder-MERN/
│
├── client/        # React frontend
├── server/        # Express backend
├── .gitignore
└── README.md
🧪 Future Improvements

Additional resume templates

Drag-and-drop resume builder

Resume version history

Export to Word format

Theme customization

👩‍💻 Author

Made with ❤️ by Isha Shah

GitHub: https://github.com/isha1shah

LinkedIn: https://www.linkedin.com/in/isha-shah-9025392b1
