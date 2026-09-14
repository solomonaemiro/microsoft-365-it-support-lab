# Lab Environment

## Microsoft 365 Tenant

The lab was built using a Microsoft 365 Business Premium tenant representing the fictional organization Apex Services Lab.

| Component | Configuration |
|---|---|
| Organization | Apex Services Lab |
| Tenant | apexserviceslab.onmicrosoft.com |
| Microsoft 365 License | Business Premium |
| Cloud Identity | Microsoft Entra ID |
| Endpoint Management | Microsoft Intune |
| Email & Calendaring | Exchange Online |
| Collaboration | Microsoft Teams |
| Personal File Storage | OneDrive |
| Organizational File Storage | SharePoint |
| Client Operating System | Windows 10 Pro |

The Microsoft 365 tenant provides the central environment for identity, email, collaboration, file management, and endpoint administration.

## Organization Structure

Users were organized into departments to provide a realistic structure for access, group membership, mailbox administration, and support scenarios.

### IT

- Alex Morgan — IT Administrator
- Emily Carter — IT Support Technician

### HR

- Sarah Johnson — HR Manager
- Jessica Davis — HR Assistant

### Finance

- Michael Brown — Finance Manager
- Laura Wilson — Finance Officer

### Sales

- Daniel Smith — Sales Manager
- James Anderson — Sales Representative
- Robert Taylor — Sales Representative

### Management

- David Wilson — General Manager
- Jennifer Thomas — Operations Manager

### Operations

- Mark Lewis — Operations Coordinator

### Additional Lab User

- Olivia Anderson — Operations Assistant

Olivia Anderson was added later as part of the user onboarding and support scenarios.

## Microsoft 365 Resource Structure

The environment also contains shared and organizational resources used throughout the lab, including:

- All Employees and department distribution groups
- Microsoft 365 Groups
- Microsoft Teams
- Shared mailboxes for IT Support, HR, and Finance
- Conference and training room resource mailboxes
- Email aliases
- An external mail contact
- Calendar delegation
- SharePoint and OneDrive resources

These resources were used both for normal administration and for controlled support scenarios.

## Managed Windows Devices

Two Windows 10 Pro virtual machines were enrolled and managed through Microsoft Intune:

- Emily Carter's Windows 10 device
- Sarah Johnson's Windows 10 device

Both devices were:

1. Joined to Microsoft Entra ID
2. Automatically enrolled into Microsoft Intune
3. Registered as managed devices
4. Evaluated against the lab compliance policy
5. Assigned the lab configuration profile
6. Used for endpoint support and troubleshooting scenarios

The devices were used to demonstrate practical endpoint-management tasks such as enrollment, compliance monitoring, configuration deployment, application deployment, and troubleshooting.

### Intune Lab User Group

An Intune Lab Users security group was created for controlled device-management assignments.

The group included:

- Emily Carter
- Sarah Johnson
- Daniel Smith

Emily and Sarah were enrolled as managed Windows endpoints. Daniel Smith was included in the assignment group but was not enrolled as a third managed device.

This allowed Intune policies and configuration profiles to be assigned consistently while keeping the number of managed lab devices controlled.

## Lab Architecture

The environment can be viewed as several connected Microsoft 365 administration layers:

Microsoft Entra ID  
↓  
Users, Groups & Licenses  
↓  
Exchange Online / Teams / SharePoint / OneDrive  
↓  
Microsoft Intune  
↓  
Entra ID–Joined Windows Devices

This structure allowed the lab to demonstrate how identity, Microsoft 365 services, collaboration resources, and endpoint management interact within a support environment.

## Lab Scope

This is a controlled training environment using fictional users, devices, and organizational data.
The environment was created for hands-on learning and portfolio demonstration rather than production use. Support scenarios were performed in the lab to practice administration, troubleshooting, verification, and technical documentation.