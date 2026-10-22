# Password Reset Using Microsoft Entra and ServiceNow

## Project Overview

In this lab, I practiced handling an employee password reset request using Microsoft Entra and ServiceNow. The goal was to reset the employee's password, require them to change it during their next sign-in, and confirm they could access their account again.

I also used ServiceNow to document the steps I completed and resolve the ticket.

## Scenario

Chase Fuller, a Sales Associate, needed assistance resetting his account password.

As the IT support technician in this simulated environment, my task was to reset his password securely and make sure he could sign in successfully.

## Tools Used

- Microsoft Entra 
- ServiceNow
- Microsoft account sign-in page

## Steps Completed

### 1. Reviewed the ServiceNow Ticket

I started by reviewing the password reset request in ServiceNow to understand the issue and what needed to be done.

<img width="905" height="543" alt="01-Password-Reset-Resquest-ServiceNow" src="https://github.com/user-attachments/assets/7692c07a-dc4c-4a2a-a4f7-261671bee6eb" />

### 2. Located the Employee Account

I signed in to the Microsoft Entra admin center, navigated to the Users section, and located Chase Fuller's account.

I reviewed his account information before making any changes.

<img width="851" height="582" alt="03-Chase-Account-Before-Reset" src="https://github.com/user-attachments/assets/4886c0df-fbf0-4056-b882-f40d2dc1c036" />

### 3. Reset the Employee's Password

I used the Reset Password option in Microsoft Entra to generate a temporary password for Chase.

The account was configured to require a password change at the next sign-in.

<img width="831" height="383" alt="04-Chase-Password-Reset" src="https://github.com/user-attachments/assets/3db0cff2-e083-47b8-9cb0-a085af855da6" />

<img width="875" height="389" alt="05-Chase-Password-Reset-Sucess" src="https://github.com/user-attachments/assets/f2ef8923-fb3c-44a7-a183-40b386c3192e" />

### 4. Verified the Password Reset

After resetting the password, I tested the employee's sign-in using the temporary password.

I completed the required password change and confirmed that the account could be accessed successfully.

<img width="899" height="733" alt="06-Chase-password-Change-Required" src="https://github.com/user-attachments/assets/1a1ceb35-acea-4b66-922f-f58fae541f1d" />

<img width="890" height="712" alt="07-Chase-Successful-Login-After-Rest" src="https://github.com/user-attachments/assets/5e0b8fdf-98eb-42a9-99a7-0463f214e5ae" />

### 5. Updated the ServiceNow Ticket

After completing and verifying the password reset, I returned to ServiceNow and documented the work performed.

I added work notes, entered resolution notes, and resolved the ticket.

<img width="880" height="603" alt="08-ServiceNow-Password-Reset-Work-Notes" src="https://github.com/user-attachments/assets/048bff19-7900-4485-af00-e9ea998ad744" />

<img width="854" height="699" alt="10-Chase-Resolution-notes" src="https://github.com/user-attachments/assets/36ea38f9-9119-4b66-bd68-12673879cf81" />

<img width="1902" height="215" alt="11-Chase-Ticket-Resolved" src="https://github.com/user-attachments/assets/784a724f-ac73-4038-9638-da94006344ee" />

## What I Learned

This project helped me get more comfortable resetting passwords in Microsoft Entra and understand why temporary passwords and required password changes matter.

It also gave me more practice following a support ticket from the initial request through troubleshooting, verification, and resolution.

