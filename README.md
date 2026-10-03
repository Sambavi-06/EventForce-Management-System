# EventForce Management System

## Project Overview

**EventForce Management System** is a Salesforce-based event management application developed to manage events, clients, vendors, venues, and feedback in a centralized platform.

The project demonstrates the use of Salesforce CRM features such as custom objects, object relationships, Salesforce Flows, validation rules, approval processes, security configurations, reports, dashboards, and a Lightning application.

---

## Objectives

The main objectives of the EventForce Management System are:

* Manage event information in a centralized Salesforce application.
* Maintain Client, Vendor, Venue, and Feedback records.
* Establish relationships between different event management records.
* Automate important business processes using Salesforce Flows.
* Apply validation rules to maintain data quality.
* Implement approval processes for required business operations.
* Configure Salesforce security using profiles and permission sets.
* Generate reports for event-related analysis.
* Create dashboards for monitoring and decision-making.
* Provide a user-friendly Lightning application for event management.

---

## Salesforce Objects

The project uses the following custom objects:

| Object           | Purpose                                                                         |
| ---------------- | ------------------------------------------------------------------------------- |
| **Event**        | Stores event details such as event name, date, status, and related information. |
| **Client**       | Maintains information about clients associated with events.                     |
| **Vendor**       | Stores vendor information used for event services.                              |
| **Venue**        | Maintains venue details for events.                                             |
| **Feedback**     | Stores feedback related to completed events.                                    |
| **Event Vendor** | Junction object used to associate events with vendors.                          |

---

## Data Model

The EventForce data model establishes relationships between the major Salesforce objects.

The **Event** object acts as the central object and is connected with related Client, Venue, Vendor/Event Vendor, and Feedback information.

The **Event Vendor** junction object helps manage the relationship between Events and Vendors.

### ER Diagram

[View ER Diagram](ER_Diagram.png)

---

## Salesforce Application

The project includes a Lightning application named:

### Event Planner

The application provides navigation to the major components of the EventForce system, including:

* Events
* Clients
* Vendors
* Venues
* Feedback
* Reports
* Dashboards

---

## Key Features

### 1. Custom Objects

Custom Salesforce objects were created to represent the different entities involved in event management.

### 2. Object Relationships

Relationships were established between the objects to connect event information with clients, venues, vendors, and feedback.

### 3. Salesforce Flows

Salesforce Flow is used to automate required business processes and reduce manual work.

### 4. Validation Rules

Validation rules help prevent incorrect or incomplete data from being entered into the system.

### 5. Approval Process

An approval process is configured for the required event management workflow.

### 6. Security Configuration

Salesforce security features such as profiles and permission sets are used to control access to application data and functionality.

### 7. Reports

Reports provide organized information about event-related records and help users monitor the system.

### 8. Dashboards

The project includes dashboards for visual monitoring of event management information.

### 9. Lightning Application

The **Event Planner** Lightning application provides a centralized interface for accessing the EventForce components.

---

# Project Screenshots

## App Overview

The Event Planner application provides access to the main EventForce objects and reporting components.

[View App Overview](EventForceScreenshorts/Overview.png)

---

## Event Record

The Event record page displays event-related information stored in Salesforce.

[View Event Record](EventForceScreenshorts/Event_Record.png)

---

## Salesforce Flow

The Flow demonstrates the automation configured for the EventForce application.

[View Flow](EventForceScreenshorts/Flow.png)

---

## Approval Process

The Approval Process demonstrates the configured approval workflow in Salesforce.

[View Approval Process](EventForceScreenshorts/Approval.process.png)

---

## Reports

Reports are used to organize and analyze event management data.

[View Reports](EventForceScreenshorts/Reports.png)

---

## Dashboard

The dashboard provides a visual representation of important event management information.

[View Dashboard](EventForceScreenshorts/Dashboard.png)

---

# Project Documentation

Detailed project documentation covers:

* Business Overview and Objectives
* Phase-wise Implementation
* Salesforce Data Model
* ER Diagram
* Automation Components
* Security Model
* Testing Results
* Screenshots
* Deployment
* Maintenance and Troubleshooting

**Documentation PDF will be added to this repository.**

---

# Demo Video

A complete demonstration of the EventForce Management System has been recorded.

The demo covers the application interface, Salesforce components, automation, approval process, reports, dashboard, and other implemented features.

### Watch the Demo

[Watch EventForce Demo Video](https://drive.google.com/file/d/1GKlgDSovfcJopBSBtwON4Pxs49u_320G/view?usp=sharing)

> Make sure the Google Drive sharing permission is set to **Anyone with the link – Viewer** so that others can access the video.

---

# Deployment

The project was developed and tested using a **Salesforce Developer Edition** environment.

Deployment activities were considered as part of the project implementation, including:

* Metadata readiness
* Configuration review
* Validation of Salesforce components
* Testing before deployment
* Version control using GitHub

The deployment approach is demonstrated as a simulated deployment suitable for the Developer Edition environment.

---

# Testing

The EventForce system was tested to verify the functionality of its major components.

Testing included:

* Creating and updating Event records
* Checking object relationships
* Testing Flow automation
* Testing validation rules
* Testing approval processes
* Verifying user access and permissions
* Checking reports
* Checking dashboard information
* Verifying the Lightning application navigation

---

# Maintenance and Troubleshooting

The system can be maintained by regularly monitoring:

* Salesforce Flows
* Approval Processes
* User permissions
* Data quality
* Reports and dashboards
* Validation rules
* Sharing and access settings

Common troubleshooting areas include:

* Permission conflicts
* Flow execution issues
* Validation rule errors
* Record access problems
* Incorrect report results
* Dashboard configuration issues

---

# Technologies Used

* **Salesforce Developer Edition**
* **Salesforce Lightning Platform**
* **Custom Salesforce Objects**
* **Salesforce Flows**
* **Validation Rules**
* **Approval Processes**
* **Profiles and Permission Sets**
* **Salesforce Reports**
* **Salesforce Dashboards**
* **GitHub**

---

# Project Structure

```text
EventForce-Management-System
│
├── ER_Diagram.png
│
├── EventForceScreenshorts
│   ├── Approval.process.png
│   ├── Dashboard.png
│   ├── Event_Record.png
│   ├── Flow.png
│   ├── Overview.png
│   └── Reports.png
│
└── README.md
```

---

# Learning Outcomes

Through this project, the following Salesforce concepts were practiced:

* Salesforce Custom Objects
* Object Relationships
* Salesforce Lightning App Development
* Salesforce Flow Automation
* Validation Rules
* Approval Processes
* Profiles and Permission Sets
* Reports and Dashboards
* Data Management
* Testing and Troubleshooting
* Project Documentation
* GitHub Version Control

---

# Project Status

**Status: Completed**

The EventForce Management System has been implemented in Salesforce with the required objects, relationships, automation, approval process, security configuration, reports, dashboard, screenshots, and project demonstration.

---

# Repository

This repository contains the project-related documentation, ER diagram, screenshots, and supporting resources for the **EventForce Management System**.

**Developed as a Salesforce academic project.**
