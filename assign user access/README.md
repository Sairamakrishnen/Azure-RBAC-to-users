This example shows how to assign role-based access control to Entra user using powershell cmdlets.

## Assign reader role to user at the subscription scope.

* Get the ID of your subscription using the **Get-AzSubscription** command.
* Save the subscription scope in a variable.

![subscope](https://github.com/user-attachments/assets/22965c6c-1ebd-4dd8-9a1e-33fd45bf226e)

* Assign Reader role to the Entra user at the subscription scope using **New-AzRoleAssignment** cmdlet.

![rbac reader](https://github.com/user-attachments/assets/e2030531-f84c-4eaa-a00b-70bd487b94d7)

## Assign Storage Blob Data Contributer role to user at the Storage account scope.

* Assign Storage Blob Data Contributer role to the Entra user at Storage account scope using **New-AzRoleAssignment** cmdlet.

![rbac blob data contributer](https://github.com/user-attachments/assets/290745c1-ab8d-45e0-93f8-e888dadfefe4)

## List access using the Azure Portal

* To see how the role assignments look in the Azure portal, view the **Azure role assignments** for the user.

![rbac](https://github.com/user-attachments/assets/0bc86534-6b99-4a05-ad3b-3783e5174226)

## Remove access

* To remove access for users use **Remove-AzRoleAssignment** cmdlet.

![remove sd](https://github.com/user-attachments/assets/68f1c4a1-21f7-42b1-ba13-3c78f154e7c9)

## Cleanup

* Remove the resource group and the user using **Remove-AzResourceGroup**, **Remove-AzADUser** cmdlets.

![remove rg user](https://github.com/user-attachments/assets/3aa8dfe4-fc0a-49aa-911f-a94e3bd14487)


