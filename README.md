# 🍅 Pomodoro Productivity App

An interactive desktop productivity tool built with Python and Tkinter. This application automates the **Pomodoro Technique**, managing work intervals and restorative breaks to help users maintain high levels of focus and mental clarity throughout the day.

## 🕹️ How It Works
The app follows the standard 4-cycle Pomodoro loop:
1. **Work Session** (25 mins) - Focus on your task.
2. **Short Break** (5 mins) - Stretch and hydrate.
3. **Repeat** - Complete 4 work sessions.
4. **Long Break** (20 mins) - Take a substantial recharge.

The UI dynamically updates its color scheme and labels to indicate the current phase, and automatically brings the window to the front when a session ends.

## ✨ Key Features
* **Automated Logic Engine**: Handles the transition between Work, Short Break, and Long Break intervals based on repetition counts.
* **Non-Blocking Timer**: Utilizes `Tkinter.after()` for a smooth, high-precision countdown without freezing the application interface.
* **Visual Progress Tracking**: Automatically tallies completed sessions with visual checkmarks.
* **Smart Notifications**: Includes a "window bell" and `topmost` priority triggers to alert you when a session completes.
* **Clean UI**: Minimalist tomato-themed canvas with a clear, color-coded status display.

## 🛠️ Tech Stack
* **Language**: Python 3.x
* **GUI Framework**: Tkinter
* **Logic**: Event-driven programming with the `math` and `time` logic implementations.

## 🚀 Getting Started

### Prerequisites
* Python 3.x
* A `tomato.png` image file in the project directory.

### Installation
1. Clone the repository:
   ```bash
   git clone [https://github.com/abatima/pomodoro-productivity-app.git](https://github.com/abatima/pomodoro-productivity-app.git)

```

2. Navigate to the project directory:
```bash
cd pomodoro-productivity-app

```


3. Run the application:
```bash
python main.py

```



## 🎮 Controls

* **Start**: Initializes the countdown and repetition tracker.
* **Reset**: Stops the current timer, clears all checkmarks, and resets the rep count.

## 📜 License

Distributed under the MIT License. See `LICENSE` for more information.

---

*Developed by [abatima*](https://www.google.com/search?q=https://github.com/abatima)


```
