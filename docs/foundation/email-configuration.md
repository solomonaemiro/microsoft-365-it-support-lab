# Email Configuration

The lab included several Exchange Online email configurations used to simulate common organizational communication and IT Support requirements.

The configurations were tested through actual mail flow and user-facing scenarios where applicable.

## Email Aliases

Email aliases were configured for selected users to provide additional addresses associated with their primary Microsoft 365 accounts.

### Emily Carter

Emily Carter was assigned:

ITSupport@apexserviceslab.onmicrosoft.com

![Emily Carter Email Alias](../images/15%20Emily%20carter%20email%20alias.png)

Evidence: Emily Carter's additional email alias.

### Sarah Johnson

Sarah Johnson was assigned:

HR@apexserviceslab.onmicrosoft.com

![Sarah Johnson Email Alias](../images/16%20Sarah%20johnson%20%20email%20alias.png)

Evidence: Sarah Johnson's additional email alias.

Email aliases were later used in a controlled troubleshooting scenario. Sarah's HR@ alias was temporarily removed, the resulting delivery failure was investigated, and the alias was restored and tested successfully.

## External Mail Contact

An external mail contact named Apex Services Vendor was configured as a placeholder external contact for the lab.

![Apex Services External Mail Contact](../images/17%20%20apex%20services%20external%20mail%20contact.png)

Evidence: External mail contact configured in Exchange Online.

The contact was created for administrative practice and was not used to represent a production vendor relationship.

## Calendar Delegation

Calendar delegation was configured for the management workflow:

- David Wilson — General Manager
- Jennifer Thomas — Operations Manager

Jennifer was given delegated calendar-management access.

![David Wilson Calendar Delegation](../images/18%20David%20wilson%20calendar%20delegation.png)

Evidence: Calendar delegation configuration between David Wilson and Jennifer Thomas.

The configuration was later verified through an actual calendar test.

## Send As

Send As permissions were configured for authorized users of the HR shared mailbox.

A test message was sent using the HR shared mailbox identity to verify that the configured permission worked as expected.

![HR Shared Mailbox Send As Test](../images/19%20HR%20shared%20mailbox%20send%20as%20test.png)

Evidence: Send As functionality verified using the HR shared mailbox.

## Message Trace

Exchange Online message trace was used to investigate and verify email delivery.

A known-good message sent using the HR shared mailbox Send As configuration was used for the trace test.

![Exchange Online Message Trace](../images/22%20Exchange%20online%20message%20trace.png)

Evidence: Exchange Online message trace used to verify the test message.

Message trace provided an administrative method for checking the processing and delivery of the test message.

## Quarantine Review

The Microsoft 365 quarantine area was also reviewed as part of the email-administration practice.

![Microsoft 365 Email Quarantine](../images/23%20microsoft%20365%20email%20quarantine%20empty%20page.png)

Evidence: Microsoft 365 quarantine review showing no messages present at the time of the check.

## Email Testing

Email functionality was tested from the user perspective using Outlook.

Testing included:

- User-to-user email
- Shared mailbox email
- Send As
- Email alias delivery
- Message delivery verification

![Emily Outlook Email Test](../images/24%20Emily%20outlook%20email%20test.png)

Evidence: Outlook email test performed using Emily Carter's account.

![IT Support Shared Mailbox Test](../images/25%20IT%20support%20shared%20mailboxl%20%20test.png)

Evidence: IT Support shared mailbox email test.

## Calendar Testing

Calendar functionality was also verified through an actual delegation test.

![Jennifer Calendar Delegation Test](../images/26%20Jennifer%20Calendar%20Delegation%20Test.png)

Evidence: Calendar delegation test involving Jennifer Thomas.

## Email Troubleshooting Approach

The email environment was used for both normal configuration testing and controlled troubleshooting scenarios.

Examples included:
- Removing and restoring shared mailbox access
- Removing and restoring a distribution-group membership
- Removing and restoring an email alias
- Testing Send As permissions
- Reviewing message trace
- Testing mailbox and calendar functionality

The general troubleshooting process was:

User Report → Configuration Review → Mail Flow / Permission Investigation → Corrective Action → Test → Verify

This provided practical experience with investigating Microsoft 365 email issues from both the administrative and end-user perspectives.