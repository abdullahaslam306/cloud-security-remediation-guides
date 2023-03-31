[![CloudSploit](https://cloudsploit.com/img/logo-new-big-text-100.png "CloudSploit")](https://cloudsploit.com)

# AWS / ELBv2 / ELBv2 TLS Version and Cipher header Enabled

## Quick Info

| | |
|-|-|
| **Plugin Title** | ELBv2 TLS Version and Cipher header Enabled |
| **Cloud** | AWS |
| **Category** | ELBv2 |
| **Description** | Ensures thet AWS ELBv2 load balancers has TLS version and cipher headers enabled. |
| **More Info** | ELBv2 load balancers should be configured with TLS version and cipher headers as security complaince and best practice. |
| **AWS Link** | https://docs.aws.amazon.com/elasticloadbalancing/latest/application/application-load-balancers.html |
| **Recommended Action** | Update ELBv2 load balancer traffic configuration to enable TLS version and cipher headers |

## Detailed Remediation Steps
1. Log in to the AWS Management Console.
2. Select the "Services" option and search for EC2. </br> <img src="/resources/aws/elbv2/elbv2-tls-version-cipher-enabled/step2.png"/>
3. In the "EC2 Dashboard" scroll down and look for "Load Balancers" and click on "Load Balancers" to get into "Load Balancers" dashboard.</br> <img src="/resources/aws/elbv2/elbv2-tls-version-cipher-enabled/step3.png"/>
4. Select the "Load Balancer" which needs to be verified. </br> <img src="/resources/aws/elbv2/elbv2-tls-version-cipher-enabled/step4.png"/>
5. On the "Load Balancers" page, scroll down and check under the "Attributes" whether the "TLS version and cipher headers" is enabled or disabled.</br> <img src="/resources/aws/elbv2/elbv2-tls-version-cipher-enabled/step5.png"/>
6. Under the Attributes tab, Click on the Eidt button.</br> <img src="/resources/aws/elbv2/elbv2-tls-version-cipher-enabled/step6.png"/>
7. On the Edit Attributes page under the "Traffic configuration" section enable the TLS version and cipher headers and Click on "Save Changes".</br> <img src="/resources/aws/elbv2/elbv2-tls-version-cipher-enabled/step7.png"/>



