azuredeploy.json

This is a modification of the GitHub AzureRM repo template for a single DC deployment.
This version uses DSC with a configuration data file to deploy the domain and populate
sample data for an instant AD test lab.

##How do I do it?
Download CallingScript.ps1 to your local machine.
Modify the string naming parameters and run the code.
In 30 minutes you will have a populated AD test lab.

Or, download all these files. Tweak the DSC configuration, DSC configuration data, and azuredeploy.json to your own needs. Then host them on your own GitHub or Azure storage account.



Prerequisites
- An Azure subscription (MSDN, trial, etc.)
- WMF 5.0 (or WMF 4.0 with PowerShellGet installed)