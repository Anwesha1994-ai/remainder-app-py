# **Assignment Reminder App – Project Report**

## **1. Title**
**Assignment Reminder App using Python (Tkinter GUI)**

## **2. Abstract**
This project presents a simple and effective Assignment Reminder Application developed using Python and Tkinter. The system allows students to add assignments with due dates and receive reminders for tasks approaching their deadlines. The solution focuses on improving student productivity through automated deadline management. It demonstrates the application of core programming concepts including problem solving, modular design, file handling, and GUI development.

## **3. Introduction**
Students often struggle with managing multiple assignment deadlines, leading to missed submissions and increased academic stress. To address this challenge, an easy-to-use reminder system is essential. This project aims to bridge this gap by providing a lightweight Assignment Reminder App that helps students organize and track their deadlines.  
This project relates to domains like **Education** and **Productivity & Automation**, fitting well within the general project theme.

## **4. Problem Statement**
Students frequently forget assignment deadlines and lack a structured system to manage academic tasks. Manual tracking is inefficient and leads to missed submissions. A simple digital reminder tool can greatly help students stay organized.

## **5. Objectives**
- Allow students to add assignment details (title, subject, due date & time).  
- Display all assignments in an organized manner.  
- Provide reminders for assignments due within the next 24 hours.  
- Store data persistently using a JSON file.  
- Provide an intuitive and user-friendly GUI.

## **6. Requirement Analysis**

### **Functional Requirements**
- Add new assignment entries  
- View all assignments  
- Check reminders for deadlines within the next 24 hours  
- Store assignments using a lightweight storage system (JSON)

### **Non-Functional Requirements**
- **Usability:** Beginner-friendly GUI  
- **Reliability:** Persistent storage  
- **Performance:** Fast load and save operations  
- **Portability:** Runs on any OS supporting Python  

## **7. System Design**

### **7.1 System Architecture**
User → Tkinter GUI → Python Logic → JSON File Storage

### **7.2 Flowchart**
Start → Add/View/Check Reminders → JSON Read/Write → End

## **8. Algorithms / Pseudocode**

### **Add Assignment**
Input fields → Combine date+time → Load JSON → Append → Save

### **Check Reminders**
Load JSON → Compare due time with now+24hrs → Show alerts

## **9. Implementation Details**
Python, Tkinter, JSON, datetime

## **10. Testing**
Basic test cases validating reminders, saving, loading.

## **11. Results**
System works successfully for adding/viewing reminders.

## **12. Conclusion**
A simple productivity tool helping students manage deadlines.

## **13. Future Scope**
Calendar view, notifications, cloud sync, mobile app.

## **14. References**
Python Docs, Tkinter Docs
