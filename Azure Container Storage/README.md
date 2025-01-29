This example shows how to create a Container storage in Azure using powershell scripts.

## Resource Group

* Create a resource group using **New-AzResourceGroup** cmdlet.

![rg](https://github.com/user-attachments/assets/2d6538c3-1c27-49dd-bf42-87bf88971281)

## Storage accounts

* Create a new general-purpose storage account with LRS replication using **New-AzStorageAccount** cmdlet. 
* Storing the account created in a variable.
* Check creation using **Get-AzStorageAccount** cmd.

![storage account](https://github.com/user-attachments/assets/0d1a8cd2-cb2c-46ca-97eb-30aafb3b650c)

## Container storage

* Create a container using **New-AzStorageContainer** cmdlet and set the container name.

![blob](https://github.com/user-attachments/assets/0b495242-e025-40f5-a613-3add2e0367b4)

