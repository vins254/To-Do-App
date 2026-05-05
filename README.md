# ✨ Modern To-Do List App

A sleek, interactive, and high-performance To-Do List application designed with a premium glassmorphism aesthetic. This app helps users stay productive with real-time progress tracking and persistent storage.

🚀 **[View Live Demo](https://vins254.github.io/To-Do-App/)**

---

## 🌟 Key Features

- **💎 Glassmorphism UI**: A modern, transparent design with backdrop blur and soft shadows for a premium feel.
- **📊 Real-time Progress Tracking**: A dynamic progress bar and task counter that update instantly as you manage your list.
- **🎉 Celebration Effects**: Integrated `tsparticles/confetti` to celebrate when you complete all your tasks!
- **💾 Persistent Storage**: Uses `localStorage` to save your tasks, so they remain available even after refreshing the page.
- **⚡ CRUD Operations**: Easily add, edit, complete, and delete tasks with smooth transitions.
- **📱 Responsive Design**: Fully optimized for mobile, tablet, and desktop screens.

---

## 🛠️ Tech Stack

### Core Technologies
- **HTML5**: Semantic structure for the web interface.
- **CSS3**: Advanced styling including Flexbox, Glassmorphism, and custom animations.
- **JavaScript (ES6)**: Functional logic, DOM manipulation, and state management.

### Libraries & Assets
- **[Font Awesome](https://fontawesome.com/)**: High-quality icons for task actions.
- **[tsparticles/confetti](https://github.com/tsparticles/confetti)**: Interactive celebration effects.
- **Google Fonts**: Modern typography using the `Outfit`, `Jost`, and `Poppins` font families.

---

## 🧠 How It Works

The application follows a simple but effective logic to ensure a seamless user experience:

1.  **Task Addition**: When a user submits a task via the input field, a new task object is created and appended to the DOM. The input is then cleared and the empty state image is hidden.
2.  **State Management**: Each task has a "completed" state. Toggling the checkbox updates the UI (striking through text) and recalculates the progress bar percentage.
3.  **Data Persistence**: Every modification (add, edit, delete, toggle) triggers the `saveTaskToLocalStorage` function, ensuring the task list is synced with the browser's local storage.
4.  **Progress Logic**: The app calculates the ratio of completed tasks to total tasks to drive the width of the progress bar and update the numerical counter.
5.  **Celebration Trigger**: A unique completion check is performed; if all active tasks are marked as finished, a confetti burst is triggered using the `tsparticles` library.

---

## 🚀 Getting Started

To run this project locally:

1. **Clone the repository**:
   ```bash
   git clone https://github.com/vins254/To-Do-App.git
   ```
2. **Navigate to the project folder**:
   ```bash
   cd To-Do-App
   ```
3. **Open the project**:
   Simply open `index.html` in your favorite browser.


Developed with ❤️ by [Vins](https://github.com/vins254)