# servicenow-oviya-onboarding-kit
Naan Mudhalvan - ServiceNow Onboarding Automation - REQ0010002 Success

### Naan Mudhalvan Project - 2026
**Student:** Oviya | **Instance:** dev399767.service-now.com | **Date:** 13-10-2026
**Status:** 100% Working - Auto Task Creation Success 🔥

## Project Proof
- **Request:** REQ0010002 - Submitted 2026-10-13 09:17:13
- **RITM:** RITM0010002 - Stage: Assess or Scope Task
- **Tasks Auto-Created:** SCTASK0010010 (Open), SCTASK0010009 (Open)
- **Created By:** System Administrator via Flow Designer

## What I Built
1. **Catalog Item:** Oviya New Joiner Kit
   - Variables: employee_name (Text), department (HR/IT/Finance), laptop_choice (MacBook Pro/Windows Laptop)
2. **Flow Designer:** Oviya New Joiner Flow
   - Trigger: RITM Created where Item = Oviya New Joiner Kit
   - Actions: Create 2 Catalog Tasks - IT Setup Task + HR Setup Task
   - Flow Status: Active & Published
3. **Testing:** Ordered via Service Portal -> 2 tasks auto-created within seconds

## Modules Used
Service Catalog Management, Flow Designer, Service Portal, sc_task table, sc_req_item

## How to Verify
1. Go to dev399767.service-now.com
2. sc_task_list.do?sysparm_query=request_item.number=RITM0010002
3. You will see SCTASK0010010 and SCTASK0010009 both Open

## Screenshots
Check /screenshots folder for proof:
- Order Confirmation REQ0010002
- RITM0010002 Detail
- sc_task_list with 2 tasks
- SCTASK0010010 Detail - Open State
- Flow Designer Active

## Future Scope
- Add Approval for laptop cost > 1 Lakh
- Add Email Notification to Employee
- Integrate with HRMS
- Add SLA and Auto-escalation

## Learning
Understood Service Catalog Lifecycle REQ->RITM->SCTASK, Flow Designer No-Code automation, Debugging via sc_task table

#ServiceNow #NaanMudhalvan #FlowDesigner #TamilNadu #Chennai