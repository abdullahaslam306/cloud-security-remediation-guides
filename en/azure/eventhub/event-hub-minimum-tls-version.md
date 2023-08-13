[![CloudSploit](https://cloudsploit.com/img/logo-new-big-text-100.png "CloudSploit")](https://cloudsploit.com)

# AZURE / Container Registry / Event Hubs Minimum TLS Version

## Quick Info

| | |
|-|-|
| **Plugin Title** | Event Hubs Minimum TLS Version |
| **Cloud** | AZURE |
| **Category** | Event Hubs |
| **Description** | Ensures Microsoft Azure Event Hubs namespaces do not allow outdated TLS certificate versions |
| **More Info** | To enforce stricter security measures, you can configure your Event Hubs namespace to require that clients send and receive data with a newer version of TLS. |
| **AZURE Link** | https://learn.microsoft.com/en-us/azure/event-hubs/transport-layer-security-enforce-minimum-version |
| **Recommended Action** | Modify Event Hubs namespaces to set the desired minimum TLS version. |

## Detailed Remediation Steps

1. Login to the Microsoft Azure Management Console.
2. In the search bar at the top search for event hub and click on "Event Hub".<br/> <img src="/resources/azure/eventhub/event-hub-minimum-tls-version/step2.png"/>
3. On the event hub page, click on the "Name" link to go to the configuration page.<br/> <img src="/resources/azure/eventhub/event-hub-minimum-tls-version/step3.png"/>
4. On the event hub pane that opens, click on "Configuration" under "Settings" in the left navigation panel.<br/> <img src="/resources/azure/eventhub/event-hub-minimum-tls-version/step4.png"/>
5. On the configuration page under security select the "Minimum TLS version" from the dropdown and Click save at the bottom of the page.<br/> <img src="/resources/azure/eventhub/event-hub-minimum-tls-version/step5.png"/>
7. Repeat step 3 - 6 for all other event hub.


