# Test Plan – Service Marketplace Web Application

## 1. Project Overview
The Service Marketplace web application allows users to discover, book, and review home services.  
This test plan defines the strategy and scope for **manual testing**, ensuring that all business-critical workflows function correctly.

---

## 2. Objective
- Verify that the application meets the functional and non-functional requirements.  
- Ensure a smooth, error-free booking experience from registration to payment and review.  
- Identify critical bugs before production deployment.

---

## 3. Scope

### In Scope
- Functional Testing of all modules
- UI Testing
- Smoke Testing
- Regression Testing of key workflows
- Exploratory Testing for edge cases

### Out of Scope
- Automation Testing
- Performance / Load Testing
- Service provider portal testing
- Mobile device testing (except tablet for UI responsiveness)

---

## 4. Modules to be Tested
1. User Registration & Login  
2. Service Discovery  
3. Service Booking  
4. Payment (Mock)  
5. Order Management  
6. Ratings & Reviews  
7. Notifications  

---

## 5. Test Approach / Strategy

- **Requirement-based Testing**: Test cases will be derived from the requirement analysis.  
- **Positive Testing**: Verify expected workflows and inputs.  
- **Negative Testing**: Verify invalid inputs, incorrect flows, and error handling.  
- **Boundary Testing**: Test input limits where applicable (e.g., ratings, comments length).  
- **Exploratory Testing**: Identify unexpected issues not captured in requirements.

---

## 6. Test Types
-----------------------------------------------------------------------------------------
| Test Type              | Description                                                  |
|------------------------|--------------------------------------------------------------|
| Functional Testing     | Validate that all application features work as expected.     |
| UI / Usability Testing | Ensure the interface is user-friendly and responsive.        |
| Regression Testing     | Verify that new changes do not break existing functionality. |
| Smoke Testing          | Basic checks to confirm application is stable for testing.   |
-----------------------------------------------------------------------------------------
---//

## 7. Test Environment
--------------------------------------------------
| Component        | Details                     |
|------------------|-----------------------------|
| Browser          | Google Chrome (latest)      |
| Operating System | Windows 10                  |
| Network          | Stable broadband (50 Mbps)  |
| Devices          | Desktop, Tablet (Chrome)    |
--------------------------------------------------
---//

## 8. Entry & Exit Criteria

### Entry Criteria
- Requirement Analysis and Test Plan approved
- Test environment is ready
- Test data prepared

### Exit Criteria
- All test cases executed
- Critical/High severity bugs resolved
- No open high-priority defects

---

## 9. Risks
- Payment simulation may behave differently from real transactions  
- Availability of service slots may cause inconsistent test results  
- Unexpected UI changes may affect test cases  

---

## 10. Deliverables
- Requirement Analysis Document (`Requirement_Analysis.md`)  
- Test Scenarios (`Test_Scenarios.xlsx`)  
- Test Cases (`Test_Cases.xlsx`)  
- Bug Reports (`Bug_Report.xlsx`)  
- Jira Screenshots (`06_Jira_Evidence/`)  

---

## 11. Assumptions
- Application functionality is limited to user workflows; service provider module is out of scope.  
- Payment is simulated; no real transactions occur.  
- Desktop Chrome browser is the primary test environment; cross-browser testing is limited.  
