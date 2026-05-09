# Salesforce Training

This repository contains my Salesforce Summer Program learning progress, organized week-wise and day-wise.  
It includes CRM concepts, Salesforce Platform basics, real-world business mapping, system design thinking, and practical Salesforce understanding.

---

# Repository Structure
```
salesforce-training/
│
├── week-1
│   │
│   ├── day1-crm-basics
│   │   ├── README.md
│   │   └── screenshots
│   │
│   └── day2-platform-basics
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
- Accounts, Contacts, Leads, Opportunities
- Salesforce Playground basics

---

## What is CRM?

CRM (Customer Relationship Management) is a technology used to manage customer interactions, business relationships, and organizational data efficiently.

Companies use CRM systems to:
- Store customer information
- Track business processes
- Improve communication
- Manage sales and services

---

## Salesforce Core Concepts

### Account
Represents an organization, institution, or company.

Example:
College/University

---

### Contact
Represents an individual person associated with an Account.

Example:
Student or Parent

---

### Lead
Represents a person who has shown interest in a service or organization.

Example:
Interested Student

---

### Opportunity
Represents a potential business process, deal, or enrollment.

Example:
Admission Application/Enrollment

---

## Difference Between Account and Contact

- Account represents an organization.
- Contact represents a person related to that organization.

Example:
- Account → ABC College
- Contact → Rahul Sharma

---

# Real World Mapping - College Admission System

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
- Apps, Objects, Tabs
- Salesforce architecture
- Configuration vs Coding
- Real system design thinking

---

## What is Salesforce Platform?

Salesforce Platform is a cloud-based environment used to build, customize, and manage business applications using apps, objects, automation tools, and code.

---

## What is an App?

An App in Salesforce is a collection of related tabs, objects, and functionalities designed for a specific business process.

Example:
College Admission Management App

---

## What is an Object?

An Object is a database table used to store records and data in Salesforce.

Examples:
- Account
- Contact
- Lead
- Opportunity

---

## What is a Tab?

A Tab is a user interface component used to access Salesforce objects, records, and applications.

Example:
Account Tab, Contact Tab

---

# Connecting CRM with Salesforce Platform

CRM concepts such as Account, Contact, Lead, and Opportunity are implemented in Salesforce as standard objects inside Apps.

In the College Admission System:
- Student enquiries are stored as Leads.
- Verified students become Contacts.
- Contacts are linked with College Accounts.
- Opportunities track admission status.

This helps manage the complete admission workflow efficiently.

---

# Configuration vs Coding

## Configuration (No Code)

Used when requirements can be achieved using Salesforce built-in tools.

### Examples
1. Creating custom fields and page layouts
2. Creating workflows and validation rules

---

## Coding (Apex)

Used for complex business logic and integrations.

### Examples
1. Scholarship eligibility calculation
2. Integration with external payment systems

---

# System Design - College Admission System

## App Name
College Admission Management App

---

## Objects Used
- Account
- Contact
- Lead
- Opportunity
- Course
- Student Documents
- Fee Details

---

## User Interaction Flow

1. Student submits admission enquiry
2. Lead record is created
3. Staff verifies details
4. Lead converts into Contact
5. Opportunity is created for admission tracking
6. Admin updates admission and fee status

---

# Learning Outcomes

Through this training, I learned:
- CRM fundamentals
- Salesforce platform structure
- Salesforce standard objects
- Real-world business mapping
- Difference between configuration and coding
- System design concepts in Salesforce
- GitHub repository organization

---

# Screenshots

Screenshots from Trailhead modules and practical exercises are included inside respective day folders.
