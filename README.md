Allows only one instance of a runbook job to run at any one time.
=================================================================

            

This runbook ensures that only one instance of a runbook is running at any one time. It is meant to be called from another runbook as an inline runbook, not started asynchronously through the web service. 


Please look at the Set-RunbookLockSample runbook for example usage. 


Scenarios where this is useful is when specific actions cannot run in parallel, like creating a unique user, installing applications using windows installer, creating a unique machine name in Active Directory.


 

 

        
    
TechNet gallery is retiring! This script was migrated from TechNet script center to GitHub by Microsoft Azure Automation product group. All the Script Center fields like Rating, RatingCount and DownloadCount have been carried over to Github as-is for the migrated scripts only. Note : The Script Center fields will not be applicable for the new repositories created in Github & hence those fields will not show up for new Github repositories.
