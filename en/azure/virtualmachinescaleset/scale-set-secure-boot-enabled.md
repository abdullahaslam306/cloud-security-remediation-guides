[![CloudSploit](https://cloudsploit.com/img/logo-new-big-text-100.png "CloudSploit")](https://cloudsploit.com)

# AZURE / Virtual Machine Scale Set / Scale Sets Secure Boot Enabled

## Quick Info

| | |
|-|-|
| **Plugin Title** | Scale Sets Secure Boot Enabled |
| **Cloud** | AZURE |
| **Category** | Virtual Machine Scale Set |
| **Description** | Ensures that secure boot is enabled for Virtual Machine Scale Sets |
| **More Info** | Secure Boot, which is implemented in platform firmware, protects against the installation of malware-based rootkits and boot kits. Secure Boot works to ensure that only signed operating systems and drivers can boot. It establishes a "root of trust" for the software stack on your VMSS. |
| **AZURE Link** | https://learn.microsoft.com/en-us/azure/virtual-machines/trusted-launch#secure-boot |
| **Recommended Action** | Modify virtual machine scale set configurations and enable secure boot. |

## Detailed Remediation Steps

1. Log in to the Microsoft Azure Management Console.
2. Select the "Search resources, services, and docs" option at the top and search for "Virtual Machine Scale Set". </br> <img src="/resources/azure/virtualmachinescaleset/scale-set-secure-boot-enabled/step2.png"/>
3. Select the "Scale Set" by clicking on the "Name" link to access the configuration changes. </br> <img src="/resources/azure/virtualmachinescaleset/scale-set-secure-boot-enabled/step3.png"/>
4. In the left navigation panel, click on the "Configurations" under "Settings".</br> <img src="/resources/azure/virtualmachinescaleset/scale-set-secure-boot-enabled/step4.png"/>
5. On Configurations page select "Enable Secure boot" checkbox under  "Security type" section and click "Apply" at the bottom of the page. </br> <img src="/resources/azure/virtualmachinescaleset/scale-set-secure-boot-enabled/step5.png"/>