[![CloudSploit](https://cloudsploit.com/img/logo-new-big-text-100.png "CloudSploit")](https://cloudsploit.com)

# AZURE / Container Registry / ACR CMK Encryption Enabled

## Quick Info

| | |
|-|-|
| **Plugin Title** | ACR CMK Encryption Enabled |
| **Cloud** | AZURE |
| **Category** | Container Registry |
| **Description** | Ensure that Microsoft Azure Container registries have CMK Encryption Enabled. |
| **More Info** | A customer-managed key gives you the ownership to bring your own key in Azure Key Vault. When you enable a customer-managed key, you can manage its rotations, control the access and permissions to use it, and audit its use. |
| **AZURE Link** | https://learn.microsoft.com/en-us/azure/container-registry/tutorial-customer-managed-keys |
| **Recommended Action** | Create new container registry with Premium SKU and enable CMK encryption. |

## Detailed Remediation Steps

1. Login to the Microsoft Azure Management Console.
2. In the search bar at the top search for container registries and click on "Container registries".<br/> <img src="/resources/azure/containerregistry/acr-cmk-encryption/step2.png"/>
3. On the container registries page, click on the "Create" button from top navigation bar.<br/> <img src="/resources/azure/containerregistry/acr-cmk-encryption/step3.png"/>
4. On the Create Registry page under "Basic" tab enter registry name, select subscription and Select Premium SKU.<br/> <img src="/resources/azure/containerregistry/acr-cmk-encryption/step4.png"/>
5. Under the Encryption tab select "Enabled" for "Customer-Managed Key". Then enter required information and Click on Next at bottom of page.  <br/> <img src="/resources/azure/containerregistry/acr-cmk-encryption/step5.png"/>
6. Complete All steps and Click Create button on bottom of the page. <br/> <img src="/resources/azure/containerregistry/acr-cmk-encryption/step6.png"/>

