Sure! Here's a **neatly formatted `README.md` file** for the [Ecommerce-Mern-Website](https://github.com/Rajatkumar2004/Ecommerce-Mern-Website) project — all in one file, clean and ready to paste directly into your repo:


# 🛒 Ecommerce MERN Website

A full-featured E-commerce platform built using the **MERN Stack** (MongoDB, Express, React, Node.js) with user authentication, product management, payment integration (Stripe & PayPal), and an admin dashboard.

---

## 🌐 Live Demo

🚀 **Demo:** _[https://nextamazonpro.vercel.app/]_  
🔐 **Admin Login:**
```bash
Email: admin@example.com
Password: admin123
````

---

## 🚀 Features

* 🔐 User Authentication with JWT (Register/Login)
* ✅ Email Verification & Password Reset via Nodemailer
* 🔑 Social Login (Google, GitHub, LinkedIn, Twitter using Passport.js)
* 🛍 Product Catalog with Search & Filters
* 💳 Stripe and PayPal Payment Integration
* 🧾 Order Placement and Tracking
* ⭐ Product Reviews (1 per purchased item)
* 📦 AWS S3 for Image Uploads
* ⚙️ Admin Dashboard for Managing Products, Users, Orders
* 🖼 Image Zoom on Hover
* 🧑‍💻 Profile Management
* 📲 Progressive Web App (PWA) Support
* 📱 Fully Responsive (Mobile + Desktop)

---

## 🛠 Tech Stack

**Frontend:**

* React.js
* Redux
* Axios
* Bootstrap 5

**Backend:**

* Node.js
* Express.js
* MongoDB (with Mongoose)
* Passport.js
* Stripe & PayPal SDKs
* Nodemailer
* AWS S3

---

## 📁 Folder Structure

```
Ecommerce-Mern-Website/
│
├── frontend/               # React frontend
│   ├── components/         # Reusable UI components
│   ├── pages/              # Page-level components
│   ├── redux/              # Redux store and slices
│   └── ...
│
├── backend/                # Node.js + Express API
│   ├── controllers/        # Business logic
│   ├── routes/             # API routes
│   ├── models/             # Mongoose schemas
│   ├── middleware/         # Auth & error handlers
│   └── ...
│
├── .env                    # Environment variables
├── README.md               # Project info
└── package.json            # Project metadata
```

---

## ⚙️ Setup & Installation

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/Rajatkumar2004/Ecommerce-Mern-Website.git
cd Ecommerce-Mern-Website
```

### 2️⃣ Backend Configuration

Create a `.env` file in the root directory:

```
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
EMAIL_USER=your_email@gmail.com
EMAIL_PASS=your_email_password
STRIPE_SECRET_KEY=your_stripe_secret
PAYPAL_CLIENT_ID=your_paypal_client_id
AWS_ACCESS_KEY_ID=your_aws_key
AWS_SECRET_ACCESS_KEY=your_aws_secret
S3_BUCKET_NAME=your_bucket_name
```

Install backend dependencies:

```bash
npm install
```

### 3️⃣ Frontend Configuration

Navigate to the frontend directory:

```bash
cd frontend
```

Create a `.env` file:

```
REACT_APP_API_URL=http://localhost:5000
```

Install frontend dependencies:

```bash
npm install
```

---

## 🧪 Running the Application

From the project root:

```bash
npm run dev
```

This will run both the frontend and backend concurrently.

* Frontend: [http://localhost:3000](http://localhost:3000)
* Backend API: [http://localhost:5000](http://localhost:5000)

---

## 👨‍💼 Admin Functionality

* View and manage all users
* Add, update, delete products
* View and manage all orders
* Mark orders as delivered

---

## 👥 User Functionality

* Register/Login via email or social accounts
* Verify email address
* Browse products
* Add to cart and checkout
* Pay with Stripe or PayPal
* Leave reviews on purchased products
* View order history and details
* Edit profile

---

## 📸 Screenshots
<img width="840" height="958" alt="screenshort" src="https://github.com/user-attachments/assets/4be7900c-ff10-4a4c-98dc-fc60a147eb25" />
<img width="840" height="953" alt="Screenshot 2025-07-20 181457" src="https://github.com/user-attachments/assets/ad40e672-3386-4a6e-adbc-9f94ba2f2127" />
<img width="840" height="950" alt="Screenshot 2025-07-20 181507" src="https://github.com/user-attachments/assets/85525b25-38f4-4bc2-8836-23f338510e58" />


---

## 🤝 Contributing

Contributions are welcome!

```bash
1. Fork this repository
2. Create a new branch: git checkout -b feature/FeatureName
3. Commit your changes: git commit -m "Add new feature"
4. Push to your branch: git push origin feature/FeatureName
5. Open a Pull Request
```

---

## 📄 License

This project is licensed under the **MIT License**.
See the [LICENSE](./LICENSE) file for details.

---

## 🙌 Acknowledgements

* [React](https://reactjs.org/)
* [Node.js](https://nodejs.org/)
* [MongoDB](https://www.mongodb.com/)
* [Bootstrap](https://getbootstrap.com/)
* [Stripe](https://stripe.com/)
* [PayPal](https://paypal.com/)
* [AWS S3](https://aws.amazon.com/s3/)
* [Nodemailer](https://nodemailer.com/)
* [Passport.js](http://www.passportjs.org/)

---

> Built with ❤️ by [@Rajatkumar2004](https://github.com/Rajatkumar2004)

---


