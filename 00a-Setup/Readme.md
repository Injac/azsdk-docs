# Installation Guide
> <h4>IMPORTANT:</h4> If you are from MSIT, please install via instructions at http://aka.ms/azsdkdocs so that IT-specific policies get setup for you. <u>Do not</u> use this page.


**Release Version: 2.3.xx**  
>**Pre-requisites**:
> - PowerShell 5.0 or higher. 
	
1. First verify that prerequisites are already installed:  
    Ensure that you have PowerShell version 5.0 or higher by typing **$PSVersionTable** in the PowerShell ISE console window and looking at the PSVersion in the output as shown below.) 
 If the PSVersion is older than 5.0, update PowerShell from [here](https://www.microsoft.com/en-us/download/details.aspx?id=54616).  
   ![PowerShell Version](../Images/00_PS_Version.png)   

2. Install the Secure DevOps Kit for Azure (AzSDK) PS module:  
	  
```PowerShell
  Install-Module AzSDK -Scope CurrentUser
```

Note: You may need to use `-AllowClobber` and `-Force` options with the Install-Module command 
above if you have a different version of AzureRM installed on your machine. 
AzSDK depends on a specific version of AzureRM and installs that during the installation above.  

------------------------------------------------
### FAQs

#### How to run AzSDK commands when both AzureRM 4.0 and AzureRM 3.8 are present?
**Approach 1:**
1. Open a new PowerShell session. 
2. Run any of the AzSDK commands directly “Get-AzSDKAzureServicesSecurityStatus”.  
>Note: If you try to login first and then PS would by default load 4.0.1 which would start failing with 3.8.0

**Approach 2:**
1. Open a new PowerShell session
2. Import-Module -Name AzureRM -RequiredVersion 3.8.0
3. Login-AzureRmAccount
4. Run any AzSDK commands.
