# 🎓 Career Mentor for University Students

![React](https://img.shields.io/badge/React-19-blue?logo=react)
![Node.js](https://img.shields.io/badge/Node.js-Express-green?logo=node.js)
![MongoDB](https://img.shields.io/badge/Database-MongoDB-green?logo=mongodb)
![Python](https://img.shields.io/badge/Python-Flask-yellow?logo=python)
![License](https://img.shields.io/badge/License-MIT-blue)
![Status](https://img.shields.io/badge/Project-Final%20Year-success)


A web-based **AI-powered Career Guidance Platform** designed to help university students prepare for their future careers.

The platform provides personalized **career recommendations**, **resume analysis**, **AI mock interviews**, **skill assessments**, and **learning resources** to improve students' employability and interview confidence.

---

## 👥 Team

| Name | Student ID | Role |
|------|------------|------|
| **May Myat Noe Phyu** | 2021-MIIT-CSE-032 | Full Stack Developer / AI Integration |
| **Thazin Phyo** | 2021-MIIT-CSE-072 | *(Add Role)* |
| **Yoon Cherry** | 2021-MIIT-CSE-092 | *(Add Role)* |
| **Yoon Moh Moh Aung** | 2021-MIIT-CSE-093 | *(Add Role)* |

---

# ✨ Key Features

## 👨‍🎓 Student Features

- 🤖 AI-powered career recommendations based on skills and interests
- 📄 Upload and analyze resumes with personalized feedback
- 🎤 Practice mock interviews with AI-generated questions
- ⏱️ Timed interview sessions with performance tracking
- 📊 View interview scores and improvement analytics
- 📚 Access career guidance articles and learning resources
- 🎯 Track career preparation progress through an interactive dashboard
- 💼 Explore career paths and required technical skills

---

## 👨‍💼 Admin Features

- 🔐 Secure administrator login using JWT Authentication
- 👥 Manage student accounts
- 📋 Manage career categories
- 📚 Manage learning resources
- 📰 Publish career tips and announcements
- 📊 View interview reports and resume analysis statistics
- 📈 Monitor platform usage and student activities
- 🗂️ Manage AI interview question banks

---

# 🛠 Tech Stack

## Frontend

- React + Vite
- Material UI (MUI)
- React Router
- Axios
- Chart.js
- Framer Motion
- React Hook Form
- React Icons

---

## Backend

- Node.js
- Express.js
- MongoDB
- Mongoose ODM
- JWT Authentication
- Multer
- bcrypt.js
- dotenv
- CORS

---

## AI & NLP

- Python
- Flask API
- NLTK
- Scikit-learn
- Sentence Transformers
- Resume Matching
- Career Recommendation Model
- AI Interview Question Generator

---

## Infrastructure

| Service | Technology |
|----------|------------|
| Database | MongoDB |
| Frontend Hosting | Netlify / Vercel |
| Backend Hosting | Railway / Render |
| AI Service | Flask API |
| File Storage | Local Uploads / Cloudinary (Optional) |

---

# 📁 Project Structure

```text
Career-Mentor-System
│
├── Client
│   ├── public
│   ├── src
│   │   ├── api
│   │   ├── assets
│   │   ├── components
│   │   ├── context
│   │   ├── hooks
│   │   ├── layouts
│   │   ├── pages
│   │   ├── routes
│   │   ├── theme.js
│   │   ├── App.jsx
│   │   ├── main.jsx
│   │   └── index.css
│   ├── package.json
│   └── vite.config.js
│
├── Server
│   ├── config
│   ├── controllers
│   ├── middleware
│   ├── models
│   ├── routes
│   ├── uploads
│   ├── utils
│   ├── server.js
│   └── package.json
│
├── AI-Service
│   ├── models
│   ├── nltk_data
│   ├── resume_parser.py
│   ├── career_prediction.py
│   ├── interview_generator.py
│   ├── app.py
│   └── requirements.txt
│
├── README.md
└── .gitignore
```

---

# 🚀 Getting Started

## 1️⃣ Clone the Repository

```bash
git clone https://github.com/yourusername/Career-Mentor-System.git

cd Career-Mentor-System
```

---

## 2️⃣ Install Dependencies

### Frontend

```bash
cd Client
npm install
```

### Backend

```bash
cd ../Server
npm install
```

### AI Service

```bash
cd ../AI-Service
pip install -r requirements.txt
```

---

## ⚙ Environment Variables

### Server/.env

```env
PORT=5004
MONGO_URI=mongodb://localhost:27017/careermentor
JWT_SECRET=your_secret_key
CLIENT_URL=http://localhost:5173
```

---

### Client/.env

```env
VITE_API_BASE_URL=http://localhost:5004/api
VITE_AI_API=http://localhost:8000
```

---

### AI-Service/.env

```env
MODEL_PATH=models/
FLASK_ENV=development
```

---

# ▶ Running the Application

## Start Backend

```bash
cd Server
npm run dev
```

---

## Start Frontend

```bash
cd Client
npm run dev
```

---

## Start AI Service

```bash
cd AI-Service

python app.py
```

---

# 🎯 Core Modules

- 🔐 User Authentication
- 🤖 Career Recommendation
- 📄 Resume Analysis
- 🎤 AI Mock Interview
- 📝 Skill Assessment
- 📊 Dashboard Analytics
- 📚 Learning Resources
- 👨‍💼 Admin Management
- 👤 User Profile
- 📈 Progress Tracking

---

# 🧪 Testing

Backend APIs can be tested using **Thunder Client** or **Postman**.

### Resume Upload

```
POST /api/resume/upload
```

### Career Prediction

```
POST /api/career
```

### Interview Generation

```
POST /api/interview
```

### Optional Testing

- Jest + Supertest (Backend)
- Pytest (AI Module)

---

# 📊 Future Improvements

- 🎙 AI Voice Interview
- 🎥 Video Interview Analysis
- 😊 Facial Emotion Detection
- 🏢 Company-specific Interview Preparation
- 💼 Job Recommendation Engine
- 🎓 Internship Recommendation
- 🔗 LinkedIn Profile Analyzer
- 💬 AI Career Assistant Chatbot
- 📧 Email Notifications
- 🏆 Certificate Generator

---

# 🤝 Contributing

Contributions are welcome!

1. Fork the repository
2. Create a feature branch

```bash
git checkout -b feature/your-feature
```

3. Commit your changes

```bash
git commit -m "Add new feature"
```

4. Push to GitHub

```bash
git push origin feature/your-feature
```

5. Open a Pull Request

---

# 📃 License

This project was developed as a **Final Year Project** for educational purposes.

Licensed under the **MIT License**.

---

# 📬 Contact

**May Myat Noe Phyu**

📧 Email: mmnp2242004@example.com

🐙 GitHub: https://github.com/MayMyatNoePhyu

---

⭐ If you like this project, don't forget to give it a **Star** on GitHub!
