# Alatree Ventures Assignments

This project consists of a **Node.js/Express backend** and a **React (Vite) frontend**.  
The backend handles APIs, Stripe payments, file uploads, and MongoDB connection, while the frontend provides the UI.

---

## 📦 Project Setup

### 1. Clone the Repository
```bash
git clone https://github.com/<your-repo>.git
cd <your-repo>

###2. Environment Variables
Create .env files
In server folder:
PORT=5000
MONGODB_URI=your-mongodb-connection-string
STRIPE_SECRET_KEY=sk_test_your_stripe_secret_key

In frontend folder:
VITE_API_URL=http://localhost:5000
VITE_STRIPE_PUBLISHABLE_KEY=pk_test_your_stripe_publishable_key

## 3. Run Locally

Backend (Server)
cd server
npm install
node server.js


Frontend (React)
cd frontend
npm install
npm run dev
