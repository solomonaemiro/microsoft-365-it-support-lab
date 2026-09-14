# Exchange Online

Exchange Online provided the email and mailbox services used throughout the Apex Services Lab.

The environment was configured to demonstrate common IT Support and junior Microsoft 365 administration tasks involving mailboxes, permissions, mail flow, aliases, and mailbox lifecycle management.

## Mailbox Administration

The lab included standard user mailboxes, shared mailboxes, and room resource mailboxes.

Administrative tasks included:

- Reviewing user mailbox configuration
- Managing shared mailbox access
- Configuring Full Access permissions
- Configuring Send As permissions
- Managing email aliases
- Reviewing message trace
- Reviewing quarantine
- Converting a user mailbox to a shared mailbox
- Testing email delivery

## Shared Mailbox Support

Three shared mailboxes were configured:

- support@apexserviceslab.onmicrosoft.com
- hr@apexserviceslab.onmicrosoft.com
- finance@apexserviceslab.onmicrosoft.com

Authorized users were assigned the required delegated permissions.

The HR shared mailbox was subsequently used for a controlled access troubleshooting scenario. Sarah Johnson's Full Access permission was removed to reproduce an access problem. The permission configuration was investigated, restored, and verified.

## Send As

Send As functionality was configured for authorized shared mailbox users.

A test was performed using the HR shared mailbox to confirm that an authorized user could send using the shared mailbox identity.

The result was also used as a known-good message for later message-trace verification.

## Email Aliases

Additional email addresses were configured for selected users.

- Emily Carter — ITSupport@apexserviceslab.onmicrosoft.com
- Sarah Johnson — HR@apexserviceslab.onmicrosoft.com

The Sarah Johnson alias was later used in a controlled troubleshooting scenario. The alias was removed, the resulting delivery problem was investigated, and the alias was restored and tested.

## Distribution Group Mail Flow

Distribution groups were also used for organizational email communication.

The Sales Team distribution group was used in a controlled troubleshooting scenario involving James Anderson.

His membership was temporarily removed, resulting in the expected loss of distribution-group delivery. Membership was investigated and restored, followed by a new delivery test.

This demonstrated the relationship between group membership and distribution-group mail delivery.

## Message Trace

Exchange Online message trace was used to investigate a known-good email transaction.

The HR shared mailbox Send As test provided the message used for the trace investigation.

This demonstrated the use of administrative mail-flow information when verifying whether an email was processed and delivered.

## Quarantine Review

The Exchange Online environment also included a review of the Microsoft 365 quarantine area.

At the time of the lab check, the quarantine was empty.

This provided basic hands-on familiarity with where an administrator can review messages that have been placed into quarantine.

## Mailbox Conversion

Mailbox conversion was demonstrated using Laura Wilson's mailbox.

The mailbox was converted to a shared mailbox as part of the controlled employee-lifecycle workflow.

The conversion preserved the mailbox while allowing the user account to remain available for the subsequent offboarding scenario.

## Email Forwarding

Internal email forwarding was configured for Laura Wilson's converted shared mailbox.

The forwarding configuration was tested using the Finance shared mailbox as the destination.

The scenario was intentionally limited to internal forwarding within the lab.

## Automatic Replies

Automatic replies were configured for Sarah Johnson to demonstrate an out-of-office support scenario.

The configuration included an appropriate automatic-reply message and scheduled period.

The configuration was subsequently tested from another user account.

## Exchange Online Support Workflow

The Exchange Online portion of the lab followed a support-oriented troubleshooting process:

User Report → Mailbox / Permission Review → Mail Flow Investigation → Corrective Action → Delivery Test → Verification

The goal was to demonstrate practical troubleshooting rather than only showing that Exchange Online features had been configured.