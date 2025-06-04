# Active-Directory-Lab
This project demonstrates practical skills in Active Directory user and group management. I gained hands-on experience by creating new users, forming new groups, and resetting user passwords.

Below is a link to my Loom video demonstrating this lab.
https://www.loom.com/share/9a9efe983f14420885e16d3f213c439d?sid=3b66a2ba-9e6e-4fbf-bd52-c08b7ea9332d

# Active Directory Lab: Windows Server 2022 on AWS EC2

## Key Activities Performed

### 1. Active Directory Domain Services Installation & Configuration.

Inside the Windows Server 2022 instance, Active Directory Domain Services were installed and configured previously by myself before the lab begins.

### 2. User and Group Management

Post-installation, standard Active Directory user and group management tasks were performed using the "Active Directory Users and Computers" (ADUC) snap-in:

* **Creating a New Organizational Unit (OU):** (Optional, but good practice) Created an OU for better organization, e.g., `Users and Groups`.
* **Creating a New User:**
    * Navigated to the desired OU (or default `Users` container).
    * Right-clicked and selected `New` > `User`.
    * Provided `First name`, `Last name`, and `User logon name` (e.g., `jdoe`).
    * Set an initial password and configured password options (e.g., "User must change password at next logon" or "Password never expires" for lab purposes).
* **Creating a New Group:**
    * Navigated to the desired OU (or default `Users` container).
    * Right-clicked and selected `New` > `Group`.
    * Provided a `Group name` (e.g., `NewHires`).
* **Adding User to Group:**
    * Opened the properties of the newly created group.
    * Navigated to the `Members` tab.
    * Clicked `Add...` and searched for the newly created user (e.g., `jdoe`).
    * Confirmed the addition of the user to the group.

### 3. User Password Reset

A password reset was performed for the newly created user:

* **Locate User:** In ADUC, navigated to and selected the new user account.
* **Reset Password:** Right-clicked the user account and selected `Reset Password...`.
* **Set New Password:** Entered and confirmed a new password. Optionally selected "User must change password at next logon."

## Learnings & Takeaways

* Successfully deployed a foundational Active Directory environment on AWS EC2, demonstrating cloud-based infrastructure management.
* Reinforced understanding of the RDP protocol for secure remote server administration.
* Gained practical experience with core Active Directory tasks, including:
    * Installing AD DS.
    * Promoting a server to a domain controller.
    * Creating and managing user accounts.
    * Creating and managing security groups.
    * Resetting user passwords.
* Underlined the importance of proper security group configuration in AWS for network access.
* Highlighted the straightforward nature of managing Windows Server roles and features in a cloud context.

This lab provided valuable hands-on experience in setting up a basic domain environment, which is a fundamental skill for cloud and on-premises IT infrastructure management.
