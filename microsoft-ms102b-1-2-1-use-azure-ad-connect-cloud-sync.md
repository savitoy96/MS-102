## Use Azure AD Connect Cloud Sync
At the end of this episode, I will be able to:    

1. Implement and manage directory synchronization by using Azure AD Connect cloud sync

Learner Objective: *Use Azure AD Cloud Sync*    

Description: In this episode, you will learn about the recommended method of syncing your on-prem AD accounts with Azure AD. This can make it very easy for you to import your user accounts for Microsoft 365 in certain scenarios. 

--------  

* This is the new and improved method of synchronizing Active Directory implementations outside of Azure to the Azure Active Directory service. 
* This is a more cloud-centric solution and therefore preferred by Microsoft. 
* It does require the installation of a small agent in the traditional AD domain. 
* It offers benefits, including:
	- Support for sync from a multi-forest disconnected AD environment 
	- Simplified installation 
	- Multiple agents can be installed to support HA
	- Support for large groups with up to 50,000 members 
* To get started - use the Azure portal to visit Azure Active Directory > Azure AD Connect > Cloud Sync

-----------

Additional Resources:

*What is Azure AD Connect Cloud Sync*
https://learn.microsoft.com/en-us/azure/active-directory/hybrid/cloud-sync/what-is-cloud-sync