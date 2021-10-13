# uev
A set of custom User Experience Virtualization templates pushed to blob storage on an Azure storage account. Used with Windows 10 Enterprise PCs managed via Microsoft Intune (or other MDM).

Deploy the PowerShell script Set-Uev.ps1 to target PCs to enable the UE-V service, download the templates from the storage account and register them locally. New-UevTask.ps1 is deployed from Intune to download Set-Uev.ps1 and register a scheduled task to run the script.
