# Ticket 2 — Distribution Group Membership

## User

James Anderson — Sales Representative

## Issue

> "I'm not receiving emails sent to the Sales Team distribution group. Please check whether I have access to the group."

## Investigation

The Sales Team distribution group was checked to establish the expected membership and mail-delivery configuration.

James Anderson was initially a member of the group.

![Sales Team Distribution Group Baseline](../images/54%20Sales%20Team%20Distribution%20group%20baseline.png)

Evidence: Sales Team distribution group showing the baseline membership.

James's membership was then removed as a controlled change to reproduce the reported access and delivery problem.

![Sales Team James Membership Removed](../images/55%20Sales%20team%20james%20memebership%20removed.png)

Evidence: James Anderson's membership removed from the Sales Team distribution group.

A test message was sent to the Sales Team distribution address to verify the resulting delivery behavior.

![Sales Team Distribution Delivery Test](../images/56%20Sales%20team%20distribution%20delivery%20test.png)

Evidence: Distribution-group delivery test following the membership change.

## Diagnosis

The issue was traced to James Anderson no longer being a member of the Sales Team distribution group.

The membership configuration was reviewed to confirm the missing group membership.

![Sales Team Membership Diagnostic](../images/57%20sales%20team%20membership%20diagnostic%20.png)

Evidence: Diagnostic review of the Sales Team distribution-group membership.

## Resolution

James Anderson's membership in the Sales Team distribution group was restored.

A new test message was then sent to the group to verify that delivery was restored.

![Sales Team Distribution Delivery Restored](../images/58%20Sales%20Team%20Distribution%20Delivery%20Restored.png)

Evidence: Distribution-group delivery successfully tested after James's membership was restored.

## Verification

The restored membership and subsequent delivery test confirmed that the corrective action resolved the issue.

## Technician Resolution

> Investigated James Anderson's missing emails from the Sales Team distribution group and identified that his group membership had been removed. Restored his membership and verified successful delivery through a new distribution-group email test.

## Evidence Summary

| Evidence | Purpose |
|---|---|
| Distribution group baseline | Establishes the original membership state |
| Membership removed | Demonstrates the controlled failure |
| Delivery test | Demonstrates the resulting mail-delivery issue |
| Membership diagnostic | Identifies the missing group membership |
| Delivery restored | Verifies successful resolution |

Support workflow:  
User Report → Membership Review → Controlled Failure → Diagnosis → Restore Membership → Verify Delivery