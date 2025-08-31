# Requirement Analysis in Software Development

This repository documents the Requirement Analysis (RA) phase for a **Booking Management System**.  
The purpose is to explore how requirements are gathered, analyzed, structured, and validated to ensure the system meets both user needs and business goals.  

---

## What is Requirement Analysis?

Requirement Analysis is the process of identifying, gathering, and defining the needs and expectations of stakeholders for a software system.  
It serves as the foundation for the entire Software Development Life Cycle (SDLC) by ensuring that developers, designers, and clients have a shared understanding of what the system should achieve.

Key points:
- Ensures alignment between stakeholders and development teams.
- Helps in identifying project scope and priorities.
- Provides clear documentation that guides design, development, and testing.

---

## Why is Requirement Analysis Important?

Requirement Analysis is a **critical phase of the SDLC** because:

1. **Clarity & Alignment**  
   Prevents misunderstandings between clients, users, and developers by providing well-documented requirements.

2. **Cost & Time Efficiency**  
   Detecting requirement issues early reduces the risk of costly changes during later stages of development.

3. **Quality & Usability**  
   Ensures the software meets user expectations and business objectives, leading to higher customer satisfaction.

---

## Key Activities in Requirement Analysis

The RA process involves several key activities:

- **Requirement Gathering**  
  Collecting information from stakeholders, users, and market research.

- **Requirement Elicitation**  
  Using techniques such as interviews, questionnaires, workshops, and brainstorming to extract requirements.

- **Requirement Documentation**  
  Recording functional and non-functional requirements clearly in Software Requirement Specification (SRS) documents.

- **Requirement Analysis and Modeling**  
  Analyzing requirements for feasibility, conflicts, and completeness. Models like use case diagrams are created.

- **Requirement Validation**  
  Reviewing requirements with stakeholders to confirm accuracy and completeness.

---

## Types of Requirements

### 1. Functional Requirements
Define **what the system should do**.  
Examples for a Booking Management System:
- Users can **search for available properties** by date, location, and price.
- Users can **book a property** and receive confirmation.
- Admins can **add, edit, or remove property listings**.
- System generates **booking history reports**.

### 2. Non-Functional Requirements
Define **how the system should perform**.  
Examples:
- The system should support **at least 10,000 concurrent users**.  
- Response time for property search results should be **under 2 seconds**.  
- The application must be **mobile responsive**.  
- Data should be **encrypted** to ensure security.

---

## Use Case Diagrams

Use Case Diagrams visually represent how users (actors) interact with the system.  

**Benefits:**
- Provide a high-level view of system functionality.
- Help stakeholders understand interactions without technical detail.
- Simplify communication between technical and non-technical stakeholders.

### Example: Booking Management System Use Case Diagram

Actors:
- **User (Guest)**  
- **Admin**  
- **Payment Gateway**  

Use Cases:
- Search Properties  
- View Property Details  
- Book Property  
- Make Payment  
- Manage Listings (Admin)  
- Generate Reports (Admin)  

![Use Case Diagram](alx-booking-uc.png)

---

## Acceptance Criteria

Acceptance Criteria define the specific conditions a feature must meet to be considered complete and accepted by stakeholders.  

**Importance:**
- Ensures requirements are testable and measurable.  
- Prevents ambiguity by providing clear expectations.  
- Acts as a checklist for developers and testers.  

**Example (Checkout Feature):**

- User can review booking details before payment.  
- System must validate payment information before processing.  
- Confirmation email/SMS is sent immediately after successful payment.  
- Booking record is stored in the database with a unique ID.  

---

## 📌 Project Summary

This project demonstrates how Requirement Analysis serves as the **blueprint for software development**.  
It ensures clear communication, reduces risks, and builds a foundation for delivering scalable, reliable, and user-friendly booking management software.

