This example shows how to create a new user account in Microsoft Azure tenant using Powershell cmdlets.

## Tenant creation

A new tenant is required to manage users for an organisation.

* Navigate to Entra ID -> Manage tenants -> Create
* On the Basics tab, select the type of tenant you want to create, Microsoft Entra ID (B2C).
* On the Configuration tab Type your desired Organization name, desired Initial domain name, your desired Country/Region 
* Next: Review + Create -> Create
* A new Tenant is created with desired Organisation and domain name as below:
![Capture](https://github.com/user-attachments/assets/fe2c3cab-b3bb-408c-8cac-ed3fa62d3f4d)

## Create new user

* Open Cloudshell module in Azure portal.
* Use **New-AzADUser** cmd to create new user, storing a user password in a variable.

![New user](https://github.com/user-attachments/assets/4c15b472-3fab-4692-9027-e339e401d635)
![new user1](https://github.com/user-attachments/assets/48742b22-3455-4926-8b9a-4ee3e7f05b05)

  
