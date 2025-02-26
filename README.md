# Next Auth with MongoDB

A secure authentication system built with Next.js, TypeScript, and MongoDB. This repository provides a robust authentication solution, including email verification, session management, and password reset functionality.  

## 🚀 Tech Stack  
- **Next.js** – React framework for server-side rendering and static site generation.  
- **TypeScript** – Ensuring type safety and maintainability.  
- **MongoDB** – NoSQL database for efficient data storage.  
- **Mailtrap** – For handling email-based functionalities.  

## ✨ Features  
✔️ User registration and login  
✔️ Email verification with secure token-based authentication  
✔️ Session-based authentication for persistent login  
✔️ Password reset functionality via email  
✔️ Secure password encryption  

## 🔧 Getting Started  

### 1️⃣ Clone the repository  
```bash
git clone https://github.com/yourusername/next-auth.git
cd next-auth
```

### 2️⃣ Install dependencies  
```bash
npm install
# or
yarn install
# or
pnpm install
```

### 3️⃣ Set up environment variables  
Create a `.env.local` file in the root directory and add the following:  
```
MONGODB_URI=your_mongodb_connection_string
NEXTAUTH_SECRET=your_secret_key
MAILTRAP_USER=your_mailtrap_username
MAILTRAP_PASS=your_mailtrap_password
```

### 4️⃣ Run the development server  
```bash
npm run dev
# or
yarn dev
# or
pnpm dev
```

Your app should now be running on `http://localhost:3000` 🎉
