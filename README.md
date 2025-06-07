# YouTube Clone - Frontend+Backend

This is the React frontend of the YouTube Clone application, built with Vite and Tailwind CSS.

---

## Git Repositories

- [Github Repo](https://github.com/bikrambiku00/youtube.git)

---

## Screenshot

---

## Usage

- Explore videos on the home page
- Register or Login to upload videos and comment
- Create and manage your own channel
- Like/Dislike videos
- Search for content with real-time suggestions

---

##  Folder Structure

```
Youtube_Clone/
├── youtube-clone-backend/
│   ├── controller/
│   │   └── authController.js
│   │   ├── channelControler.js
│   │   ├── commentControler.js
│   │   └── videoController.js
│   ├── middleware/
│   │   └── authenticatUser.js
│   ├── model/
│   │   ├── ChannelModel.js
│   │   ├── CommentModel.js
│   │   ├── UserModel.js
│   │   └── VideoModel.js
│   ├── routes/
│   │   ├── auth.js
│   │   ├── channels.js
│   │   ├── comments.js
│   │   └── videos.js
│   ├── .env
│   ├── package.json
│   └── server.js
│
└── youtube-clone-frontend/
    ├── public/
    │   └── youtube.png
    ├── src/
    │   ├── utils/
    │   │   └── timeAgo.js
    │   ├── assets/
    │   │   └── logo.jpg
    │   ├── components/
    │   │   ├── ChannelPage.jsx
    │   │   ├── CreateChannel.jsx
    │   │   ├── Header.jsx
    │   │   ├── HomePage.jsx
            ├── PageNotFound.jsx
    │   │   ├── Sidebar.jsx
    │   │   ├── SignIn.jsx
    │   │   └── UploadVieoForm.jsx
    │   ├── App.jsx
    │   ├── main.jsx
    │   └── vite-env.d.ts
    ├── .env.example
    ├── package.json
    └── vite.config.js


```

## 💡 Features

- Multi-step forms (auth, upload)
- Responsive video player
- Channel management with banner
- Modal-based forms for UX
- Sidebar with subscriptions and filters

---



## ⚙️ Local Setup

```bash
cd youtube_clone_frontend
npm install
npm run dev

cd youtube_clone_bakend
npm install
node server.js 
```

---

REACT_APP_API_BASE_URL=http://localhost:5173/

```

## Usage

- Explore videos on the home page
- Register or Login to upload videos and comment
- Create and manage your own channel
- Subscribe to other channels
- Like/Dislike videos
- Search for content with real-time suggestions

---

## 📦 Dependencies

- React + Vite
- React Router
- Axios
- Tailwind CSS

```