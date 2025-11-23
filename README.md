# VITYarthi-Project

## 1st sem project

Simple Reminder Project

## Reminder App in Python

This is a simple and user-friendly *Reminder Application* built using Python and Tkinter.  
The application allows the user to schedule a reminder by selecting a *start time, **end time, and entering a **goal or note*.  
When the selected time arrives, the app plays a *voice alert* using Google Text-to-Speech (gTTS) to notify the user.  
It also shows a *live clock* and a *progress bar* that fills gradually between the start and end times.

This project demonstrates the use of:
- Tkinter GUI  
- Threads (to prevent the app from freezing)  
- Time handling  
- Text-to-Speech  
- A dynamic progress bar  

---

## Features:

- *Start Time Selection:* Choose the hour and minute when the reminder should begin.  
- *End Time Selection:* Choose the hour and minute when the reminder should end.  
- *Goal/Note Input:* Enter what the reminder is for (example: “Study Physics”).  
- *Voice Alerts:*  
  - At start time → plays “Start of <goal>”.  
  - At end time → plays “End of <goal>”.  
- *Live Digital Clock:* Shows current system time updated every second.  
- *Progress Bar:* Visual indicator showing how much of the time interval has passed.  
- *Responsive Interface:* Uses threading so the GUI remains active while waiting for time.  
- *Exit Button:* Allows the user to safely close the application.

---
