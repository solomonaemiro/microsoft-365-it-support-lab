# Ticket 14 — Employee Offboarding

## User

Laura Wilson — Finance Officer

## Request

> "Laura is leaving the organization. Please complete the required Microsoft 365 offboarding steps while preserving the mailbox and confirming that required Finance resources remain accessible."

## Investigation

Laura Wilson's account and existing access were reviewed before the offboarding actions were performed.

The mailbox had previously been converted to a shared mailbox to preserve the existing mailbox data.

![Laura Offboarding Baseline](../images/84%20Laura%20offboarding%20baseline.png)

Evidence: Laura Wilson's account and mailbox state before the offboarding changes.

Existing group membership was also reviewed as part of the access review.

![Laura Offboarding Group Review](../images/85%20Laura%20offboarding%20group%20review.png)

Evidence: Review of Laura Wilson's existing group membership during offboarding.

## Sign-In Block

Laura Wilson's sign-in was blocked as part of the offboarding process.

![Laura Wilson Sign-In Blocked](../images/86%20Laura%20wilson%20sign%20in%20blocked.png)

Evidence: Laura Wilson's account with sign-in blocked.

## License Removal

After the mailbox-preservation step had been completed, the Microsoft 365 Business Premium license was removed from Laura Wilson's account.

![Laura Offboarding License Removed](../images/87%20Laura%20offboarding%20license%20removed.png)

Evidence: Laura Wilson's Microsoft 365 license removed during offboarding.

## Shared Mailbox Verification

The Finance shared mailbox was checked to verify that the required departmental mailbox remained available after Laura's offboarding changes.

![Finance Shared Mailbox Offboarding Verification](../images/88%20Finance%20shared%20mailbox%20offboarding%20verification.png)

Evidence: Finance shared mailbox verified during the offboarding process.

## Sign-In Verification

A sign-in test was performed after the account was blocked to confirm that Laura Wilson could no longer authenticate to Microsoft 365.

![Laura Wilson Sign-In Blocked Test](../images/89%20Laura%20wilson%20Sign%20in%20blocked%20test.png)

Evidence: Sign-in test confirming that Laura Wilson's account remained blocked.

## Resolution

The controlled offboarding process was completed by:

1. Reviewing the user's baseline configuration
2. Reviewing existing group membership
3. Preserving the mailbox through mailbox conversion
4. Blocking user sign-in
5. Removing the Microsoft 365 Business Premium license
6. Verifying continued access to the Finance shared mailbox
7. Testing that the former user's sign-in was blocked

The user account was retained in the lab rather than permanently deleted so that the completed offboarding state could remain available for documentation and verification.

## Technician Resolution

> Completed Laura Wilson's Microsoft 365 offboarding by reviewing her existing access, preserving the mailbox through shared mailbox conversion, blocking sign-in, and removing the Microsoft 365 license. Verified that the Finance shared mailbox remained available and confirmed that Laura's sign-in was blocked.

## Evidence Summary

| Evidence | Purpose |
|---|---|
| Offboarding baseline | Establishes the user's original state |
| Group review | Documents existing access before offboarding |
| Sign-in blocked | Shows the account security change |
| License removed | Confirms license removal |
| Finance mailbox verification | Confirms departmental mailbox availability |
| Sign-in blocked test | Verifies that authentication was blocked |

Support workflow:  
Offboarding Request → Baseline Review → Access Review → Mailbox Preservation → Block Sign-In → Remove License → Verify Resources → Verify Sign-In Block