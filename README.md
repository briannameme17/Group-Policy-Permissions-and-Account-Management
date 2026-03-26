# Active Directory Account Management 
**Account Lockouts, Password Resets, and Security Logging**

# Overview  
This project demonstrates how to manage user accounts in Active Directory by real-world scenarios such as account lockouts, password resets, enabling and disabling accounts, and reviewing security logs. These tasks reflect common responsibilities in IT support and cybersecurity roles, where maintaining account security and troubleshooting authentication issues are critical.  

Understanding how to manage account lockouts, enforce security policies, and monitor logs is essential in protecting systems from unauthorized access. This highlights my core Identity and Access Management (IAM) skills used in real-world environments, including user lifecycle management and security monitoring.  
---

## Steps Taken  

1. Logged into DC-1 and selected an existing user account to simulate failed login attempts  

2. Attempted multiple incorrect logins to trigger an account lockout scenario  

3. Configured Group Policy to enforce an account lockout threshold after 5 failed attempts  

4. Verified the account was locked out in Active Directory and proceeded to unlock the account  

5. Reset the user’s password and confirmed successful login after unlocking  

6. Disabled the account, tested login failure, then re-enabled the account and verified access restoration  

7. Forced Group Policy updates using `gpupdate /force` to apply changes across the system  

8. Reviewed security logs on the Domain Controller and client machine to analyze login attempts and account activity  

---

## Screenshots  

<p align="left">
  <img src="images/Lockout.png" width="400">
</p>
<p align="right">
 <img src="images/warning.png" width="400">
  
<p align="center">
  <img src="images/Unlock.png" width="400">
  <img src="images/reset.png" width="400">
</p>

<p align="center">
  <img src="images/disable account.png" width="300">
   <img src="images/changed pass.png" width="300">
  <img src="images/enable account.png" width="300">
</p>


<p align="center">
  <img src="images/users.png" width="400">
  <img src="Images/list.png" width="470">
  <img src="Images/logs.png" width="470">

  <img src="images/Updatepolicy.png" width="400">

</p>
