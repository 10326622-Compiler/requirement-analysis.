# Requirement Analysis in Software Development.
This repository focuses on the Requirement Analysis phase of software development — one of the most important stages in building successful software projects.

The purpose of this repository is to document and demonstrate how to gather, analyze, and define user and system requirements before development begins. The project provides clear, structured documentation of requirements such as functional needs, user stories, system goals, and constraints.

By organizing these details early, developers and stakeholders can ensure a shared understanding of the project’s objectives, reduce errors, and build a solid foundation for design and implementation.



##  Introduction
**Requirement Analysis** is one of the most critical phases of the **Software Development Life Cycle (SDLC)**. It involves identifying, gathering, analyzing, and documenting the needs and expectations of users, stakeholders, and the system itself before actual development begins. This ensures that developers understand *what to build*, *why to build it*, and *how it should function* to meet business goals.

---

##  What Is Requirement Analysis?
Requirement Analysis (also called requirements engineering) is the process of studying user needs to define clear, detailed, and testable requirements for a software system. It bridges the gap between clients and developers by translating business ideas into technical specifications.

**The process includes:**
1. **Requirement Gathering:** Collect information from stakeholders through interviews, surveys, and observations.  
2. **Requirement Elicitation:** Understand *what users truly need* versus *what they say they want.*  
3. **Requirement Analysis:** Evaluate requirements for clarity, completeness, and feasibility.  
4. **Requirement Specification:** Document the requirements in a **Software Requirement Specification (SRS)**.  
5. **Requirement Validation:** Review and confirm that the documented requirements accurately reflect user needs.

---
 ##  Types of Requirements

| Type | Description | Example |
|------|--------------|----------|
| **Functional Requirements** | Define *what* the system should do. | “The user should be able to reset their password via email.” |
| **Non-Functional Requirements** | Define *how* the system performs tasks (quality attributes). | “The system should respond within 2 seconds.” |
| **Business Requirements** | Describe the overall goals and objectives of the project. | “Increase user engagement by 30%.” |
| **User Requirements** | Focus on user interactions and expectations. | “Users should be able to view transaction history.” |

---

---

## 🔍 Importance of Requirement Analysis in SDLC
Requirement Analysis is a foundation for project success. Its importance includes:

- **Clear Understanding of Objectives:** Ensures developers and stakeholders have a shared understanding.  
- **Reduced Errors and Rework:** Identifies problems early, saving time and cost.  
- **Improved Project Planning:** Enables accurate time and resource estimation.  
- **Enhanced Communication:** Acts as a reference between clients, users, and developers.  
- **Better System Quality:** Leads to software that meets user expectations.  
- **Traceability and Validation:** Ensures all requirements are implemented and tested correctly.

---

## ⚙️ Role in the Software Development Life Cycle (SDLC)
Requirement Analysis typically follows **Feasibility Study** and precedes **System Design**. It acts as the blueprint for all later stages.

##  Why Requirement Analysis Is Critical in the SDLC

Requirement Analysis is a crucial phase in the Software Development Life Cycle because it lays the groundwork for every other stage. Below are three key reasons why it is so important:

### 1.  Clear Understanding of Project Goals
Requirement Analysis ensures that both developers and stakeholders share the same understanding of what the system is supposed to achieve. By defining functional and non-functional requirements early, teams can align their objectives and avoid confusion later in the project.

### 2. Reduced Errors and Rework
Identifying potential issues and unclear requirements at the beginning helps prevent costly changes during the design or coding stages. This saves time, reduces project costs, and ensures a smoother development process.

### 3.  Improved Planning and Decision-Making
Well-defined requirements provide a solid foundation for accurate project estimation, scheduling, and resource allocation. It helps project managers plan effectively and developers make informed technical decisions.

> In short, strong Requirement Analysis leads to fewer misunderstandings, more efficient development, and higher-quality software.

# Key Activities in Requirement Analysis.

**The Activities includes:**
1. **Requirement Gathering:** Collect information from stakeholders through interviews, surveys, and observations.  
2. **Requirement Elicitation:** Understand *what users truly need* versus *what they say they want.*  
3. **Requirement Analysis:** Evaluate requirements for clarity, completeness, and feasibility.  
4. **Requirement Specification:** Document the requirements in a **Software Requirement Specification (SRS)**.  
5. **Requirement Validation:** Review and confirm that the documented requirements accurately reflect user needs.

   ##  Types of Requirements

| Type | Description | Example |
|------|--------------|----------|
| **Functional Requirements** | Define *what* the system should do. | Booking list and User authentication |
| **Non-Functional Requirements** | Define *how* the system performs tasks (quality attributes). |The perfromance and scalability |

---
##  Use Case Diagrams

###  What is a Use Case Diagram?
A **Use Case Diagram** is a visual representation that shows how different users (called *actors*) interact with a system to achieve specific goals. It helps in identifying the system’s functional requirements and understanding the relationships between users and system processes.

###  Benefits of Use Case Diagrams
- Clearly defines the system’s boundaries and functionalities.  
- Improves communication between stakeholders and developers.  
- Helps identify user needs and system behavior early in the SDLC.  
- Serves as a blueprint for writing detailed use case specifications.

---

###  Use Case Diagram for Booking System

Below is a use case diagram illustrating how users interact with a booking system.

**Actors:**
-  **Customer:** Browses listings, makes a booking, cancels a booking, and views booking history.  
-  **Host:** Adds new property listings, updates listings, and manages bookings.  
-  **Admin:** Manages users, oversees listings, and handles complaints.

**Use Cases:**
- View available properties  
- Book property  
- Cancel booking  
- Add listing  
- Manage users  
- View booking history  

---

###  Diagram
![Use Case Diagram for Booking System](alx-booking-uc.png)
*(Diagram created using [Draw.io](https://app.diagrams.net/))*

##  Acceptance Criteria

### What Are Acceptance Criteria?
**Acceptance Criteria (AC)** are the conditions that a software product must meet to be accepted by a user, customer, or other stakeholders.  
They define what “done” means for a feature or user story — providing a clear, testable understanding of the system’s expected behavior.

---

### 💡 Importance of Acceptance Criteria in Requirement Analysis
- **Ensures Clarity:** Clearly defines what needs to be built, reducing misunderstandings between developers and stakeholders.  
- **Improves Testing:** Each acceptance criterion can be turned into a test case to verify that the system works as intended.  
- **Supports Agile Development:** Helps teams agree on the scope of work for each user story or feature before implementation begins.  
- **Enhances Quality Assurance:** Ensures that every feature aligns with user needs and business requirements.

---

###  Example: Acceptance Criteria for the Checkout Feature (Booking Management System)

**Feature:** Checkout and Payment for Booking

**User Story:**  
> As a customer, I want to complete my booking by paying securely online, so that my reservation is confirmed immediately.

**Acceptance Criteria:**
1.  The system must display a summary of the booking before payment (property details, dates, total cost).  
2.  The user must be able to select a payment method (credit card, PayPal, or mobile money).  
3.  The system must validate payment information before processing.  
4.  Upon successful payment, the booking status must update to **“Confirmed.”**  
5.  The user must receive a payment confirmation email within one minute of successful payment.  
6.  If payment fails, the user should see an error message and have the option to retry or cancel.

---

>  **In summary:**  
> Acceptance Criteria help bridge the gap between *requirements* and *implementation*. They make each feature measurable, testable, and aligned with user expectations — a vital component of effective requirement analysis.
