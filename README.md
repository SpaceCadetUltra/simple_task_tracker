# 📝 Tasker CLI

A simple, user-friendly command-line To-Do list application written in Python. Manage your tasks directly from the terminal without relying on third-party software or complex UIs. Perfect for beginners learning Python or anyone looking for a lightweight task manager.

> 🔗 GitHub Repository: [SpaceCadetUltra/simple_task_tracker](https://github.com/SpaceCadetUltra/simple_task_tracker/tree/main)

---

## 🚀 Features

- ✅ Add, update, and delete tasks  
- 📋 View all tasks or filter by status (done, not done, in progress)  
- 🔢 Sort tasks by ID, title, or status  
- 💾 All data stored locally in a `tasks.json` file  
- 🧠 Simple structure, easy to extend  

---

## 📦 Installation

1. **Clone the repo**:

   ```bash
   git clone https://github.com/SpaceCadetUltra/simple_task_tracker.git
   cd simple_task_tracker
   ```

2. **Run with Python**:

   ```bash
   python tasker.py
   ```

---

## 🛠 How to Use

Once running, you’ll see a menu of available commands:

```
Available commands:
add
list
list_done
list_not_done
list_in_progress
update
delete
exit
```

### ✍️ Add a Task
```bash
add
```

### 📃 List Tasks
```bash
list
```
You’ll be prompted to sort by:
- `id`
- `status`
- `title`

### 🔄 Update a Task
```bash
update
```
Provide the task ID and the new status (`not done`, `in progress`, `done`).

### ❌ Delete a Task
```bash
delete
```
Provide the task ID to remove it.

---

## 🧪 Packaging as an .exe (Optional)

If you'd like to share this as a standalone Windows `.exe`:

1. Install PyInstaller:

   ```bash
   pip install pyinstaller
   ```

2. Create the executable:

   ```bash
   pyinstaller --onefile tasker.py
   ```

3. Your `.exe` will be in the `/dist` folder.

---

## 📁 File Structure

```
simple_task_tracker/
│
├── tasker.py        # Main Python script
├── tasks.json       # Auto-created on first run to store tasks
└── README.md        # You're here!
```

---

## 📌 Requirements

- Python 3.x  
- No external libraries needed

---

roadmap: https://roadmap.sh/projects/task-tracker


## 📄 License

This project is open-source and free to use under the MIT License.
