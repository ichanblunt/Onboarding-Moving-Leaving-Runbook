# Onboarding-Moving-Leaving-Runbook


1. A new employee named Lisa joins the organization

<img width="700" alt="Screenshot 2026-11-19 110611" src="https://github.com/user-attachments/assets/d61dee1d-9688-4543-8a59-08880d192894" />

<img width="700" alt="Screenshot 2026-11-19 110745" src="https://github.com/user-attachments/assets/0407e6f6-7414-44b3-8ed0-a566159d237e" />

<img width="700" alt="Screenshot 2026-11-19 111004" src="https://github.com/user-attachments/assets/02afba60-1af1-48f7-876b-7aae3630054a" />

<img width="700" alt="Screenshot 2026-11-19 111112" src="https://github.com/user-attachments/assets/17dd08f8-2779-496f-8cf7-e9f68b415ea9" />

An email will then need to be sent to the user's personal email with credential information. 

<img width="700" alt="Screenshot 2026-11-19 112508" src="https://github.com/user-attachments/assets/9c4be169-4657-4442-93b4-2bb85ba93783" />

Lisa will be prompted with steps to set up her two factor authentication via microsoft authenticator, once she logs in.

In Entra more details can be specified for the user such as their department and position. This will allow the user to be automatically assigned to the tech security group through the use of dynamic groups. 

<img width="700" alt="Screenshot 2026-11-20 104458" src="https://github.com/user-attachments/assets/b0e4b073-6eb7-47b8-a282-91542d0f15c3" />

<img width="700" alt="Screenshot 2026-11-20 104551" src="https://github.com/user-attachments/assets/e5ccdfa7-3b82-4017-9bd0-c7126c01e41e" />

<img width="700" alt="Screenshot 2026-11-20 104836" src="https://github.com/user-attachments/assets/23005955-f8c3-4876-8446-1178d3a024b0" />

2. Lisa has been given a new opportunity in the Human Resources department so must switch security groups.

When the HR group was originally set up it was built as a dynamic security group for quick transfers between departments. This type of security group can only be created in Entra ID.

Firstly, the group named Human Resources was created.

<img width="700" alt="Screenshot 2026-11-23 165206" src="https://github.com/user-attachments/assets/564c23f3-3dab-4413-8110-ca47be93dc99" />

<img width="700" alt="Screenshot 2026-11-23 165348" src="https://github.com/user-attachments/assets/d44f83ea-26a7-45ad-804c-7d6cd99dc639" />

Below demonstrates rules for a dynamic group based on the user's department. 

<img width="700" alt="Screenshot 2026-11-23 170836" src="https://github.com/user-attachments/assets/b35865b2-230f-4ca2-a24c-c05cf641e082" />

Since HR was built as a dynamic group, it's simple to switch groups. The user's department will need to be changed and then Lisa will be sent to the HR group. 

<img width="700" alt="Screenshot 2026-11-23 171136" src="https://github.com/user-attachments/assets/feae6a88-6dd5-411e-9201-da5a5622f345" />

<img width="700" alt="Screenshot 2026-11-24 165114" src="https://github.com/user-attachments/assets/c0139974-6733-4d80-a509-1992e373b81a" />


3. Lisa is leaving the company due to finding a new job.

A users account should not be immediately deleted as there is typically important data which is associated with Lisa's account. 
Firstly, the helpdesk should disable sign in for Lisa's account.

<img width="700" alt="Screenshot 2026-11-23 173855" src="https://github.com/user-attachments/assets/8dd3ffc6-58ea-41bd-81ba-ff014de23c88" />

A user's current session can also be disabled. If Lisa is currently logged into an active session, then she will be forced to re-authenticate.  

<img width="700" alt="Screenshot 2026-11-23 174036" src="https://github.com/user-attachments/assets/95c6eeb5-afdd-41ab-80e0-9d14c63d8261" />

Data then can be saved by the helpdesk. This is done in many companies in order to retain data and for documentation purposes. This data can be transferred to current employees with appropriate permissions. Data could be found in a SharePoint site, OneDrive, Outlook, etc. 

Now Lisa's account can have her access removed from groups as groups have access to licenses and other features. Licenses are sometimes directly tied to the user so they can be removed directly. 

<img width="700" alt="Screenshot 2026-11-24 211137" src="https://github.com/user-attachments/assets/d1ac2c8e-105c-4ab7-8a85-5b310e7f95e8" />

<img width="1297" height="556" alt="Screenshot 2026-11-24 211210" src="https://github.com/user-attachments/assets/a222adb6-8f55-404f-9288-c8ee254a0d90" />

Finally the account can be completely deleted

<img width="1001" height="631" alt="Screenshot 2026-11-24 211456" src="https://github.com/user-attachments/assets/bf03b991-62e3-486f-8fc6-dcf4672275c3" />
