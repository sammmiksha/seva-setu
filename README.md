<div align="center">

# 🤝 SevaSetu v2
### Smart Volunteer & Help Matching Platform 
(this is my version)

[![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)](https://reactjs.org)
[![Firebase](https://img.shields.io/badge/Firebase-FFCA28?style=for-the-badge&logo=firebase&logoColor=black)](https://firebase.google.com)
[![Hosted](https://img.shields.io/badge/Live-Firebase_Hosting-orange?style=for-the-badge&logo=firebase)](https://seva-setu-9a8e3.web.app)

*Connecting people in need with volunteers — simply, efficiently, accessibly.*

**[🌐 Live Demo →](https://seva-setu-9a8e3.web.app)**

---

</div>

## 📖 Overview

**SevaSetu** (सेवासेतु — *"Bridge of Service"*) is a web-based volunteer matching platform that connects individuals who need help with people willing to offer it. It provides a structured, easy-to-use system for posting help requests and enabling community members to respond in a meaningful way.

This repository is **my independently developed v2**, rebuilt and significantly improved from an earlier collaborative version — with a focus on cleaner UI, smoother authentication, and a more reliable data flow.

---

## 📸 Screenshots

<p align="center">
  <img src="https://github.com/user-attachments/assets/60bb71ea-7a63-4173-84fe-6e1b1cd8097d" width="30%" />
  <img src="https://github.com/user-attachments/assets/556a4643-8715-415c-8e72-d3c70533bf96" width="30%" />
  <img src="https://github.com/user-attachments/assets/d9b210ad-6c87-4e29-9f31-f6e3075fdaed" width="30%" />
</p>

---

## ✨ Features

| Feature | Description |
|---|---|
| 🔐 Authentication | Secure login and registration flow |
| 📋 Help Requests | Create, browse, and manage requests for assistance |
| 🙋 Volunteer Response | Respond to open requests in your community |
| 👤 Profile Management | View and update your personal profile |
| 📱 Responsive UI | Clean, mobile-friendly interface |

---

## 🛠 Tech Stack

| Layer | Technology |
|---|---|
| Frontend | React.js |
| Backend & Database | Firebase (Firestore) |
| Authentication | Firebase Auth |
| Styling | CSS |
| Deployment | Firebase Hosting |

---

## 🔧 My Contributions (v2 Improvements)

This version was independently built and improved from the original collaborative project. Key changes include:

- **Redesigned UI** — rebuilt with React for a cleaner, more intuitive experience
- **Refined auth flow** — smoother login/registration with better error handling
- **Fixed request handling** — resolved data flow issues from the original version
- **Improved navigation** — more consistent routing and user journey
- **Deployed to Firebase** — publicly accessible via a live hosted URL

---

## ⚙️ Local Setup

### Prerequisites
- Node.js 18+
- A Firebase project with Firestore and Auth enabled

### 1. Clone the repo

```bash
git clone https://github.com/your-username/sevasetu-v2.git
cd sevasetu-v2
```

### 2. Install dependencies

```bash
npm install
```

### 3. Configure Firebase

Create a `.env` file in the root directory:

```env
VITE_FIREBASE_API_KEY=your_api_key
VITE_FIREBASE_AUTH_DOMAIN=your_project.firebaseapp.com
VITE_FIREBASE_PROJECT_ID=your_project_id
VITE_FIREBASE_STORAGE_BUCKET=your_bucket
VITE_FIREBASE_MESSAGING_SENDER_ID=your_sender_id
VITE_FIREBASE_APP_ID=your_app_id
```

### 4. Run locally

```bash
npm run dev
```

> App runs at `http://localhost:5173`

---

## 📁 Project Structure

```
SevaSetu-v2/
├── src/
│   ├── pages/            # Home, Login, Register, Requests, Profile
│   ├── components/       # Navbar, RequestCard, RequestForm
│   ├── firebase.js       # Firebase config & initialization
│   └── App.jsx           # Root component & routing
├── public/
├── .env                  # Firebase credentials (not committed)
└── package.json
```

---

## 🚀 Roadmap

- [ ] Location-based request filtering
- [ ] In-app messaging between volunteers and requesters
- [ ] Request categories (medical, grocery, transport, etc.)
- [ ] Volunteer ratings and reviews
- [ ] Admin dashboard for moderation
- [ ] Email/SMS notifications for new matching requests

---

## 🙏 Acknowledgment

SevaSetu was originally a collaborative group project. This repository reflects my **individual v2 implementation** — independently rebuilt, improved, and deployed — with a focus on refining the user experience and fixing functionality gaps from the original version.

---

## 👨‍💻 Author

**Sam**  
BSc Information Technology  
Focused on AI, ML & Full-Stack Development

---

<div align="center">

*SevaSetu — because a small act of help can bridge a big gap.*

</div>
