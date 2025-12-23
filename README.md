<p align="center">
  <img src="picture/copy_tip.png" alt="copy_tip logo" width="280">
</p>

# copy_tip

copy_tip is a desktop-based educational project created for ethical hacking
and security awareness learning. It demonstrates how application-scoped
input capture can occur when users interact with untrusted or fake interfaces.

This project is intended strictly for educational and lab purposes.

## 🎯 Purpose

- Demonstrate controlled input capture techniques
- Explain risks of fake login windows and social engineering
- Help learners understand user-executed attack vectors

## 🚀 Features

- Desktop GUI built with Python (Tkinter)
- Explicit user consent before capture
- Captures keystrokes ONLY inside the application window
- Logs input locally for analysis
- No system-wide monitoring
- No background execution or persistence

## 🛠️ Project Structure

| File / Folder | Purpose |
|--------------|---------|
| `app.py` | Main GUI application script |
| `logger.py` | Application-scoped input logging logic |
| `picture/` | Project assets and branding |
| `picture/copy_tip.png` | copy_tip logo used in README |
| `README.md` | Project documentation |
| `DISCLAIMER.md` | Legal, ethical usage disclaimer |
| `logs/` | Directory for locally stored runtime logs |


The log file (keystrokes.log) is automatically created inside the logs/
directory when the application is executed.

## ▶️ How to Run

python3 app.py

Captured logs are stored at:
logs/keystrokes.log

## 🧠 Educational Mapping (MITRE ATT&CK)

- T1204 – User Execution
- T1056.001 – Input Capture (Application-Scoped)

## ⚠️ Disclaimer

This project captures input only within its own application window and
requires explicit user consent.

Do not use this project on systems or users without permission.
See DISCLAIMER.md for full details.

## ✅ Ethical Notice

copy_tip does not bypass operating system security controls and does not
perform any form of stealth, persistence, or unauthorized monitoring.

This project exists solely for education and ethical hacking practice.


