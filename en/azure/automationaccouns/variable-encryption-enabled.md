[![CloudSploit](https://cloudsploit.com/img/logo-new-big-text-100.png "CloudSploit")](https://cloudsploit.com)

# AZURE / Automation Accounts / Variables Encryption Enabled

## Quick Info

| | |
|-|-|
| **Plugin Title** | Variables Encryption Enabled |
| **Cloud** | AZURE |
| **Category** | Automation Account |
| **Description** |Ensure that Azure Automation Account Variables are Encrypted. |
| **More Info** | Azure Automation has the ability to share variable assets across runbooks and configurations. In doing so, it is considered best practice to encrypt these variables to ensure that sensitive information and intellectual property is protected. |
| **AZURE Link** | https://learn.microsoft.com/en-us/azure/automation/shared-resources/variables |
| **Recommended Action** | Remove the unencrypted variable and recreate new variable with encryption enabled. |

## Detailed Remediation Steps

1. Login to the Microsoft Azure Management Console.
2. In the search bar at the top search for automation accounts and click on "Automation Accounts".<br/> <img src="/resources/azure/automationaccounts/variable-encryption-enabled/step2.png"/>
3. On the Automation Accounts page, click on the name of account.<br/> <img src="/resources/azure/automationaccounts/variable-encryption-enabled/step3.png"/>
4. On the account details page Click on "Variables" under "Shared Resources" section from left navigation panel.<br/> <img src="/resources/azure/automationaccounts/variable-encryption-enabled/step4.png"/>
5. On Variables page Click on variable name which is unencrypted and Click "Delete" from the newly opened panel.<br/> <img src="/resources/azure/automationaccounts/variable-encryption-enabled/step5.png"/>
6. After deleting the variable Click on "Add Variable" from top navigation bar on variables page. Enter the variable Name, description and value of variable and Click on yes for Encryption to encrypt the variable and Click "Save".<br/> <img src="/resources/azure/automationaccounts/variable-encryption-enabled/step6.png"/>

