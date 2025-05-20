
# 📘 DailyLedger- Finance Management site


A full-stack web application inspired by the traditional "Khatabook" system — allowing users to securely manage their **Finance (records)**, track activity, and maintain a clean personal ledger.

---

---

## 🛠️ Tech Stack

- **Backend**: Node.js, Express.js  
- **Database**: MongoDB + Mongoose  
- **Templating Engine**: EJS  
- **Styling**: Tailwind CSS  
- **Utilities**:
  - `bcrypt` for secure password hashing  
  - `express-session` for session management  
  - `multer` for file uploads  

---

## 🔐 Features

- ✅ **User Authentication**  
  Secure registration and login with encrypted passwords.

- 👤 **Profile Management**  
  Update and manage user profile information.

- 📒 **Finance Management**  
  - Add new records  
  - View all entries  
  - Filter by date and criteria  
  - Status indicators for quick insights

- 🖼️ **File Uploads**  
  Upload and update profile pictures.

---

## 📂 Project Structure

khatabook-pjt/ ├── config/ # Configuration files (e.g., DB setup, middlewares) ├── controllers/ # Logic handling for routes ├── middlewares/ # Custom middlewares (auth, error handling, etc.) ├── models/ # Mongoose schemas ├── node_modules/ # Node.js modules ├── public/ # Static assets (CSS, images) │ └── css/ # Tailwind CSS file ├── routes/ # API and page route handlers ├── views/ # EJS templates for rendering pages ├── uploads/ # Uploaded profile pictures ├── .env # Environment variables (do not commit) ├── .gitignore # Git ignore file for node_modules, .env, etc. ├── app.js # Main app file ├── package-lock.json # Auto-generated, lock for dependencies ├── package.json # Project metadata and dependencies


---
📫 Let's Connect
LinkedIn – www.linkedin.com/in/ekant-pawar-0339742b7
GitHub – https://github.com/pawarekant

## 🚀 How to Run Locally

1. Clone the repository:
```bash
git clone https://github.com/pawarekant/khatabook-pjt.git
cd khatabook-pjt
npm install

2. Add a .env file in the root with the following:
MONGO_URI=your_mongodb_connection_string
SESSION_SECRET=your_secret_key

3. node app.js

_____




