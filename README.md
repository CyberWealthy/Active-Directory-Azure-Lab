# Active Directory Deployment in Microsoft Azure

## Project Overview

This project demonstrates the deployment of an Active Directory environment in Microsoft Azure to simulate a corporate IT infrastructure. The lab includes domain controller configuration, DNS setup, user management, and domain-joined client authentication.

## Technologies Used

- Microsoft Azure
- Windows Server 2022
- Active Directory Domain Services (AD DS)
- DNS
- Windows 10/11 Client VM

## Lab Architecture

- 1x Windows Server 2022 Virtual Machine (Domain Controller)
- 1x Windows Client Virtual Machine (Domain-Joined Workstation)
- Azure Virtual Network (VNet)
- Custom DNS configuration pointing to the Domain Controller
- Domain: corp.local

## Implementation Steps

1. Deployed Windows Server 2022 VM in Azure.
2. Installed Active Directory Domain Services.
3. Promoted server to Domain Controller.
4. Configured DNS services.
5. Created Organizational Units (OUs), users, and security groups.
6. Deployed Windows client VM.
7. Configured custom DNS settings on client.
8. Joined client machine to the domain.
9. Verified authentication and user login.
10. Simulated Tier 1 help desk tasks (password reset, account unlock).

## Skills Demonstrated

- Active Directory deployment and configuration
- DNS configuration and troubleshooting
- Domain join process
- User account and OU management
- Authentication validation
- Basic help desk administrative tasks

## Future Improvements

- Implement Group Policy Objects (GPOs)
- Add PowerShell automation
- Expand lab to include hybrid Azure AD integration
