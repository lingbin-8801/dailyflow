# DailyFlow - 智能任务管家 / Smart Task Manager

> 🎯 **中文**: 一款简洁高效的个人任务管理工具，帮助你追踪每日任务，智能处理未完成事项。  
> 🎯 **English**: A clean and efficient personal task management tool that helps you track daily tasks and smartly handle incomplete items.

---

## 🌟 功能特点 / Features

### 📋 任务管理 / Task Management
- ✅ **中文**: 快速添加任务，支持优先级和重要程度设置
- ✅ **English**: Quickly add tasks with priority and importance settings
- ✅ **中文**: 拖拽排序，灵活调整任务顺序
- ✅ **English**: Drag-and-drop sorting for flexible task ordering
- ✅ **中文**: 点击任务查看详情，记录任务概要
- ✅ **English**: Click to view task details and record summaries
- ✅ **中文**: 完成任务、编辑、删除等完整操作
- ✅ **English**: Complete task operations: complete, edit, delete

### 📝 子任务清单 / Subtask Lists
- ✅ **中文**: 为每个任务添加多个子任务
- ✅ **English**: Add multiple subtasks for each task
- ✅ **中文**: 子任务支持拖拽排序
- ✅ **English**: Drag-and-drop sorting for subtasks
- ✅ **中文**: 子任务点击即可编辑
- ✅ **English**: Click subtask text to edit inline
- ✅ **中文**: 实时显示完成进度
- ✅ **English**: Real-time progress display

### 🔔 智能提醒 / Smart Reminders
- ✅ **中文**: 第二天自动弹出未完成任务
- ✅ **English**: Automatically show unfinished tasks the next day
- ✅ **中文**: 可选择：保留到今天 / 标记完成 / 遗弃
- ✅ **English**: Options: Keep / Mark Complete / Discard
- ✅ **中文**: 支持批量操作
- ✅ **English**: Batch operations supported

### 💾 数据安全 / Data Safety
- ✅ **中文**: 本地存储，数据永不丢失
- ✅ **English**: Local storage, data never lost
- ✅ **中文**: 支持导出/导入 JSON 备份
- ✅ **English**: Export/Import JSON backup
- ✅ **中文**: 自动保存，无需手动操作
- ✅ **English**: Auto-save, no manual operation needed

---

## 🎨 界面预览 / Preview

![DailyFlow 界面 / DailyFlow Screenshot](preview.png)

---

## 🚀 快速开始 / Quick Start

### 在线访问 / Online Access

**🌐 GitHub Pages (推荐 / Recommended):**  
👉 [https://lingbin-8801.github.io/dailyflow](https://lingbin-8801.github.io/dailyflow)

**📁 本地打开 / Open Locally:**  
直接打开 `index.html` 文件即可使用，无需任何安装。  
Just open `index.html` in your browser, no installation needed.

### 本地运行 / Run Locally

```bash
# 克隆项目 / Clone the repository
git clone https://github.com/lingbin-8801/dailyflow.git

# 进入目录 / Enter the directory
cd dailyflow

# 使用 Python 启动本地服务器（可选）/ Start a local server (optional)
python -m http.server 8000

# 浏览器访问 / Open in browser: http://localhost:8000
```

---

## 🛠️ 技术栈 / Tech Stack

| 技术 / Technology | 用途 / Purpose |
|---|---|
| **原生 JavaScript (Vanilla JS)** | 核心逻辑 / Core logic |
| **CSS3 (CSS Variables)** | 样式主题 / Styling & theming |
| **SortableJS** | 拖拽排序 / Drag & drop |
| **Font Awesome 6** | 图标 / Icons |
| **LocalStorage** | 数据存储 / Data storage |

---

## 📖 使用指南 / Usage Guide

### 创建任务 / Create a Task
1. **中文**: 在顶部输入框输入任务标题，按 Enter 或点击"添加"按钮
1. **English**: Enter a task title in the top input box, press Enter or click "Add"
2. **中文**: 可选：展开"高级选项"设置优先级和重要程度
2. **English**: Optional: Expand "Advanced Options" to set priority and importance

### 任务详情 / Task Details
- **中文**: 点击任务内容区域打开详情弹窗
- **English**: Click the task content area to open the detail modal
- **中文**: 在"任务概要"中记录详细信息
- **English**: Record details in the "Task Summary" section
- **中文**: 在"子任务清单"中添加子任务
- **English**: Add subtasks in the "Subtask List" section

### 子任务操作 / Subtask Operations
- 📌 **中文**: 拖拽左侧手柄调整顺序 / **English**: Drag the left handle to reorder
- ✏️ **中文**: 点击文本直接编辑 / **English**: Click text to edit inline
- ✅ **中文**: 点击复选框标记完成 / **English**: Click checkbox to mark complete
- 🗑️ **中文**: 点击 × 删除 / **English**: Click × to delete

### 处理未完成任务 / Handle Unfinished Tasks
- **中文**: 每天首次打开应用会显示昨日未完成任务
- **English**: Unfinished tasks from yesterday will pop up on first open each day
- **中文**: 可单独处理或批量操作
- **English**: Handle individually or batch process

---

## 🚀 部署到 GitHub Pages / Deploy to GitHub Pages

本项目已配置 GitHub Pages 自动部署，每次推送代码到 `main` 分支后，GitHub Actions 会自动构建并部署到 Pages。

This project is configured with GitHub Pages auto-deployment. Every time you push to the `main` branch, GitHub Actions will automatically build and deploy to Pages.

**设置步骤 / Setup Steps:**
1. 打开仓库的 **Settings > Pages** / Go to your repo's **Settings > Pages**
2. 在 "Source" 中选择 **GitHub Actions** / Select **GitHub Actions** as the source
3. 推送代码后，等待 Actions 运行完成即可 / Push code and wait for the Actions workflow to finish

> 👉 访问地址 / Visit: **https://lingbin-8801.github.io/dailyflow**

---

## 🤝 贡献 / Contributing

**中文**: 欢迎提交 Issue 和 Pull Request！  
**English**: Issues and Pull Requests are welcome!

---

## 📄 许可证 / License

MIT License - **中文**: 欢迎自由使用和修改 / **English**: Free to use and modify.

---

⭐ **中文**: 如果这个项目对你有帮助，请给我一个 Star！  
⭐ **English**: If this project helps you, please give it a Star!