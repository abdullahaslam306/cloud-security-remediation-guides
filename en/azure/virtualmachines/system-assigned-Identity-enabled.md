[![CloudSploit](https://cloudsploit.com/img/logo-new-big-text-100.png "CloudSploit")](https://cloudsploit.com)

# AZURE / Virtual Machines / VM System Assigned Identity Enabled

## Quick Info

| | |
|-|-|
| **Plugin Title** | VM System Assigned Identity Enabled |
| **Cloud** | AZURE |
| **Category** | Virtual Machines |
| **Description** | Ensures that Virtual Machines have System Assigned Managed Identities Enabled |
| **More Info** | Managed identities for Azure resources provides Azure services with a managed identity in Azure AD which can be used to authenticate to any service that supports Azure AD authentication, without having to include any credentials in code. |
| **AZURE Link** | https://docs.microsoft.com/en-us/azure/security-center/security-center-enable-vm-agent |
| **Recommended Action** | Modify virtual machines and enable system assigned managed identity. |

## Detailed Remediation Steps

1. Log into the Microsoft Azure Management Console.
2. Select the "Search resources, services, and docs" option at the top and search for Virtual Machines. </br> <img src="/resources/azure/virtualmachines/system-assigned-Identity-enabled/step2.png"/>
3. Select the "Virtual machine" by clicking the "Name" as a link to get into the configuration changes. </br> <img src="/resources/azure/virtualmachines/system-assigned-Identity-enabled/step3.png"/>
4. Scroll down the "Virtual machine" navigation panel and choose "Identity" under the "Settings" section. </br> <img src="/resources/azure/virtualmachines/system-assigned-Identity-enabled/step4.png"/>
5. On identity settings page under the "System assigned" tab turn the "Status" ON and click "Save" from top navigation menu. </br> <img src="/resources/azure/virtualmachines/system-assigned-Identity-enabled/step5.png"/>