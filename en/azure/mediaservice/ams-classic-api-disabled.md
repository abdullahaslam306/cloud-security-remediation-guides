[![CloudSploit](https://cloudsploit.com/img/logo-new-big-text-100.png "CloudSploit")](https://cloudsploit.com)

# AZURE / Media Services / Media Services Classic API Disabled

## Quick Info

| | |
|-|-|
| **Plugin Title** | Media Services Classic API Disabled |
| **Cloud** | AZURE |
| **Category** | Media Services |
| **Description** | Ensure that Microsoft Azure Media Services do not have the Classic API enabled |
| **More Info** | Disabling the Classic API for Azure Media Services is recommended to utilize modern APIs and features. Enabling classic features can enable the use of classic V2 APIs but might disable advanced security features like managed identities. |
| **AZURE Link** | https://learn.microsoft.com/en-us/azure/media-services/latest/migrate-v-2-v-3-differences-api-access |
| **Recommended Action** | Remove Azure Media Services accounts with Classic API enabled and create new accounts without enabling the Classic API. |

## Detailed Remediation Steps

1. Log into the Microsoft Azure Management Console.
2. Select the "Search resources, services, and docs" option at the top and search for Media Services. </br> <img src="/resources/azure/mediaservices/ams-classic-api-disabled/step2.png"/>
3. On the "Media Services" page, click on the media service account page to access it.</br> <img src="/resources/azure/mediaservices/ams-classic-api-disabled/step3.png"/>
4. On the "Overview" page, under the "Essential" section, check for the "V2 REST API endpoint" to confirm the presence of Classic APIs.</br> <img src="/resources/azure/mediaservices/ams-classic-api-disabled/step4.png"/>
5. If Classic APIs are present, click on the "Delete" button on the Overview page and enter the media service name to confirm deletion.</br> <img src="/resources/azure/mediaservices/ams-classic-api-disabled/step5.png"/>
6. Repeat steps 3 to 5 to check and delete other Media Service accounts, if necessary.
7. After deletion, return to the "Media Services" page and click on "Create".</br> <img src="/resources/azure/mediaservices/ams-classic-api-disabled/step2.png"/>
8. On the "Create media service account" page, input all required information without selecting the "Enable classic APIs" checkbox, then click "Review + Create".</br> <img src="/resources/azure/mediaservices/ams-classic-api-disabled/step8.png"/>
9. Review the provided details and click "Create" at the bottom of the page to create a new Media Service account with Classic APIs disabled.</br> <img src="/resources/azure/mediaservices/ams-classic-api-disabled/step9.png"/>
