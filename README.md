# DailyFlow - Smart Task Manager

> 🎯 A clean and efficient personal task management tool that helps you track daily tasks and smartly handle incomplete items.

---

## 🌟 Features

### 📋 Task Management
- ✅ Quickly add tasks with priority and importance settings
- ✅ Drag-and-drop sorting for flexible task ordering
- ✅ Click to view task details and record summaries
- ✅ Complete task operations: complete, edit, delete

### 📝 Subtask Lists
- ✅ Add multiple subtasks for each task
- ✅ Drag-and-drop sorting for subtasks
- ✅ Click subtask text to edit inline
- ✅ Real-time progress display

### 🔔 Smart Reminders
- ✅ Automatically show unfinished tasks the next day
- ✅ Options: Keep / Mark Complete / Discard
- ✅ Batch operations supported

### 💾 Data Safety
- ✅ Local storage, data never lost
- ✅ Export/Import JSON backup
- ✅ Auto-save, no manual operation needed

---

## 🎨 Preview

![DailyFlow Screenshot](preview.png)

---

## 🚀 Quick Start

### Online Access

**🌐 GitHub Pages (Recommended):**
👉 [https://lingbin-8801.github.io/dailyflow](https://lingbin-8801.github.io/dailyflow)

**📁 Open Locally:**
Just open `index.html` in your browser, no installation needed.

### Run Locally

```bash
# Clone the repository
git clone https://github.com/lingbin-8801/dailyflow.git

# Enter the directory
cd dailyflow

# Start a local server (optional)
python -m http.server 8000

# Open in browser: http://localhost:8000
```

---

## 🛠️ Tech Stack

| Technology | Purpose |
|---|---|
| **Vanilla JS** | Core logic |
| **CSS3 (CSS Variables)** | Styling & theming |
| **SortableJS** | Drag & drop |
| **Font Awesome 6** | Icons |
| **LocalStorage** | Data storage |

---

## 📖 Usage Guide

### Create a Task
1. Enter a task title in the top input box
2. Press Enter or click "Add"
3. Optional: Expand "Advanced Options" to set priority and importance

### Task Details
- Click the task content area to open the detail modal
- Record details in the "Task Summary" section
- Add subtasks in the "Subtask List" section

### Subtask Operations
- 📌 Drag the left handle to reorder
- ✏️ Click text to edit inline
- ✅ Click checkbox to mark complete
- 🗑️ Click × to delete

### Handle Unfinished Tasks
- Unfinished tasks from yesterday will pop up on first open each day
- Handle individually or batch process

---

## 🚀 Deploy to GitHub Pages

This project is configured with GitHub Pages auto-deployment. Every time you push to the `main` branch, GitHub Actions will automatically build and deploy to Pages.

**Setup Steps:**
1. Go to your repo's **Settings > Pages**
2. Select **GitHub Actions** as the source
3. Push code and wait for the Actions workflow to finish

> 👉 Visit: **https://lingbin-8801.github.io/dailyflow**

---

## 🤝 Contributing

Issues and Pull Requests are welcome!

---

## 📄 License

MIT License - Free to use and modify.

---

⭐ If this project helps you, please give it a Star!