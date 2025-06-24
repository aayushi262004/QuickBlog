# 🚀 QuickBlock – AI-Powered Blog Generation Platform

**QuickBlock** is a full-stack AI-powered blogging platform that lets you effortlessly **generate**, **edit**, **store**, and **publish blogs** using **Google Gemini**. With a sleek interface and powerful backend, it's your go-to solution for intelligent content creation.

---

## 🌍 Live Demo

🔗 [Visit QuickBlock on Vercel](https://quick-blog-theta-five.vercel.app)

---

## ✨ Key Features

- ✨ Generate blogs using Gemini AI
- 📝 Edit blog content with a rich editor
- 📦 Store and manage your posts in MongoDB
- 🌐 Publish directly from the dashboard
- 📸 Image uploading integrated with ImageKit
- 🔐 Secure credential management via environment variables

---

## 🛠️ Tech Stack

- **Frontend:** React + Vite
- **Backend:** Node.js + Express
- **AI Integration:** Google Gemini API
- **Database:** MongoDB Atlas
- **Image Hosting:** ImageKit
- **Deployment:** Vercel (Frontend), Render (Backend or custom)

---

## 🔐 Environment Variables

The project uses environment variables for secure configuration. Required keys include:

### For Backend (`server/.env`):

```env
MONGO_URI=your_mongodb_connection_string
GEMINI_PUBLIC_KEY=your_key
GEMINI_PRIVATE_KEY=your_key
GEMINI_URL=https://your-api-url.com
GEMINI_ENDPOINT=/v1/blog
