# 🔁 File Sharing Web App

A full-stack file-sharing platform built with **MERN Stack** (MongoDB, Express.js, React, Node.js). This app lets users upload, store, and securely share files with others — just like WeTransfer or Google Drive, but custom-built!

---

## 🚀 Features

- 📤 Upload any type of file with progress indication  
- 🔗 Generate shareable download links  
- 📨 Share files directly via email  
- 🗂️ Secure file storage with metadata  
- 🧾 File history (recent uploads)  
- 🌐 Fully responsive UI with React  

---

## 🧱 Tech Stack

### 💻 Frontend
- React.js  
- Tailwind CSS  
- Axios  

### 🌐 Backend
- Node.js  
- Express.js  
- MongoDB (Mongoose)  
- Multer (for file uploads)  
- Nodemailer (for email sharing)  

---

## 📷 Screenshots

| Upload Page | File List | Email Share |
|-------------|-----------|-------------|
| ![upload](https://i.imgur.com/XYZupload.png) | ![list](https://i.imgur.com/XYZlist.png) | ![email](https://i.imgur.com/XYZemail.png) |

> 📝 Replace these image URLs with your own actual screenshots

---

## 🔧 Setup Instructions

### 1. Clone the repository
```bash
git clone https://github.com/AnantInamdar77/File-Sharing.git
cd File-Sharing
```

### 2. Install dependencies

#### Backend
```bash
cd server
npm install
```

#### Frontend
```bash
cd ../client
npm install
```

### 3. Configure Environment Variables

Create a `.env` file in `server/`:
```env
PORT=5000
MONGO_URI=your_mongodb_connection_string
EMAIL_USER=your_email@example.com
EMAIL_PASS=your_email_password
BASE_URL=http://localhost:5000
```

### 4. Run the App

#### Backend:
```bash
cd server
npm start
```

#### Frontend:
```bash
cd client
npm start
```

---

## ✨ How It Works

1. User uploads a file  
2. Backend stores file and generates a unique link  
3. User can copy the link or send it directly via email  
4. Recipient uses the link to download the file  

---

## 🤝 Author

**Anant Inamdar**  
📍 Full Stack Developer  
📬 [LinkedIn](https://www.linkedin.com/in/anantinamdar77)

---

## 📜 License

This project is open-source and free to use for personal or educational purposes.
