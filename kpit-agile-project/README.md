# 🚀 Agile Project Management Tool

A full-stack web application designed to manage projects for small teams using an agile workflow. This tool allows users to organize work in a structured hierarchy: **Project → User Story → Task**.

---

## 📌 Project Overview

This application helps teams (3–10 users) to:

- Create and manage projects
- Break work into user stories and tasks
- Track progress with status updates
- Organize tasks efficiently

Built as part of a **Full-Stack Intern Assignment** focusing on real-world application design and development .

---

## 🏗️ Tech Stack

### 🔹 Frontend

- **HTML**
- **CSS**
- JavaScript

### 🔹 Backend

- Python (Flask)
- **REST** APIs

### 🔹 Database

- SQLite (lightweight and sufficient for small teams)

---

## 📂 Project Structure

``` **KPTI**-**AGILE**-**PROJECT**/ │ ├── backend/ │   ├── app.py │   ├── models.py │   ├── routes.py │   └── requirements.txt │ ├── frontend/ │   ├── index.html │   ├── style.css │   └── app.js │ ├── .gitignore └── **README**.md ```

---

## ⚙️ Features

- ✅ Create Projects
- ✅ Add User Stories inside Projects
- ✅ Add Tasks inside User Stories
- ✅ Update status (e.g., Pending, In Progress, Done)
- ✅ Hierarchical data structure
- ✅ **REST** **API** integration
- ✅ Simple and responsive UI

---

## 🔗 API Overview

| Method | Endpoint  | Description      |
| ------ | --------- | ---------------- |
| GET    | /projects | Get all projects |
| POST   | /projects | Create project   |
| GET    | /stories  | Get user stories |
| POST   | /stories  | Create story     |
| GET    | /tasks    | Get tasks        |
| POST   | /tasks    | Create task      |

---

## ▶️ How to Run the Project

### 🔹 1. Clone Repository

```bash git clone [https://github.com/your-username/agile-project-management.git](https://github.com/your-username/agile-project-management.git) cd agile-project-management ```

### 🔹 2. Setup Backend

```bash cd backend pip install -r requirements.txt python app.py ```

### 🔹 3. Run Frontend

- Open `frontend/index.html` in browser
  **OR**
- Use Live Server in VS Code

---

## 🔄 Async / Background Workflow

- Can include features like:

    * Notifications
    * Task reminders
    * Auto status updates

(Current implementation can be extended for async processing.)

---

## 🧠 Design Decisions

- Used **Flask** for simplicity and fast development
- Chose **SQLite** for lightweight storage
- Separated frontend and backend for scalability
- **REST** APIs for clean communication

---

## 🔐 Security Considerations

- Input validation required
- Avoid **SQL** injection (use **ORM**)
- **CORS** handling for frontend-backend communication
- Authentication can be added in future

---

## 🤖 AI Usage

AI tools (like ChatGPT) were used for:

- Debugging
- UI improvements
- Code structuring
- Documentation

---

## 🚧 Future Improvements

- 🔐 User authentication system
- 📊 Dashboard with analytics
- 🧲 Drag & drop tasks (Trello style)
- 🎨 Better UI/UX
- ☁️ Deployment (**AWS** / Render)
- 🔔 Real-time notifications

---

## 🎥 Optional

- Demo Video: (Add link)
- Live Demo: (Add link)

---

## 👩‍💻 Author

**Anjali Singh**

---

⭐ If you like this project, give it a star on GitHub!