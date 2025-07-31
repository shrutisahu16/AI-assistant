<h1 align="center" style="font-size:3rem;"> 🤖 J.A.R.V.I.S – Virtual AI Assistant</h1>

<p align="center">
🎙️ A voice-controlled virtual AI assistant built with Gemini AI and the MERN stack. Supports smart web commands, avatar customization, and secure login.
</p>

---

## 📦 Repository

[👉 GitHub – shrutisahu16/AI-assistant]((https://github.com/shrutisahu16/AI-assistant.git))

---

## 🛠️ Tech Stack

### 🌐 Frontend
- **HTML**, **CSS**, **JavaScript**
- **React.js** – Component-based UI


### 🔧 Backend
- **AI:** **Gemini AI** 
- **Node.js** with **Express.js**
- **MongoDB** – NoSQL database for storing user information and virtual AI assistance.
- **REST APIs** – For frontend-backend communication
- **JWT** – For authentication & role-based access control
- **Multer** - For upload image for virtal assistant

---
🎥 Demo
👉 👉 [Click here to watch the demo](https://virtual-assistant-frontend-5bqi.onrender.com/)

## ✨ Features

- 🎤 *Real-Time Voice Recognition*  
  Speak to J.A.R.V.I.S and it will understand and act!

- 🔎 *Voice Commands*  
  Open or search Google, YouTube, Instagram, Facebook, and more using simple voice instructions.

- 🧑‍🎨 *Customizable Avatar & Assistant Name*  
  Personalize your AI assistant with your own name and image using Cloudinary & Multer.

- 🔒 *Secure Login System*  
  Authenticated using JWT tokens and password encryption via bcrypt.js.

---


## 🚀 How to Run Locally

1. *Clone the Repository*
   ```bash
   git clone https://github.com/yourusername/AI-assistant.git
   cd AI-assistant
   
2. Install Dependencies

npm install   # For backend
cd frontend
npm install   # For frontend

3. Setup Environment Variables
Create .env files for both frontend and backend. Add your keys (Mongo URI, JWT secret, Cloudinary keys, etc.).

4. Start the Project
# Run backend
npm start
# In a new terminal, run frontend
cd frontend
npm start

