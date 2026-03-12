# Pomodoro App

A beautiful, feature-rich Pomodoro timer built with **HTML**, **Tailwind CSS** (Material-inspired), and **Vanilla JavaScript** — no database, no build step required.

## ✨ Features

| Feature | Details |
|---|---|
| 🍅 **Timer Modes** | Pomodoro, Short Break, Long Break |
| ⏱ **Circular Progress Ring** | SVG-animated countdown ring |
| ▶️ **Controls** | Start / Pause, Reset, Skip session |
| 🔢 **Session Counter** | Dot indicator tracking pomodoros in a cycle |
| ⚙️ **Settings Modal** | Customise all durations, long-break interval, auto-start behaviour |
| 🔔 **Sound Alerts** | Web Audio API chimes (no external files needed) |
| 📱 **Browser Notifications** | Optional desktop push notifications |
| 📝 **Task List** | Add, complete, delete tasks; clear completed in one click |
| 📅 **Session History** | Every completed pomodoro & task saved to `localStorage` |
| 📊 **Statistics Panel** | Pomodoro count, focus time, day-streak, tasks done, 7-day bar chart |
| 🌓 **Dark Mode** | One-click toggle, persisted across reloads |
| ⌨️ **Keyboard Shortcuts** | `Space` start/pause · `R` reset · `S` skip · `1/2/3` switch mode |
| 💾 **No Database** | All data persists in browser `localStorage` |

## 🚀 Getting Started

Just open `index.html` in any modern browser — no installation or build step required.

```bash
# Clone the repo
git clone https://github.com/vineet4196/Pomodro-App-js.git
cd Pomodro-App-js

# Open the app
open index.html        # macOS
xdg-open index.html    # Linux
start index.html       # Windows
```

CDN dependencies (loaded automatically):
- [Tailwind CSS](https://tailwindcss.com/)
- [Material Icons](https://fonts.google.com/icons)
- [Roboto font](https://fonts.google.com/specimen/Roboto)

## 🎯 How the Pomodoro Technique Works

1. Work for **25 minutes** (one Pomodoro)
2. Take a **5-minute short break**
3. After every **4 Pomodoros**, take a **15-minute long break**
4. Repeat!

## 🗂 File Structure

```
Pomodro-App-js/
└── index.html   # Single-file app (HTML + CSS + JS)
```

## 📦 Data Storage

All sessions, tasks, and settings are stored in the browser's `localStorage` under the following keys:

| Key | Contents |
|---|---|
| `pomo_settings` | Timer durations, auto-start, sound, notification preferences |
| `pomo_history`  | Array of completed pomodoro sessions and finished tasks |
| `pomo_tasks`    | Current task list |
| `pomo_state`    | Current mode, session count |
| `pomo_dark`     | Dark mode preference |

## 📄 License

[MIT](LICENSE)