# 🗓️ University/College Timetable Generator (Manual + Auto)

A Java-based Timetable Generator for universities and colleges with support for both **manual** and **auto-generation** of schedules. Built with a modular code structure using **AWT for the UI** and clean object-oriented design separating logic into `Screens` and `Models`.

> ⚠️ UI is currently developed using Java AWT and will be upgraded to a modern GUI framework soon.

---

## 🧩 Features

- ✅ Add subjects for various semesters
- ✅ Add faculty and assign subject expertise
- ✅ Define maximum lecture limits per faculty
- ✅ Manual class scheduling
- ✅ Automatic timetable generation with clash-free logic
- ✅ Modular code design (Screens & Models)

---

## 🗂️ Project Structure
```bash
📁 timetable-generator/n
├── 📁 Models/n
│ ├── Classroom.java
│ ├── Faculty.java
│ ├── ScheduleEntry.java
│ ├── Semester.java
│ ├── Subject.java
│ ├── TimeSlot.java
│ └── Timetable.java
├── 📁 Screens/
│ ├── HomeScreen.java
│ ├── AddSubjectScreen.java
│ ├── AddFacultyScreen.java
│ ├── ManualScheduleScreen.java
│ └── AutoScheduleScreen.java


---

## 🚀 How to Use

### 1. Clone the Repository


git clone https://github.com/yourusername/timetable-generator.git
cd timetable-generator

2. Run the Project
You can use any Java IDE like IntelliJ IDEA or Eclipse,Vscode or run via command line:


javac Homescreen.java

📌 Step-by-Step Usage
 1.Add Subjects
    Start by entering the subject list categorized by semesters.

 2.Add Faculty
    Add faculty members and assign them the subjects they teach along with max lectures per day.

 3.Create Timetable

 4.Use Manual Scheduling to assign faculty to timeslots.

 Or use the Auto Scheduler to automatically generate a clash-free schedule.

---

    💡 Planned Improvements
    Upgrade to Swing or JavaFX

    Export timetable to PDF or Excel

    Add student-course registration system

    Build visual calendar-like interface

    Integrate with SQLite database

---

🧠 Tech Stack
Component	Description
Language	Java
UI Framework	AWT (Java Abstract Window Toolkit)
Architecture	Modular OOP (Screens & Models)
---
🙌 Credits
This project is created and maintained by Owais.