# Active Directory Home Lab

## Project Overview

This project demonstrates the deployment and administration of a Windows Server 2022 Active Directory environment in a virtual lab.

The lab simulates common IT Support and System Administration tasks, including Active Directory deployment, user and group management, shared folder permissions, Group Policy configuration, password policies, and account recovery procedures.

The goal of this project was to gain hands-on experience with technologies commonly used in enterprise environments and frequently required for IT Help Desk and Junior System Administrator roles.

---

## Business Scenario

A growing organization requires a centralized identity management solution to manage users, groups, devices, and access permissions across multiple departments.

As a Junior IT Administrator, I was responsible for:

- Deploying Active Directory Domain Services (AD DS)
- Creating Organizational Units (OUs)
- Managing users and security groups
- Implementing Role-Based Access Control (RBAC)
- Configuring Group Policy Objects (GPOs)
- Managing shared folder permissions
- Performing password reset and account recovery tasks

---

## Lab Environment

| Component | Technology |
|------------|------------|
| Hypervisor | Oracle VirtualBox |
| Server OS | Windows Server 2022 |
| Client OS | Windows 11 |
| Directory Service | Active Directory Domain Services (AD DS) |
| Management Tools | Group Policy Management, ADUC |
| Scripting | PowerShell |

---

## Key Tasks Completed

### Active Directory Deployment
- Installed Active Directory Domain Services (AD DS)
- Promoted the server to a Domain Controller
- Created a new forest (corp.local)
- Configured DNS Server and Global Catalog

### Organizational Unit Administration
- Created departmental OUs
- Implemented logical AD structure
- Prepared OUs for Group Policy deployment

### User and Group Management
- Created domain user accounts
- Created security groups
- Assigned users to appropriate groups
- Implemented Role-Based Access Control (RBAC)

### Shared Folder Administration
- Configured departmental file shares
- Applied Share Permissions
- Applied NTFS Permissions
- Managed access through security groups

### Group Policy Management
- Configured Password Policies
- Configured Account Lockout Policies
- Created and linked custom GPOs
- Restricted Control Panel and Command Prompt access

### Help Desk Administration
- Performed password resets
- Verified account status
- Simulated account recovery procedures

---

## Skills Demonstrated

- Active Directory Administration
- Windows Server Administration
- User & Group Management
- Organizational Unit Management
- Group Policy Management (GPO)
- Role-Based Access Control (RBAC)
- DNS Administration
- File Share Management
- NTFS Permissions
- Password & Account Lockout Policies
- Identity and Access Management (IAM)
- IT Help Desk Operations

---

## Project Outcomes

This lab provided practical experience deploying and administering an Active Directory environment from the ground up. It demonstrates the ability to perform common IT Support and Junior System Administrator tasks within a Windows domain environment.

---

## Documentation

📄 Full project documentation can be downloaded here:

[Download Project Documentation](./Project-01-Active-Directory-Lab.pdf)

## Steps Performed

### Phase 1 – Initial Windows Server Configuration

The lab began with the deployment of a Windows Server 2022 virtual machine. The server was renamed to DC01 and configured with a static IP address to provide a stable foundation for Active Directory services.

<img width="631" height="531" alt="image" src="https://github.com/user-attachments/assets/2062bdee-0ccc-4f74-9d1d-14a87c64536b" />

### Phase 2 – Install Active Directory Domain Services (AD DS)

After preparing the server, the Active Directory Domain Services (AD DS) role was installed along with the required management tools. This prepared the environment for Domain Controller promotion and centralized identity management.

<img width="777" height="596" alt="image" src="https://github.com/user-attachments/assets/2f0849ee-8c5f-4ca7-9386-814c22f5a404" />

### Phase 3 – Create Organizational Units

To establish a clear administrative structure, Organizational Units (OUs) were created for departments including IT, HR, Finance, and Sales. This approach simplifies user management and supports future Group Policy deployment.

<img width="754" height="488" alt="image" src="https://github.com/user-attachments/assets/388affa2-b34f-450e-8480-af75b17da151" />


### Phase 4 – Create Users and Security Admin

User accounts and security groups were then created within Active Directory. Group memberships were assigned based on departmental responsibilities, demonstrating a basic Role-Based Access Control (RBAC) model.

<img width="625" height="468" alt="image" src="https://github.com/user-attachments/assets/8ddc4edc-168e-4691-9cc9-865f496b7a50" />

### Phase 5 – Create Shared Folder and Assign Permissions

A departmental file share was configured to simulate resource access within an organization. Share Permissions and NTFS Permissions were applied to ensure that users could only access data relevant to their assigned roles.

<img width="756" height="584" alt="image" src="https://github.com/user-attachments/assets/f2545de8-504e-472d-a58d-34987e6d4e87" />

### Phase 6 – Configure Password and Account Lockout Policies

Security settings were strengthened through the configuration of password and account lockout policies. These controls help enforce stronger authentication practices and reduce the risk of unauthorized access attempts..

<img width="940" height="408" alt="image" src="https://github.com/user-attachments/assets/f42a73df-7e46-4c15-a14e-52f22580e5b8" />

### Phase 7 – Create and Link a Custom Group Policy Object (GPO)

In this phase, I created and linked a custom Group Policy Object (GPO) to the IT Organizational Unit. The policy was used to restrict access to tools such as Control Panel, Command Prompt, and Registry Editor to improve security and standardization.

<img width="746" height="517" alt="image" src="https://github.com/user-attachments/assets/3767103c-4b26-4e9b-bd7a-1b4b27fa013a" />

<img width="612" height="436" alt="image" src="https://github.com/user-attachments/assets/00a49dd7-42d5-43dc-b1b6-ec8fb8902e61" />

### Phase 8 – Password Reset and Account Unlock

The project concluded with a common Help Desk support scenario involving password recovery and account access restoration. This exercise demonstrated a routine administrative task frequently performed in enterprise environments.

<img width="675" height="501" alt="image" src="https://github.com/user-attachments/assets/986e5f1c-a1bc-4b2b-8baf-07e64c396958" />

---

## Outcome and Validation

The Active Directory environment was successfully deployed and configured from the ground up using Windows Server 2022. Throughout the lab, I validated each configuration step, including Domain Controller promotion, Organizational Unit creation, user and security group management, shared folder permissions, Group Policy deployment, and password recovery procedures. Testing confirmed that policies were applied correctly and that access permissions functioned as intended across the domain environment.

---

## What I Learned

This project provided practical experience with core Windows Server and Active Directory administration tasks commonly performed by IT Support and Junior System Administrators. I gained hands-on experience deploying Active Directory Domain Services (AD DS), organizing resources through Organizational Units, managing users and security groups, implementing Role-Based Access Control (RBAC), configuring Group Policy Objects (GPOs), and managing shared folder permissions. In addition, I strengthened my understanding of account security controls, password policies, and common Help Desk account recovery procedures.

---





