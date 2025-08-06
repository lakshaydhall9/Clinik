# Clinik

Clinik is a full-stack web application for booking doctor appointments, featuring authentication for Patients, Doctors, and Admins. It supports secure payments and is built with modern technologies.

---

## 🛠️ Tech Stack

- **Frontend**: React.js (admin and user panels)
- **Backend**: Node.js, Express.js
- **Database**: MongoDB
- **Authentication**: JWT
- **Payments**: Razorpay (integrated), Stripe (integration in progress)

---

## 🚀 Getting Started

### 1. Clone the Repository

```sh
git clone https://github.com/your-username/Clinik.git
cd Clinik
```

### 2. Install Dependencies

#### Backend

```sh
cd backend
npm install
```

#### Admin Panel

```sh
cd ../admin
npm install
```

#### Frontend (User Panel)

```sh
cd ../frontend
npm install
```

### 3. Configure Environment Variables

Create a `.env` file in the `backend` folder with the following (sample values):

```env
PORT=4000
MONGODB_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret

ADMIN_EMAIL=admin@example.com
ADMIN_PASSWORD=Passw0rd!

CLOUDINARY_NAME=your_cloudinary_name
CLOUDINARY_API_KEY=your_cloudinary_api_key
CLOUDINARY_SECRET_KEY=your_cloudinary_secret_key

RAZORPAY_KEY_ID=your_razorpay_key_id
VITE_RAZORPAY_KEY_ID=your_razorpay_key_id
RAZORPAY_KEY_SECRET=your_razorpay_key_secret
```

> Razorpay integration is complete; Stripe integration is in progress.

### 4. Start the Servers

#### Backend

```sh
cd backend
npm run start
```

#### Admin Panel

```sh
cd admin
npm run dev
```

#### Frontend (User Panel)

```sh
cd frontend
npm run dev
```

---

## 🔑 Admin Credentials

- **Email**: `admin@example.com`
- **Password**: `Passw0rd!`

---

## 📦 Folder Structure

```plaintext
Clinik/
├── admin/      # Admin Panel (React.js)
├── backend/    # Backend (Node.js, Express.js)
├── frontend/   # User Panel (React.js)
```

---
