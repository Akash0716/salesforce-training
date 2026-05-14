# Day 6 - SOQL and Apex Triggers

## Topics Covered

- Salesforce Data Retrieval
- SOQL Basics
- SOSL Basics
- DML Operations
- Apex Triggers
- Event-Driven Systems
- Flow vs Trigger
- Before vs After Trigger

---

# What is SOQL?

SOQL (Salesforce Object Query Language) is a query language used to retrieve data from Salesforce objects.  
It is similar to SQL but specifically designed for Salesforce data and relationships.  
SOQL helps developers search, filter, and retrieve records from objects efficiently.

SOQL is mainly used in Apex code, reports, integrations, and automation processes.

---

# Why SOQL is Important

Enterprise systems store large amounts of structured data.  
SOQL allows applications to retrieve only the required information quickly and efficiently.  
It helps businesses generate reports, automate workflows, and process records dynamically.

---

# What is an Apex Trigger?

An Apex Trigger is a piece of Apex code that executes automatically when specific events occur on Salesforce records.  
Triggers help automate actions when records are created, updated, deleted, or restored.  
They are used to implement advanced business logic and event-driven behavior in Salesforce.

Triggers work automatically in the background whenever data changes happen.

---

# Why Triggers are Important

Enterprise applications must react automatically when data changes occur.  
Triggers help systems perform actions instantly without waiting for manual intervention.  
They improve automation, consistency, and real-time processing in business systems.

---

# Difference Between Flow and Trigger

| Flow | Apex Trigger |
|------|---------------|
| No-code automation | Code-based automation |
| Easier to build and maintain | More powerful and flexible |
| Best for simple workflows | Best for complex business logic |
| Uses visual interface | Uses Apex programming |
| Faster development | Advanced customization |

---

# Difference Between Before and After Trigger

| Before Trigger | After Trigger |
|----------------|---------------|
| Executes before record is saved | Executes after record is saved |
| Used for validation and field updates | Used for related actions and notifications |
| Faster because data is not committed yet | Used when record ID or final data is needed |
| Example: Update attendance percentage | Example: Send confirmation email |

---

# Trigger Use Cases in College Management System

## 1. Welcome Email After Student Registration

### Trigger Event
After a new student record is created.

### Action
Automatically send a welcome email to the student.

### Why?
Improves communication and provides instant confirmation.

---

## 2. Notify Faculty When Course Becomes Full

### Trigger Event
After course seat count reaches maximum capacity.

### Action
Automatically notify the assigned faculty member.

### Why?
Helps faculty manage enrollment planning efficiently.

---

## 3. Attendance Warning Notification

### Trigger Event
After student attendance percentage drops below 75%.

### Action
Send warning notification to student and faculty.

### Why?
Helps improve academic monitoring and student performance.

---

## 4. Auto Update Remaining Seats

### Trigger Event
After a student enrolls in a course.

### Action
Automatically reduce available seat count.

### Why?
Maintains accurate course seat availability.

---

## 5. Fee Payment Confirmation

### Trigger Event
After student fee payment status changes to “Paid”.

### Action
Automatically send payment confirmation message.

### Why?
Improves transparency and reduces manual communication.

---

# Query Examples

## 1. Find all students enrolled in Course A

```text
Find all students whose course is Course A
```

---

## 2. Find all courses handled by Faculty X

```text
Retrieve all courses assigned to Faculty X
```

---

## 3. Find students with attendance below 75%

```text
Retrieve students whose attendance percentage is less than 75
```

---

## 4. Find students who have pending fee balance

```text
Retrieve students with remaining fee balance greater than 0
```

---

## 5. Find all faculty members in the Computer Science department

```text
Retrieve faculty records where department is Computer Science
```

---

# Flow vs Trigger Thinking

| Scenario | Best Choice | Reason |
|----------|-------------|--------|
| Simple email notification | Flow | Easy no-code automation |
| Complex scholarship eligibility logic | Apex Trigger | Requires advanced calculations |
| Updating related records | Flow | Easier and maintainable |
| External payment API integration | Apex Trigger | Requires programming and API handling |
| Timetable conflict checking | Apex Trigger | Needs complex record comparison |

---

# Event-Driven System Thinking

Enterprise systems work based on events and automatic reactions.  
Whenever data changes occur, the system immediately performs required actions automatically.

Examples:
- Student registration triggers welcome emails
- Attendance updates trigger alerts
- Fee payments trigger confirmations

This event-driven behavior improves speed, automation, and system intelligence.

---

# Reflection - Why Enterprise Systems React Automatically to Data Changes

Modern enterprise systems handle thousands of transactions and data updates every day.  
Manual monitoring is inefficient and error-prone.  
Automatic reactions help businesses process operations quickly and consistently.

Event-driven systems improve:
- Real-time processing
- Productivity
- Automation
- Data consistency
- User experience

Salesforce uses Flows and Apex Triggers to implement intelligent business automation.

---

# Learning Outcomes

Through this task, I learned:
- What SOQL is
- How Salesforce retrieves data
- What Apex Triggers do
- Difference between Flow and Trigger
- Difference between Before and After Trigger
- Importance of event-driven systems
- How enterprise applications react automatically to data changes

---

# Screenshots

![](# Day 6 - SOQL and Apex Triggers

## Topics Covered

- Salesforce Data Retrieval
- SOQL Basics
- SOSL Basics
- DML Operations
- Apex Triggers
- Event-Driven Systems
- Flow vs Trigger
- Before vs After Trigger

---

# What is SOQL?

SOQL (Salesforce Object Query Language) is a query language used to retrieve data from Salesforce objects.  
It is similar to SQL but specifically designed for Salesforce data and relationships.  
SOQL helps developers search, filter, and retrieve records from objects efficiently.

SOQL is mainly used in Apex code, reports, integrations, and automation processes.

---

# Why SOQL is Important

Enterprise systems store large amounts of structured data.  
SOQL allows applications to retrieve only the required information quickly and efficiently.  
It helps businesses generate reports, automate workflows, and process records dynamically.

---

# What is an Apex Trigger?

An Apex Trigger is a piece of Apex code that executes automatically when specific events occur on Salesforce records.  
Triggers help automate actions when records are created, updated, deleted, or restored.  
They are used to implement advanced business logic and event-driven behavior in Salesforce.

Triggers work automatically in the background whenever data changes happen.

---

# Why Triggers are Important

Enterprise applications must react automatically when data changes occur.  
Triggers help systems perform actions instantly without waiting for manual intervention.  
They improve automation, consistency, and real-time processing in business systems.

---

# Difference Between Flow and Trigger

| Flow | Apex Trigger |
|------|---------------|
| No-code automation | Code-based automation |
| Easier to build and maintain | More powerful and flexible |
| Best for simple workflows | Best for complex business logic |
| Uses visual interface | Uses Apex programming |
| Faster development | Advanced customization |

---

# Difference Between Before and After Trigger

| Before Trigger | After Trigger |
|----------------|---------------|
| Executes before record is saved | Executes after record is saved |
| Used for validation and field updates | Used for related actions and notifications |
| Faster because data is not committed yet | Used when record ID or final data is needed |
| Example: Update attendance percentage | Example: Send confirmation email |

---

# Trigger Use Cases in College Management System

## 1. Welcome Email After Student Registration

### Trigger Event
After a new student record is created.

### Action
Automatically send a welcome email to the student.

### Why?
Improves communication and provides instant confirmation.

---

## 2. Notify Faculty When Course Becomes Full

### Trigger Event
After course seat count reaches maximum capacity.

### Action
Automatically notify the assigned faculty member.

### Why?
Helps faculty manage enrollment planning efficiently.

---

## 3. Attendance Warning Notification

### Trigger Event
After student attendance percentage drops below 75%.

### Action
Send warning notification to student and faculty.

### Why?
Helps improve academic monitoring and student performance.

---

## 4. Auto Update Remaining Seats

### Trigger Event
After a student enrolls in a course.

### Action
Automatically reduce available seat count.

### Why?
Maintains accurate course seat availability.

---

## 5. Fee Payment Confirmation

### Trigger Event
After student fee payment status changes to “Paid”.

### Action
Automatically send payment confirmation message.

### Why?
Improves transparency and reduces manual communication.

---

# Query Examples

## 1. Find all students enrolled in Course A

```text
Find all students whose course is Course A
```

---

## 2. Find all courses handled by Faculty X

```text
Retrieve all courses assigned to Faculty X
```

---

## 3. Find students with attendance below 75%

```text
Retrieve students whose attendance percentage is less than 75
```

---

## 4. Find students who have pending fee balance

```text
Retrieve students with remaining fee balance greater than 0
```

---

## 5. Find all faculty members in the Computer Science department

```text
Retrieve faculty records where department is Computer Science
```

---

# Flow vs Trigger Thinking

| Scenario | Best Choice | Reason |
|----------|-------------|--------|
| Simple email notification | Flow | Easy no-code automation |
| Complex scholarship eligibility logic | Apex Trigger | Requires advanced calculations |
| Updating related records | Flow | Easier and maintainable |
| External payment API integration | Apex Trigger | Requires programming and API handling |
| Timetable conflict checking | Apex Trigger | Needs complex record comparison |

---

# Event-Driven System Thinking

Enterprise systems work based on events and automatic reactions.  
Whenever data changes occur, the system immediately performs required actions automatically.

Examples:
- Student registration triggers welcome emails
- Attendance updates trigger alerts
- Fee payments trigger confirmations

This event-driven behavior improves speed, automation, and system intelligence.

---

# Reflection - Why Enterprise Systems React Automatically to Data Changes

Modern enterprise systems handle thousands of transactions and data updates every day.  
Manual monitoring is inefficient and error-prone.  
Automatic reactions help businesses process operations quickly and consistently.

Event-driven systems improve:
- Real-time processing
- Productivity
- Automation
- Data consistency
- User experience

Salesforce uses Flows and Apex Triggers to implement intelligent business automation.

---

# Learning Outcomes

Through this task, I learned:
- What SOQL is
- How Salesforce retrieves data
- What Apex Triggers do
- Difference between Flow and Trigger
- Difference between Before and After Trigger
- Importance of event-driven systems
- How enterprise applications react automatically to data changes

---

# Screenshots

![](# Day 6 - SOQL and Apex Triggers

## Topics Covered

- Salesforce Data Retrieval
- SOQL Basics
- SOSL Basics
- DML Operations
- Apex Triggers
- Event-Driven Systems
- Flow vs Trigger
- Before vs After Trigger

---

# What is SOQL?

SOQL (Salesforce Object Query Language) is a query language used to retrieve data from Salesforce objects.  
It is similar to SQL but specifically designed for Salesforce data and relationships.  
SOQL helps developers search, filter, and retrieve records from objects efficiently.

SOQL is mainly used in Apex code, reports, integrations, and automation processes.

---

# Why SOQL is Important

Enterprise systems store large amounts of structured data.  
SOQL allows applications to retrieve only the required information quickly and efficiently.  
It helps businesses generate reports, automate workflows, and process records dynamically.

---

# What is an Apex Trigger?

An Apex Trigger is a piece of Apex code that executes automatically when specific events occur on Salesforce records.  
Triggers help automate actions when records are created, updated, deleted, or restored.  
They are used to implement advanced business logic and event-driven behavior in Salesforce.

Triggers work automatically in the background whenever data changes happen.

---

# Why Triggers are Important

Enterprise applications must react automatically when data changes occur.  
Triggers help systems perform actions instantly without waiting for manual intervention.  
They improve automation, consistency, and real-time processing in business systems.

---

# Difference Between Flow and Trigger

| Flow | Apex Trigger |
|------|---------------|
| No-code automation | Code-based automation |
| Easier to build and maintain | More powerful and flexible |
| Best for simple workflows | Best for complex business logic |
| Uses visual interface | Uses Apex programming |
| Faster development | Advanced customization |

---

# Difference Between Before and After Trigger

| Before Trigger | After Trigger |
|----------------|---------------|
| Executes before record is saved | Executes after record is saved |
| Used for validation and field updates | Used for related actions and notifications |
| Faster because data is not committed yet | Used when record ID or final data is needed |
| Example: Update attendance percentage | Example: Send confirmation email |

---

# Trigger Use Cases in College Management System

## 1. Welcome Email After Student Registration

### Trigger Event
After a new student record is created.

### Action
Automatically send a welcome email to the student.

### Why?
Improves communication and provides instant confirmation.

---

## 2. Notify Faculty When Course Becomes Full

### Trigger Event
After course seat count reaches maximum capacity.

### Action
Automatically notify the assigned faculty member.

### Why?
Helps faculty manage enrollment planning efficiently.

---

## 3. Attendance Warning Notification

### Trigger Event
After student attendance percentage drops below 75%.

### Action
Send warning notification to student and faculty.

### Why?
Helps improve academic monitoring and student performance.

---

## 4. Auto Update Remaining Seats

### Trigger Event
After a student enrolls in a course.

### Action
Automatically reduce available seat count.

### Why?
Maintains accurate course seat availability.

---

## 5. Fee Payment Confirmation

### Trigger Event
After student fee payment status changes to “Paid”.

### Action
Automatically send payment confirmation message.

### Why?
Improves transparency and reduces manual communication.

---

# Query Examples

## 1. Find all students enrolled in Course A

```text
Find all students whose course is Course A
```

---

## 2. Find all courses handled by Faculty X

```text
Retrieve all courses assigned to Faculty X
```

---

## 3. Find students with attendance below 75%

```text
Retrieve students whose attendance percentage is less than 75
```

---

## 4. Find students who have pending fee balance

```text
Retrieve students with remaining fee balance greater than 0
```

---

## 5. Find all faculty members in the Computer Science department

```text
Retrieve faculty records where department is Computer Science
```

---

# Flow vs Trigger Thinking

| Scenario | Best Choice | Reason |
|----------|-------------|--------|
| Simple email notification | Flow | Easy no-code automation |
| Complex scholarship eligibility logic | Apex Trigger | Requires advanced calculations |
| Updating related records | Flow | Easier and maintainable |
| External payment API integration | Apex Trigger | Requires programming and API handling |
| Timetable conflict checking | Apex Trigger | Needs complex record comparison |

---

# Event-Driven System Thinking

Enterprise systems work based on events and automatic reactions.  
Whenever data changes occur, the system immediately performs required actions automatically.

Examples:
- Student registration triggers welcome emails
- Attendance updates trigger alerts
- Fee payments trigger confirmations

This event-driven behavior improves speed, automation, and system intelligence.

---

# Reflection - Why Enterprise Systems React Automatically to Data Changes

Modern enterprise systems handle thousands of transactions and data updates every day.  
Manual monitoring is inefficient and error-prone.  
Automatic reactions help businesses process operations quickly and consistently.

Event-driven systems improve:
- Real-time processing
- Productivity
- Automation
- Data consistency
- User experience

Salesforce uses Flows and Apex Triggers to implement intelligent business automation.

---

# Learning Outcomes

Through this task, I learned:
- What SOQL is
- How Salesforce retrieves data
- What Apex Triggers do
- Difference between Flow and Trigger
- Difference between Before and After Trigger
- Importance of event-driven systems
- How enterprise applications react automatically to data changes

---

# Screenshots
![](https://github.com/Akash0716/salesforce-training/blob/main/week-1/day6-triggers-soql/Apex%20Triggers.png?raw=true)

