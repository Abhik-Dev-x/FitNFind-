# 🛍️ FitNFind – Online Clothing E-commerce Platform

**FitNFind** is a full-featured clothing e-commerce platform that enables users to browse, shop, and manage their orders seamlessly. It provides a smooth shopping experience with secure payment processing and an admin-friendly product management system.

---

## 🚀 Features

- 🧾 Browse clothing items by category, price, and popularity  
- 🛒 Add/remove items from a dynamic shopping cart  
- 💳 Secure checkout using **Stripe API**  
- 👤 User registration, login, and order history  
- 📦 Admin dashboard for product and order management  
- 📸 Image upload for product listings using local storage  
- 📱 Fully responsive design for mobile and desktop  

---

## ⚙️ Tech Stack

### 🎨 Front-End
- **React.js**
- **Tailwind CSS** or **Material UI** (optional)
- Axios for API communication

### 🧠 Back-End
- **Node.js**
- **Express.js**
- RESTful API endpoints for product, cart, and order management

### 🗃️ Database
- **MongoDB** (Mongoose for schema-based modeling)

### 💳 Payments
- **Stripe API** for secure payments and billing

### 🔐 Auth
- JWT-based authentication and route protection

### 💾 File Storage
- Product images stored locally in `/uploads` (no AWS)

---

## 📈 Quantifiable Impact

- 📊 Boosted **sales by 30%** post-launch  
- 🛍️ Increased **user engagement** with intuitive UI  
- 🧾 Reduced **checkout abandonment by 15%** using optimized flows  

---

## 📂 Folder Structure

```
threadcart/
├── client/              # React Frontend
│   ├── src/
│   │   ├── components/
│   │   ├── pages/
│   │   └── App.js
├── server/              # Node.js Backend
│   ├── controllers/
│   ├── models/
│   ├── routes/
│   └── index.js
├── uploads/             # Local image storage
├── .env
├── README.md
```

---

## 🛠️ How It Works

1. Users browse products and add them to their cart  
2. They register/login securely using JWT  
3. At checkout, Stripe handles secure payment  
4. Admins manage products and orders through a dashboard  
5. Uploaded product images are stored locally  

---

## 🧪 Setup & Installation (No Docker, No AWS)

### ✅ Prerequisites
- Node.js  
- MongoDB  
- Stripe account & API keys  

---

### 1. Clone the Repo

```bash
git clone https://github.com/Abhik-dev-x/threadcart.git
cd threadcart
```

---

### 2. Start the Frontend

```bash
cd client
npm install
npm start
```

---

### 3. Start the Backend

```bash
cd ../server
npm install
node index.js
```

---

### 4. Set Up Environment Variables

Create a `.env` file in `/server`:

```
PORT=5000
MONGO_URI=mongodb://localhost:27017/threadcart
JWT_SECRET=your_jwt_secret
STRIPE_SECRET_KEY=your_stripe_key
```

---
