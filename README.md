Stop All VMs in Specified Azure Resource Group
==============================================

            

**SYNOPSIS        **


This PowerShell Workflow script, intended to run in an Azure Automation runbook, stops all the Azure VMs in a specific Azure Resource Group.


**DESCRIPTION**


This sample runbooks stops all of the virtual machines in the specified Azure Resource Group. For more information about how this runbook authenticates to your Azure subscription, see the Microsoft documentation here: http://aka.ms/fxu3mn. 


**Note:** If you do not uncomment the 'Select-AzureSubscription' statement (on line 57) and insert  the name of your Azure subscription, the runbook will use the default subscription.


**PARAMETER ResourceGroupName       **


Name of the Azure Resource Group containing the VMs to be stopped.

**REQUIREMENTS        **


This runbook requires the Azure Resource Manager PowerSHell module has been imported into your Azure Automation instance.


This runbook will only return VMs deployed using the new Azure IaaS features available in the Azure Preview Portal and Azure Resource Manager templates. For more information, see  http://azure.microsoft.com/en-us/documentation/videos/build-2015-introduction-and-what-s-new-in-azure-iaas/.
         



**NOTES       **


AUTHOR: Pete Zerger, MVP        


LASTEDIT: May 13, 2015


 

 

        
    
TechNet gallery is retiring! This script was migrated from TechNet script center to GitHub by Microsoft Azure Automation product group. All the Script Center fields like Rating, RatingCount and DownloadCount have been carried over to Github as-is for the migrated scripts only. Note : The Script Center fields will not be applicable for the new repositories created in Github & hence those fields will not show up for new Github repositories.
