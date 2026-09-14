# Ticket 15 — Teams Access & Membership

## User

James Anderson — Sales Representative

## Issue

> "I can no longer see the Sales Collaboration Team in Microsoft Teams. Please check my access."

## Investigation

James Anderson's membership in the Sales Collaboration Microsoft 365 Group was reviewed.

Before the issue was introduced, James was a member of the group.

![Sales Collaboration Team Membership Baseline](../images/90%20Sales%20collab%20team%20membership%20baseline.png)

Evidence: James Anderson's baseline membership in the Sales Collaboration environment.

His membership was then temporarily removed as a controlled change to reproduce the reported Teams access problem.

## User Impact

After James's membership was removed, the resulting impact was checked from the user's Teams environment.

The Sales Collaboration Team was no longer available to James.

![James Teams Access Impact](../images/91%20James%20Teams%20Access%20impact.png)

Evidence: Impact of the membership change on James Anderson's Teams access.

## Diagnosis

The Microsoft 365 Group membership was reviewed to identify why the Team was no longer available.

The investigation confirmed that James Anderson was no longer a member of the underlying Sales Collaboration group.

![Sales Collaboration Membership Diagnosis](../images/92%20Sales%20collab%20membership%20diagnosis.png)

Evidence: Investigation identifying the missing Sales Collaboration membership.

## Resolution

James Anderson's membership in the Sales Collaboration Microsoft 365 Group was restored.

His Teams access was then checked to verify that the Team became available again.

![James Sales Collaboration Membership Restored](../images/93%20%20James%20sales%20collab%20membership%20restored%20and%20resolved.png)

Evidence: James Anderson's Sales Collaboration membership restored and the issue resolved.

## Verification

The restored membership and resulting Teams access confirmed that the missing group membership was responsible for the reported problem.

## Technician Resolution

> Investigated James Anderson's missing Sales Collaboration Team access and identified that his membership in the underlying Microsoft 365 Group had been removed. Restored his group membership and verified that access to the Sales Collaboration Team was restored.

## Evidence Summary

| Evidence | Purpose |
|---|---|
| Membership baseline | Establishes the expected membership state |
| Teams access impact | Demonstrates the user-facing problem |
| Membership diagnosis | Identifies the missing group membership |
| Membership restored | Verifies the corrective action and restored access |

Support workflow:  
User Report → Review Group Membership → Controlled Membership Removal → Verify Access Impact → Diagnose → Restore Membership → Verify Teams Access