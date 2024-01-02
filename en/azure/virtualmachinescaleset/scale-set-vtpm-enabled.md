[![CloudSploit](https://cloudsploit.com/img/logo-new-big-text-100.png "CloudSploit")](https://cloudsploit.com)

# AZURE / Virtual Machine Scale Set / Scale Sets vTPM Enabled

## Quick Info

| | |
|-|-|
| **Plugin Title** | Scale Sets vTPM Enabled |
| **Cloud** | AZURE |
| **Category** | Virtual Machine Scale Set |
| **Description** | Ensures that Virtual Trusted Platform Module (vTPM) is enabled for Virtual Machine Scale Sets |
| **More Info** | vTPM is TPM2.0 compliant and enhances security by validating VM boot integrity and providing a secure storage mechanism for keys and secrets. The vTPM enables attestation by measuring the entire boot chain of your VM (UEFI, OS, system, and drivers). |
| **AZURE Link** | https://learn.microsoft.com/en-us/windows/security/hardware-security/tpm/trusted-platform-module-overview |
| **Recommended Action** | Modify virtual machine scale set configurations and enable vTPM. |

## Detailed Remediation Steps

1. Log in to the Microsoft Azure Management Console.
2. Select the "Search resources, services, and docs" option at the top and search for "Virtual Machine Scale Set". </br> <img src="/resources/azure/virtualmachinescaleset/scale-set-vtpm-enabled/step2.png"/>
3. Select the "Scale Set" by clicking on the "Name" link to access the configuration changes. </br> <img src="/resources/azure/virtualmachinescaleset/scale-set-vtpm-enabled/step3.png"/>
4. In the left navigation panel, click on the "Configurations" under "Settings".</br> <img src="/resources/azure/virtualmachinescaleset/scale-set-vtpm-enabled/step4.png"/>
5. On Configurations page select "Enable vTPM" checkbox under  "Security type" section and click "Apply" at the bottom of the page. </br> <img src="/resources/azure/virtualmachinescaleset/scale-set-vtpm-enabled/step5.png"/>