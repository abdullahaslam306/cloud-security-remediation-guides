[![CloudSploit](https://cloudsploit.com/img/logo-new-big-text-100.png "CloudSploit")](https://cloudsploit.com)

# AZURE / Virtual Machine Scale Set / Scale Sets AD Authentication Enabled

## Quick Info

| | |
|-|-|
| **Plugin Title** | Scale Sets AD Authentication Enabled |
| **Cloud** | AZURE |
| **Category** | Virtual Machine Scale Set |
| **Description** | Ensures that Azure Active Directory (AD) authentication is enabled for Virtual Machine Scale Sets |
| **More Info** | Enabling Azure Active Directory (AD) authentication for VM Scale Sets ensures access from one central point and simplifies access permission management. It allows conditional access by using Role-Based Access Control (RBAC) policies, and enable MFA. |
| **AZURE Link** | https://learn.microsoft.com/en-us/entra/identity/devices/howto-vm-sign-in-azure-ad-linux |
| **Recommended Action** | Enable Active Directory authentication for all Virtual Machines scale sets.
## Detailed Remediation Steps

1. Log in to the Microsoft Azure Management Console.
2. Select the "Search resources, services, and docs" option at the top and search for "Virtual Machine Scale Set". </br> <img src="/resources/azure/virtualmachinescaleset/scaleset-ad-auth-enabled/step2.png"/>
3. Select the "Scale Set" by clicking on the "Name" link to access the configuration changes. </br> <img src="/resources/azure/virtualmachinescaleset/scaleset-ad-auth-enabled/step3.png"/>
4. In the left navigation panel, click on the "Extensions + applications" under "Settings".</br> <img src="/resources/azure/virtualmachinescaleset/scaleset-ad-auth-enabled/step4.png"/>
5. On "Extensions + applications" page click on "Add" button under extensions tab. </br> <img src="/resources/azure/virtualmachinescaleset/scaleset-ad-auth-enabled/step5.png"/>
6. On "Install an Extension" page search for "Azure AD based Windows Login" for windows VMSS or "Azure AD based SSH Login" for linux based VMSS. Select the extension by clicking on it and click "Next" at the bottom of the page. </br> <img src="/resources/azure/virtualmachinescaleset/scaleset-ad-auth-enabled/step6.png"/>
7. On Extension configurations page click on "Create" at the bottom of the page and extension will be installed on your virtual machine scale set.