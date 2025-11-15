# TaskPro\_Project\_Muge

Manual Testing Project - End-to-end QA testing project for a Kanban-based task management web app. Includes Test Plan, RTM, 52+ Test Cases, Test Suites, API testing (Postman), UI/UX testing, Bug Reports, and a final Test Summary Report with execution metrics.

# TaskPro – End-to-End QA Testing for a Kanban-Based Task Management Web Application



Comprehensive end-to-end QA testing project for a Kanban-based task management web application. Includes Test Plan, Requirement Traceability Matrix, 52 core Test Cases, Test Suites, and full Test Execution across UI (Desktop/Mobile) and API (Postman) workflows. Covers 23 API endpoints, 26 UI acceptance tests, bug reporting (Jira), severity/priority classification, and a final Test Summary Report with key metrics and findings.



---



\## 1. Project Overview



This project presents a complete end-to-end Quality Assurance workflow for a Kanban-based Task Management Web Application. The testing process begins with Static Analysis and the creation of a comprehensive Test Plan covering goals, scope, environments, assumptions, risks, and Entry/Exit Criteria. A Requirement Traceability Matrix (RTM) was developed to map 33 functional and UI/API requirements to test coverage, ensuring full traceability across 4 Epics: API Authentication, API Internal Functions, UI Authorized, and UI Unauthorized components.



A total of 52 core Test Cases were designed using Positive/Negative, Functional, Non-functional, Smoke, and Regression testing methodologies. Each test case included clear descriptions, steps, preconditions, and expected results with assigned Priority and Severity. The project executed 77 total tests across three environments: Desktop, Mobile/Tablet, and responsive views using DevTools. API testing was performed via Postman, covering all 23 REST endpoints (Register, Login, CRUD operations). UI Acceptance Testing validated user workflows, interaction logic, responsive layouts, and state management behavior.



Testing execution delivered a Pass Rate of 90.4% (47/52 Test Cases). Four high-severity bugs were identified, including a critical data inconsistency issue. All defects were logged and documented in Jira with detailed reproduction steps, attachments (via Jam.dev), severity/priority scoring, and component classifications. The results were consolidated into a 92.5% UI Pass Rate and an 88.5% API Pass Rate, later presented in a structured Test Summary Report.



The repository includes: Test Plan, RTM, Test Suites, Test Cases, Bug Reports, API Test Collections, and documentation necessary to demonstrate a complete QA lifecycle from planning to reporting.



---



\## 2. Repository Contents



Depending on how you downloaded and exported the artefacts, the repository contains some or all of the following files:



\- \*\*Test Plan \& Design\*\*

&nbsp; - `TaskPro\_Project\_Müge.xlsx`  

&nbsp;   - Test Plan

&nbsp;   - Requirement Traceability Matrix (RTM)

&nbsp;   - Test Suites

&nbsp;   - Detailed Test Cases (with Priority, Severity, Preconditions, Steps, Expected Results)



\- \*\*API Testing\*\*

&nbsp; - `TaskPro\_Project\_Postman-collection\_Müge.json`  

&nbsp;   - Postman collection covering 23 REST API endpoints (Login, Register, CRUD)



\- \*\*Test Execution \& Reporting\*\*

&nbsp; - `TaskPro\_TEST-REPORT\_Müge.pptx`  

&nbsp;   - Test Summary Report

&nbsp;   - Execution metrics (Pass Rate, Failures)

&nbsp;   - UI vs API pass rates

&nbsp;   - Key defects and recommendations



\- \*\*Archive\*\*

&nbsp; - `TaskPro\_Project.zip`  

&nbsp;   - Packaged version of the full artefact set (for backup/quick download).



\*(File names may include diacritics like `ü`, depending on export settings.)\*



---



\## 3. Tools \& Technologies



\- \*\*Test Management:\*\* TestRail (conceptually), Google Sheets  

\- \*\*Bug Tracking:\*\* Jira  

\- \*\*API Testing:\*\* Postman  

\- \*\*Browser \& Responsive Testing:\*\* Chrome DevTools  

\- \*\*Documentation \& Reporting:\*\* Google Slides, Jam.dev (for recordings/attachments)



---



\## 4. Testing Scope \& Techniques



\- \*\*Scope\*\*

&nbsp; - API Authentication (Login, Register)

&nbsp; - API In-App Functions (CRUD operations)

&nbsp; - UI for Authorized Users

&nbsp; - UI for Unauthorized Users



\- \*\*Techniques\*\*

&nbsp; - Positive / Negative Testing

&nbsp; - Functional \& Non-functional Testing

&nbsp; - Smoke Testing

&nbsp; - Regression Testing

&nbsp; - Cross-environment testing (Desktop, Mobile/Tablet, Responsive)



---



\## 5. Key Metrics \& Outcomes



\- \*\*Total Designed Test Cases:\*\* 52  

\- \*\*Total Executed Tests:\*\* 77  

\- \*\*UI Pass Rate:\*\* 92.5%  

\- \*\*API Pass Rate:\*\* 88.5%  

\- \*\*Overall Pass Rate:\*\* 90.4% (47/52 TCs)  

\- \*\*High-Severity Bugs Identified:\*\* 4  

&nbsp; - Includes a critical data inconsistency defect.



All defects were logged in Jira with clear reproduction steps, Severity/Priority, environment information, and evidence (screenshots / recordings via Jam.dev).



---



\## 6. How to Use This Repository (For Recruiters / Reviewers)



This repository is intended as a \*\*QA portfolio project\*\* to demonstrate:



\- Ability to design a complete Test Plan from requirements.

\- Experience with Requirement Traceability (RTM) and coverage mapping.

\- Hands-on practice with API testing (Postman) and UI validation.

\- Structured defect reporting and severity/priority handling.

\- Professional documentation and summarization of test results.



Please feel free to explore the artefacts to review the testing approach, level of detail in test cases, and reporting style.



