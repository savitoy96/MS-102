## Implement Retention and Sensitivity Labels
At the end of this episode, I will be able to:    

1. Implement retention labels, retention label policies, and retention policies
2. Implement sensitivity labels and sensitivity label policies

Learner Objective: *Implement retention labels and retention policies as well as sensitivity labels*    

Description: In this episode, you will learn about using sensitivity and retention labels and policies for use in Microsoft Purview environments. 

--------  

* Companies today are often required by laws or policies to do the following:
	- Retain content - prevent permanent deletion
	- Delete content - ensure permanent deletion 
* Available retention settings are:
	- Retain-only 
	- Delete-only
	- Retain and then delete 
* The content can stay in its original location and still be subject to these labels and policies 
* What if a user deletes content that must be retained:
	- For SharePoint and OneDrive sites - copy made in Preservation Hold library
	- For Exchange mailboxes - a copy is retained in the Recoverable Items folder
	- For Teams and Viva Engage messages - copy retained in SubstrateHolds hidden folder 
* There are two approaches to retention:
	- Retention Policies 
	- Retention Labels with Label Policies 
* Retention labels are often preferred because:
	- Labels travel with the content
	- Retention period can start more flexibly based on events
	- Trainable classifiers can be used
	- Default labels exist
	- More options available at the end of the retention period 
	- You can also use retention labels with no action assigned 
	- Retention labels can be basis for DLP 
* Sensitivity labels let you classify and protect your organization's data 
* Sensitivity labels can:
	- Provide protection settings that include encryption and content markings 
	- Protect content in Office apps across different platforms and devices
	- Protect content in third-party apps and services using Defender for Cloud Apps
	- Protect containers that include apps like Teams
	- Protect meetings and chat
	- Extend sensitivity lanes to Power BI
	- Extend sensitivity labels to third-party apps and services 
	- Label content without using any protection settings 
* Sensitivity labels can:
	- Encrypt
	- Mark the content
	- Protect content in containers 
	- Apply labels automatically 
	- Set defaults 
* Sensitivity labels have a priority setting 

-----------

Additional Resources:

*Learn About Retention Policies and Retention Labels*
https://learn.microsoft.com/en-us/purview/retention

*Learn About Sensitivity Labels*
https://learn.microsoft.com/en-us/purview/sensitivity-labels