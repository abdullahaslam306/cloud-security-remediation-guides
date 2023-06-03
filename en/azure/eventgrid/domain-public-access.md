[![CloudSploit](https://cloudsploit.com/img/logo-new-big-text-100.png "CloudSploit")](https://cloudsploit.com)

# AZURE / Event Grid / Event Grid Domain Public Access

## Quick Info

| | |
|-|-|
| **Plugin Title** | Event Grid Domain Public Access |
| **Cloud** | AZURE |
| **Category** | Event Grid |
| **Description** | Ensures that Azure Event Grid domains are not publicly accessible. |
| **More Info** | By default, domains are accessible from internet as long as the request comes with valid authentication and authorization exposing sensitive information. By disabling public access, Event Grid domains can be configured to use private endpoint. |
| **AZURE Link** | https://learn.microsoft.com/en-us/azure/event-grid/configure-firewall |
| **Recommended Action** | Modify the affected domains and disable public network access |

## Detailed Remediation Steps
1. Log in to the Microsoft Azure Management Console.
2. Select the "Search resources, services, and docs" option at the top and search for "Event Grid Domains". </br> <img src="/resources/azure/eventgrid/domain-public-access/step2.png"/>
3. Select the "Event Grid Domains" by clicking on the "Name" link to access the configuration changes. </br> <img src="/resources/azure/eventgrid/domain-public-access/step3.png"/>
4. In the left navigation panel, click on "Networking" under the "Settings" section.</br> <img src="/resources/azure/eventgrid/domain-public-access/step4.png"/>
5. On the "Networking" page, under the "Public network access" tab, select "Private endpoints only" and click "Save" from navigation bar on top of the page.</br> <img src="/resources/azure/eventgrid/domain-public-access/step5.png"/>
