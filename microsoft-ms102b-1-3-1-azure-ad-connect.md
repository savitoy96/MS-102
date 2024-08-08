## Azure AD Connect
At the end of this episode, I will be able to:    

1. Implement and manage directory synchronization by using Azure AD Connect
2. Azure AD Connect Health

Learner Objective: *Understand the Azure AD Connect option*    

Description: In this episode, you will learn about the Azure AD Connect method of synchronizing an on-prem AD with the Azure AD located in the cloud. While this method is now considered legacy, it still might be in use in some organizations. 

--------  

* On-prem application for sync; set to go away thanks to Cloud Sync
* Azure AD Connect v1 retired Aug 31, 2022; v2 now "current"
* Features:
	- Password hash synchronization
	- Pass-through authentication
	- Federation integration
	- Synchronization
	- Health Monitoring
* Replaced DirSync and Azure AD Sync
* License is free
* Requirements and recommendations:
	- Azure AD
	- Add and verify domain
	- 50,000/300,000/500,000 object limits 
	- Use Id Fix
	- On-prem must be 2003 Functional Level or later
	- DC must be writable
	- Enable AD Recycle Bin
	- PowerShell execution required
	- Installed on Windows Server 2016 GUI version 
	- Harden the server
	- Uses SQL Server 2019 Express by default 
* Azure AD Connect Health is available for monitoring the synchronization process

-----------

Additional Resources:

*Prerequisites for Azure AD Connect*
https://learn.microsoft.com/en-us/azure/active-directory/hybrid/connect/how-to-connect-install-prerequisites