## Implement DLP for Workloads 
At the end of this episode, I will be able to:    

1. Implement DLP for workloads

Learner Objective: *Implement DLP for workloads in Microsoft 365*    

Description: In this episode, you will learn the basics of using DLP in Microsoft 365 thanks to Microsoft Purview. 

--------  

* Microsoft Purview permits the implementation of Data Loss Prevention (DLP) for workloads; this works across:
	- MS 365 services like Teams, OneDrive, etc. 
	- Office applications
	- Windows 10, Windows 11, and macOS
	- SharePoint file shares 
	- Power BI
* Permissions required:
	- Compliance Administrator
	- Compliance Data Administrator 
	- Information Protection 
	- Information Protection Admin 
	- Security Administrator 
* To create a policy for a workload, follow these steps:
	- Sign in to the Microsoft Purview Compliance Portal
	- Choose Solutions - Data Loss Prevention - Policies - Create Policy 
* In order to deploy policies in a non-disruptive way - use the state feature - possible options here include: 
	- Test it out first
	- Test it out and show policy tips while in test mode 
	- Turn it on right away 
	- Keep it off 
* Possible actions are:
	- Allow
	- Audit Only 
	- Block with override 
	- Block 
* Microsoft's recommended deployment steps: 
	- Use the KEEP IT OFF state while stakeholders are reviewing the policy 
	- Change the state to TEST IT OUT FIRST 
	- Tune the policy based on the behavior data 
	- Change the state to TEST IT OUT FIRST AND SHOW POLICY TIPS
	- Gather user feedback and alert and event data 
	- Change the state to TURN IT ON RIGHT AWAY 

-----------

Additional Resources:

*Learn about data loss prevention*
https://learn.microsoft.com/en-us/purview/dlp-learn-about-dlp