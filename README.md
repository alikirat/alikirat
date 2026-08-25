# 👋 Hi, I'm **Ali Kirat**

## 💻 Full-Stack Software Engineer | React · TypeScript · Node.js · Python · AI/LLM Integration

Full-stack software engineer with **2+ years of experience** building and deploying production web applications using React, TypeScript, Node.js, Python, and MongoDB. I integrate LLM APIs and AI agent systems as a core part of how I build, not as an afterthought.

I bring strong communication and cross-functional collaboration skills from a background in education and business consulting, and I use Claude Code and GitHub Copilot as daily development tools.

📍 Claremont, CA  
📧 alikirat.dev@gmail.com  
[![Portfolio](https://img.shields.io/badge/Portfolio-alikirat.netlify.app-0077B5?style=for-the-badge&logo=netlify&logoColor=white)](https://alikirat.netlify.app)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-ali--kirat-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/ali-kirat)

---

## ⭐ Featured Projects

### 🚕 Atlas Taxi: Full-Stack Ride Booking Platform

A production MERN stack application with TypeScript, JWT authentication, role-based dashboards, and CI/CD deployment.

![Atlas Taxi screenshot](images/atlas-taxi.png)

**Tech Stack:**  
![React](https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=black)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)
![Express](https://img.shields.io/badge/Express.js-000000?style=for-the-badge&logo=express&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-4EA94B?style=for-the-badge&logo=mongodb&logoColor=white)
![JWT](https://img.shields.io/badge/JWT-000000?style=for-the-badge)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=github-actions&logoColor=white)

🔗 **Live Demo:** https://atlastaxi.netlify.app  
🔗 **Frontend Repo:** https://github.com/alikirat/atlas-taxi-frontend  
🔗 **Backend Repo:** https://github.com/alikirat/atlas-taxi-backend

**Highlights**
- 🔐 JWT authentication with bcrypt, secure httpOnly cookies, and role-based access control
- 📅 Ride scheduling, cancellation, and admin management dashboard
- 🔁 12+ protected REST API endpoints with validation and error handling
- 🗄 MongoDB data modeling with indexing
- 🧪 Vitest + Supertest test suite against an in-memory MongoDB
- ☁️ CI/CD deployment via GitHub Actions to Netlify and Render
- 📜 Licensed PolyForm Shield: source-available, not open source

---

### 🤖 Chatbot: AI Chat App with Per-User Accounts

A chat app built with the Groq API, with JWT-based user accounts so each person's conversation history is private to their own account.

![Chatbot screenshot](images/chatbot.png)

**Tech Stack:**  
![React](https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=black)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)
![Express](https://img.shields.io/badge/Express.js-000000?style=for-the-badge&logo=express&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-4EA94B?style=for-the-badge&logo=mongodb&logoColor=white)
![Groq](https://img.shields.io/badge/Groq_API-F55036?style=for-the-badge)
![JWT](https://img.shields.io/badge/JWT-000000?style=for-the-badge)

🔗 **Live Demo:** https://akdev-chatbot.netlify.app  
🔗 **Frontend Repo:** https://github.com/alikirat/chatbot  
🔗 **Backend Repo:** https://github.com/alikirat/chatbot-backend

**Highlights**
- 🔐 JWT-based user accounts (register/login), bcrypt-hashed passwords
- 🔒 Chats scoped per user, with ownership checks on every read/write
- 💬 Groq-powered chat responses with persistent conversation history
- 🧪 Vitest + Supertest test suite against an in-memory MongoDB
- 🔑 One-click demo login for trying it out without signing up

---

### 🎯 JobMatch AI: AI-Powered Job Search Assistant

An AI-powered job search assistant that ingests job postings, scores them against your resume, analyzes skill gaps, and helps optimize your resume content, surfaced through a swipeable review interface.

![JobMatch AI screenshot](images/jobmatch-ai.png)

**Tech Stack:**  
![React](https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=black)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-4EA94B?style=for-the-badge&logo=mongodb&logoColor=white)
![Google ADK](https://img.shields.io/badge/Google_ADK-4285F4?style=for-the-badge&logo=google&logoColor=white)
![Gemini](https://img.shields.io/badge/Gemini-8E75B2?style=for-the-badge&logo=google&logoColor=white)

🔗 **Repo:** https://github.com/alikirat/jobmatch-ai

**Highlights**
- 🔁 Multi-stage agent graph: ingest → ATS gate check → semantic fit scoring → gap analysis → resume optimization
- ⚙️ FastAPI backend with MongoDB persistence
- 📱 React + TypeScript swipeable review interface
- 🤖 Google ADK 2.0 workflow powered by Gemini
- 🔌 Adzuna API integration for live job ingestion
- 📜 Licensed PolyForm Noncommercial: source-available, not open source

---

### 🎧 Customer Support Graph Agent: Multi-Agent Support Routing

A graph-based AI customer support representative built with Google ADK 2.0. Classifies incoming customer queries and routes them to a shipping FAQ agent or a polite decline node for out-of-scope requests.

![Customer Support Graph Agent workflow](images/customer-support-agent.png)

**Tech Stack:**  
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Google ADK](https://img.shields.io/badge/Google_ADK-4285F4?style=for-the-badge&logo=google&logoColor=white)
![Gemini](https://img.shields.io/badge/Gemini-8E75B2?style=for-the-badge&logo=google&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)

🔗 **Repo:** https://github.com/alikirat/customer-support-agent

**Highlights**
- 🧭 Graph workflow with Pydantic-based query classification
- 📦 Shipping FAQ agent with playful, emoji-rich responses
- 🚫 Polite decline routing for out-of-scope queries
- 🧪 Unit-tested with ruff/ty validation
- 🐳 Dockerized for deployment

---

### 📦 Equipment Tracker: Internal Asset Checkout System

An internal tool for tracking physical equipment and asset checkouts. Staff check items in and out with live status updates, admins manage the catalog and checkout history through a separate panel.

![Equipment Tracker screenshot](images/equipment-tracker.png)

**Tech Stack:**  
![Laravel](https://img.shields.io/badge/Laravel-FF2D20?style=for-the-badge&logo=laravel&logoColor=white)
![Livewire](https://img.shields.io/badge/Livewire-4E56A6?style=for-the-badge)
![Alpine.js](https://img.shields.io/badge/Alpine.js-8BC0D0?style=for-the-badge&logo=alpinedotjs&logoColor=black)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)
![FilamentPHP](https://img.shields.io/badge/FilamentPHP-F59E0B?style=for-the-badge)
![PHP](https://img.shields.io/badge/PHP-777BB4?style=for-the-badge&logo=php&logoColor=white)

🔗 **Repo:** https://github.com/alikirat/equipment-tracker

**Highlights**
- 🔁 Livewire check-out/check-in flow, no page reloads
- 🔍 Alpine-powered live search on the equipment list
- 📧 Queued overdue-return email notification, dispatched as a real job
- 📝 Event/listener pair logging every checkout
- 🗂️ FilamentPHP admin panel with read-only checkout history to protect the audit trail
- 📜 Licensed PolyForm Shield: source-available, not open source

---

## 🛠️ Tech Stack

### Languages
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![PHP](https://img.shields.io/badge/PHP-777BB4?style=for-the-badge&logo=php&logoColor=white)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)

### Frontend
![React](https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=black)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)
![React Router](https://img.shields.io/badge/React_Router-CA4245?style=for-the-badge&logo=react-router&logoColor=white)
![Bootstrap](https://img.shields.io/badge/Bootstrap-7952B3?style=for-the-badge&logo=bootstrap&logoColor=white)

### Backend & Database
![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)
![Express.js](https://img.shields.io/badge/Express.js-000000?style=for-the-badge&logo=express&logoColor=white)
![Laravel](https://img.shields.io/badge/Laravel-FF2D20?style=for-the-badge&logo=laravel&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-4EA94B?style=for-the-badge&logo=mongodb&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white)

### AI & LLM
![Anthropic](https://img.shields.io/badge/Anthropic_Claude-000000?style=for-the-badge)
![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=for-the-badge&logo=openai&logoColor=white)
![Google ADK](https://img.shields.io/badge/Google_ADK-4285F4?style=for-the-badge&logo=google&logoColor=white)
![GitHub Copilot](https://img.shields.io/badge/GitHub_Copilot-000000?style=for-the-badge&logo=github&logoColor=white)

### Cloud & DevOps
![AWS](https://img.shields.io/badge/AWS-FF9900?style=for-the-badge&logo=amazonaws&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=github-actions&logoColor=white)
![Netlify](https://img.shields.io/badge/Netlify-00C7B7?style=for-the-badge&logo=netlify&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)

### Tools
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![Postman](https://img.shields.io/badge/Postman-FF6C37?style=for-the-badge&logo=postman&logoColor=white)
![VS Code](https://img.shields.io/badge/VS_Code-007ACC?style=for-the-badge&logo=visual-studio-code&logoColor=white)
![Figma](https://img.shields.io/badge/Figma-F24E1E?style=for-the-badge&logo=figma&logoColor=white)

---

## 🏆 Certifications

- 🤖 **AI Agents Intensive**: Kaggle x Google | Dec 2025 | Multi-agent systems, LLM orchestration, tool use, and evaluation using Gemini and Google ADK
- 💻 **Frontend Development**: Skillcrush | Dec 2022
- ⚙️ **Software Engineering**: Per Scholas | Apr 2025 | Full-Stack JavaScript, TypeScript, React, Node.js

---

## 📊 GitHub Stats

![GitHub Stats](https://github-readme-stats.vercel.app/api?username=alikirat&show_icons=true&theme=tokyonight)
![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=alikirat&layout=compact&theme=tokyonight)

---

## 🤝 Let's Connect

I'm actively seeking **full-stack** and **AI-focused** software engineering roles.

[![Portfolio](https://img.shields.io/badge/Portfolio-alikirat.netlify.app-00C7B7?style=for-the-badge&logo=netlify&logoColor=white)](https://alikirat.netlify.app)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-ali--kirat-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/ali-kirat)
[![Email](https://img.shields.io/badge/Email-alikirat.dev@gmail.com-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:alikirat.dev@gmail.com)
