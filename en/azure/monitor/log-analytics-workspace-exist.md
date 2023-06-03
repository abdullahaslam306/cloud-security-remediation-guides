[![CloudSploit](https://cloudsploit.com/img/logo-new-big-text-100.png "CloudSploit")](https://cloudsploit.com)

# AZURE / Monitor / Log Analytics WorkSpace Exits

## Quick Info

| | |
|-|-|
| **Plugin Title** | Log Analytics WorkSpace Exits |
| **Cloud** | AZURE |
| **Category** | Monitor |
| **Description** | Ensures that Microsoft Azure Log Analytics Workspace Exits |
| **More Info** | A Log Analytics workspace is a unique environment for log data from Azure Monitor and other Azure services.Each workspace has its own data repository and configuration but might combine data from multiple services. |
| **AZURE Link** | https://learn.microsoft.com/en-us/azure/azure-monitor/logs/log-analytics-workspace-overview |
| **Recommended Action** | Ensure that Log Analytics Workspace exists in your azure account. |

## Detailed Remediation Steps

1. Log in to the Microsoft Azure Management Console.
2. Select the "Search resources, services, and docs" option at the top and search for "Log Analytics Workspace". </br> <img src="/resources/azure/monitor/nsg-log-analytics-enabled/step2.png"/>
3. On "Log Analytics Workspace" if there is no workspace exist then Click "create" from top navigation bar.</br> <img src="/resources/azure/monitor/nsg-log-analytics-enabled/step3.png"/>
4. On "Create Log Analytics Workspace" page select "Resource Group", enter workspace name and enter all the required information then Click "Next" button on the bottom of the page.</br> <img src="/resources/azure/monitor/nsg-log-analytics-enabled/step4.png"/>
5. Under the "Tags" tab enter the tags related to workspace and then "Click Review and Create" button on the bottom of the page.</br> <img src="/resources/azure/monitor/nsg-log-analytics-enabled/step5.png"/>
6. Review all the information then click on Create button on the bottom of the page.</br> <img src="/resources/azure/monitor/nsg-log-analytics-enabled/step6.png"/>
