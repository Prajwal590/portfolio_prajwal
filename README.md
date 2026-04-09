# Prajwal Marapur — Personal Portfolio & Blog Management System

> Production-quality personal portfolio + CMS built with React, Vite, and Tailwind CSS.

[![React](https://img.shields.io/badge/React-18-61DAFB?logo=react)](https://reactjs.org)
[![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-3-38BDF8?logo=tailwindcss)](https://tailwindcss.com)
[![Vite](https://img.shields.io/badge/Vite-5-646CFF?logo=vite)](https://vitejs.dev)
[![License: MIT](https://img.shields.io/badge/License-MIT-green)](LICENSE)

---
## 🌐 Live Demo
https://your-vercel-link.vercel.app

## 👤 About the Developer

| Field       | Details |
|-------------|---------|
| **Name**    | Prajwal Marapur |
| **Role**    | Full Stack Developer & AI Engineer |
| **Company** | Brightpath Technology & Services, Bangalore |
| **Email**   | prajwalmarapur1@gmail.com |
| **Phone**   | +91-8867851979 |
| **Location**| Bangalore, Karnataka, India |
| **GitHub**  | [github.com/Prajwal590](https://github.com/Prajwal590) |
| **LinkedIn**| [linkedin.com/in/prajwal-m-615984280](https://www.linkedin.com/in/prajwal-m-615984280/) |

---

## ✨ Features

### Public Portfolio
- **Home** — Hero with typewriter (Full Stack Developer / AI Engineer / React.js Specialist / FastAPI Developer / LLM/RAG Builder), real bio, skills grouped by category, experience timeline (Brightpath → JSpider → Rooman), VTU education card, CTA
- **Projects** — 3 real projects (Nail Disease Detection, Movie Recommender, Student Management System)
- **Blog** — Search, filter (Published/Draft/All), skeleton loaders, empty states
- **Single Blog** — Markdown rendering, reading time, tags

### Admin Portal
- **Login** — `admin` / `admin123`, show/hide password, loading spinner
- **Dashboard** — Stats (total, published, drafts), recent posts
- **Blog CRUD** — Create, Edit, Delete, Toggle status with confirmations & toasts

### UX
- 🌙 Dark / Light mode (localStorage + system preference)
- 🔔 Toast notifications (react-hot-toast)
- 💀 Skeleton loaders on all data screens
- 📱 Fully responsive (mobile sidebar collapses)
- ⚡ Smooth animations and hover effects

---

## 🛠 Tech Stack

| Layer | Technology |
|---|---|
| Framework | React 18 (functional hooks) |
| Build | Vite 5 |
| Styling | Tailwind CSS 3 (dark mode) |
| Routing | React Router DOM v6 |
| Notifications | react-hot-toast |
| Icons | lucide-react |
| Persistence | localStorage |
| Deployment | Vercel |

---

## 🚀 Run Locally

```bash
# Clone
git clone https://github.com/Prajwal590/portfolio.git
cd portfolio

# Install
npm install

# Start
npm run dev
```

Open **http://localhost:5173**

**Admin:** http://localhost:5173/admin/login → `admin` / `admin123`

---

## ☁️ Deploy on Vercel

```bash
npm install -g vercel
vercel --prod
```

Or via Vercel Dashboard: import repo → Framework: **Vite** → Build: `npm run build` → Output: `dist` → Deploy ✅

---

## 📂 Structure

```
src/
├── components/     Navbar, Footer, BlogCard, ProjectCard, Skeleton, ProtectedRoute
├── context/        ThemeContext, AuthContext
├── pages/
│   ├── Home.jsx    Hero, Skills, Experience, Education, CTA
│   ├── Projects.jsx Real projects grid
│   ├── Blogs.jsx   Search + filter blog list
│   ├── SingleBlog.jsx Full post + Markdown renderer
│   └── admin/
│       ├── AdminLogin.jsx
│       └── AdminDashboard.jsx  CRUD + sidebar + stats
└── utils/
    └── blogStore.js  localStorage CRUD + 5 real seed posts
```

---

## 🤖 AI Tools Used

## 🤖 AI Tools Used

This project was built using AI-assisted development.

### Tools Used
- ChatGPT (OpenAI)
- Antigravity (Google DeepMind)

### How AI Helped
- Generated initial project structure (React + Vite setup)
- Assisted in building UI components like Navbar, Cards, Dashboard
- Helped implement blog CRUD functionality using localStorage
- Generated sample blog content based on my tech stack
- Suggested UI/UX improvements using Tailwind CSS

### Code Contribution
- AI-generated: ~85–90%
- Manually written/modified: ~10–15%

### Understanding of Code
Yes, I have reviewed and understood all AI-generated code.  
I modified logic where needed and ensured the application works correctly end-to-end.

---

## 📄 License

MIT © 2026 Prajwal Marapur   
