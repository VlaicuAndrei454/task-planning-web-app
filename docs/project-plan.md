# Task Planning Web Application

## Overview
This application enables users to manage tasks efficiently by allowing task creation, allocation, monitoring, and status updates. It supports role-based user management (Admin, Manager, Executing User).

---

## Task Breakdown

### **Backend**
- Set up Node.js and Express.js environment.
- Implement database models:
  - **Users**: Role-based users (Admin, Manager, Executing User).
  - **Tasks**: Track status, assigned users, and timestamps.
- Create REST API endpoints for:
  - **User Management**: Add, update, and assign managers to users.
  - **Task Management**: CRUD for tasks and state transitions.
  - **History**: Fetch task history (by user, status, or date range).
- Implement JWT-based authentication and role-based access control.

### **Frontend**
- Build SPA with React.js.
- Design user-friendly interfaces for:
  - Login and authentication.
  - Manager dashboard to:
    - View and create tasks.
    - Assign tasks to users.
    - Monitor task statuses.
  - User dashboard to:
    - View assigned tasks.
    - Mark tasks as completed.
  - History views for completed tasks.
- Implement filters and sorting for tasks and history.
- Ensure responsiveness for mobile, tablet, and desktop.

### **Deployment**
- Deploy the backend to AWS/Azure.
- Host the frontend on a static site host.


## Roles and User Stories

### **Admin**
- Add and manage users, including assigning managers to executing users.

### **Manager**
- Create, assign, and monitor tasks.
- View task statuses and histories.

### **Executing User**
- View assigned tasks and mark them as completed.
- View historical tasks they’ve completed.
