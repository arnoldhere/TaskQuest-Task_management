# 📝 TaskQuest - MERN Stack Project

**TaskQuest** is a powerful task management system built using the **MERN Stack (MongoDB, Express.js, React.js, Node.js)**. It supports multiple user roles with strong authentication, role-based access control, and an intuitive, responsive UI.

---

## 🚀 Features

- **Three User Roles**:
  - **Admin**: Manage users, view detailed reports and system data.
  - **Team Leader**: Assign tasks to team members, monitor progress.
  - **Team Member**: View assigned tasks and update their status.

- **Authentication & Validation**:
  - Secure login/signup with JWT tokens.
  - Backend validation for all user inputs.
  - Passwords hashed using bcrypt.

- **Role-Based Access Control (RBAC)**:
  - Routes and actions are protected based on user roles.
  - Only authorized users can access specific features and data.

- **Admin Dashboard**:
  - View system reports: Active tasks, team statistics, task progress.
  - Manage users: Create, update, delete team leaders and members.

- **Task Management**:
  - Create, assign, update, delete tasks.
  - Status tracking: pending, in-progress, completed.

- **Responsive UI**:
  - Clean and responsive interface built with modern design practices.
  - Works seamlessly on mobile, tablet, and desktop devices.

- **Real-time Notifications** *(optional enhancement)*:
  - Alert users about new tasks or updates (using WebSocket or simple polling).

---

## 🛠️ Tech Stack

- **Frontend**: React.js, Redux (optional), Tailwind CSS / Bootstrap
- **Backend**: Node.js, Express.js
- **Database**: MongoDB (Mongoose ODM)
- **Authentication**: JWT (JSON Web Tokens), bcrypt
- **Authorization**: Custom RBAC middleware

---
# Project Setup
- Install necessary dependencies, libraries & toolkits  
```
> cd code/back
> npm i update
```
```
> cd code/front
> npm i update
```
