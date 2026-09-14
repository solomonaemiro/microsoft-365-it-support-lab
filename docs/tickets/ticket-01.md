# Ticket 1 — Shared Mailbox Access

## User

Sarah Johnson — HR Manager

## Issue

> "I can't access the HR shared mailbox. Please check my access and restore it."

## Investigation

The HR shared mailbox was checked to verify the permissions assigned to Sarah Johnson and Jessica Davis.

Sarah's Full Access permission had been removed while the existing Send As configuration remained unchanged.

The resulting configuration explained why Sarah could no longer access the shared mailbox.

![HR Shared Mailbox Access Failure](../images/51%20HR%20shared%20mailbox%20access%20failure.png)

Evidence: Sarah Johnson's shared mailbox access failure.

![HR Shared Mailbox Permission Diagnosis](../images/52%20HR%20shared%20mailbox%20permission%20diagnosis.png)

Evidence: Investigation of the HR shared mailbox permissions identifying the missing Full Access permission.

## Diagnosis

The issue was caused by the removal of Sarah Johnson's Full Access permission from the HR shared mailbox.

The Send As permission was not the cause of the access problem.

## Resolution

Sarah Johnson's Full Access permission was restored on the HR shared mailbox.

The restored configuration was then tested to verify that Sarah could access the mailbox again.

![HR Shared Mailbox Access Restored](../images/53%20HR%20Shared%20Mailbox%20Access%20Restored.png)

Evidence: HR shared mailbox access restored after the permission was corrected.

## Verification

The mailbox was tested from the user perspective after the permission was restored.

The restored access confirmed that the corrective action resolved the reported issue.

## Technician Resolution

> Investigated Sarah Johnson's inability to access the HR shared mailbox and identified that her Full Access permission had been removed. Restored the required Full Access permission and verified that access to the shared mailbox was restored.

## Evidence Summary

| Evidence | Purpose |
|---|---|
| HR shared mailbox access failure | Demonstrates the user-facing problem |
| Permission diagnosis | Shows the missing access permission |
| Access restored | Verifies the corrective action |

Support workflow:  
User Report → Permission Review → Diagnosis → Restore Access → Verify