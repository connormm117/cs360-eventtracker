# Event Tracker App – CS 360 Portfolio Submission

## Artifact Description
This repository contains my completed **Event Tracker** mobile application, developed in Android Studio as part of CS 360 Project Three.  
The ZIP file includes:
- Finalized UI design (from Project Two)
- Functional app code design (Project Three)
- SQLite database integration
- Login/registration system
- Optional SMS notification functionality

---

## Reflection

**Requirements and Goals**  
The goal of this app was to create a mobile tool that allows users to log in, store event details, and view them in an organized grid.  
It addresses the need for quick and accessible event tracking, giving users the ability to create, update, and delete entries, while also sending optional SMS reminders.

**User-Centered UI Design**  
The app includes:
- **Login/Registration screen** for secure access
- **Main event list screen** with grid view for quick scanning
- **Add/Edit/Delete event functions**
- **SMS permission prompt** to manage notifications  
The layout and flow were kept simple and intuitive to reduce the learning curve for first-time users. Large touch targets, clear labels, and minimal steps between actions help ensure a smooth experience.

**Coding Approach**  
I followed a modular approach:
- Separated UI logic from database handling (using a `Repo` class for SQLite operations)
- Implemented input validation to avoid crashes
- Used consistent naming conventions and in-line comments for readability  
These techniques will be valuable for future projects because they make the code easier to maintain and scale.

**Testing Process**  
I tested functionality step-by-step in Android Studio:
- Verified login/registration logic with test credentials
- Checked CRUD operations on the database
- Simulated both granting and denying SMS permissions to confirm fallback behavior  
Testing revealed that handling empty inputs and permission denials early prevented later errors.

**Challenges and Innovation**  
A key challenge was integrating SMS permissions without breaking core functionality if denied.  
I solved this by structuring the code so that notifications were optional, allowing the app to remain fully functional without them.

**Successful Component**  
I am most proud of the **SQLite database integration**, which reliably stores event data across app restarts and displays it in an organized, user-friendly format.

---

## Repository Contents
- `/EventTrackerApp.zip` – Complete Android Studio project
- `/App_Launch_Plan.docx` – Optional document outlining the planned launch strategy
- `README.md` – This reflection and project summary

---

## Author
Connor Martin – CS 360 Mobile Architect Student  
