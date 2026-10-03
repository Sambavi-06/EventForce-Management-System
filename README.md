# EventForce Management System

## Project Overview

EventForce Management System is a Salesforce-based Event Management application developed to manage events, clients, vendors, venues, and feedback in a centralized platform.

The project demonstrates the use of Salesforce CRM features such as custom objects, relationships, automation, approval processes, security configurations, reports, dashboards, and a Lightning application.

---

## Objectives

* Manage event information in a centralized system.
* Maintain Client, Vendor, Venue, and Feedback records.
* Establish relationships between different event management records.
* Automate important business processes using Salesforce Flows.
* Apply validation rules to maintain data quality.
* Implement approval processes for required workflows.
* Configure security using Salesforce profiles and permission sets.
* Generate reports for monitoring event-related information.
* Create dashboards for visualizing important information.
* Provide a user-friendly Lightning application for event management.

---

## Salesforce Objects

The EventForce Management System contains the following objects:

* Event
* Client
* Vendor
* Venue
* Feedback
* Event Vendor

The Event Vendor object is used as a junction object to associate Events and Vendors.

---

## Application

The project includes a Salesforce Lightning application named **Event Planner**.

The application provides access to:

* Events
* Clients
* Vendors
* Venues
* Feedback
* Reports
* Dashboards

---

## Key Features

### Custom Objects

Custom objects were created to represent the major entities involved in event management.

### Object Relationships

Relationships were established between the objects to connect events with clients, venues, vendors, and feedback.

### Salesforce Flows

Salesforce Flows are used to automate required business processes and reduce manual operations.

### Validation Rules

Validation rules are used to maintain data accuracy and prevent invalid records from being submitted.

### Approval Process

An approval process is configured to support the required event management approval workflow.

### Security

Salesforce security features such as profiles and permission sets are used to manage access to the application and its data.

### Reports

Reports are created to organize and analyze event management information.

### Dashboards

Dashboards provide a visual representation of important event-related information.

---

## Data Model

The EventForce data model represents the relationships between the major Salesforce objects.

The Event object is the central component of the system and is connected with related Client, Venue, Vendor/Event Vendor, and Feedback information.

The ER diagram is included in the project repository for reference.

---

## Automation

The project uses Salesforce automation to reduce manual work and support business processes.

The implemented automation components include:

* Salesforce Flows
* Validation Rules
* Approval Process

These components help maintain data consistency and automate required operations.

---

## Security

Security configurations are implemented using Salesforce access-control features.

The project includes:

* Profiles
* Permission Sets
* Object-level access
* Record-level access where configured

These configurations help control which users can access and modify application data.

---

## Reports and Dashboards

The project includes Salesforce reports and dashboards for monitoring event management information.

Reports help users view organized event data, while dashboards provide a visual overview of important information.

---

## Testing

The application was tested to verify the functionality of its major components.

Testing included:

* Creating Event records
* Updating Event records
* Checking object relationships
* Testing Flow automation
* Testing validation rules
* Testing approval processes
* Verifying permissions
* Checking reports
* Checking dashboards
* Verifying Lightning application navigation

---

## Deployment

The project was developed and tested using a Salesforce Developer Edition environment.

Deployment readiness was considered by reviewing the configured Salesforce components, testing the application, and maintaining project resources using GitHub.

The deployment process is demonstrated as a simulated deployment suitable for the Developer Edition environment.

---

## Maintenance and Troubleshooting

The application can be maintained by regularly monitoring:

* Salesforce Flows
* Approval Processes
* User permissions
* Data quality
* Reports and dashboards
* Validation rules
* Sharing and access settings

Common troubleshooting areas include:

* Permission issues
* Flow execution issues
* Validation errors
* Record access problems
* Report configuration issues
* Dashboard configuration issues

---

## Project Documentation

The project documentation contains information about:

* Business Overview and Objectives
* Phase-wise Implementation
* Data Model
* ER Diagram
* Automation Components
* Security Model
* Testing Results
* Screenshots
* Deployment
* Maintenance and Troubleshooting

The documentation is maintained separately in the project repository.

---

## Demo Video

A complete demonstration video has been prepared for the EventForce Management System.

The demonstration covers:

* Project Introduction
* Event Planner Application
* User Interface
* Salesforce Objects
* Automation
* Approval Process
* Security Configuration
* Reports
* Dashboard
* Testing and Troubleshooting
* Project Conclusion

The demo video is available through the project resources.

---

## Technologies Used

* Salesforce Developer Edition
* Salesforce Lightning Platform
* Salesforce Custom Objects
* Salesforce Flows
* Validation Rules
* Approval Processes
* Profiles and Permission Sets
* Salesforce Reports
* Salesforce Dashboards
* GitHub

---

## Learning Outcomes

Through this project, the following concepts were practiced:

* Salesforce Custom Objects
* Object Relationships
* Lightning Applications
* Salesforce Flow Automation
* Validation Rules
* Approval Processes
* Profiles and Permission Sets
* Reports and Dashboards
* Data Management
* Testing
* Troubleshooting
* Project Documentation
* GitHub Repository Management

---

## Project Status

**Completed**

The EventForce Management System has been implemented and tested as a Salesforce-based event management application.

The repository contains the project resources, screenshots, ER diagram, documentation, and demonstration details.

---

## Author

**Sambavi Arjunan**

B.E. Computer Science and Engineering

Government College of Engineering, Erode
