[![CloudSploit](https://cloudsploit.com/img/logo-new-big-text-100.png "CloudSploit")](https://cloudsploit.com)

# AZURE / Subscription / Azure Subscription Has Tags

## Quick Info

| | |
|-|-|
| **Plugin Title** | Azure Subscription Has Tags |
| **Cloud** | AZURE |
| **Category** | Subscription |
| **Description** | Ensures that Azure subscriptions have tags associated. |
| **More Info** | Tags help you to group resources together that are related to or associated with each other. It is a best practice to tag cloud resources to better organize and gain visibility into their usage. |
| **AZURE Link** | https://learn.microsoft.com/en-us/azure/azure-resource-manager/management/tag-resources-portal |
| **Recommended Action** | Modify affected subscription and add tags. |

## Detailed Remediation Steps

1. Log into the Microsoft Azure Management Console.
2. Select the "Search resources, services, and docs" option at the top and search for Subscriptions. </br> <img src="/resources/azure/subscription/subscription-has-tags/step2.png"/>
3. Select the "Subscription" by clicking the "Name" as a link to get into the configuration changes. </br> <img src="/resources/azure/subscription/subscription-has-tags/step3.png"/>
4. On "Resource Group" click on "Tags" from left navigation panel. </br> <img src="/resources/azure/subscription/subscription-has-tags/step4.png"/>
5. Enter the tags Name and value then click "Apply" button on the bottom of the page to save tags.</br> <img src="/resources/azure/subscription/subscription-has-tags/step5.png"/>
