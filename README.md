# Salesforce Training

This repository contains my Salesforce Summer Program learning progress, organized week-wise and day-wise.  
It includes CRM concepts, Salesforce Platform basics, data modeling, relationships, business logic, and real-world Salesforce system design.

---

# Repository Structure

```text
salesforce-training/
│
├── week-1
│   │
│   ├── day1-crm-basics
│   │   ├── README.md
│   │   └── screenshots
│   │
│   ├── day2-platform-basics
│   │   ├── README.md
│   │   └── screenshots
│   │
│   └── day3-data-modeling
│       ├── README.md
│       └── screenshots
│
└── README.md
```

---

# Day 1 - CRM Basics

## Topics Learned
- What is Salesforce
- What is CRM
- Business workflow in Salesforce
- Accounts, Contacts, Leads, and Opportunities
- Salesforce Playground basics

---

## What is CRM?

CRM (Customer Relationship Management) is a technology used to manage customer interactions, business relationships, and organizational data efficiently.  
It helps companies improve communication, manage sales processes, and store customer information in a centralized system.

---

## Salesforce Core Concepts

### Account
Represents an organization, institution, or company.

### Example
College/University

---

### Contact
Represents an individual person associated with an Account.

### Example
Student or Parent

---

### Lead
Represents a person who has shown interest in a service or organization.

### Example
Interested Student

---

### Opportunity
Represents a potential business process, deal, or enrollment.

### Example
Admission Application/Enrollment

---

## Difference Between Account and Contact

- Account represents an organization.
- Contact represents a person related to that organization.

### Example
- Account → ABC College
- Contact → Rahul Sharma

---

## Real World Mapping - College Admission System

| Salesforce Object | Real World Mapping |
|-------------------|-------------------|
| Account | College/University |
| Contact | Student/Parent |
| Lead | Interested Student |
| Opportunity | Admission Application |

---

# Day 2 - Salesforce Platform Basics

## Topics Learned
- Salesforce Platform structure
- Apps, Objects, and Tabs
- Salesforce architecture
- Configuration vs Coding
- Real system design thinking

---

## What is Salesforce Platform?

Salesforce Platform is a cloud-based environment used to build, customize, and manage business applications using apps, objects, automation tools, and code.

---

## What is an App?

An App in Salesforce is a collection of related tabs, objects, and functionalities designed for a specific business process.

### Example
College Admission Management App

---

## What is an Object?

An Object is a database table used to store records and data in Salesforce.

### Examples
- Account
- Contact
- Lead
- Opportunity

---

## What is a Tab?

A Tab is a user interface component used to access Salesforce objects, records, and applications.

### Example
Account Tab, Contact Tab

---

## Connecting CRM with Salesforce Platform

CRM concepts such as Account, Contact, Lead, and Opportunity are implemented in Salesforce as standard objects inside Apps.

In the College Admission System:
- Student enquiries are stored as Leads.
- Verified students become Contacts.
- Contacts are linked with College Accounts.
- Opportunities track admission status.

This helps manage the complete admission workflow efficiently.

---

## Configuration vs Coding

### Configuration (No Code)

Configuration is used when requirements can be achieved using Salesforce built-in tools without programming.

#### Examples
1. Creating custom fields and page layouts
2. Creating workflows and validation rules

---

### Coding (Apex)

Apex coding is used for complex business logic and integrations.

#### Examples
1. Scholarship eligibility calculation
2. Integration with external payment systems

---

## System Design - College Admission System

### App Name
College Admission Management App

---

### Objects Used
- Account
- Contact
- Lead
- Opportunity
- Course
- Student Documents
- Fee Details

---

### User Interaction Flow

1. Student submits admission enquiry
2. Lead record is created
3. Staff verifies details
4. Lead converts into Contact
5. Opportunity is created for admission tracking
6. Admin updates admission and fee status

---

# Day 3 - Data Modeling

## Topics Learned
- Objects, Fields, and Records
- Standard vs Custom Objects
- Relationships in Salesforce
- Formula Fields
- Validation Rules
- Structured Enterprise Data

---

## Difference Between App, Object, Record, and Field

| Concept | Description |
|----------|-------------|
| App | Collection of related tabs, objects, and tools |
| Object | Database table used to store data |
| Record | Single entry inside an object |
| Field | Individual data attribute in a record |

---

## Standard vs Custom Objects

### Standard Objects
Standard objects are pre-built objects provided by Salesforce for CRM functionality.

#### Examples
- Account
- Contact
- Lead
- Opportunity

---

### Custom Objects
Custom objects are user-created objects designed according to business requirements.

#### Examples
- Student
- Faculty
- Course
- Department

---

## College Management System Data Model

### Objects Used
- Student
- Faculty
- Course
- Department

---

## Relationships

| Object | Relationship | Related Object |
|--------|--------------|----------------|
| Student | Lookup | Course |
| Faculty | Lookup | Department |
| Course | Lookup | Department |
| Student | Lookup | Faculty |

---

## Formula Fields

### 1. Course Duration
Automatically calculates course duration using start and end dates.

### 2. Attendance Percentage
Calculates student attendance percentage automatically.

### 3. Total Fee Balance
Calculates remaining fee amount after payment.

---

## Validation Rules

### 1. Phone Number Must Contain 10 Digits
Prevents storing incorrect contact numbers.

### 2. Course Start Date Cannot Be After End Date
Prevents invalid course schedules.

### 3. Student Name Cannot Contain Numbers
Prevents invalid student data entry.

---

## Why Structured Data Matters

Structured data helps organizations:
- Organize information properly
- Maintain data consistency
- Improve reporting and automation
- Build relationships between records
- Reduce duplicate and invalid data

Salesforce uses structured objects and relationships to manage enterprise-level business data efficiently.

---

# Overall Learning Outcomes

Through this Salesforce training, I learned:
- CRM fundamentals
- Salesforce platform structure
- Apps, Objects, Records, and Fields
- Difference between standard and custom objects
- Business workflow management
- Relationship modeling
- Formula Fields and Validation Rules
- Configuration vs Coding
- Enterprise data management concepts
- GitHub repository organization

---

# Screenshots

Trailhead screenshots and practical exercises are included inside the screenshots folder of each day.
