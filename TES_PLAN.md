# Test Plan

## Objective
The objective of this test plan is to ensure that the **Financing Application Web System**
functions correctly according to the defined requirements and is ready for release.

This test plan defines the testing scope, approach, environment, and criteria
used to validate the quality of the application.

---

## Scope
The testing scope is aligned with the project documentation and includes:

- Authentication (Login)
- Financing application submission
- Financing application history
- Manager review, approval, and rejection flow
- Admin verification of pending financing applications
- Status synchronization across User, Manager, and Admin roles
- Data validation
- Basic CRUD operations
- Role-based access control and authorization

---

## Test Types
The following testing types are applied:

- Manual Testing
- Functional Testing

---

## Actors Involved
The testing activities involve the following roles:

- **User**
- **Manager**
- **Admin**

---

## Test Environment
The testing environment is defined as follows:

- **Application Type:** Web Application  
- **Browser:** Google Chrome  
- **Test Environment:** Local / Staging  

---

## Test Tools
The following tools are used during testing:

- **Google Sheets** – test case documentation and test summary reporting  
- **GitHub** – test documentation and version control  

---

## Entry Criteria
Testing activities can begin when the following conditions are met:

- Application build has been deployed successfully
- Test environment is accessible
- Test accounts for User, Manager, and Admin are available
- Application requirements have been reviewed and approved

---

## Exit Criteria
Testing activities can be concluded when the following conditions are met:

- All planned and critical test cases have been executed
- No high or critical severity defects remain open
- Test results have been documented and reviewed
- Application is ready for User Acceptance Testing (UAT)

---

## Test Deliverables
The following documents are produced as part of the testing process:

- Test Plan
- Test Scenarios
- Test Case Documentation
- Scenario-Based Test Summary
- Test Case-Based Summary

---

## Assumptions and Risks

### Assumptions
- The application functionality remains stable during the testing phase
- Test data is available and can be reused
- All required test environments are accessible

### Risks
- Changes in requirements during testing may impact test coverage
- Limited test environment availability may delay test execution

---
