# Recruitment Management System 🚀

![MERN Stack](https://img.shields.io/badge/MERN-Stack-green) ![Status](https://img.shields.io/badge/Status-Completed-blue)

## 📖 Overview

The **Recruitment Management System** is a full-stack web application designed to streamline the hiring process. It serves as a centralized platform where **Recruiters** can post job openings and manage applications, while **Candidates** can search for jobs, view detailed descriptions, and apply securely. 

This project demonstrates a complete **MERN (MongoDB, Express, React, Node.js)** architecture, featuring role-based authentication, real-time database updates, and a responsive frontend interface.

---

## 📸 Screenshots

*(To add your screenshots, just drag and drop your image files directly into this section on GitHub)*

| **Secure Login** | **Recruiter Dashboard** |
|:---:|:---:|
| [Login Page](https://via.placeholder.com/500x300? text=Login+Screen+Screenshot) | [Dashboard](https://via.placeholder.com/500x300? text=Dashboard+Screenshot) |

---

## ✨ Key Features

### 🏢 For Recruiters (Admin)

- **Job Management:** Create, Read, Update, and Delete (CRUD) job postings.
- **Applicant Tracking:** View a list of candidates who have applied to specific roles.
- **Company Profiles:** Manage company details, logos, and descriptions.

### 👨‍💻 For Candidates (Users)

- **Advanced Search:** Filter jobs by category, location, and salary range.
- **One-Click Apply:** Seamless application process that links user profiles to job documents. 
- **User Dashboard:** Track status of applied jobs and manage resume details. 

### ⚙️ Technical Highlights

- **Secure Authentication:** Implemented using **JWT (JSON Web Tokens)** and bcrypt for password hashing.
- **State Management:** Utilized React Hooks (`useState`, `useEffect`) and Context API for global user state. 
- **RESTful API:** Designed a scalable backend API with Node.js and Express to handle HTTP requests efficiently.

---

## 🛠️ Tech Stack

| Layer | Technology |
|-------|------------|
| **Frontend** | React.js, Tailwind CSS |
| **Backend** | Node.js, Express. js |
| **Database** | MongoDB (Atlas or Local) |
| **Authentication** | JWT (JSON Web Tokens) |

---

## 🚀 How to Run Locally

This project is split into a **Client** (Frontend) and **Server** (Backend). Follow these steps to get it running: 

### 1. Clone the Repository

```bash
git clone https://github.com/VanshKardam/Recruitment-Management-System.git
cd Recruitment-Management-System
```

### 2. Install Backend Dependencies

```bash
# You are currently in the root folder
npm install
```

### 3. Install Frontend Dependencies

```bash
cd frontend
npm install
```

### 4. Configure Environment Variables

Create a `.env` file in the root directory and add your configuration:

```env
MONGO_URI=mongodb://localhost:27017/recruitment-system
PORT=5000
JWT_SECRET=your_secret_key_here
```

### 5. Run the Project

**Option A: Run Frontend Only**

```bash
cd frontend
npm run dev
# Access at http://localhost:5173
```

**Option B: Run Full Stack**

```bash
# In Root Terminal
npm start
```

---

## 📁 Project Structure

```
Recruitment-Management-System/
├── frontend/               # React. js frontend application
│   ├── src/
│   │   ├── components/     # Reusable UI components
│   │   ├── pages/          # Page components
│   │   └── context/        # React Context for state management
│   └── package.json
├── models/                 # MongoDB schemas
├── routes/                 # Express API routes
├── controllers/            # Route handlers
├── middleware/             # Authentication middleware
├── . env                    # Environment variables (create this)
├── server.js               # Express server entry point
└── package.json
```

---

## 🤝 Contributing

Contributions are welcome! Feel free to open an issue or submit a pull request. 

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

---

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

## 👤 Author

**Vansh Kardam**

- GitHub: [@VanshKardam](https://github.com/VanshKardam)
