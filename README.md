# 🚌 BusSpotter – Real-Time School/College Bus Tracking System

**BusSpotter** is a smart, real-time school/college bus tracking system that does **not require GPS hardware**. It allows drivers to start tracking directly from the website using device GPS, providing students/parents with live tracking updates.

---

## 🚀 Features

- 🔐 **Secure Driver Login**  
- 📍 **Real-Time Bus Location Sharing**  
- 🧭 **Map View for Students/Parents**  
- 🌐 **No External Hardware Required**  
- 📲 **Responsive Design with Tailwind CSS**  
- 💡 **Simple Admin Control Panel (Optional)**

---

## 🗂️ Folder Structure

BusSpotter/
│

├── Frontend/ # React + Tailwind frontend

│ ├── public/

│ ├── src/

│ └── ...

│

├── Backend/ # (Optional, for auth/storage)

│ └── ...
│
└── README.md # This file


---

## 🛠️ Tech Stack

**Frontend:**

- ⚛️ React.js
- 💨 Tailwind CSS
- 🗺️ Mapbox API

**Backend (Optional):**

- 🐒 Express.js + Node.js  
- 🛢️ MongoDB (if using persistent login or bus DB)  
- 🔐 JWT for authentication  

---

## 🧑‍💻 How It Works

1. **Driver Login** – Secure login (optional).
2. **Start Tracking** – Driver allows browser GPS, and location is fetched in real-time.
3. **Live Map** – Students/parents can see the bus location via shared tracking link or public map.
4. **No App Needed** – Works via any modern browser.

---

## ⚙️ Setup Instructions

### 1. Clone the Repository

```bash
git clone https://github.com/AjinkyaxSuryawanshi/BusSpotter.git
cd BusSpotter/Frontend

2. Install Dependencies
bash
Copy
Edit
npm install

3. Start Development Server
bash
Copy
Edit
npm run dev
Now open http://localhost:5173 in your browser.

🔐 Deployment Notes
Deployed on: Vercel or Netlify

Optional backend can be deployed using Render, Railway, or MongoDB Atlas

🧾 Privacy & Security
All GPS data stays on-device or in your database (if backend used).

No third-party data storage unless configured by you.

🛣️ Future Plans
🔔 Push Notifications

📍 Route Optimization

📱 PWA Support

👨‍👩‍👧‍👦 Parent Account Linking

📄 License
This project is licensed under the MIT License.

🤝 Contributions
Pull requests are welcome!
Feel free to fork, modify, and submit improvements.
