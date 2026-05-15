# Smart Task Manager

A modern, responsive **To-Do List Web App** built using **Vanilla JavaScript**, designed with a clean UI and smooth user experience. This app allows users to efficiently manage daily tasks with real-time updates and persistent storage.

---

##  Features

*  Add new tasks instantly
*  Mark tasks as completed (toggle)
*  Delete tasks 
*  Filter tasks (All / Active / Completed)
*  Persistent storage using `localStorage`
*  Instant UI updates without page reload
*  Modern dark-themed UI with smooth interactions

---

##  Preview

> <img width="1343" height="571" alt="image" src="https://github.com/user-attachments/assets/6ed5e797-ee3e-4090-8019-676e4ddaaae1" />




##  Tech Stack

* **HTML5** – Structure
* **CSS3** – Styling (Flexbox, modern UI design)
* **Vanilla JavaScript (ES6)** – Logic & interactivity
* **LocalStorage API** – Data persistence

---

##  Project Structure

```
 Smart-Task-Manager
 ├── index.html   # Main application file
```

---

##  How It Works

* Tasks are stored as objects:

```js
{
  id: Number,
  text: String,
  completed: Boolean
}
```

* All tasks are saved in **localStorage**, so they remain even after refreshing the browser.
* The UI updates dynamically using JavaScript DOM manipulation.

---

##  Getting Started

1. Clone the repository:

```bash
git clone https://github.com/your-username/smart-task-manager.git
```

2. Open the project folder:

```bash
cd smart-task-manager
```

3. Run the app:

* Simply open `index.html` in your browser
 **or**
* Use Live Server in VS Code for a better experience



##  Future Improvements

To make this project even more powerful:

*  Edit tasks inline
*  Add due dates & priorities
*  Progress tracking (task completion %)
*  Light/Dark theme toggle
*  Drag & drop task reordering



##  What I Learned

* DOM manipulation using JavaScript
* Event handling and UI updates
* Managing application state
* Using `localStorage` for persistence
* Writing clean and maintainable front-end code



## 📜 License

This project is open-source and available under the **MIT License**.



## Acknowledgements

Built as part of a front-end development practice project to strengthen JavaScript fundamentals and UI design skills.



 If you like this project, consider giving it a star!

