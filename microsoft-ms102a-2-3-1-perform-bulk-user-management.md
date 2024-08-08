## Perform Bulk User Management
At the end of this episode, I will be able to:    

1. Perform bulk user management, including PowerShell

Learner Objective: *Manage multiple users simultaneously in Microsoft 365.*    

Description: In this episode, you will learn different options for managing multiple users in Microsoft 365.

--------  

* There are steps available for Google Workspace to Microsoft 365 migration 
* Users > Active Users > Add multiple users  - you can use a CSV with user information in order to bulk create user accounts 
* You can automate the adding of accounts and assigning licenses using PowerShell 
	- Certain properties are required - DisplayName, UserPrincipleName
	- The steps are 1) create a CSV file that contains the required information 2) Use the PowerShell syntax: Import-Csv -Path <Input CSV File Path and Name> | foreach {New-MsolUser -DisplayName $_.DisplayName -FirstName $_.FirstName -LastName $_.LastName -UserPrincipalName $_.UserPrincipalName -UsageLocation $_.UsageLocation -LicenseAssignment $_.AccountSkuId [-Password $_.Password]} | Export-Csv -Path <Output CSV File Path and Name>
* You can setup Active Directory synchronization for Microsoft 365 
	- Use the Azure AD Connect tool to configure directory synchronization 
* You can also migrate user accounts from Exchange 

-----------

Additional Resources:

*Create and use a template to add users*
https://learn.microsoft.com/en-us/microsoft-365/admin/add-users/create-and-use-a-template-to-add-users?view=o365-worldwide

*Create Microsoft 365 user accounts with PowerShell*
https://learn.microsoft.com/en-us/microsoft-365/enterprise/create-user-accounts-with-microsoft-365-powershell?view=o365-worldwide