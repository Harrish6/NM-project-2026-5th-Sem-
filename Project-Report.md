# PROJECT REPORT

# Streamlining IT Procurement: Automating Standard Laptop Orders with Flow Designer

## TNSKILLS GROUP PROJECT

**Team Members:**  
1. `Prakash K`  
2. `Deva Anandh M`  
3. `Ranjith E`  
4. `Raguram E`
5. `Harrish K`

---

# 1. ABSTRACT

The project “Streamlining IT Procurement: Automating Standard Laptop Orders with Flow Designer” aims to automate the processing of standard laptop requests in an IT environment. Manual procurement processes can involve repetitive activities such as request verification, approval, task creation, status updates, and fulfilment tracking.

The proposed solution uses ServiceNow Flow Designer to create a structured workflow for standard laptop orders. The flow automates defined actions after a laptop request is submitted and helps move the request through approval and fulfilment stages. The project demonstrates how workflow automation can improve consistency, reduce manual effort, and provide better visibility of IT procurement activities.

This project is developed as a TNSKILLS group project to demonstrate practical knowledge of ServiceNow workflow automation and Flow Designer.

---

# 2. INTRODUCTION

IT departments regularly receive requests for laptops and other computing equipment. A standard laptop request may need to pass through several stages before it is completed. If these activities are performed manually, employees and IT staff may spend considerable time handling repetitive tasks.

Workflow automation provides a way to connect these activities into a defined process. ServiceNow Flow Designer can be used to create flows containing triggers, conditions, actions, approvals, and other workflow steps.

This project applies these concepts to the standard laptop procurement process. The goal is to create a structured and automated workflow that handles standard laptop requests consistently.

---

# 3. PROBLEM STATEMENT

IT laptop procurement may involve multiple manual activities such as reviewing request information, obtaining approvals, assigning fulfilment work, updating statuses, and closing requests.

Manual processing can lead to repetitive work, delays, inconsistent handling, and errors in request updates. Therefore, an automated workflow is required to streamline the standard laptop ordering process.

The project addresses this problem by using ServiceNow Flow Designer to automate the defined procurement workflow.

---

# 4. OBJECTIVES

- To automate the processing of standard laptop requests.
- To reduce repetitive manual activities.
- To create a consistent procurement workflow.
- To automate approval and fulfilment steps where applicable.
- To improve visibility of request status.
- To reduce the possibility of manual processing errors.
- To gain practical knowledge of ServiceNow Flow Designer.
- To demonstrate workflow automation in an IT service environment.

---

# 5. PROJECT SCOPE

## 5.1 Included Scope

- Standard laptop request processing.
- ServiceNow request workflow.
- Flow Designer configuration.
- Request validation and conditions.
- Approval handling where required.
- Fulfilment task creation or update.
- Request status progression.
- Workflow testing.
- Project documentation.

## 5.2 Excluded Scope

- Non-standard or specialized hardware procurement.
- Actual financial transactions.
- External vendor integration unless separately configured.
- Physical delivery management outside the configured workflow.
- Enterprise-wide deployment.

---

# 6. EXISTING SYSTEM

In a manual process, an employee submits a laptop requirement and IT personnel review the request. The request may then require approval, fulfilment assignment, status updates, and closure.

## Limitations of Existing System

1. Repetitive manual work.
2. Possible delays between processing steps.
3. Dependence on human intervention.
4. Possibility of inconsistent status updates.
5. Difficulty maintaining a standardized process.
6. Limited automation of routine actions.

---

# 7. PROPOSED SYSTEM

The proposed system uses ServiceNow Flow Designer to automate the standard laptop procurement process.

When a standard laptop request is submitted, the configured flow is triggered. The flow evaluates the required conditions and performs the configured actions. Where necessary, approval is requested. After approval, fulfilment activities are created or updated, and the request progresses toward completion.

## Main Features

- Automated request processing.
- Configurable conditions.
- Approval handling.
- Fulfilment task management.
- Status updates.
- Structured workflow execution.

---

# 8. SYSTEM ARCHITECTURE

The project consists of the following major components:

```text
+----------------------+
|      User/Employee   |
+----------+-----------+
           |
           v
+----------------------+
| Standard Laptop      |
| Request              |
+----------+-----------+
           |
           v
+----------------------+
| ServiceNow           |
| Flow Designer        |
+----------+-----------+
           |
           v
+----------------------+
| Conditions / Rules   |
+----------+-----------+
           |
           v
+----------------------+
| Approval (if needed)|
+----------+-----------+
           |
           v
+----------------------+
| Fulfilment Task      |
+----------+-----------+
           |
           v
+----------------------+
| Status Update        |
+----------+-----------+
           |
           v
+----------------------+
| Request Completion   |
+----------------------+
```

---

# 9. METHODOLOGY

## Phase 1 – Requirement Analysis
The standard laptop procurement process was studied to identify repetitive steps that could be automated.

## Phase 2 – ServiceNow Configuration
The required request and workflow components were configured in the ServiceNow project environment.

## Phase 3 – Flow Design
The procurement process was converted into a sequence of automated steps using Flow Designer.

## Phase 4 – Conditions and Actions
Conditions and actions were configured according to the project requirements. These may include approval, fulfilment, task updates, and request status changes.

## Phase 5 – Testing
Test requests were submitted to verify that the flow was triggered correctly and that the configured actions occurred as expected.

## Phase 6 – Documentation
Screenshots and documentation were prepared to record the implementation and results.

---

# 10. TECHNOLOGIES USED

## ServiceNow
ServiceNow provides the platform used to configure and execute the IT service workflow.

## Flow Designer
Flow Designer is used to create the automated sequence of triggers, conditions, actions, and approvals.

## Service Catalog / Request Management
The request mechanism represents the user's requirement for a standard laptop.

## GitHub
GitHub is used to store project documentation, screenshots, presentation material, and the project report.

---

# 11. MODULES

## 11.1 Laptop Request Module
Handles submission of the standard laptop request.

## 11.2 Request Validation Module
Checks the request according to the configured project conditions.

## 11.3 Approval Module
Handles approval when the configured workflow requires it.

## 11.4 Fulfilment Module
Creates or updates fulfilment activities.

## 11.5 Status Management Module
Updates the request as it progresses through the workflow.

## 11.6 Testing Module
Tests the workflow using different request scenarios.

---

# 12. FUNCTIONAL REQUIREMENTS

1. The system shall allow a user to submit a standard laptop request.
2. The system shall trigger the configured flow for the defined request condition.
3. The system shall evaluate configured conditions.
4. The system shall support approval handling where required.
5. The system shall create or update fulfilment activities.
6. The system shall update request information during workflow execution.
7. The system shall support workflow testing.
8. The workflow shall provide a defined path from request submission to completion.

---

# 13. NON-FUNCTIONAL REQUIREMENTS

## Usability
The workflow should be easy for IT personnel to understand and use.

## Reliability
The configured flow should execute consistently for valid requests.

## Maintainability
The workflow should be structured so that conditions and actions can be modified.

## Security
Credentials, passwords, tokens, and confidential information must not be stored in the GitHub repository.

## Traceability
The request and its fulfilment activities should provide sufficient information to track progress.

---

# 14. WORKFLOW

The standard workflow is:

1. User submits a standard laptop request.
2. Flow Designer detects the configured trigger.
3. Request information is evaluated.
4. The flow checks the configured conditions.
5. Approval is requested when applicable.
6. Approved requests proceed to fulfilment.
7. Fulfilment activities are created or updated.
8. Request status is updated.
9. Request is completed after fulfilment.

---

# 15. IMPLEMENTATION

## 15.1 Request Creation
A standard laptop request is submitted through the configured ServiceNow request mechanism.

**Screenshot:** Add `Screenshots/01_request.png`

## 15.2 Flow Designer
The Flow Designer workflow contains the configured trigger, conditions, and actions.

**Screenshot:** Add `Screenshots/02_flow_designer.png`

## 15.3 Conditions
The flow evaluates the conditions required for the standard laptop workflow.

**Screenshot:** Add `Screenshots/03_condition.png`

## 15.4 Approval
Where approval is required, the workflow sends the request through the configured approval step.

**Screenshot:** Add `Screenshots/04_approval.png`

## 15.5 Fulfilment
After the required approval, the workflow proceeds to the configured fulfilment activity.

**Screenshot:** Add `Screenshots/05_fulfilment.png`

## 15.6 Completion
After the required activities are completed, the request reaches the configured final state.

**Screenshot:** Add `Screenshots/06_completed.png`

> Replace all screenshot placeholders with screenshots from your actual ServiceNow implementation.

---

# 16. TESTING

| Test Case | Input | Expected Result | Status |
|---|---|---|---|
| TC01 | Valid standard laptop request | Flow is triggered | `[Pass/Fail]` |
| TC02 | Request requiring approval | Approval is generated | `[Pass/Fail]` |
| TC03 | Rejected request | Rejection handling occurs | `[Pass/Fail]` |
| TC04 | Approved request | Fulfilment activity is created/updated | `[Pass/Fail]` |
| TC05 | Completed fulfilment | Request reaches completed state | `[Pass/Fail]` |

---

# 17. RESULTS

The project demonstrates that the standard laptop procurement process can be organized into an automated workflow using ServiceNow Flow Designer.

The configured workflow provides a structured sequence for request processing, conditions, approval handling, fulfilment, and status updates.

## Results Observed

- Standard laptop requests can be processed through the configured flow.
- Workflow conditions control the appropriate path.
- Approval steps can be handled within the workflow.
- Fulfilment activities can be managed through automation.
- Request progress can be tracked through workflow states.

---

# 18. ADVANTAGES

- Reduces repetitive manual work.
- Provides a consistent procurement process.
- Improves visibility of request progress.
- Helps reduce manual data-entry errors.
- Simplifies routine approval and fulfilment activities.
- Provides practical workflow automation experience.
- Creates a foundation for future procurement automation.

---

# 19. LIMITATIONS

- The project focuses on standard laptop requests.
- The workflow depends on ServiceNow configuration.
- External vendor and payment systems are outside the current scope.
- Physical procurement and delivery are not automatically controlled unless separately integrated.
- Workflow results depend on correctly configured conditions and actions.

---

# 20. FUTURE ENHANCEMENTS

1. Integrate inventory availability.
2. Add vendor and purchase-order integration.
3. Add automated email or platform notifications.
4. Create procurement dashboards.
5. Support multiple standard hardware categories.
6. Add escalation for delayed approvals.
7. Integrate delivery tracking.
8. Add analytics for request processing time.

---

# 21. CONCLUSION

The project “Streamlining IT Procurement: Automating Standard Laptop Orders with Flow Designer” demonstrates the application of workflow automation to an IT procurement process.

By using ServiceNow Flow Designer, the standard laptop request process can be organized into automated steps involving request handling, conditions, approvals, fulfilment, and status updates. This reduces repetitive manual activities and provides a consistent approach to processing requests.

The project also provides practical experience in ServiceNow configuration, workflow design, testing, documentation, and project collaboration.

---

# 22. REFERENCES

1. ServiceNow platform and Flow Designer learning resources.
2. TNSKILLS project learning materials.
3. Tutorial used as a learning reference:  
   https://youtu.be/3nsUWtzpDz4
4. Project-specific ServiceNow configuration and testing performed by the team.
