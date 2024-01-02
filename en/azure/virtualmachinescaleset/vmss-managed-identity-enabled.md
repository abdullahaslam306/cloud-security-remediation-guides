[![CloudSploit](https://cloudsploit.com/img/logo-new-big-text-100.png "CloudSploit")](https://cloudsploit.com)

# AZURE / Virtual Machine Scale Set / VM Scale Set Managed Identity Enabled

## Quick Info

| | |
|-|-|
| **Plugin Title** | VM Scale Set Managed Identity Enabled |
| **Cloud** | AZURE |
| **Category** | Virtual Machine Scale Set |
| **Description** | Ensures that Azure Virtual Machine Scale Sets have managed identity enabled |
| **More Info** | Enabling managed identities eliminate the need for developers having to manage credentials by providing an identity for the Azure resource in Azure AD and using it to obtain Azure Active Directory (Azure AD) tokens. |
| **AZURE Link** | https://learn.microsoft.com/en-us/entra/identity/managed-identities-azure-resources/qs-configure-portal-windows-vmss |
| **Recommended Action** | Modify VM Scale Set and enable managed identity |

## Detailed Remediation Steps

1. Log in to the Microsoft Azure Management Console.
2. Select the "Search resources, services, and docs" option at the top and search for "Virtual Machine Scale Set". </br> <img src="/resources/azure/virtualmachinescaleset/scale-set-vtpm-enabled/step2.png"/>
3. Select the "Scale Set" by clicking on the "Name" link to access the configuration changes. </br> <img src="/resources/azure/virtualmachinescaleset/scale-set-vtpm-enabled/step3.png"/>
4. In the left navigation panel, click on the "Identity" under "Security" section.</br> <img src="/resources/azure/virtualmachinescaleset/scale-set-vtpm-enabled/step4.png"/>
5. On Identity page to enable "System assigned" identity click on "On" under status label and click "Save".  </br> <img src="/resources/azure/virtualmachinescaleset/scale-set-vtpm-enabled/step5.png"/>
6. For "User Assigned" identity click on "Add" under the "User assigned" tab.</br> <img src="/resources/azure/virtualmachinescaleset/scale-set-vtpm-enabled/step6.png"/>
7. On the  "Add user assigned managed identity" panel select the subscription and identity you want to assign and Click "Add" at the bottom.
</br> <img src="/resources/azure/virtualmachinescaleset/scale-set-vtpm-enabled/step7.png"/>