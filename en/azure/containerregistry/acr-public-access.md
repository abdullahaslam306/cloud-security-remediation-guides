[![CloudSploit](https://cloudsploit.com/img/logo-new-big-text-100.png "CloudSploit")](https://cloudsploit.com)

# AZURE / Container Registry / ACR Public Access

## Quick Info

| | |
|-|-|
| **Plugin Title** | ACR Public Access |
| **Cloud** | AZURE |
| **Category** | Container Registry |
| **Description** | Ensures that the container registries are not publicly accessible |
| **More Info** | Azure Container Registries should be not be publicly accessible to prevent unauthorized actions. |
| **AZURE Link** | https://learn.microsoft.com/en-us/azure/container-registry/container-registry-access-selected-networks |
| **Recommended Action** | Ensure that the public network access is disabled for each container registry. |

## Detailed Remediation Steps

1. Login to the Microsoft Azure Management Console.
2. In the search bar at the top search for container registries and click on "Container registries".<br/> <img src="/resources/azure/containerregistry/acr-public-access/step2.png"/>
3. On the container registries page, click on the "Name" link to go to the configuration page.<br/> <img src="/resources/azure/containerregistry/acr-public-access/step3.png"/>
4. On the container registry pane that opens, click on "Networking" under "Settings" in the left navigation panel.<br/> <img src="/resources/azure/containerregistry/acr-public-access/step4.png"/>
5. On "Networking details" page under the "Public access" tabs ensure that Public network access is disabled. Select Disabled from Public network access and Click "Save" <br/> <img src="/resources/azure/containerregistry/acr-public-access/step5.png"/>

