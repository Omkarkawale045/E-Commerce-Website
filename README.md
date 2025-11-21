# E-Commerce-Website
A full-stack eCommerce platform built with HTML, CSS, JavaScript, React.js, Node.js, Express.js, and MongoDB. This project allows users to browse products, add items to cart, and securely place orders. It includes both frontend UI and a backend REST API with authentication and database integration.

# ⚙️ Installation & Setup Guide

Follow the steps below to install and run this full-stack eCommerce project on your local machine.

# 📌 Prerequisites

Ensure the following are installed on your system:

Node.js

Git

MongoDB Atlas Account

(Optional) Stripe / Razorpay Account

Cloudinary Account

# 🚀 Step 1 — Install Node.js

(⚠️ Skip if already installed)

Visit the official Node.js website
👉 https://nodejs.org/en/download/

Download the installer

Install and follow the setup prompts

# 🛠️ Backend Setup

⚠️ You must run the backend before starting frontend or admin panel.

Open the project folder in VS Code

Right-click on the backend folder → Open in Integrated Terminal

Install dependencies:

```bash
npm install
```

Create a .env file inside the backend folder and add the required configuration:

# 🔧 Setup Cloudinary

```Create an account: https://cloudinary.com/```

Go to Dashboard

Copy the following credentials and paste them into .env:

```CLOUD_NAME=your_cloud_name
CLOUD_API_KEY=your_api_key
CLOUD_API_SECRET=your_secret
```
# 🗄️ Setup MongoDB

Go to MongoDB Atlas
```
👉 https://www.mongodb.com/cloud/atlas/register
```
Create a project & cluster (M0 Free Tier)

Create a database user (⚠️ avoid @ symbol in password)

Whitelist IP → 0.0.0.0/0

Click Connect → Compass

Copy the connection string and paste in .env:

```MONGODB_URI=your_mongodb_connection_string ```

(Replace <password> with the password created earlier — do not add / at the end.)

# 💳 Setup Payment Gateway (Optional)
Stripe Setup

```Create account: https://stripe.com```
Copy Secret Key from dashboard and add to .env:

```STRIPE_SECRET_KEY=your_stripe_secret```   

Razorpay Setup

```Create account: https://razorpay.com```

Copy Key ID and Secret Key and add to .env:
```
RAZORPAY_KEY_ID=your_key_id
RAZORPAY_SECRET=your_secret_key
```

# ▶️ Run Backend
```
npm run server
```

Make sure the backend is running before starting the frontend or admin panel.

# 🖥️ Frontend Setup

Right-click on the frontend folder → Open in Integrated Terminal

Install dependencies:

```
npm install
```

Start the frontend:

```
npm run dev
```

Open the link generated in terminal (usually):
```
http://localhost:5173
```
# 🛠️ Admin Panel Setup

Right-click on the admin folder → Open in Integrated Terminal

Install dependencies:

```
npm install
```

Start the admin panel:
```
npm run dev
```


Open the generated link in the browser (usually):

```
http://localhost:5174
```
