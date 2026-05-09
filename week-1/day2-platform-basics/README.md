## What Is Salesforce Platform?  
  Salesforce is a cloud-based CRM platform used to manage customer relationships, sales, marketing, and support services.
It helps organizations store customer data, track business activities, and automate workflows.
Salesforce also provides tools to build custom applications using low-code and no-code development.
Businesses use it to improve communication, productivity, and decision-making.
It is widely used across industries because it is secure, scalable, and accessible from anywhere.  

## Key Terminology  
**App:**
An App in Salesforce is a set of objects,fields,and other functionality that supports a business process.you can see Which app you are using and switch between apps using the App Launcher.  

**Object:**
An Object in Salesforce is a database table used to store data.it contains records and fields,such as Acccounts,Contacts,or custom objects created for business needs.  

**Tab:**
Tab is a user interface component used to access and display data stored in objects like Accounts, Contacts, Leads, or custom objects.
Tabs help users quickly navigate different features and records in Salesforce.
They appear on the navigation bar and open pages related to a specific object or application.
Salesforce provides standard tabs as well as custom tabs created by users or developers.

## Configuration vs Coding  
| Configuration                                                                                    | Coding                                                                  |
| ------------------------------------------------------------------------------------------------ | ----------------------------------------------------------------------- |
| Configuration means customizing Salesforce using clicks and built-in tools without writing code. | Coding means developing features by writing programming code.           |
| It uses tools like Flow, Process Builder, and Object Manager.                                    | It uses languages like Apex, Visualforce, and Lightning Web Components. |
| Easier and faster to implement.                                                                  | Requires programming knowledge.                                         |
| Example: Creating fields, validation rules, workflows.                                           | Example: Writing Apex triggers or custom applications.                  |

## System Design  

### App

The Salesforce App used in this system is the **College Admission Management App**.
It helps manage student enquiries, admissions, and communication in a single platform.

### Objects

The system uses standard Salesforce objects:

* **Account** → College/University
* **Contact** → Student/Parent
* **Lead** → Interested Student
* **Opportunity** → Admission/Application Process

These objects store and organize all admission-related data.

### User Interaction

1. A student submits an enquiry form.
2. Salesforce creates a Lead record for the student.
3. After verification, the Lead is converted into a Contact linked with the College Account.
4. An Opportunity is created to track the admission or enrollment process.
5. Staff members can update student details, admission status, and communication records through the Salesforce App.

   ![](https://github.com/Akash0716/salesforce-training/blob/main/week-1/day2-platform-basics/Screenshot%202026-05-09%20154202.png?raw=true)
