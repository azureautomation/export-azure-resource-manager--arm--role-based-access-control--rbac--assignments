Export Azure Resource Manager (ARM) Role Based Access Control (RBAC) Assignments
================================================================================

            

This script allows you to export the current Azure Resource Manager (ARM) Role Based Access Control (RBAC) Permissions.


It will loop through all subscriptions that you have access to and export the permissions.


It will create an individual CSV file on the desktop per subscription.


The report will appear as follows


![Image](https://github.com/azureautomation/export-azure-resource-manager-(arm)-role-based-access-control-(rbac)-assignments/raw/master/accessPermissions.png)


 


Notice the **Scope **of the assignment is listed


- It could be at the Subscription level


- It could be as a Resource Group or other lower level





**Scope**


/subscriptions/1f0713fe-9b12-4c8f-ab0c-1234adf1234a


/subscriptions/1f0713fe-9b12-4c8f-ab0c-1234adf1234a/resourceGroups/rgMWilliams












 

 

        
    
TechNet gallery is retiring! This script was migrated from TechNet script center to GitHub by Microsoft Azure Automation product group. All the Script Center fields like Rating, RatingCount and DownloadCount have been carried over to Github as-is for the migrated scripts only. Note : The Script Center fields will not be applicable for the new repositories created in Github & hence those fields will not show up for new Github repositories.
