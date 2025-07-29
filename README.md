# AIDCOM-LMS

AIDCOM-LMS is a Learning Management System (LMS) built to facilitate online education, course management, and student-teacher interaction.

## 📂 Project Structure
This project is structured into two main parts:

- **Backend (Node.js, Express)** – Handles user authentication, roles, courses, enrollments, and admin features.
- **Frontend (React JS)** – Provides role-based dashboards for Admin, Teacher, and Student using Material Dashboard 2 UI.

Local project folder name: `LMS`

---

## 🚀 Key Features

✅ Role-based login system (Admin, Teacher, Student)  
✅ Course creation, enrollment, and management  
✅ File upload/download (PDF, videos)  
✅ Live class schedule calendar  
✅ Notifications and notice board  
✅ Analytics for admins (total users, revenue, etc.)  
✅ AI-powered course recommendations  
✅ Chat/doubt discussion system (Socket.io)

---

## 🛠 Tech Stack

| Part      | Tech Used                          |
|-----------|------------------------------------|
| Frontend  | React JS, Tailwind CSS, Framer Motion, Axios |
| Backend   | Node.js, Express.js, MongoDB, Mongoose |
| UI Kit    | Material Dashboard 2 by Creative Tim |
| Realtime  | Socket.io                          |
| Tools     | Git, GitHub, VS Code               |

---

## 📦 Installation & Setup

```bash
# 1. Clone the repository
git clone https://github.com/chandanjaiswallove/AIDCOM-LMS.git
cd LMS

# 2. Navigate into client and install frontend dependencies
cd client
npm install

# 3. Navigate into server and install backend dependencies
cd ../server
npm install

# 4. Start both servers (suggest using concurrently or separate terminals)
npm start
