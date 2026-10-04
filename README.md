# Vetri-Thiran-Payirchi Thittam
 WhatNext Vision Motors: Shaping the Future of Mobility with Innovation and Excellence Project
 # WhatNext Vision Motors

### Shaping the Future of Mobility with Innovation and Excellence

<p align="center">
  <strong>Salesforce CRM | Automotive Order Management | Apex Automation</strong>
</p>

---

## Project Overview

**WhatNext Vision Motors** is a Salesforce-based CRM solution designed to modernize vehicle ordering, dealership operations, and customer engagement.

The project automates the vehicle ordering lifecycle through intelligent dealer assignment, real-time stock validation, automated order status updates, and scheduled test drive reminders.

By replacing manual and disconnected processes with a centralized Salesforce platform, the solution aims to improve operational efficiency, order accuracy, and customer satisfaction.

## Problem Statement

Traditional vehicle ordering and dealership operations often rely on manual processes and disconnected systems, resulting in:

* Incorrect vehicle orders due to outdated stock information.
* Delays in assigning orders to suitable dealerships.
* Lack of real-time order status visibility.
* Manual follow-ups for test drive appointments.
* Increased operational workload and customer dissatisfaction.

## Proposed Solution

The Salesforce CRM implementation provides an integrated solution that:

* Manages vehicle, dealer, and customer information.
* Validates vehicle stock before accepting orders.
* Automatically assigns orders to the nearest eligible dealer based on customer location.
* Prevents orders when vehicles are out of stock.
* Updates order statuses through automation.
* Sends scheduled email reminders for test drives.
* Provides centralized reporting and dashboards.

## Objectives

1. Automate the vehicle ordering process.
2. Improve stock accuracy and prevent invalid orders.
3. Streamline dealer assignment.
4. Enhance customer communication and engagement.
5. Reduce manual intervention in dealership operations.
6. Improve business visibility through Salesforce reports and dashboards.

## Key Features

| Feature                     | Description                                     |
| --------------------------- | ----------------------------------------------- |
| Vehicle Management          | Maintain vehicle details and stock availability |
| Dealer Management           | Manage dealership information and locations     |
| Customer Order Management   | Create and track vehicle orders                 |
| Stock Validation            | Prevent orders for unavailable vehicles         |
| Automatic Dealer Assignment | Assign orders to the nearest eligible dealer    |
| Order Status Automation     | Dynamically update order statuses               |
| Test Drive Reminders        | Schedule automated email notifications          |
| Batch Processing            | Process vehicle stock updates efficiently       |
| Reports & Dashboards        | Monitor orders, stock, and operations           |

## Technology Stack

| Layer                | Technology                         |
| -------------------- | ---------------------------------- |
| CRM Platform         | Salesforce                         |
| User Interface       | Salesforce Lightning Experience    |
| Business Logic       | Apex                               |
| Automation           | Salesforce Flows                   |
| Database             | Salesforce Custom Objects          |
| Data Validation      | Validation Rules and Apex Triggers |
| Bulk Processing      | Batch Apex                         |
| Scheduled Automation | Scheduled Apex                     |
| Analytics            | Salesforce Reports and Dashboards  |

## System Architecture

```text
          Customer / Operations Manager
                      |
                      v
          Salesforce Lightning UI
                      |
                      v
             Salesforce CRM
                      |
          +-----------+-----------+
          |           |           |
          v           v           v
       Vehicle      Dealer      Customer
       Records      Records     Orders
          |           |           |
          +-----------+-----------+
                      |
                      v
             Business Automation
                      |
          +-----------+-----------+
          |           |           |
          v           v           v
      Apex Trigger  Batch Apex  Scheduled Apex
          |           |           |
          v           v           v
      Stock       Stock        Order Status
      Validation  Updates      & Test Drive
                                  Reminders
                      |
                      v
             Reports & Dashboards
```

## Functional Requirements

| ID    | Requirement                    |
| ----- | ------------------------------ |
| FR-01 | Vehicle management             |
| FR-02 | Dealer management              |
| FR-03 | Customer order creation        |
| FR-04 | Vehicle stock validation       |
| FR-05 | Automatic dealer assignment    |
| FR-06 | Test drive scheduling          |
| FR-07 | Automated order status updates |
| FR-08 | Reports and dashboards         |

## Non-Functional Requirements

* **Usability:** Easy navigation through Salesforce Lightning.
* **Security:** Role-based access control.
* **Reliability:** Accurate business automation.
* **Performance:** Efficient order processing.
* **Availability:** Cloud-based access.
* **Scalability:** Support for multiple dealerships.

## Customer Journey

```text
Customer Inquiry
       |
       v
Vehicle Selection
       |
       v
Order Placement
       |
       v
Stock Validation
       |
       v
Nearest Dealer Assignment
       |
       v
Order Processing
       |
       v
Test Drive Scheduling
       |
       v
Automated Reminders
       |
       v
Order Confirmation
       |
       v
Reports & Dashboards
```

## Apex Components

The project incorporates the following Apex components:

| Component                    | Responsibility                                            |
| ---------------------------- | --------------------------------------------------------- |
| `VehicleOrderTriggerHandler` | Handles vehicle order business logic and stock validation |
| `VehicleOrderBatch`          | Processes vehicle stock updates in batches                |
| `VehicleOrderBatchScheduler` | Schedules batch execution                                 |

**Note:** Component names describe the intended responsibilities. Actual implementation details depend on the Apex code configured in the Salesforce org.

## Project Design

### Problem–Solution Fit

The solution addresses fragmented dealership operations by integrating vehicle stock validation, dealer assignment, order processing, and customer communication within Salesforce.

The centralized CRM system reduces repetitive manual work and provides better visibility into the complete vehicle ordering lifecycle.

## Expected Benefits

* Reduced order processing errors.
* Improved inventory accuracy.
* Faster dealership coordination.
* Better customer communication.
* Reduced manual workload.
* Improved operational transparency.
* Centralized business reporting.

## Project Information

| Attribute            | Details                                            |
| -------------------- | -------------------------------------------------- |
| Project Name         | WhatNext Vision Motors                             |
| Project Type         | Salesforce CRM Implementation                      |
| Domain               | Automotive / Customer Relationship Management      |
| Platform             | Salesforce                                         |
| Development Approach | Declarative Automation + Apex Programming          |
| Primary Focus        | Vehicle Order Management and Dealership Automation |

## Future Enhancements

* Integration with external vehicle inventory systems.
* Advanced geographical dealer assignment.
* Customer self-service vehicle ordering portal.
* Real-time order tracking notifications.
* AI-powered vehicle recommendations.
* Advanced analytics for dealership performance.

## Conclusion

WhatNext Vision Motors demonstrates how Salesforce CRM can transform automotive business operations through workflow automation, Apex programming, centralized data management, and customer-focused processes.

The solution establishes a foundation for more accurate vehicle ordering, efficient dealership coordination, and improved customer experience.

---

**Project:** WhatNext Vision Motors
**Platform:** Salesforce CRM
**Domain:** Automotive Technology & Business Process Automation

