# Automated Employee Onboarding & Offboarding System (ServiceNow)

## Overview
This project is developed in ServiceNow to automate the employee onboarding and offboarding process. It reduces manual work by handling approvals, task assignments, and notifications automatically.

The system helps different departments like IT, Facilities, and Security to coordinate better and complete tasks on time.

---

## Objectives
- To automate onboarding and offboarding processes  
- To reduce manual effort and delays  
- To improve coordination between departments  
- To provide a simple request system for users  
- To track request status easily  

---

## Tools and Concepts Used
- ServiceNow  
- Service Catalog  
- Catalog Variables  
- Flow Designer  
- Approvals  
- Catalog Tasks (sc_task)  
- Notifications  

---

## Workflow

1. A catalog item is created for onboarding/offboarding requests  
2. User fills in employee details such as ID, manager, department, etc.  
3. Flow Designer triggers when the request is submitted  
4. System captures all input data  
5. A record is created in the employee lifecycle table  
6. Approval is sent to the manager  
7. If approved:
   - Tasks are created for IT, Facilities, and Security  
   - System waits until all tasks are completed  
   - Request is marked as completed  
8. If rejected:
   - Request is marked as rejected  
   - Notification is sent to the user  

---

## Results
- Requests can be submitted easily  
- Workflow is automated  
- Tasks are assigned automatically  
- Status can be tracked in real time  
- Manual effort is reduced  

---

## Conclusion
This project shows how ServiceNow can be used to automate employee lifecycle processes. It improves efficiency, reduces delays, and ensures better coordination between departments.

---

## Future Improvements
- Integration with Active Directory  
- SLA tracking  
- Chatbot support  
- Dashboard for reporting  

---

## Author
Subash Reddy S
