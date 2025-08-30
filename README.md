# Requirement Analysis in Software Development.
The **Requirement Analysis Project** focuses on crafting a comprehensive foundation for software development by documenting, analyzing, and structuring requirements.  

Through a series of well-defined tasks, learners will create a detailed blueprint of the requirement analysis phase for a **Booking Management System**. This project simulates a real-world development scenario, emphasizing **clarity, precision, and structure** in defining requirements to set the stage for successful project execution.

## ❓ What is Requirement Analysis?

**Requirement Analysis** is the process of identifying, gathering, documenting, and analyzing the needs and expectations of stakeholders for a software system.  

It serves as the foundation of the **Software Development Lifecycle (SDLC)**, ensuring that the final product aligns with business goals and user needs.  

During this phase, developers and analysts:  
- Communicate with stakeholders to **understand the problem domain**.  
- Translate business needs into **functional and non-functional requirements**.  
- Create documentation, diagrams, and models to provide a **clear blueprint** for development.  

✅ **Key Goal:** To establish a shared understanding between stakeholders and the development team, minimizing risks of miscommunication and ensuring successful project execution.

## 🌟 Why is Requirement Analysis Important?

Requirement Analysis is a **critical phase** in the Software Development Lifecycle (SDLC) because it lays the groundwork for building successful systems. Here are three key reasons why it is essential:

1. **Clarity and Alignment**
   - Ensures that all stakeholders (clients, users, and developers) have a shared understanding of the system requirements.  
   - Reduces ambiguity by documenting needs in a clear and structured manner.  

2. **Risk Reduction**
   - Identifies potential challenges, constraints, and gaps early in the process.  
   - Minimizes costly rework and delays by addressing issues before development begins.  

3. **Efficient Resource Utilization**
   - Provides a solid roadmap for the project, enabling better planning of time, budget, and manpower.  
   - Ensures that developers focus on building features that directly support business and user needs.  

## 🔑 Key Activities in Requirement Analysis

Requirement Analysis involves several structured activities that ensure the system requirements are well-understood, documented, and validated. The five key activities are:

- **Requirement Gathering**  
  - Collecting high-level information from stakeholders about what they need from the system.  
  - Involves initial discussions, reviewing business documents, and studying the existing system (if any).  

- **Requirement Elicitation**  
  - Digging deeper to uncover explicit and hidden requirements.  
  - Uses techniques such as interviews, questionnaires, workshops, observation, and brainstorming sessions.  

- **Requirement Documentation**  
  - Recording requirements in a structured and accessible format (e.g., Software Requirement Specification - SRS).  
  - Ensures requirements are written clearly, concisely, and unambiguously.  

- **Requirement Analysis and Modeling**  
  - Examining requirements for feasibility, consistency, completeness, and prioritization.  
  - Creating models and diagrams (e.g., use case diagrams, data flow diagrams) to visualize system interactions.  

- **Requirement Validation**  
  - Verifying that documented requirements accurately represent stakeholder needs.  
  - Conducted through reviews, walkthroughs, and prototyping to ensure correctness and completeness.
 
    
## 📂 Types of Requirements

In software projects, requirements are generally classified into two categories: **Functional Requirements** and **Non-functional Requirements**. Both are critical to ensure that the system not only works as intended but also delivers the right quality of service.

---

### ✅ Functional Requirements
**Definition:**  
Functional requirements define **what the system should do**. They describe the features, services, and operations of the system as expected by users and stakeholders.  

**Examples for the Booking Management System:**  
- The system shall allow users to **create, update, and cancel bookings**.  
- The system shall send **email or SMS confirmations** after a booking is completed.  
- The system shall allow administrators to **manage available rooms, services, and schedules**.  
- The system shall enable users to **make payments online** through secure payment gateways.  
- The system shall generate a **booking history report** for both users and administrators.  

---

### ⚙️ Non-functional Requirements
**Definition:**  
Non-functional requirements specify **how the system performs its functions**, focusing on quality attributes such as performance, usability, and reliability.  

**Examples for the Booking Management System:**  
- The system should handle **up to 1,000 concurrent users** without performance degradation.  
- The system should have an **uptime of 99.9%** to ensure availability.  
- The booking confirmation emails should be delivered **within 60 seconds** after a successful transaction.  
- The system’s user interface should be **mobile-responsive** and accessible across devices.  
- All sensitive user data (e.g., payment details) must be **encrypted using industry-standard protocols (e.g., SSL/TLS)**.  

---

✅ **Summary:**  
- **Functional Requirements = What the system does** (features, tasks, services).  
- **Non-functional Requirements = How the system does it** (performance, quality, constraints).  
Both are essential to ensure the project’s success.
## 🎭 Use Case Diagrams

**Definition:**  
A **Use Case Diagram** is a visual representation of the interactions between **actors** (users or external systems) and the system itself. It highlights the functional requirements of a system by showing **who** can do **what** with the system.  

**Benefits of Use Case Diagrams:**  
- Provide a **high-level view** of system functionality.  
- Help stakeholders and developers maintain a **shared understanding** of requirements.  
- Simplify communication by representing complex requirements visually.  
- Act as a foundation for creating detailed **use case descriptions** and scenarios.  

---

### 📊 Use Case Diagram for Booking Management System

The diagram below represents the major actors and use cases in the **Booking Management System**.

**Actors:**  
- **Customer** – books, updates, and cancels bookings.  
- **Admin** – manages rooms, services, and schedules.  
- **Payment Gateway** – processes payments.  
- **Notification Service** – sends booking confirmations.  

**Use Cases:**  
- Create Booking  
- Update Booking  
- Cancel Booking  
- View Booking History  
- Process Payment  
- Manage Rooms & Services  
- Send Confirmation Notification  

---

### 🖼 Diagram

![Booking Management Use Case Diagram](https://res.cloudinary.com/dsrxjzmcl/image/upload/v1756563865/bookingPlan_rmeoly.png)

---

## ✅ Acceptance Criteria

**Definition & Importance:**  
Acceptance Criteria are the conditions that a software product must satisfy to be accepted by a user, customer, or other stakeholders. They serve as a **bridge between requirements and testing**, ensuring that the delivered feature aligns with the intended functionality and quality standards.  

**Why Acceptance Criteria are Important:**  
- Provide **clear expectations** for developers, testers, and stakeholders.  
- Act as a **basis for test cases** and validation during Quality Assurance (QA).  
- Reduce misunderstandings by making requirements **measurable and testable**.  
- Help in determining when a feature is **“done” and ready for release**.  

---

### 🛒 Example: Checkout Feature (Booking Management System)

**Feature:** Online Checkout for Bookings  

**Acceptance Criteria:**  
- ✅ The system should allow the user to proceed to checkout after selecting a booking.  
- ✅ The user must be able to enter and validate payment details securely.  
- ✅ The system should display the total cost (including taxes/fees) before final confirmation.  
- ✅ Payment should be processed via the integrated payment gateway (e.g., Stripe, PayPal).  
- ✅ Upon successful payment, the system must generate a booking confirmation and send it via **email/SMS**.  
- ✅ If the payment fails, the system should display an error message and allow the user to retry.  
- ✅ The checkout page must be accessible and responsive across desktop and mobile devices.  

---

✅ **In summary:** Acceptance Criteria make requirements **testable, verifiable, and reliable**, ensuring that the delivered software meets both business and user needs.

