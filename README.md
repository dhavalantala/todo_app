# 📝 To-Do List App

A clean, minimal to-do list web application built with vanilla HTML, CSS, and JavaScript. Tasks are saved to the browser's local storage so they persist across sessions.

---

## 🌐 Live Demo
👉 [https://dhavalantala.github.io/todo_app/](https://dhavalantala.github.io/todo_app/)


## 🚀 Features

- **Add tasks** by typing and clicking the Add button or pressing Enter
- **Mark tasks as complete** by clicking on a task (strikes through with a checkmark)
- **Delete tasks** using the × button on each item
- **Persistent storage** — tasks are saved in `localStorage` and restored on page reload
- **Responsive design** with a modern gradient background and card layout

---

## 📁 Project Structure

```
todo-app/
├── index.html       # Main HTML structure
├── style.css        # Styling and layout
├── script.js        # App logic (add, delete, toggle, save)
└── images/
    ├── icon.png         # App header icon
    ├── checked.png      # Checked state icon for list items
    └── unchecked.png    # Unchecked state icon for list items
```

---

## 🛠️ Getting Started

No build tools or dependencies required. Just open the project in a browser.

1. **Clone or download** the repository
2. Make sure the `images/` folder contains `icon.png`, `checked.png`, and `unchecked.png`
3. Open `index.html` in any modern web browser

```bash
# Or serve locally with Python
python -m http.server 3000
```

Then visit `http://localhost:3000` in your browser.

---

## 📖 How to Use

| Action | How |
|---|---|
| Add a task | Type in the input box → click **Add** or press **Enter** |
| Complete a task | Click on the task text to toggle it |
| Delete a task | Click the **×** button on the right side of any task |

---

## 💾 Local Storage

Tasks are automatically saved to `localStorage` under the key `data`. They are loaded on every page visit, so your list survives refreshes and browser restarts. Clearing browser storage will reset the list.

---

## 🎨 Tech Stack

| Layer | Technology |
|---|---|
| Markup | HTML5 |
| Styling | CSS3 (Flexbox, custom gradients) |
| Logic | Vanilla JavaScript (ES6) |
| Font | [Roboto Condensed](https://fonts.google.com/specimen/Roboto+Condensed) via Google Fonts |
| Storage | Browser `localStorage` |

---

## 🌐 Browser Support

Works in all modern browsers that support `localStorage`:

- Chrome / Edge (latest)
- Firefox (latest)
- Safari (latest)

---

## 📌 Known Limitations

- Tasks are stored only in the browser — no backend or sync across devices
- No due dates or priority levels (date input is present in HTML but commented out)
- No drag-and-drop reordering

---

## 🔮 Possible Improvements

- Enable the date/deadline input for each task
- Add task categories or priority tags
- Support drag-and-drop to reorder tasks
- Add a filter to view All / Active / Completed tasks
- Sync tasks with a backend or cloud database

---

## 📄 License

This project is open source and free to use for personal or educational purposes.
