# Razorpay Payment Gateway Integration 💳

🔗 **Live Demo:** [Click Here](https://razorpay-demo-frontend-5p6n.onrender.com/)

This is a demo project that integrates the Razorpay Payment Gateway using **Node.js (Express)** for the backend and **React.js** for the frontend. A sample t-shirt product is displayed with a “Pay” button to initiate and verify payment using Razorpay.

---

## 📦 Features

- Display a sample product (t-shirt)
- Integrate Razorpay Checkout
- Generate payment order from backend
- Verify payment signature securely

---
## ⚙️ Tech Stack

- **Frontend**: React, CSS
- **Backend**: Node.js, Express
- **Payment Gateway**: Razorpay
- **Deployment**: Render

## 🛠️ How to Run Locally

### Prerequisites

- Node.js (v16 or v18 recommended)
- Razorpay test credentials from [Razorpay Dashboard](https://dashboard.razorpay.com/)

### 1. Clone the Repository

```bash
git clone https://github.com/vjy-07/Razorpay-Demo.git
cd Razorpay-Demo
```
### 2. Backend Setup
```
cd server
npm install
```

### 3. Create a .env file and add the following:
```
RAZORPAY_KEY_ID=your_key_id
RAZORPAY_SECRET=your_secret
PORT=4000
```
Then start the server: ``` npm start```

---

### 4. Frontend Setup
```
cd ../client
npm install
```
### 5. Create a .env file and add the following:
```
REACT_APP_API_URL=http://localhost:4000

```

Then start development server:  ``` npm start```
