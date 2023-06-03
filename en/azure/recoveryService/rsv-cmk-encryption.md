[![CloudSploit](https://cloudsploit.com/img/logo-new-big-text-100.png "CloudSploit")](https://cloudsploit.com)

# AZURE / Recovery Service / Recovery Service Vault CMK Encryption

## Quick Info

| | |
|-|-|
| **Plugin Title** | Recovery Service Vault CMK Encryption |
| **Cloud** | AZURE |
| **Category** | Backup |
| **Description** | Ensure that Microsoft Azure Recovery Service Vault have CMK Encryption Enabled. |
| **More Info** | A customer-managed key gives you the ownership to bring your own key in Azure Key Vault. When you enable a customer-managed key, you can manage its rotations, control the access and permissions to use it, and audit its use. |
| **AZURE Link** | https://docs.microsoft.com/en-us/azure/azure-resource-manager/resource-group-lock-resources |
| **Recommended Action** | Modify Recovery Service vault and enable CMK encryption. |

## Detailed Remediation Steps
1. Log in to the Microsoft Azure Management Console.
2. Select the "Search resources, services, and docs" option at the top and search for "Recovery Service Vault". </br> <img src="/recoveryService/azure/recoveryService/rsv-cmk-encryption/step2.png"/>
3. Select the "Recovery Service Vault" by clicking on the "Name" link to access the configuration changes. </br> <img src="/recoveryService/azure/recoveryService/rsv-cmk-encryption/step3.png"/>
4. In the left navigation panel, click on "Properties" under the "Settings" section.</br> <img src="/recoveryService/azure/recoveryService/rsv-cmk-encryption/step4.png"/>
5. On the "Properties" page, under the "Backup" section, click on the "Update" button next to "Encryption" settings.</br> <img src="/recoveryService/azure/recoveryService/rsv-cmk-encryption/step5.png"/>
6. On the Encryption settings page, select "Use your own key". Then, choose either "Enter key Uri" or "Select from Key Vault" to provide the key details. Enter the necessary information and click "Save" in the navigation bar at the top. </br> <img src="/recoveryService/azure/recoveryService/rsv-cmk-encryption/step6.png"/>
