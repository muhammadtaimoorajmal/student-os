# Student OS | Productivity Dashboard

![Student OS Banner](https://via.placeholder.com/1200x400/0f172a/6366f1?text=Student+OS+-+Productivity+Dashboard)

> A premium, all-in-one productivity dashboard built entirely with vanilla HTML, CSS, and JavaScript. 

**[Live Demo](https://muhammadtaimoorajmal.github.io/student-os/)** <!-- Replace with actual link later if different -->

Student OS is a modern, fast, and feature-rich offline web application designed to help students manage their entire academic life from a single dashboard. It requires no backend, no build tools, and stores all data securely in your local browser.

## 📸 Screenshots

| Dashboard | Task Manager |
|---|---|
| ![Dashboard Screenshot](./Screenshot%202026-06-16%20214355.png) | ![Tasks Screenshot](./Screenshot%202026-06-16%20214418.png) |

| Pomodoro Timer | Grade Calculator |
|---|---|
| ![Pomodoro Screenshot](./Screenshot%202026-06-16%20214433.png) | ![GPA Screenshot](./Screenshot%202026-06-16%20214451.png) |

## ✨ Features

- **Dashboard**: High-level overview of tasks, upcoming deadlines, focus hours, and current habits.
- **Task Manager**: Organize tasks by priority, subject, and due date. Filter and track completion.
- **Assignment Tracker**: Keep an eye on coursework, due dates, weightage, and visually track progress.
- **Study Planner**: Schedule study sessions with dates, times, and duration to block out your calendar.
- **Pomodoro Timer**: A beautiful, focus-driven timer with customizable focus and break intervals, complete with a visual progress ring and session tracking.
- **Habit Tracker**: Build healthy routines with an interactive daily grid and automatic streak calculation.
- **GPA Calculator**: Dynamically calculate your estimated GPA based on course credits and letter grades.
- **Notes Workspace**: A simple, powerful text editor to jot down ideas, class notes, and pin important files.
- **Analytics**: Visualize your productivity score and monitor task completion and focus hours.
- **Quick Tools**: Built-in mini-calculator and word counter for speedy access.

## 🛠 Tech Stack

- **HTML5**: Semantic structure.
- **CSS3**: Custom properties (variables) for theme management, Flexbox/Grid for layout, animations, and a glassmorphism aesthetic.
- **Vanilla JavaScript**: Zero dependencies, fully modularized ES5/ES6 logic.
- **Storage**: Browser `localStorage` for complete data persistence.

## 📂 File Structure

The project is intentionally kept simple to ensure immediate deployability:

```text
/
├── index.html     # Application structure and templates
├── styles.css     # UI design, responsive rules, and themes
├── script.js      # App logic, state management, and DOM manipulation
└── README.md      # This file
```

## 🚀 How to Run Locally

Since this app requires no backend or build process, running it is incredibly simple:

1. Clone the repository:
   ```bash
   git clone https://github.com/muhammadtaimoorajmal/student-os.git
   ```
2. Navigate to the project folder.
3. Open `index.html` in your favorite web browser.

That's it! Everything runs locally.

## 🌐 Deploying to GitHub Pages

To make this app accessible anywhere:

1. Create a new repository on GitHub.
2. Push these four files (`index.html`, `styles.css`, `script.js`, `README.md`) to the `main` branch.
3. Go to your repository **Settings** -> **Pages**.
4. Set the **Source** to `Deploy from a branch`.
5. Select the `main` branch and `/root` folder, then save.
6. Within minutes, your app will be live at `https://muhammadtaimoorajmal.github.io/student-os/`.

## ⌨️ Keyboard Shortcuts & Features

- **Light/Dark Mode**: Click the sun/moon icon in the top right to switch themes instantly.
- **Quick Add**: Use the top-right button to instantly open a modal to add a Task, Assignment, Note, or Habit without switching tabs.
- **Data Export/Import**: Go to **Settings** to download your entire workspace as a `.json` file, allowing you to backup data or move it between devices.

## 🔒 Storage Details

This application respects your privacy. All user data (tasks, habits, notes, etc.) is strictly saved in the browser's `localStorage` under the key `studentOS_data`.

- No data is sent to any external server.
- The app functions 100% offline.
- Clearing your browser cache *may* wipe your data. Always use the built-in **Export JSON** feature to back up your work!

## 🎨 Customization Notes

If you'd like to customize the colors of the app, simply open `styles.css` and look at the `:root` and `[data-theme="dark"]` CSS variables at the top of the file. You can easily tweak the `--primary`, `--accent`, and `--bg` variables to match your personal aesthetic.

## 🗺 Future Roadmap

- Add simple offline-first calendar grid view.
- Enable browser push notifications for Pomodoro and Deadlines.
- Drag and drop reordering for Tasks.
- Service Worker integration to make the app a fully installable PWA (Progressive Web App).

## 🐛 Troubleshooting

- **My data disappeared!** 
  Make sure you didn't run the app in an "Incognito" or "Private Browsing" window, as `localStorage` is cleared when those windows are closed.
- **The UI looks broken on mobile.**
  Ensure you are using a modern browser (Chrome, Safari, Firefox, Edge).

## 📄 License

This project is licensed under the MIT License - feel free to use it, modify it, and share it.

## 👨‍💻 Credits

Designed and developed with a focus on premium user experiences and robust vanilla architecture.
