# osTicket-Ticket-Lifecycle-Examples
This repository demonstrates the lifecycle of tickets in the osTicket help desk ticketing system. It includes practical scenarios such as creating, observing, and resolving tickets, along with configuring departments, SLAs, and ticket properties. Ideal for understanding end-to-end help desk workflows
<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>



---

## Objectives
1. Create tickets as an end-user.
2. Observe ticket properties and update them as a help desk professional.
3. Configure departments and manage SLAs.
4. Work on and resolve tickets based on the assigned properties.

---

## Lab Environment
- **Admin/Analyst Login Page:** `http://localhost/osTicket/scp/login.php`  
- **End Users osTicket URL:** `http://localhost/osTicket`

---

## Steps and Scenarios

### **1. Configure Departments**
- Change the **SysAdmins Department** to a **Top Level Department**.
- DELETE the **Maintenance Department** (not archive).

---

### **2. Scenario 1: Mobile/Online Banking System Issue**
**As an End-User**:  
- Create a ticket with the following details:  
  - **Issue:** "Entire mobile/online banking system is down."

**As a Help Desk Agent (John)**:  
- Observe the ticket’s properties:
  - **Priority**  
  - **Department**  
  - **SLA**  
  - **Assigned To**  

- Set the ticket properties:
  - **Priority:** Sev-A (1 hour, 24/7)  
  - **Department:** Online Banking Department  

**As a Help Desk Agent (John)**:  
- Attempt to observe the ticket again.  
  - **Question:** Can you view or change the ticket after assigning?  

**As a Help Desk Agent (Jane)**:  
- Work the ticket to completion.  

---

### **3. Scenario 2: Adobe Upgrade Issue**
**As an End-User**:  
- Create a ticket with the following details:  
  - **Issue:** "Accounting department needs Adobe upgrade, broken."

**As a Help Desk Agent (John)**:  
- Observe the ticket’s properties:
  - **Priority**  
  - **Department**  
  - **SLA**  
  - **Assigned To**  

- Set the ticket properties:
  - **Priority:** Sev-B (4 hours, 24/7)  
  - **Department:** Support  

---

## Summary
This lab demonstrates a complete ticket lifecycle, including creation, assignment, and resolution, with a focus on managing departments, SLAs, and ticket visibility.

---

## Visual Demonstrations
(*Images will be added here later.*)
