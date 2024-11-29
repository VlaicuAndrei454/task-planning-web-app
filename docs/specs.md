# Objective
Develop a web app to streamline task management through creation, allocation, and monitoring of tasks.

## Features and Functionalities
1. **Task Management**: 
   - Managers can create tasks with descriptions and assign them to executing users.
   - Executing users can mark tasks as completed.
   - Managers can mark completed tasks as closed.

2. **User Roles**:
   - Admins can manage users (add/edit roles and assign managers to users).
   - Managers can create and assign tasks to users.
   - Executing users can view assigned tasks and track their completion history.

3. **Task History**:
   - Executing users can view their task completion history.
   - Managers can view task histories filtered by user or status.

4. **Notifications**:
   - Users receive notifications when tasks are assigned or updated.

## Technical Details
### Frontend
- Framework: React.js

### Backend
- Framework: Node.js
- REST API: Express.js
- Data Persistence: Sequelize ORM (for relational database)

### Database
- Relational Database: MySQL
- Key Tables:
  - Users
  - Tasks

### Deployment
- Server: AWS or Azure (free tier for students)
