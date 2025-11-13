# 🧾 React To-Do List Application

A simple To-Do List application built using **React (Vite)**.  
This project allows users to **add, edit, delete, and mark tasks as completed**.  
It follows the assignment requirements for components, props, state, event handling, and Git usage.

---

## 🚀 Features

✅ Add new tasks  
✅ Delete existing tasks  
✅ Mark tasks as completed  
✅ Edit existing tasks  
✅ Styled with clean UI using CSS  
✅ Built using React functional components, state, and props

---

## 🧩 Project Structure

todo-app/
│
├── src/
│ ├── components/
│ │ ├── Header.jsx
│ │ ├── ToDoList.jsx
│ │ └── ToDoItem.jsx
│ ├── App.jsx
│ ├── App.css
│ └── main.jsx
│
├── index.html
├── package.json
└── README.md

yaml
Copy code

---

## ⚙️ Technologies Used

- React (Vite)
- JavaScript (ES6)
- CSS (Flexbox + basic styling)
- Git & GitHub

---

## 🧠 How to Run the Application

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/your-username/todo-app.git
cd todo-app
2️⃣ Install Dependencies
bash
Copy code
npm install
3️⃣ Start the Development Server
bash
Copy code
npm run dev
Then open the provided localhost URL in your browser (e.g., http://localhost:5173)

🧱 Coding Steps
Step 1: Create Project with Vite
bash
Copy code
npm create vite@latest todo-app -- --template react
cd todo-app
npm install
Step 2: Create Components
Inside the src/components/ folder, create:

Header.jsx

ToDoList.jsx

ToDoItem.jsx

Each component should use props to receive data and functions.

Step 3: Manage State in App.jsx
Use useState() to store the list of to-do items.

Pass state and handler functions to child components.

Step 4: Implement Event Handling
Add new tasks with an input and button.

Mark as completed using a checkbox or toggle.

Delete a task using a delete button.

Edit an existing task inline or via input.

Step 5: Style the Application
Use App.css for custom styling.
Example snippet:

css
Copy code
.app {
  max-width: 500px;
  margin: 40px auto;
  padding: 20px;
  text-align: center;
  background: #f9f9f9;
  border-radius: 10px;
  box-shadow: 0 0 10px #ccc;
}
🧾 Git and GitHub Steps
Initialize Git
bash
Copy code
git init
Add Remote Repository
bash
Copy code
git remote add origin https://github.com/your-username/todo-app.git
Add and Commit Files
bash
Copy code
git add .
git commit -m "Initial commit - setup Vite React project"
Push to GitHub
bash
Copy code
git branch -M main
git push -u origin main
Add More Commits (At least 5)
bash
Copy code
git add .
git commit -m "Added Header component"
git push

git add .
git commit -m "Implemented add and delete task functionality"
git push

git add .
git commit -m "Added edit and mark as completed feature"
git push

git add .
git commit -m "Styled app using CSS"
git push

git add .
git commit -m "Updated README file"
git push
✅ Submission Checklist
 Project created using Vite

 Contains 4 components: App, Header, ToDoList, ToDoItem

 Functional features: Add, Delete, Edit, Mark Complete

 Proper state and props usage

 Styled for user-friendly experience

 Minimum 5 commits on GitHub

 node_modules folder removed before upload

 README file with setup instructions included

👩‍💻 Author
Boppudi Indu Sri
📧github link:
🔗 https://github.com/Boppudi-Indusri/