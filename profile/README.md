# Team Management System

| Nama                    | NRP        | GitHub                                                                                           |
| ----------------------- | ---------- | ------------------------------------------------------------------------------------------------ |
| Syarifah Talitha Erfany | 5025211175 | [![Syarifah Talitha Erfany](https://skillicons.dev/icons?i=github)](https://github.com/tlithaee) |
| Wan Sabrina Mayzura     | 5025211023 | [![Wan Sabrina Mayzura](https://skillicons.dev/icons?i=github)](https://github.com/wansabrina)   |

---

## 📌 Project Overview

The **Team Management System** is a platform designed to manage team and assign tasks effectively. It enables team members to be added to teams, tasks to be created, and users to be assigned to specific tasks within the team.

## ⚙️ Technologies Used

- **Backend:** Go (Golang), Gin (Web Framework), GORM (ORM for Database)
- **Frontend:** Next.js
- **Database:** MySQL

## 🎥 Video Demo

You can check out a demo of the system here: [Video Demo Link](https://youtu.be/Sw7O-Jah9dk)

## 🛠 Features

1. **Add Users to Teams:**
   - Admins can add new users to the team during team creation or through the team settings.
2. **Create and Manage Tasks within a Team:**
   - Users can create tasks for their teams with titles, descriptions, due dates, and status updates.
3. **Assign Tasks to Users:**
   - Tasks can be assigned to specific users within the team for better task management.

## 💻 Setup Instructions

### Backend Setup (Go)

1. Clone the repository:

   ```bash
   git clone https://github.com/Team-Management-Sytem/Backend-Golang
   cd Backend-Golang
   ```

2. Run the backend server:
   ```bash
   go run main.go
   ```

This will start the Go backend server.

### Frontend Setup (Next.js)

1. Clone the repository and navigate to the frontend folder:

   ```bash
   git clone https://github.com/Team-Management-Sytem/Frontend-NextJS
   cd Frontend-NextJS
   ```

2. Install dependencies:

   ```bash
   pnpm install
   ```

3. Start the frontend server:

   ```bash
   pnpm dev
   ```

   This will start the Next.js frontend server at `http://localhost:3000`.

   Here's how you can structure the README for your Team Management System project with a section for the screenshots, dashboard, and explanations:

## Page Screenshots

Here are the screenshots of the web's pages:

1. **Sidebar and Task View**  
   This shows the sidebar with the list of teams (you can also delete teams from the sidebar) and the tasks assigned to the current user. You can view details of the tasks, such as the title, description, and due date.

   ![alt text](image.png)

2. **Add New Team**  
   In this section, you can create a new team by filling out the name and description. This action adds the new team to your team list.
   
   ![alt text](image-1.png)

3. **Team Details Page**  
   This screenshot displays the details of the selected team, with the ability to add users, delete users from the team, and manage tasks associated with that team.
   
   ![alt text](image-2.png)

4. **Edit Team Modal**  
   This modal allows editing the team's name and description, making it easy to update team details directly from the team management page.
   
   ![alt text](image-3.png)

5. **Team Management Page**  
   Here, you can add new members to a team, delete members, and manage tasks related to the team. The edit functionality allows modifying the team's details.
   
   ![alt text](image-4.png)

6. **Add User to the Team Modal**
   This modal allows adding a new user to a team by selecting the user from a dropdown list. It helps in managing team members effectively and assigning them to the respective teams.
   
   ![alt text](image-5.png) 

7. **Create New Task**  
    This is the screen for creating a new task, including setting the title, description, due date, and assigning it to a user.
    
    ![alt text](image-6.png)

8. **Edit Task Modal**  
    When editing a task, the modal provides an interface for updating the task's details, including the assignee, due date, status, and description.
    
    ![alt text](image-7.png)
