# DecoupleFullStackVedioEditor

# 🎬 Web-Based Video Editor

A browser-based video editing tool inspired by Adobe Premiere and Photoshop's timeline layout. This tool allows users to upload or load videos via URL, preview them on a timeline with frame thumbnails, mark and manage multiple clips, and simulate or export trimmed segments. Built using the **MERN stack**, this project demonstrates core full-stack engineering capabilities.

## 🌐 Live Demo
[🔗 Visit the Live Demo](https://decouple-client-git-t33z.vercel.app/)  
_(Replace with your Netlify/Vercel deployment URL)_

## 📸 Preview
![Timeline Preview](./preview.png)  
_(Optional: Add a screenshot of your application interface)_

---

## 🚀 Features

### ✅ Core Functionalities
- Upload or load videos via URL
- Play / Pause functionality with progress tracking
- Timeline with scrollable frame thumbnails
- Draggable start/end handles for clipping
- Support for **multiple overlapping clips**
- Clip preview functionality
- Simulate and **export trimmed clips**

### 🎨 UI/UX
- Dark-themed editor interface
- Layout inspired by Adobe Premiere
- Interactive time ruler with markers and playback slider
- Visual clip blocks shown beneath the timeline

### 🔧 Backend (Optional)
- Built with **Node.js** and **Express**
- Uses **Multer** for file uploads
- **FFmpeg** integration for clip extraction

### 🧪 Bonus Features (Implemented / To-Do)
- [ ] Trim clips directly in-browser using `ffmpeg.wasm`
- [ ] Rename and reorder clips
- [ ] Export all clips as ZIP
- [ ] Keyboard shortcuts (I/O marks, JKL navigation)

---

## 🛠️ Tech Stack

### Frontend
- [React.js](https://reactjs.org/)
- [Tailwind CSS](https://tailwindcss.com/)
- [React Player](https://www.npmjs.com/package/react-player)
- [React Draggable](https://www.npmjs.com/package/react-draggable)
- [Vite](https://vitejs.dev/) (for lightning-fast development)

### Backend (Optional)
- [Node.js](https://nodejs.org/)
- [Express.js](https://expressjs.com/)
- [Multer](https://www.npmjs.com/package/multer)
- [FFmpeg](https://ffmpeg.org/) (`fluent-ffmpeg` for backend; `ffmpeg.wasm` for browser-side processing)

---

## 📂 Project Structure


