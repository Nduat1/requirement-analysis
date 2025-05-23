# Requirement Analysis in Software Development.
## Introduction
This repository explores the critical process of Requirement Analysis in the Software Development Life Cycle (SDLC). It includes theoretical explanations, real-world examples, and practical illustrations such as use case diagrams and acceptance criteria. The purpose of this repository is to provide a foundational guide for students, developers, and teams working on software projects — ensuring they gather, document, and validate software requirements effectively.


## What is Requirement Analysis?
Requirement Analysis is a critical phase in the software development lifecycle (SDLC) where the project team gathers, analyzes, and defines the requirements of the software product to be developed. This process ensures that all stakeholders have a clear and mutual understanding of what the system should do and how it should perform.


## Why is Requirement Analysis Important?
- Clarity and Understanding: It helps in understanding what the stakeholders expect from the software, reducing ambiguity.
- Scope Definition: Clearly defines the scope of the project, which helps in preventing scope creep.
- Basis for Design and Development: Provides a solid foundation for designing and developing the system.
- Cost and Time Estimation: Facilitates accurate estimation of project cost, resources, and time.
- Quality Assurance: Ensures that the final product meets the specified requirements, leading to higher customer satisfaction.


## Key Activities in Requirement Analysis.
- Requirement Gathering 🗂️
  - Interviews: Engage stakeholders for direct insights.
  - Surveys/Questionnaires: Collect data from a wider audience.
  - Workshops: Collaborative sessions to gather ideas.
  - Observation: Understand user behavior in real-world scenarios.
  - Document Analysis: Review existing systems and documentation.

- Requirement Elicitation ✍️
  - Brainstorming: Generate ideas collectively.
  - Focus Groups: Collect detailed input from a group of users.
  - Prototyping: Use mockups to refine and visualize needs.

- Requirement Documentation 📚
  - Specification Document: Detailed list of all requirements.
  = User Stories: Capture user needs from a user-centric view.
  - Use Cases: Visual representations of user interactions.

- Requirement Analysis and Modeling 📊
  - Prioritization: Rank requirements by impact and urgency.
  - Feasibility Analysis: Assess time, cost, and technology feasibility.
  - Modeling: Create diagrams like ERD or DFD for clarity.

- Requirement Validation ✅
  - Review and Approval: Confirm requirements with stakeholders.
  - Acceptance Criteria: Define measurable completion conditions.
  - Traceability: Map each requirement through the development stages.

 
## Types of Requirements.
### Functional Requirements ⚙️
They define specific behaviors or functions of the system.
Examples from the Booking Management System:
  - Search Properties: Users can search properties using filters like location, price, and dates.
  - User Registration: New users can  create an account with personal details and login credentials.
  - Booking System: Users can book properties, view booking details, and manage their bookings.
  - Authentication: Secure login and registration.

### Non-functional Requirements 🛡️
They define system qualities and performance expectations.
Examples from the Booking Management System:
  - Performance: The system should load pages within 2 seconds and handle up to 1000 concurrent users.
  - Security: Ensure data is encrypted and secured against threats.
  - Scalability: System supports traffic growth without downtime.
  - Usability: The application should have an intuitive UI/UX, making it easy for users to navigate and perform tasks.
  - Reliability: The system should have an uptime of 99.9% and recover quickly from any failures.


## Use Case Diagrams.
Use Case Diagrams are visual representations showing how users (actors) interact with a system to achieve specific tasks (use cases). These diagrams help capture system functionalities and user expectations, aiding communication between stakeholders and developers.
- Benefits:
  - Clarifies functional requirements.
  - Helps in identifying system boundaries and actors.
  - Facilitates early validation with stakeholders.


## Acceptance Criteria.
Acceptance Criteria are pre-defined conditions that a software feature must meet to be accepted by the stakeholders. They ensure that the development output aligns with the business expectations and requirements.

### Benefits of Acceptance Criteria:
  - Ensure all parties have a clear understanding of feature requirements.
  - Provide a basis for testing and validation.
  - Help in maintaining quality and meeting user expectations.

### Acceptance criteria example for a checkout feature:
  - Users must be able to review booking details (property, dates, price).
  - The system must validate the availability of selected dates before processing payment.
  - Users must provide payment details via a secure form.
  - Upon successful payment, a confirmation message and email are sent.
  - System updates booking status and logs the transaction.
  - Process must complete within 2 minutes for up to 1000 concurrent users.

