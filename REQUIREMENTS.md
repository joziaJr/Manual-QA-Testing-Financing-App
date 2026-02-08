# Application Requirements

## Application Name
Financing Application Web System

---

## Application Type
Web Application

---

## Description
This web-based financing application allows users to submit financing applications online.
Users can log in to the system, complete a financing application form, submit the application,
and track the status of their submissions.

The system supports role-based access where Manager and Admin users can review, verify,
and manage submitted financing applications according to their responsibilities.

---

## Actors
The application involves the following actors:

- **User**  
  Submits financing applications and views application status.

- **Manager**  
  Reviews submitted financing applications and performs approval or rejection actions.

- **Admin**  
  Verifies pending financing applications, manages application data, and controls system access.

---

## Main Business Flow

### User Flow
1. User accesses the web application through a browser.
2. User logs in using valid credentials.
3. After successful login, the user fills in the financing application form.
4. The user submits the financing application.
5. The system validates the input data and stores the submission.
6. The user can view the application status through the application history page.

---

### Manager Flow
1. Manager logs into the system using manager credentials.
2. Manager views the list of submitted financing applications.
3. Manager reviews application details.
4. Manager approves or rejects financing applications based on predefined criteria.
5. The system updates the application status accordingly.

---

### Admin Flow
1. Admin logs into the system using admin credentials.
2. Admin accesses the verification (pending) page.
3. Admin verifies submitted financing applications.
4. The system updates the application status and removes verified data from the pending list.
5. Admin manages application data and access permissions through the admin dashboard.

---

## Scope of Testing
The following functionalities are included in the testing scope:

- Authentication (Login)
- Financing application submission (simple form)
- Financing application status tracking
- Data validation
- Basic CRUD operations
- Role-based access control

---

## Out of Scope
The following items are not covered in this testing scope:

- Performance testing
- Security penetration testing
- Automation testing
- User interface (UI) design validation

---

## Assumptions
- All test accounts (User, Manager, Admin) are available.
- The application is accessible through a supported web browser.
- Test data is prepared and can be reused during testing.

---
