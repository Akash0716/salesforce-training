# Day 8 - Lightning Web Components (LWC)

## Topics Covered

- Lightning Web Components (LWC)
- Component-Based UI Architecture
- Reusable Components
- Frontend vs Backend Thinking
- Modern Salesforce UI Development
- Secure Development Basics
- Enterprise UI Design

---

# What is LWC?

Lightning Web Components (LWC) is Salesforce’s modern UI framework used for building user interfaces on the Salesforce platform.  
LWC is based on modern web standards and uses HTML, JavaScript, and Metadata configuration files.  
It helps developers create reusable, fast, and modular components for Salesforce applications.

LWC provides better performance and a modern development approach compared to older UI technologies.

---

# Why Salesforce Uses LWC

Salesforce uses LWC because modern enterprise systems require reusable, scalable, and efficient user interfaces.  
Component-based architecture improves maintainability and allows developers to build applications faster.

Benefits of LWC:
- Reusable UI components
- Better performance
- Modular design
- Faster development
- Modern web standards support

---

# UI Thinking Exercise - College Management System

## 1. Student Registration Screen

Purpose:
Allows students to submit admission details and registration information.

Features:
- Personal information form
- Contact details
- Course selection
- Document upload

---

## 2. Course Dashboard

Purpose:
Displays course details and enrollment information.

Features:
- Course list
- Available seats
- Faculty information
- Enrollment statistics

---

## 3. Attendance Dashboard

Purpose:
Shows attendance records and performance tracking.

Features:
- Attendance percentage
- Low attendance alerts
- Academic status

---

## 4. Faculty Panel

Purpose:
Allows faculty members to manage courses and students.

Features:
- Student list
- Attendance updates
- Notifications
- Course assignments

---

## 5. Notification Widget

Purpose:
Displays system notifications and alerts.

Examples:
- Fee reminders
- Attendance warnings
- Registration confirmation
- Course updates

---

# Component Thinking

## Selected Screen: Student Dashboard

Student Dashboard can be divided into reusable components.

---

## Header Component

Displays:
- Student name
- Student ID
- Navigation menu

Purpose:
Provides common navigation across screens.

---

## Student Information Component

Displays:
- Personal details
- Course information
- Contact details

Purpose:
Keeps profile information modular.

---

## Attendance Component

Displays:
- Attendance percentage
- Attendance chart
- Warning notifications

Purpose:
Separates academic tracking logic.

---

## Notification Component

Displays:
- Alerts
- Announcements
- Fee reminders

Purpose:
Provides reusable notification handling.

---

## Fee Component

Displays:
- Fee status
- Remaining balance
- Payment history

Purpose:
Manages fee information independently.

---

# Why Reusable Components Are Useful

Reusable components help developers avoid repeated code and simplify maintenance.  
One component can be reused across multiple pages and applications.  
This improves scalability, consistency, and development speed.

Enterprise systems use reusable UI to manage large applications efficiently.

---

# Frontend vs Backend Thinking

| Function | Frontend (UI) | Backend (Apex) |
|-----------|--------------|----------------|
| Button Click | Yes | No |
| Notification Display | Yes | No |
| Form Validation | Yes | Yes |
| Fee Calculation | No | Yes |
| Database Operations | No | Yes |
| Business Logic | No | Yes |

---

# Frontend Logic

Frontend handles user interaction and presentation.

Examples:
- Button clicks
- Form display
- Notification display
- Screen navigation
- User input handling

Purpose:
Provides user interface and interaction.

---

# Backend Logic

Backend handles processing and business logic.

Examples:
- Fee calculation
- Database updates
- Trigger execution
- Validation processing
- External integrations

Purpose:
Manages system operations and business rules.

---

# Secure Development Awareness

Enterprise applications handle sensitive business data.  
Security is important to prevent unauthorized access and protect information.

Security considerations:
- Access control
- User permissions
- Data validation
- Safe coding practices

---

# Reflection - Why Modern Enterprise Systems Use Component-Based UI

Modern enterprise systems are large and continuously evolving.  
Component-based UI architecture helps break large interfaces into smaller reusable parts.  
This improves maintainability, scalability, performance, and development speed.

Component thinking allows teams to work independently and build applications efficiently.

---

# Learning Outcomes

Through this task, I learned:
- What Lightning Web Components are
- Why Salesforce moved to LWC
- Importance of reusable components
- Frontend vs Backend separation
- Modern UI architecture
- Component-based design thinking
- Secure development awareness

---

# Screenshots
![](https://github.com/Akash0716/salesforce-training/blob/main/week-1/day8-lwc-basics/Lightning%20web%20components%20basics.png?raw=true)
![](https://github.com/Akash0716/salesforce-training/blob/main/week-1/day8-lwc-basics/Lightning%20web%20components%20for%20aura%20developers.png?raw=true)
![](https://github.com/Akash0716/salesforce-training/blob/main/week-1/day8-lwc-basics/Secure-server%20side%20Development.png?raw=true)
