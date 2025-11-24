# VITYarthi-Project

## 1st Sem Project  
Simple Reminder App

---

# Reminder App in Python

This is a simple and user-friendly *Reminder Application* built using Python and Tkinter.  
The application allows the user to schedule a reminder by selecting a *start time, **end time**, and entering a **goal or note***.  
When the selected time arrives, the app plays a *voice alert* using Google Text-to-Speech (gTTS) to notify the user.  
It also shows a *live clock* and a *progress bar* that fills gradually between the start and end times.

This project demonstrates the use of:
- Tkinter GUI  
- Threads (to prevent the app from freezing)  
- Time handling  
- Text-to-Speech  
- A dynamic progress bar  

---

## Features

- **Start Time Selection:** Choose the hour and minute when the reminder should begin.  
- **End Time Selection:** Choose the hour and minute when the reminder should end.  
- **Goal/Note Input:** Enter what the reminder is for (example: “Study Physics”).  
- **Voice Alerts:**  
  - At start time → plays “Start of <goal>”.  
  - At end time → plays “End of <goal>”.  
- **Live Digital Clock:** Shows current system time updated every second.  
- **Progress Bar:** Visual indicator showing how much of the time interval has passed.  
- **Responsive Interface:** Uses threading so the GUI remains active while waiting for time.  
- **Exit Button:** Allows the user to safely close the application.

---

# 🚀 Project Setup

Follow the steps below to run the Reminder App on your system.

---

## 1️⃣ Clone the Repository

```bash
git clone https://github.com/Anwesha1994-ai/remainder-app-py.git
cd remainder-app-py
```

## 2️⃣ Create Virtual Environment (venv)
- **Windows**
```bash
python -m venv venv
venv\Scripts\Activate.ps1
```
- **macOS or Linux**
```
python3 -m venv venv
source venv/bin/activate
```
## 3️⃣ Install Dependencies
```bash
pip install -r requirements.txt
```

## 4️⃣ Run the Application
- **Windows**
``` bash
python main.py
```
- **macOS or Linux**
``` bash
python3 main.py
```
---
<img width="586" height="813" alt="Screenshot 2025-11-24 170724" src="https://github.com/user-attachments/assets/f10703a4-df16-468d-8cbf-b2a2687b1027" /> 
<img width="696" height="839" alt="Screenshot 2025-11-24 170749" src="https://github.com/user-attachments/assets/594e00e2-3c18-45f7-873d-8d99599a6eaf" /> 
<img width="660" height="836" alt="Screenshot 2025-11-24 170812" src="https://github.com/user-attachments/assets/37fc141f-cd90-49b5-a6dc-04d949c37da8" /> 


