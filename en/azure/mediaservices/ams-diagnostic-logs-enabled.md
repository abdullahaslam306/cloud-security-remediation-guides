[![CloudSploit](https://cloudsploit.com/img/logo-new-big-text-100.png "CloudSploit")](https://cloudsploit.com)

# AZURE / Media Services / Media Services Diagnostic Logs Enabled

## Quick Info

| | |
|-|-|
| **Plugin Title** | Media Services Diagnostic Logs Enabled |
| **Cloud** | AZURE |
| **Category** | Media Services |
| **Description** | Ensures that Azure Media Services have diagnostic logs enabled |
| **More Info** | Diagnostic logs provide valuable insights into the operation and health of Media Services. By enabling diagnostic logs, you can gather diagnostic data that could be useful to create notification alerts. |
| **AZURE Link** | https://learn.microsoft.com/en-us/azure/media-services/latest/monitoring/monitor-media-services |
| **Recommended Action** | Modify Media Service settings and enable diagnostic logs. |

## Detailed Remediation Steps

1. Log into the Microsoft Azure Management Console.
2. Select the "Search resources, services, and docs" option at the top and search for Media Services. </br> <img src="/resources/azure/mediaservices/ams-diagnostic-logs-enabled/step2.png"/>
3. On the "Media Services" page, select the specific media service you want to enable Diagnostic logging for by clicking on its name.</br> <img src="/resources/azure/mediaservices/ams-diagnostic-logs-enabled/step3.png"/>
4. On the "Overview" page, navigate to the left-hand side navigation bar and click on "Diagnostic Settings" under the "Monitoring" section.</br> <img src="/resources/azure/mediaservices/ams-diagnostic-logs-enabled/step4.png"/>
5. On the "Diagnostic Settings" page, click the "Add diagnostic settings" button located under the settings table.</br> <img src="/resources/azure/mediaservices/ams-diagnostic-logs-enabled/step5.png"/>
6. In the "Create Diagnostic Setting" page, provide a setting name, select the desired log types, configure the destination for storing the logs, then click "Save" from the top navigation bar.</br> <img src="/resources/azure/mediaservices/ams-diagnostic-logs-enabled/step6.png"/>