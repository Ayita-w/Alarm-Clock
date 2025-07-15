# ⏰ Terminal Alarm Clock – Python

A simple Python-based alarm clock that lets you set a countdown timer in **minutes and seconds**. It displays a live countdown in the terminal and plays an alarm sound (`alarm.mp3`) when the time is up.

---

## 📦 Features

- Set time using minutes and seconds
- Displays a live countdown in the terminal
- Plays a sound when time runs out
- Clean and minimal command-line interface

---

## 🛠️ Requirements

- Python 3.x
- [`playsound`](https://pypi.org/project/playsound/) module
- An audio file named `alarm.mp3` in the same directory

Install `playsound` with:
```bash
pip install playsound

📌 Note
This project uses ANSI escape codes (\033) to clear and update the terminal screen — works best in standard terminals.

Make sure your sound is on and alarm.mp3 is playable.


