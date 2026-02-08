# Test Scenarios

This document defines high-level test scenarios based on
the application requirements, testing scope, and implemented test cases.
Each scenario represents a core business flow that is validated during testing.

---

## User (Nasabah) Scenarios

- Verify user can log in with valid credentials
- Verify user cannot log in with invalid credentials
- Verify user can submit a financing application with valid data
- Verify system validates required fields on financing application form
- Verify user can view financing application history
- Verify financing application status is displayed correctly in history
- Verify monthly installment calculation is displayed correctly
- Verify system displays an empty state when no financing application exists
- Verify user is redirected to login page when accessing application history without authentication

---

## Manager Scenarios

- Verify manager can log in with valid credentials
- Verify manager cannot log in with invalid credentials
- Verify manager can view submitted financing applications
- Verify manager can approve a financing application
- Verify manager can reject a financing application
- Verify application status is updated and reflected on user dashboard after manager action

---

## Admin Scenarios

- Verify admin can log in with valid credentials
- Verify admin cannot log in with invalid credentials
- Verify admin can view pending financing applications
- Verify admin can verify a pending financing application
- Verify verified application is removed from pending list
- Verify non-admin user cannot access admin verification page

---
