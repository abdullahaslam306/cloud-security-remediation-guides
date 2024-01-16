[![CloudSploit](https://cloudsploit.com/img/logo-new-big-text-100.png "CloudSploit")](https://cloudsploit.com)

# AZURE / Virtual Machine Scale Set / Scale Sets Health Monitoring Enabled

## Quick Info

| | |
|-|-|
| **Plugin Title** | Scale Sets Health Monitoring Enabled |
| **Cloud** | AZURE |
| **Category** | Virtual Machine Scale Set |
| **Description** | Ensures that health monitoring is enabled for virtual machine scale sets |
| **More Info** | Scale set health monitoring feature reports on VM health from inside the scale set instance and can be configured to probe on an application endpoint and update the status of the application on that instance. That instance status is checked by Azure to determine whether an instance is eligible for upgrade operations. |
| **AZURE Link** | https://learn.microsoft.com/en-us/azure/virtual-machine-scale-sets/virtual-machine-scale-sets-health-extension |
| **Recommended Action** | Enable health monitoring for virtual machine scale sets. |

## Detailed Remediation Steps

1. Log in to the Microsoft Azure Management Console.
2. Select the "Search resources, services, and docs" option at the top and search for "Virtual Machine Scale Set". </br> <img src="/resources/azure/virtualmachinescaleset/scale-set-health-monitoring/step2.png"/>
3. Select the "Scale Set" by clicking on the "Name" link to access the configuration changes. </br> <img src="/resources/azure/virtualmachinescaleset/scale-set-health-monitoring/step3.png"/>
4. In the left navigation panel, click on the "Health and repair" under "Operations".</br> <img src="/resources/azure/virtualmachinescaleset/scale-set-health-monitoring/step4.png"/>
5. On Health and repair page select "Enable application health monitoring" checkbox under  "Health" section and click "Save" at the bottom of the page to enable health monitoring for scale set. </br> <img src="/resources/azure/virtualmachinescaleset/scale-set-health-monitoring/step5.png"/>