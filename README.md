# Task Management Application

A full-stack task management application designed for teams and individuals to efficiently manage tasks, track progress, and collaborate in real-time.

## Features

- **User Dashboard** – View assigned tasks, track progress, and get task insights.
- **Task Management** – Create, update, and track tasks with due dates and priorities.
- **Automated Status Updates** – Task status updates automatically based on checklist progress.
- **Team Collaboration** – Assign tasks to multiple users and track completion.
- **Priority & Progress Tracking** – Categorize tasks by priority and monitor completion levels.
- **Task Report Downloads** – Export task data for analysis and reporting.
- **Attachments Support** – Add and access task-related file links.
- **Responsive UI** – Optimized for desktop, tablet, and mobile devices.

## Tech Stack

### **Frontend**
- React.js
- Tailwind CSS v4
- Axios
- React Router DOM
- Chart.js (for data visualization)

### **Backend**
- Node.js
- Express.js
- MongoDB (Mongoose ODM)
- Multer (for file uploads)
- JWT Authentication


## Core Functionalities

### **User Management**
- Sign up / Login / Logout
- Role-based access control (Admin & User)
- Profile image upload

### **Task Management**
- Create, update, and delete tasks
- Assign tasks to multiple users
- Set due dates, priorities, and descriptions
- Checklist-based progress tracking

### **Reporting**
- Download overall tasks report
- Download detailed user task reports


##  Installation & Setup

### **Clone the repository**
- git clone https://github.com/SandithP2001/Task-Management-Application.git
- cd task-management-app

### **Install backend dependencies**
- cd backend
- npm install

### **Install frontend dependencies**
-cd frontend/Task-Manager
-npm install

### **Set environment variables - Create a .env file in the backend directory:**
-MONGO_URI=
-JWT_SECRET=
-ADMIN_INVITE_TOKEN=
-PORT=

### **Run the backend**
-cd backend
-npm run dev

### **Run the frontend**
-cd frontend/Task-Manager
-npm run dev
