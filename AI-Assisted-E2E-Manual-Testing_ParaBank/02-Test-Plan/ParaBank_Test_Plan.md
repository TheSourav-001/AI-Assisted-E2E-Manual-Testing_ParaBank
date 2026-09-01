# MASTER TEST PLAN DOCUMENT

## 1. Project Information

<table>
  <tr>
    <td><b>Document Title</b></td>
    <td>Master Test Plan</td>
  </tr>
  <tr>
    <td><b>Project Name</b></td>
    <td>ParaBank Web Application Testing</td>
  </tr>
  <tr>
    <td><b>Application Under Test</b></td>
    <td>ParaBank</td>
  </tr>
  <tr>
    <td><b>Document Version</b></td>
    <td>1.0</td>
  </tr>
  <tr>
    <td><b>Prepared By</b></td>
    <td>Sourav Dipta Apu</td>
  </tr>
  <tr>
    <td><b>Role</b></td>
    <td>SQA Engineer</td>
  </tr>
</table>

## 2. Introduction
This document defines the comprehensive software testing strategy and planning for the ParaBank demonstration banking application. It provides a structured approach for the QA team to ensure all functional components meet expected business logic and provide a secure, seamless user experience. 

## 3. Test Objectives
* Validate all core banking functionalities including user authentication, account management, and financial transactions.
* Ensure data consistency and integrity across different user sessions and account operations.
* Identify and document defects early to ensure the application reaches a stable release state.
* Verify proper error handling and boundary value validations across all input fields.

## 4. Scope of Testing

### 4.1 Features to be Tested (In Scope)
* <b>User Registration and Login:</b> Validating new user sign up, session creation, and secure login workflows.
* <b>Account Operations:</b> Creating new checking and savings accounts, verifying correct initial balances.
* <b>Financial Transactions:</b> Executing fund transfers between accounts and confirming immediate balance updates.
* <b>Bill Payment Services:</b> Processing utility payments and validating payee information retention.
* <b>Transaction History:</b> Retrieving and filtering past transactions accurately.

### 4.2 Features Not to be Tested (Out of Scope)
* Server infrastructure and database backend configurations.
* Advanced security penetration testing and vulnerability scanning.
* High capacity load, stress, and performance testing.
* Third party payment gateway API validations.

## 5. Testing Methodology
The primary testing methodology will revolve around Manual Black Box Testing.

* <b>Functional Testing:</b> Checking each feature against predefined expected outcomes.
* <b>End to End Testing:</b> Navigating complete user journeys from initial registration through successful fund transfers and final logout.
* <b>Session Management Testing:</b> Validating secure session creation, proper termination upon logout, and invalidating expired session IDs.
* <b>Regression Testing:</b> Rechecking previously functioning modules after new changes or bug fixes are applied.

## 6. Test Environment Setup
* <b>Target Application URL:</b> https://parabank.parasoft.com/parabank/index.htm
* <b>Supported Browsers:</b> Google Chrome, Mozilla Firefox, Microsoft Edge
* <b>Operating System:</b> Windows Environment

## 7. Defect Management Process
Defects identified during the execution phase will be systematically logged, tracked, and managed utilizing JIRA. 

Each defect report will include:
* A clear and concise title.
* Detailed steps to reproduce the issue.
* Expected behaviour versus Actual behaviour.
* Environment details and browser version.
* Supporting evidence such as screenshots or video recordings.
* Severity classification (Critical, High, Medium, Low).

## 8. Entry and Exit Criteria

### 8.1 Entry Criteria
* The test environment is fully accessible and stable.
* This Master Test Plan is formally reviewed and finalized.
* Required baseline test data is identified and prepared.

### 8.2 Exit Criteria
* All documented test scenarios and cases have been executed.
* Zero Critical or High severity defects remain unresolved.
* The Final Test Execution Report is drafted and approved by stakeholders.

## 9. QA Deliverables
The following documentation will be produced throughout the testing lifecycle:
* Master Test Plan Document
* Detailed Test Case Specifications
* Requirement Traceability Matrix
* Active Defect Logs
* Final Test Summary Report
