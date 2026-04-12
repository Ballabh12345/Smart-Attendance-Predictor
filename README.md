# 🎯 Smart Attendance Predictor

A modern, frontend-only web application that helps students **predict their attendance** and **plan ahead smartly** using calendar-based logic.

---

## 🚀 Overview

Smart Attendance Predictor is not a basic calculator.  
It is a **date-driven attendance simulation tool** that allows users to:

- Calculate attendance for a future date 📅  
- Predict when they will reach a target attendance 🎯  
- Account for holidays and absences intelligently  

All calculations are done using **pure JavaScript (no backend required)**.

---

## 🧠 Core Concept

- Each working day = **7 lectures**
- Sundays are automatically treated as holidays
- Users can add:
  - **Past holidays** (to fix calculation accuracy)
  - **Future holidays**
  - **Planned absences**

The system simulates attendance over time using real calendar logic.

---

## 📌 Base Reference

- **Base Date:** 12 April (Sunday, 9 PM)  
- **Total Lectures till this date:** 358  

All calculations begin from this fixed reference point.

---

## ✨ Features

### 📅 Future Attendance Prediction
- Select a target date
- Get your predicted attendance for that date

---

### 🎯 Goal Attendance Predictor
- Enter your target attendance %
- Get the exact date when you'll reach it

---

### 📆 Holiday Management
- Add past holidays (after 12 April)
- Add future holidays
- Automatically excludes Sundays

---

### ❌ Absence Planner
- Mark days you plan to skip
- See how it affects your attendance

---

### ⚡ Smart Simulation Engine
- Dynamically calculates total lectures
- Converts percentage → actual attendance
- Simulates day-by-day progression

---

## ⚠️ Important Note

All attendance calculations are based on the final updated value after all lectures of the day (**9 PM IST**).

If you want to check your attendance **before attending classes** on a specific day, select the **previous date**.

👉 Example:  
To check attendance before 19 April classes, select **18 April**.

Similarly, the goal achievement date represents when your attendance will reach the target percentage by **9 PM IST** on that day.

---

## 🎨 UI/UX Highlights

- Clean, minimal, modern design  
- Glassmorphism + soft gradient background  
- Smooth interactions and animations  
- Mobile responsive layout  

---

## 🛠️ Tech Stack

- **HTML5**
- **CSS3**
- **JavaScript (Vanilla)**

No frameworks. No backend. Fully client-side.

---

## 📦 Installation & Usage

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/attendance-predictor.git
