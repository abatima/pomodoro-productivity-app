# 🍅 Pomodoro Productivity App

## <img width="515" height="450" alt="image" src="https://github.com/user-attachments/assets/8594c8ff-04a7-4c82-a873-dd3ec53898a0" />

An event-driven desktop productivity application built with Python and Tkinter. This project implements the **Pomodoro Technique**, utilizing a modular logic system to automate work intervals and restorative breaks. It features a non-blocking countdown mechanism and dynamic UI state management.

## 🕹️ How It Works

The application manages a cycle of focused work and timed breaks based on a repetition-tracking system:

* **Work Session**: 25 minutes of high-focus activity.
* **Short Break**: 5 minutes of rest after each work session.
* **Long Break**: 20 minutes of restorative rest after every 4 work sessions (8 reps).

## ✨ Key Features

* **Event-Driven Countdown**: Implements the `.after()` method to handle time increments every 1000ms without interrupting the main UI loop.
* **Integer-Based Formatting**: Uses floor division (`//`) and modulo (`%`) arithmetic to convert raw seconds into a clean `MM:SS` digital display.
* **Dynamic State UI**: Automatically updates label text and foreground colors (`PINK`, `RED`, `GREEN`) to reflect the current session type.
* **Automated Notifications**: Triggers the `window.bell()` sound and forces the window to the `topmost` layer upon session completion.
* **Progress Persistence**: Tracks completed work sessions by dynamically updating checkmark labels based on the `reps` count.

## 🛠️ Tech Stack

* **Language**: Python 3.x
* **Library**: Tkinter (Standard GUI Library)
* **Logic**: Procedural event-handling and integer arithmetic

## 🚀 Getting Started

### Prerequisites

* Python 3.x
* `tomato.png` asset file

### Installation

1. Clone the repository:
```bash
git clone https://github.com/abatima/pomodoro-productivity-app.git

```


2. Navigate to the directory:
```bash
cd pomodoro-productivity-app

```


3. Run the application:
```bash
python main.py

```

## 🎮 Controls

* **Start Button**: Triggers the `start_timer()` function to initiate the countdown.
* **Reset Button**: Calls `reset_timer()`, canceling the active `after()` loop and clearing all session progress.

---

*Developed by [abatima*](https://github.com/abatima)
