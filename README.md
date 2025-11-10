# 🛒 SmartCartia - AI-Powered E-Commerce Platform

<div align="center">

[![Next.js](https://img.shields.io/badge/Next.js-14.0-black?style=for-the-badge&logo=next.js)](https://nextjs.org/)
[![React](https://img.shields.io/badge/React-18.0-blue?style=for-the-badge&logo=react)](https://reactjs.org/)
[![MongoDB](https://img.shields.io/badge/MongoDB-6.0-green?style=for-the-badge&logo=mongodb)](https://mongodb.com/)
[![Node.js](https://img.shields.io/badge/Node.js-18.0-green?style=for-the-badge&logo=node.js)](https://nodejs.org/)
[![Express](https://img.shields.io/badge/Express-4.18-lightgrey?style=for-the-badge&logo=express)](https://expressjs.com/)
[![TailwindCSS](https://img.shields.io/badge/Tailwind-3.4-38B2AC?style=for-the-badge&logo=tailwind-css)](https://tailwindcss.com/)

</div>

<p align="center">
  <img src="/public/project-banner.png" alt="SmartCartia Banner" width="800" />
</p>

## 🌟 Overview

**SmartCartia** is an AI-powered e-commerce platform that enhances online shopping with natural-language search, intelligent product recommendations, and a polished shopping experience. Built with modern frontend and backend technologies, SmartCartia is designed for performance, scalability, and extensibility.

---

## ✨ Key Features

- AI-powered natural language product search and recommendations  
- Full product catalog, categories, filtering, and variants  
- Shopping cart, wishlist, order management, and user profiles  
- Responsive UI with dark/light themes and accessible components  
- Analytics for product performance and user behavior  
- Secure authentication, data protection, and GDPR-aware handling

---

## 👨‍💻 My Role & Contribution

**Role:** API Integration & Database Management

**Key contributions I implemented:**
- Designed and implemented RESTful APIs for **products**, **categories**, **users**, and **orders** used by the frontend.
- Integrated backend with **MongoDB** using **Mongoose** and created the core schemas (`Product`, `User`, `Order`, `Category`).
- Implemented efficient query patterns and indexes to optimize read/write performance for product search and order flow.
- Built endpoints for natural-language search and recommendation integration used by the frontend AI features.
- Wrote API documentation and helped seed initial data for local development and testing.

---

## ⚡ Quick Start (local)

1. **Clone the repo**
   ```bash
   git clone https://github.com/farhanAhmed113/SmartCartia-AI-Powered-E-Commerce-Platform.git
   cd SmartCartia-AI-Powered-E-Commerce-Platform
Install dependencies

bash
Copy code
npm install
Create .env.local in the project root and add:

env
Copy code
MONGODB_URI=mongodb://localhost:27017/smartcartia
LLM_API_KEY=your_llm_api_key_here
JWT_SECRET=your-super-secret-jwt-key
NEXT_PUBLIC_BACKEND_URL=http://localhost:3001
Start MongoDB

bash
Copy code
mongod --dbpath C:\data\mongodb
Run migrations and seed data

bash
Copy code
npx migrate-mongo up
node db/seedData.js
Start servers

bash
Copy code
npm run dev
Open:

Frontend → http://localhost:3000

Backend → http://localhost:3001

✅ Demo Steps (for Interview)
Login or register

Search for products using natural language (e.g., “wireless earbuds under 5000”)

View details → Add to cart → Checkout

Show order in profile dashboard

“My contribution focused on the API integration and MongoDB database management.”

🗄️ Database Design (Summary)
Product → Product catalog with specs, price, stock

User → Customer accounts, hashed passwords

Order → Order tracking, payment details

Category → Multi-category product organization

Review → User feedback and ratings

Indexes added for optimized search and sorting.

🛠️ Deployment
Frontend: Vercel (Next.js)

Backend: Render / Railway / Heroku

Database: MongoDB Atlas

📞 Contact
GitHub: farhanAhmed113

Email: your-email@example.com

LinkedIn: https://www.linkedin.com/in/your-linkedin-profile

Built with ❤️ for the future of e-commerce
