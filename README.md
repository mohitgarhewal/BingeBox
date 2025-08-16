# 🎬🐦 BingeBox – The Ultimate YouTube-Twitter Hybrid  

[![Node.js](https://img.shields.io/badge/Node.js-18.x-green)](https://nodejs.org/)  
[![Express.js](https://img.shields.io/badge/Express.js-Backend-lightgrey)](https://expressjs.com/)  
[![MongoDB](https://img.shields.io/badge/MongoDB-Database-brightgreen)](https://www.mongodb.com/)  
[![Contributions Welcome](https://img.shields.io/badge/Contributions-Welcome-blue)](./CONTRIBUTING.md)  
[![License](https://img.shields.io/badge/License-MIT-yellow.svg)](./LICENSE)  

---

BingeBox is a modern **media streaming & micro-social platform** that blends the best of YouTube and Twitter.  
With BingeBox, users can **stream, share, interact, and engage**—all in one place.  

---

## 📌 References  

- 📄 [Data Modeling](https://documenter.getpostman.com/view/33297672/2sA2xmTVL8) – Detailed Database Design  
- ⚡ [API Documentation](https://app.eraser.io/workspace/V6SS5LVjjRu9nOB5LSvC) – Full API Endpoints  

---

## 🛠️ Tech Stack  

- **Backend:** Node.js, Express.js  
- **Database:** MongoDB + Mongoose (Aggregation Pipeline)  
- **Storage:** Cloudinary  
- **Middleware:** Multer (for uploads)  
- **Authentication:** JWT (Access + Refresh Tokens)  

---

## ✨ Features  

### 🔐 Authentication & Security  
- Register / Login  
- Change Password & Logout  
- JWT-based Secure Authentication  
- Refresh & Access Token Flow  

### 👤 User Management  
- Get User by ID  
- Update Profile Details  
- Upload & Update Avatar / Cover Image  
- Follow / Unfollow Users  

### 👍📝 Social Interactions  
- Like Videos & Tweets  
- Comment on Videos & Tweets  
- Create, Update & Delete Tweets  
- Share Videos & Tweets  

### 📼 Video Management  
- Upload, Update & Delete Videos  
- Get All Liked Videos of a User  
- Video Recommendations (based on likes & subscriptions)  
- Playlist Management: Create, Update, Add/Remove Videos  

### 👥 Subscriptions & Community  
- Subscribe / Unsubscribe to Channels  
- Personalized Feed from Subscribed Channels  
- Notification System for New Uploads & Tweets  

### 📊 Dashboard & Analytics  
- Channel Stats (views, subscribers, total likes)  
- Watch History Tracking  
- Trending Content & Engagement Metrics  

### 🆕 Extra Functionalities  
- 🔎 **Search**: Find users, videos, and tweets with powerful filters  
- 🧵 **Hashtags & Tags**: Discover trending conversations  
- 🕒 **Watch Later**: Save videos for later viewing  
- 🌐 **Explore Feed**: Get recommended content outside subscriptions  
- 🗂️ **Categories**: Organize videos by genre (Music, Tech, Vlogs, etc.)  
- 📲 **Responsive API** ready for Mobile & Web integration  

---

## ⚙️ Setup  

### 1️⃣ Create `.env.local` File  

```ini
PORT=8000
MONGODB_URI=[Your MongoDB URI]
CORS_ORIGIN=*
ACCESS_TOKEN_SECRET=[Your Access Token Secret]
ACCESS_TOKEN_EXPIRY=1d
REFRESH_TOKEN_SECRET=[Your Refresh Token Secret]
REFRESH_TOKEN_EXPIRY=10d
CLOUDINARY_NAME=[Your Cloudinary Name]
CLOUDINARY_API_KEY=[Your Cloudinary API Key]
CLOUDINARY_API_SECRET=[Your Cloudinary API Secret]
```

### 2️⃣ Run the Project  

```bash
# Clone the repo
git clone https://github.com/your-username/bingebox.git

# Navigate to project folder
cd bingebox

# Install dependencies
npm install

# Start development server
npm run dev
```

---

## 🤝 Contributing  

We welcome contributions!  

1. Fork the repo  
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)  
3. Commit changes (`git commit -m 'Add some AmazingFeature'`)  
4. Push to branch (`git push origin feature/AmazingFeature`)  
5. Open a Pull Request 🚀  

---

## 🙌 Acknowledgments  

BingeBox is inspired by the **engagement of Twitter** and the **entertainment of YouTube**.  
Special thanks to the **open-source community** for making innovation possible. 💡  

---

🔥 Ready to **Binge. Share. Connect.**?  
Welcome to **BingeBox** 🎥🐦  
