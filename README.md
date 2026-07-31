# Checkmarx PowerShell Module
PowerShell module to interact with the Checkmarx REST API. Mostly used in security scan report generation, but can be used to search for projects or download reports from Checkmarx on-demand using certain search criteria. Thanks to [Atlassian.BitBucket](https://github.com/beyondcomputing-org/Atlassian.Bitbucket) for code samples.

## Installation
Run the following command in PowerShell session to install the module from our internal PowerShell Gallery. If following the instructions above, the below command should not require elevation

```powershell
Install-Module -Name CheckmarxPS -Scope CurrentUser
```
Often the repository shouldn't need to be specified as long as the name of the module is universally unique.

## Update
If you already have the module installed, run the following command in PowerShell session to update the module from our internal PowerShell Gallery to the latest version.

```powershell
Update-Module -Name CheckmarxPS
```

## Before using The Module
For help on connecting for the first time:
```powershell
Get-Help Connect-Checkmarx -ShowWindow
```
or
```powershell
Get-Help Connect-Checkmarx -Examples
```
To verify that you an authenticate:
```powershell
Test-CheckmarxLogin
```
