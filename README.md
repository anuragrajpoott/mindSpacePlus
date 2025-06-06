# 🧠 Mind Space + — Mental Health Social Media Platform

Welcome to **Mind Space +**, a full-stack MERN (MongoDB, Express, React, Node.js) social media platform tailored specifically to support mental health through community, conversation, and connection.

---

## 🌟 Project Overview

Mind Space + is designed to provide users a safe, anonymous, and empathetic space to share their mental health journey, connect with like-minded individuals, and access helpful tools and resources. With privacy, accessibility, and emotional well-being at its core, Mind Space + goes beyond a traditional social network.

---

## 🛠 Tech Stack

- **Frontend**: React, Redux, React Router, Tailwind CSS  
- **Backend**: Node.js, Express.js  
- **Database**: MongoDB (Mongoose ODM)  
- **Authentication**: JWT, bcrypt, OTP email verification  
- **State Management**: Redux Toolkit  
- **API Calls**: Axios  
- **Email Service**: Nodemailer  
- **Toast Notifications**: React Hot Toast

---

## 🚀 Features

### 🧑‍💼 Authentication & User Management
- Sign Up with OTP verification
- Login with JWT-based sessions
- Protected routes
- User profile creation and editing
- Secure password hashing

### 🗣 Social Feed & Engagement
- Post creation (with media and tags)
- Anonymous posting option
- Like, comment, and view posts
- Feed with posts from friends/public

### 💬 Messaging
- Private 1-on-1 messaging system
- Chat blocking & reporting
- (Planned) Group chats

### 🔔 Notifications
- Real-time or batched notifications
- Alerts for likes, comments, messages, etc.

### 👥 Friend System
- Add, accept, or remove friends
- View mutual friends
- Block users

### 🧘‍♀️ Mental Health–Focused Tools
- Mood Tracker (planned)
- Daily Journals & Prompts
- Support group communities
- Emergency/Crisis support resources
- Mental health tags and content filtering

### ⚙️ Admin Dashboard
- User and post moderation
- View reports and flagged content
- Manage therapists and support groups

---

## 📁 Project Structure

```
Mind Space +/
├── client/              # React frontend
│   ├── components/      # Reusable UI components
│   ├── pages/           # Page-level views (Feed, Login, Profile, etc.)
│   ├── redux/           # Redux store and slices
│   ├── services/        # Axios & API integrations
│   └── App.jsx          # Main component
├── server/              # Node.js backend
│   ├── controllers/     # Route logic (auth, posts, etc.)
│   ├── models/          # Mongoose schemas
│   ├── routes/          # Express routes
│   ├── utils/           # Mail sender, helpers
│   └── index.js         # Express app entry
└── .env                 # Environment variables
```

---

## 🔐 Environment Variables

Create a `.env` file in your `server/` directory:

```
PORT=4000
MONGODB_URL=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
MAIL_HOST=smtp.mailprovider.com
MAIL_USER=your_email@example.com
MAIL_PASS=your_email_password
```

---

## 📦 Installation

1. **Clone the repository**
```bash
git clone https://github.com/anuragrajpoott/mindSpace-.git
cd Mind Space +
```

2. **Install server and client dependencies**
```bash
# Backend
cd backEnd
npm install

# Frontend
cd ../Frontend
npm install
```

3. **Run the app**
```bash
# In one terminal
cd server
npm run dev

# In another terminal
cd client
npm run dev
```

---

## 💡 Future Enhancements

- Group Therapy Chats
- AI-Powered Sentiment Monitoring
- Real-time feed updates via WebSocket
- Therapist onboarding & chat
- Mobile App (React Native)

---

## 🤝 Contributing

Contributions are welcome! Whether it's bug fixes, new features, or improvements to documentation, feel free to open a pull request.

---

## 🛡 License

This project is licensed under the [MIT License](LICENSE).

---

## 🙌 Acknowledgements

Built with care to support mental wellness. ❤️  
Thanks to the open-source community and mental health professionals who inspire us.

---

## 📬 Contact

Feel free to reach out:

- GitHub: [@anuragrajpoott](https://github.com/anuragrajpoott)
- Email: anuragrajpoot2468@gmail.com
