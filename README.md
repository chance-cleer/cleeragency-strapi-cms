# 🚀 Cleer Agency CMS (Strapi Backend)

This is the **Strapi backend** for [Cleer Agency](https://cleer.agency), a modern web agency specializing in building fast, scalable, and beautiful websites for **small businesses, hobbyists, and artists**.  

The CMS serves as the **content hub**, powering the frontend with structured data, media, and dynamic content management.

---

## ✨ Features

- ⚡ **Headless CMS** – Built with [Strapi](https://strapi.io/) for flexibility and scalability.  
- 🖼️ **Media Management** – Easily upload and manage images, icons, and media assets.  
- 🔑 **Authentication & Roles** – Secure API with role-based permissions.  
- 📡 **API-first** – REST & GraphQL support for frontend consumption.  
- ☁️ **Cloud-ready** – Deployable to **Render**, **Railway**, or **Heroku**.  
- 📱 **Decoupled Architecture** – Optimized for use with the [Cleer Agency frontend](https://cleer.agency).  

---

## 🛠️ Tech Stack

- **Framework:** [Strapi v5+](https://strapi.io/)  
- **Database:** SQLite (dev) → PostgreSQL (prod recommended)  
- **Media Storage:** [Cloudinary](https://cloudinary.com/) (free tier supported)  
- **Deployment:** Render / Railway / DigitalOcean / Vercel (frontend only)  

---

## 📂 Project Structure

📦 cleer-agency-cms
┣ 📂 src # Strapi source files
┣ 📂 public # Static assets
┣ 📂 database # SQLite dev database (gitignored)
┣ 📜 .env # Environment variables
┣ 📜 package.json
┗ 📜 README.md



---

## 🚀 Getting Started (Local Dev)

1. **Clone the repo**
   ```bash
   git clone https://github.com/your-username/cleer-agency-cms.git
   cd cleer-agency-cms


npm install



npm run develop