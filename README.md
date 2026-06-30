# 📋 Kanban Board

A simple and interactive **Kanban Board** built using **HTML, CSS, and JavaScript**. Users can create, organize, move, and delete tasks across different workflow stages. Tasks are automatically saved using **Local Storage**, so they remain available even after refreshing the page.

---

## 🚀 Features

- ✅ Create new tasks
- 📌 Drag and drop tasks between columns
- 🗑️ Delete tasks
- 💾 Save tasks using Local Storage
- 🔄 Restore tasks after page refresh
- 📊 Live task count for each column
- 🌙 Clean and responsive dark UI
- 🪟 Modal popup for adding tasks

---

## 🛠️ Built With

- HTML5
- CSS3
- Vanilla JavaScript
- Local Storage API

---

## 📂 Project Structure

```
kanban-board/
│
├── index.html
├── style.css
├── script.js
└── README.md
```

---



## ⚙️ How It Works

### Add a Task

- Click **Add New Task**
- Enter the task title and description
- Click **Add Task**

The task is added to the **To Do** column.

---

### Drag & Drop

Tasks can be dragged between:

- 📝 To Do
- 🚧 In Progress
- ✅ Done

The board automatically updates and saves the new task positions.

---

### Delete a Task

Click the **Delete** button on any task to remove it.

The task is removed from:

- The UI
- Local Storage

---

### Local Storage

Tasks are stored inside the browser using:

```javascript
localStorage.setItem("tasks", JSON.stringify(tasksData));
```

When the page loads:

```javascript
JSON.parse(localStorage.getItem("tasks"));
```

restores all previously saved tasks.

---

## 📚 JavaScript Concepts Used

- DOM Manipulation
- Event Listeners
- Drag & Drop API
- Arrow Functions
- Arrays
- Objects
- `Array.from()`
- `map()`
- `forEach()`
- `querySelector()`
- Local Storage
- Template Literals
- Dynamic Element Creation

---

## 🎯 Future Improvements

- ✏️ Edit existing tasks
- 🎨 Task priority colors
- 📅 Due dates
- 🔍 Search tasks
- 🏷️ Task labels/tags
- 🌙 Light/Dark theme toggle
- 📱 Improved mobile experience
- 📦 Export/Import tasks
- 👤 User authentication
- ☁️ Backend database integration

---

## 📖 What I Learned

While building this project, I learned how to:

- Build dynamic user interfaces using JavaScript
- Create HTML elements programmatically
- Implement drag-and-drop functionality
- Persist application state using Local Storage
- Organize JavaScript code into reusable functions
- Handle user interactions with event listeners

---

## 🚀 Getting Started

1. Clone the repository

```bash
git clone https://github.com/your-username/kanban-board.git
```

2. Navigate to the project

```bash
cd kanban-board
```

3. Open `index.html` in your browser.

---

## 👨‍💻 Author

**Piyush**

GitHub: https://github.com/your-username

---

## ⭐ If you like this project

Give this repository a ⭐ on GitHub!