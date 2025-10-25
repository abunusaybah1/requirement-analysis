##Requirement Analysis in Software Development

This repository documents the Requirement Analysis phase of a Booking Management System. Its purpose is to define clear functional and non-functional requirements that guide development and ensure the system meets user and business needs.

##What is Requirement Analysis?

Requirement Analysis is the process of identifying, gathering, and documenting what a software system should do and how it should perform. It helps developers understand user and business needs before building the system, serving as the foundation of the Software Development Life Cycle (SDLC).

#Importance in the SDLC

Defines the project’s goals and scope clearly.
Guides developers, designers, and testers with a common understanding.
Prevents costly errors and rework.
Improves communication between stakeholders.
Ensures the final product meets real user needs.

##Why is Requirement Analysis Important?

Requirement Analysis is important because it ensures that the software being developed meets real user and business needs.It helps developers and stakeholders share a clear understanding of project goals, reduces costly mistakes, and improves the overall quality of the final product.

##Key Activities in Requirement Analysis

- Requirement Gathering:
Collecting information about user and business needs through interviews, surveys, observations, or questionnaires.

- Requirement Elicitation:
Engaging with stakeholders to clarify, refine, and uncover hidden or conflicting requirements that may not be immediately stated.

- Requirement Documentation:
Organizing and recording all gathered requirements in a clear, structured form (such as this README) for easy reference and future use.

- Requirement Analysis and Modeling:
Examining relationships between requirements, identifying priorities, and representing them visually through diagrams or models for better understanding.

- Requirement Validation:
Reviewing requirements with stakeholders to ensure they are accurate, complete, and feasible before development begins.

##Types of Requirements

#Functional Requirements

Definition: These specify what the system should do — the features, behaviours and operations the system must provide.

Examples (for the booking-management project):

- A user must be able to create an account and log in.

- A user must be able to search for available rooms by date, location and price.

- The system must allow a user to book a room, cancel or modify the reservation.

- An admin must be able to add, update or delete room listings (availability, price, description).

- The system must send a confirmation email or notification after a successful booking.

- The system must integrate with a payment gateway to process payments for bookings.

- The system must allow users to view their booking history (past and current bookings).

#Non-Functional Requirements

Definition: These specify how the system should behave — its quality attributes, performance, reliability, security, usability, etc.

Examples (for the booking-management project):

- The system should respond to user search or booking requests within 2 seconds.

- The system should be able to handle at least 500 concurrent users without performance degradation.

- All sensitive user data (e.g., payment details, personal information) must be encrypted and stored securely.

- The user interface must be mobile-responsive and accessible (usable on both mobile devices and desktop).

- The system should maintain availability of 99.9% uptime excluding planned maintenance.

- Booking transactions must be logged and auditable to allow tracing of changes by admins.

- The system should support caching of frequent queries (e.g., room availability) to improve speed and reduce database load (as in the article where caching with Redis is mentioned). 