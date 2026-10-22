# Employee Offboarding Using Microsoft Entra and ServiceNow

## Project Overview

In this lab, I practiced handling an employee offboarding request using Microsoft Entra and ServiceNow. The goal was to disable the employee's account, remove their security group access, revoke their active sign-in sessions, and confirm they could no longer sign in.

I also used ServiceNow to document the steps I completed and resolve the offboarding ticket.

## Scenario

The HR department submitted a request to offboard Chase Fuller, a Sales Associate who was leaving the company.

As the IT support technician in this simulated environment, my responsibility was to remove his account access and make sure the offboarding request was completed properly.

## Tools Used

- Microsoft Entra
- ServiceNow
- Microsoft account sign-in page

## Steps Completed

### 1. Reviewed the ServiceNow Request

I started by reviewing the employee offboarding request in ServiceNow to understand which account needed to be disabled and what access needed to be removed.

<img width="883" height="555" alt="01-ServiceNow-Offboarding-Request" src="https://github.com/user-attachments/assets/0d363a47-51f6-4e14-9102-944c27cac20e" />

### 2. Located the Employee Account

I signed in to the Microsoft Entra admin center, navigated to the Users section, and located Chase Fuller's account.

I reviewed his account information and existing group membership before making any changes.

<img width="886" height="783" alt="02-Chase-Account-Before-Offboarding" src="https://github.com/user-attachments/assets/2bee37e6-f352-4fb0-b851-3fe82d54d47a" />

### 3. Disabled the Employee Account

I disabled Chase Fuller's account in Microsoft Entra to prevent further sign-ins.

After making the change, I verified that his account status showed Disabled.

<img width="844" height="750" alt="03-Chase-Account-Disabled" src="https://github.com/user-attachments/assets/b8ff963d-c580-43b8-89df-ba5a9c4d0b3e" />

### 4. Removed Security Group Access

I removed Chase Fuller from the Sales security group because he no longer needed access to company resources.

I checked his group memberships afterward to confirm that the access had been removed.

<img width="825" height="792" alt="04-Chase-Offboarding-Verfication" src="https://github.com/user-attachments/assets/05c39203-9d0c-411c-a52c-63f6232b4158" />

### 5. Revoked Active Sign-In Sessions

I used the Revoke Sessions option in Microsoft Entra to invalidate the employee's existing sign-in sessions.

This was an additional security measure to help prevent continued access after offboarding.

<img width="851" height="370" alt="05-Chase-sessions-Revoked" src="https://github.com/user-attachments/assets/54241a50-87f4-4f09-a4ac-8e6332023c86" />

### 6. Verified That the Employee Could No Longer Sign In 
I attempted to sign in to Chase Fuller's account after disabling it and revoking his sessions. Microsoft displayed an account access error, confirming that the sign-in attempt was unsuccessful.

<img width="895" height="406" alt="Chase-verfiy" src="https://github.com/user-attachments/assets/c8d9bd93-206a-4bc6-81e8-1e5a1a74d013" />

### 7. Updated the ServiceNow Ticket

After completing the offboarding steps, I returned to ServiceNow and documented the actions I performed.

I added work notes, entered resolution notes, and resolved the offboarding request.

<img width="866" height="818" alt="06-Chase-offboarding-notes-service-now" src="https://github.com/user-attachments/assets/ae67b49a-136d-43ce-939a-e138a0e31926" />

<img width="881" height="507" alt="07-Chase-Resolution-Notes-ServiceNow" src="https://github.com/user-attachments/assets/3817d1fd-040d-4eab-afd4-c60f32a2a931" />

<img width="1886" height="223" alt="08-Chase-Resolved-Ticket-ServiceNow" src="https://github.com/user-attachments/assets/caae13fd-25a1-40ca-843d-2c9fc836cfd5" />

## What I Learned

This project helped me better understand the employee offboarding process and why removing access promptly is important for account security.

I gained more hands-on experience disabling accounts, managing security group memberships, revoking sessions, and documenting account management tasks in ServiceNow.
