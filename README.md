# 🎵 WeTunes – Spotify Web Player Inspired 🎧

Welcome to **WeTunes**, a Spotify-inspired music web player built using **HTML**, **CSS**, **JavaScript**, and **Node.js (Express)**. Stream tracks with a clean UI, responsive design, and smooth playlist interaction — now powered by **Cloudinary-hosted audio** and deployed via **Render**.

---

## 🚀 Features

- 🎧 Play music from custom playlists
- 🎛️ Interactive play, pause, next, previous
- 🔊 Volume control and mute toggle
- 🕓 Real-time song duration progress
- 📁 Dynamic playlist rendering from backend
- 🌐 Fully responsive UI
- ☁️ Cloud-based audio hosting (via Cloudinary)

---

## 🛠️ Tech Stack

| Frontend       | Backend        | Hosting         | Media Hosting    |
|----------------|----------------|------------------|------------------|
| HTML, CSS, JS  | Node.js, Express | Render (Free Tier) | Cloudinary (Free Tier) |

---

## 📂 Folder Structure

```
WeTunes/
├── public/
│   ├── index.html
│   ├── styles.css
│   ├── utility.css
│   ├── script.js
│   └── assets/ (SVGs, icons, images)
├── server.js
├── package.json
└── README.md
```

---

## 🧠 How It Works

- Static frontend files are served from the `public/` folder via Express.
- Cloudinary hosts all audio files to bypass Git LFS and Render storage limits.
- Playlist cards are rendered dynamically, and clicking them loads songs.
- Audio player plays `.mp3` files directly from Cloudinary URLs.


---

## 🌐 Live Demo

👉 [Visit WeTunes on Render](https://your-render-url.onrender.com)


## 📸 Screenshots

- WeTune's Desktop View:

- ![image](https://github.com/user-attachments/assets/ee3b15a9-1946-4de4-ae30-4e052287f799)

- WeTune's Responsive View:

- ![image](https://github.com/user-attachments/assets/ee060858-f313-4a23-85c8-302d6c28e524)


## 🚧 How to Run Locally

### 1. Clone the Repository
```bash
git clone https://github.com/your-username/wetunes.git
cd wetunes
```

### 2. Install Dependencies
```bash
npm install
```

### 3. Start Server
```bash
node server.js
```

Visit `http://localhost:3000`

---

## 🛠️ Deployment

### ✅ Frontend + Backend: [Render](https://render.com)

1. Push project (without `songs/`) to GitHub
2. Go to Render > Web Service > Connect GitHub repo
3. Set:
   - Build Command: `npm install`
   - Start Command: `node server.js`
4. Done!

### ✅ Songs: [Cloudinary](https://cloudinary.com)

1. Upload all `.mp3` files into Cloudinary folders
2. Copy their secure URLs
3. In `script.js`, set:

---

## ✨ Future Enhancements

- 🔁 Shuffle and Repeat functionality
- 🔍 Search by song name
- 📱 PWA support
- 🗂️ Admin dashboard to upload/edit songs

---

## 📜 License

MIT License

---

## 🙌 Special Thanks

- [CodeWithHarry](https://www.codewithharry.com/)
- [Render](https://render.com/)
- [Cloudinary](https://cloudinary.com/)

---

## 🤝 Connect

📧 **Vansh Bhatt** – vanshbhattok@gmail.com  
🔗 [GitHub](https://github.com/Vanshbhattok)  
🏫 BTech-CSE – UPES 

---
