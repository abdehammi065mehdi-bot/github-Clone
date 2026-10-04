# ApnaGitHub – GitHub Clone with Custom Git System

ApnaGitHub is a full-stack GitHub clone that replicates core version control workflows and repository management.

The application allows users to initialize repositories, stage files, create commits, push commits to cloud storage, and revert repositories to previous versions.

It also provides a GitHub-style user interface for interacting with repositories and viewing commit history.

## 🌐 Live Demo

The project is deployed and accessible online.

👉 **Live Application:**  
https://github-clone-frontend-izc1.onrender.com

## 🚀 Features

- GitHub-style repository interface
- Custom Git-like command system
- Initialize repositories
- Stage files and create commits
- Push commits to AWS S3 cloud storage
- Pull commits from cloud
- Revert repository to previous commits
- Secure authentication using JWT
- Real-time communication using Socket.io

## 🛠 Tech Stack

### Frontend

- React (Vite)
- React Router
- Axios
- Material UI
- Primer React
- React Heat Map

### Backend

- Node.js
- Express.js
- MongoDB
- Mongoose
- JWT Authentication
- bcryptjs

### Real-time

- Socket.io

### Cloud Services

- AWS S3

### CLI Tools

- Yargs

## ⚙️ Custom Git Commands

This project implements a simplified Git-like command system.

Available commands:

- init → initialize a repository
- add → add file to staging area
- commit → create a commit
- push → push commits to AWS S3
- pull → pull commits from cloud
- revert → revert repository to previous commit

#Example

node app.js init
node app.js add hello.txt
node app.js commit "initial commit"
node app.js push

## 📂 Project Structure

Apna_GitHub_clone
│
├── backend
│ ├── controllers
│ ├── models
│ ├── routes
│ ├── config
│ │ └── aws-config.js
│ └── app.js
│
├── frontend
│ ├── src
│ │ ├── components
│ │ ├── authContext
│ │ ├── routes
│ │ └── main.jsx
│
└── README.md

## 🔑 Environment Variables

Create a `.env` file in the backend folder.

Example:

PORT=3000
MONGODB_URL=your_mongodb_connection

AWS_ACCESS_KEY=your_access_key
AWS_SECRET_KEY=your_secret_key
AWS_REGION=your_region
S3_BUCKET=your_bucket_name

FRONTEND_URL=http://localhost:5173

## ⚙️ Installation

Clone the repository

git clone https://github.com/Mdirfan0786/github-Clone.git

Go to project folder

cd Apna_GitHub_clone

#Backend Setup

cd backend
npm install
npm run dev

## 🎯 Learning Outcomes

This project helped me understand:

- Version control system concepts
- Git workflow implementation
- Full-stack MERN architecture
- Cloud storage using AWS S3
- Real-time communication using Socket.io
- CLI tool development using Yargs

#Frontend setup

cd frontend
npm install
npm run dev

## 👨‍💻 Author

MD IRFAN

GitHub  
https://github.com/Mdirfan0786

LinkedIn  
https://www.linkedin.com/in/md-irfan-2623b4210/

portfolio
Portfolio: https://apna-portfolio-drab.vercel.app/
owner: [212649841917]
