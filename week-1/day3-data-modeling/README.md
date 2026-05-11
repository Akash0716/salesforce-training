# Day 3 - Data Modeling in Salesforce

## Topics Covered

- Objects, Fields, and Records
- Standard vs Custom Objects
- Relationships in Salesforce
- Formula Fields
- Validation Rules
- Structured Enterprise Data
- Business Logic without Coding

---

# Difference Between App, Object, Record, and Field

## App
An App in Salesforce is a collection of related tabs, objects, and tools designed for a specific business process.  
Apps help users access all required functionalities from one place.  
They improve navigation and organize business operations efficiently.

### Example
College Management App

---

## Object
An Object in Salesforce is similar to a database table used to store information.  
Objects contain records and fields related to a particular business entity.  
Salesforce provides both standard and custom objects for managing data.

### Example
Student Object, Course Object

---

## Record
A Record is a single entry or row inside an object.  
Each record stores complete information about a specific item or person.  
Records help organizations manage and track business-related data efficiently.

### Example
One student’s complete details

---

## Field
A Field is an individual data attribute stored inside a record.  
Fields help capture specific pieces of information such as names, numbers, or dates.  
Different field types are available depending on the data being stored.

### Example
Student Name, Age, Email

---

# Standard vs Custom Objects

## Standard Objects
Standard objects are pre-built objects provided by Salesforce.  
They are commonly used for CRM functionalities like managing customers, sales, and business processes.  
These objects are available by default in Salesforce.

### Examples
- Account
- Contact
- Lead
- Opportunity

---

## Custom Objects
Custom objects are user-created objects designed according to specific business requirements.  
They help organizations store data that is unique to their business processes.  
Custom objects extend Salesforce functionality beyond standard CRM operations.

### Examples
- Student
- Faculty
- Course
- Department

---

# College Management System Data Model

## Objects Used

1. Student  
2. Faculty  
3. Course  
4. Department  

---

# Relationships Between Objects

| Object | Relationship | Related Object |
|--------|--------------|----------------|
| Student | Lookup | Course |
| Faculty | Lookup | Department |
| Course | Lookup | Department |
| Student | Lookup | Faculty |

---

# Relationship Explanation

Relationships connect objects and allow related data to work together.  
They help maintain structured and organized enterprise data.  
Lookup relationships are used when objects are related but can exist independently.

### Examples
- One Department can have many Courses.
- One Course can have many Students.
- One Faculty member can guide many Students.

---

# College Management System Diagram

```text
Department
   │
   ├── Faculty
   │
   └── Course
            │
            └── Student
```

---

# Formula Fields

## What is a Formula Field?

A Formula Field automatically calculates values using formulas and existing field data.  
It reduces manual calculations and ensures data accuracy.  
Formula Fields help automate repetitive business calculations without coding.

---

## 1. Course Duration
Calculates course duration using:

End Date - Start Date

### Why?
Helps automatically calculate the total duration of the course without manual counting.

---

## 2. Attendance Percentage
Calculates attendance percentage using:

(Classes Attended / Total Classes) × 100

### Why?
Helps track student attendance accurately and reduces manual calculation errors.

---

## 3. Total Fee Balance
Calculates pending fee amount using:

Total Fee - Paid Amount

### Why?
Helps administrators quickly identify remaining student fee balances.

---

# Validation Rules

## What is a Validation Rule?

A Validation Rule checks data before saving a record in Salesforce.  
It prevents users from entering invalid or incomplete information.  
Validation Rules improve data quality and maintain system consistency.

---

## 1. Phone Number Must Contain 10 Digits

### Why?
Prevents storing incorrect or incomplete contact numbers.

---

## 2. Course Start Date Cannot Be After End Date

### Why?
Prevents invalid course scheduling and incorrect date entries.

---

## 3. Student Name Cannot Contain Numbers

### Why?
Prevents invalid student names and maintains clean data quality.

---

# Reflection - Why Structured Data Matters

Companies need structured data because enterprise systems handle huge amounts of information.  
Random spreadsheets can create duplication, inconsistency, and data errors.  
Structured data helps maintain relationships, improve reporting, and support automation.

Salesforce uses objects, records, fields, and relationships to organize business information efficiently.

---

# Learning Outcomes

Through this task, I learned:
- How Salesforce stores business data
- Difference between App, Object, Record, and Field
- Importance of relationships in enterprise systems
- Difference between Formula Fields and Validation Rules
- How no-code business logic works in Salesforce
- Why structured data is important for organizations

---

# Screenshots
![](https://github.com/Akash0716/salesforce-training/blob/main/week-1/day3-data-modeling/Data%20Modeling.png?raw=true)  

