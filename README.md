# 🩺 SkinGuard AI – AI-Powered Skin Screening Platform

SkinGuard AI is a web-based intelligent skin screening platform designed to help users analyze skin images and receive AI-assisted screening insights, skincare guidance, and relevant health information.

The platform combines a modern web interface with a Node.js backend to provide an interactive and user-friendly experience.

## ✨ Features

- 🖼️ **Skin Image Upload** – Upload skin images for AI-assisted screening.
- 🤖 **AI-Based Analysis** – Analyze uploaded images and display screening results.
- 💬 **AI Chat Assistant** – Interact with the assistant for skin-related information.
- 📋 **Scan History** – Access previous screening records.
- 🧴 **Personalized Care Guide** – Get skincare guidance and recommendations.
- 🌍 **Multi-language Support** – Language and translation features.
- 🔊 **Text-to-Speech** – Listen to available information.
- 📍 **Nearby Doctors** – Explore nearby healthcare options.
- 🌤️ **Environmental Insights** – View environment-related information and suggestions.
- 📚 **Verified Information** – Access additional skin health information.

## 🛠️ Technologies Used

**Frontend**
- React.js
- Vite
- JavaScript
- CSS

**Backend**
- Node.js
- Express.js
- REST API

**Database**
- MongoDB
- In-memory fallback storage

## 📂 Project Structure

```text
SkinGuard_AI/
│
├── backend/
│   ├── config/
│   ├── models/
│   ├── rag/
│   ├── routes/
│   ├── services/
│   ├── server.js
│   └── package.json
│
├── frontend/
│   ├── src/
│   │   ├── components/
│   │   ├── utils/
│   │   ├── App.jsx
│   │   ├── main.jsx
│   │   └── index.css
│   ├── index.html
│   └── package.json
│
└── .gitignore
```

## ⚙️ Installation and Setup

### 1. Clone the Repository

```bash
git clone https://github.com/Sabarish-007/SkinGuard_AI.git
```

### 2. Navigate to the Project

```bash
cd SkinGuard_AI
```

### 3. Backend Setup

```bash
cd backend
npm install
```

Configure the backend environment variables using the provided `.env.example` file.

Start the backend:

```bash
npm start
```

For development:

```bash
npm run dev
```

Backend runs at:

`http://localhost:5001`

### 4. Frontend Setup

Open a new terminal:

```bash
cd frontend
npm install
npm run dev
```

Frontend runs at:

`http://localhost:5173`

## 🔍 Backend Health Check

Check whether the backend server is running:

`http://localhost:5001/api/health`

## ⚠️ Medical Disclaimer

SkinGuard AI is an educational and AI-assisted screening project. It is not a substitute for professional medical diagnosis, advice, or treatment.

Users should consult qualified healthcare professionals for proper evaluation of skin conditions.

## 👨‍💻 Developer

**Sabarish M**

B.Tech – Information Technology

GitHub: https://github.com/Sabarish-007

## ⭐ Support

If you find this project interesting, consider giving the repository a star!

---

**Developed with ❤️ by Sabarish M**
