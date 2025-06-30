## What is Requirement Analysis?

Requirement Analysis is a critical phase in the Software Development Life Cycle (SDLC) where the needs, expectations, and constraints of stakeholders are identified, documented, and analyzed to define the system’s intended functionality and behavior.

This process involves gathering both **functional requirements** (what the system should do) and **non-functional requirements** (how the system should perform), ensuring that the final software product aligns with business objectives and user needs.

### Importance in SDLC:
- ✅ **Prevents Miscommunication:** Clarifies expectations between developers, stakeholders, and end-users.
- ✅ **Reduces Cost & Time:** Catching ambiguities early prevents costly rework later in the development cycle.
- ✅ **Provides a Clear Roadmap:** Acts as a foundation for design, development, testing, and deployment.
- ✅ **Improves Quality:** Well-defined requirements help in building a product that meets user satisfaction and business goals.

Requirement Analysis typically includes activities such as stakeholder interviews, document analysis, use case modeling, and the creation of Software Requirement Specifications (SRS).


## Why is Requirement Analysis Important?

Requirement Analysis plays a foundational role in the success of any software project. Here are three key reasons why it is critical in the Software Development Life Cycle (SDLC):

### 1. Clear Understanding of Objectives
Requirement Analysis helps bridge the gap between stakeholders and developers by documenting what needs to be built. It ensures everyone is aligned with the project’s goals and scope from the beginning.

### 2. Risk Mitigation
By identifying potential conflicts, ambiguities, or unrealistic expectations early, Requirement Analysis helps reduce the risk of project failure, delays, or budget overruns.

### 3. Better Planning and Design
Well-defined requirements serve as a blueprint for the design, development, and testing phases. They allow teams to estimate time, cost, and resources more accurately, resulting in more efficient and organized development.

Optional additional reasons (if you'd like to add more):
- ✅ **Enhanced Product Quality:** Products built based on clear and validated requirements are more likely to meet user needs.
- ✅ **Improved Communication:** Requirement documents serve as a reference for all stakeholders throughout the project lifecycle.


## Key Activities in Requirement Analysis

Requirement Analysis involves several key activities that help define and refine the needs of stakeholders. These activities ensure that the final system meets user expectations and business goals.

- **Requirement Gathering:**  
  This involves collecting high-level needs from stakeholders, customers, users, and subject matter experts. Techniques include interviews, surveys, observations, and document analysis.

- **Requirement Elicitation:**  
  A deeper process where the focus is on uncovering the underlying needs and expectations that may not be explicitly stated. Techniques include workshops, brainstorming sessions, prototyping, and use case analysis.

- **Requirement Documentation:**  
  The gathered and elicited requirements are documented in a structured and standardized format, typically in a Software Requirements Specification (SRS) document. This ensures consistency and provides a reference point for all stakeholders.

- **Requirement Analysis and Modeling:**  
  This activity involves refining and organizing the requirements. It includes analyzing dependencies, feasibility, and conflicts, and modeling them using tools like flowcharts, data flow diagrams (DFDs), and UML models.

- **Requirement Validation:**  
  Ensures that the documented requirements are complete, clear, and aligned with stakeholder needs. Validation methods include reviews, walkthroughs, and formal approval processes.


  ## Types of Requirements

In software development, requirements are typically categorized into two main types: **Functional Requirements** and **Non-functional Requirements**. Both are essential for building a complete and usable system.

### Functional Requirements

Functional requirements describe **what the system should do** — the features and functions that the software must perform. These are derived from user needs and business processes.

**Examples for a Booking Management System:**
- Users should be able to create, view, update, and cancel bookings.
- The system should allow admin users to manage all bookings and assign rooms or resources.
- Customers should receive an email confirmation upon successful booking.
- The system should prevent double booking for the same room and time slot.
- Only registered users should be able to make a booking.

### Non-functional Requirements

Non-functional requirements define **how the system performs**. These relate to the system's quality attributes such as performance, security, usability, and maintainability.

**Examples for a Booking Management System:**
- The system should handle up to 500 concurrent users without performance degradation.
- Booking confirmation emails must be sent within 2 seconds after submission.
- The system must comply with GDPR data protection regulations.
- The UI should be accessible and responsive across desktop and mobile devices.
- System uptime should be at least 99.9% per month.



## Use Case Diagrams

Use Case Diagrams are a type of UML diagram that visually represent the functional requirements of a system. They show the interactions between users (called actors) and the various use cases (functions) the system provides.

### Benefits of Use Case Diagrams:
- Help identify the main functions and scope of the system.
- Provide a high-level overview of how users interact with the system.
- Enhance communication between stakeholders and developers.
- Serve as a foundation for writing detailed functional requirements and user stories.

Below is a sample use case diagram for a Booking Management System:

![Use Case Diagram for Booking System](./alx-booking-uc.png)


## Acceptance Criteria

Acceptance Criteria are predefined conditions that a software feature must satisfy to be considered complete and acceptable by the stakeholders. They help define the boundaries of a user story or feature and ensure that all parties have a shared understanding of the feature’s expected behavior.

### Importance of Acceptance Criteria in Requirement Analysis:
- ✅ Ensures that requirements are testable and measurable.
- ✅ Aligns expectations between developers, testers, and stakeholders.
- ✅ Helps in defining the “Done” state for a feature.
- ✅ Reduces ambiguity and miscommunication in the development process.

### Example: Acceptance Criteria for the Checkout Feature in the Booking Management System

**Feature:** Checkout Booking

**Acceptance Criteria:**
- ✅ The user must be logged in to initiate the checkout process.
- ✅ The system must display a summary of the booking details before confirmation.
- ✅ The user must be able to select a payment method (e.g., credit card, mobile money).
- ✅ The payment must be successfully processed through the integrated payment gateway.
- ✅ Upon successful payment, the system must update the booking status to “Confirmed.”
- ✅ The user must receive a confirmation email with booking and payment details.





