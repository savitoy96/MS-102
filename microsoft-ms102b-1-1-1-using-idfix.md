## Using IdFix
At the end of this episode, I will be able to:    

1. Prepare for identity synchronization by using IdFix

Learner Objective: *Describe the IdFix tool*    

Description: In this episode, you will learn about the IdFix tool for Azure AD Connect usage. You will understand why this tool is so celebrated and how it assists with Azure AD Connect utilization. 

--------  

* This tool is an attempt by Microsoft to reduce the time required to onboard to Microsoft 365. 
* The tool seeks to reduce the errors that must be remediated when using the Windows Server Active Directory errors that occur when using the Azure AD Connect tool or the Azure AD Connect Cloud Sync tool. 
* The tool allows you to remediate potential synchronization errors in your AD Forest before synchronization is attempted. 
* The tool might actually catch more issues than would be caught during synchronization. 
* IdFix scans all objects and ensures that values are compliant for synchronization. 
* In the case of invalid characters - a "fix" is recommended by the tool. 
* Works with Windows Server 2008 R2 or later. 
* Works with Exchange 2003 or later. 
* The tool can be installed on a workstation in the forest. It does NOT need to be installed on an Exchange or AD server. 

-----------

Additional Resources:

*Query and Fix Invalid Object Attributed with the IdFix Tool*
https://microsoft.github.io/idfix/