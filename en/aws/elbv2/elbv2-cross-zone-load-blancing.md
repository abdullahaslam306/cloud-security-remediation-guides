[![CloudSploit](https://cloudsploit.com/img/logo-new-big-text-100.png "CloudSploit")](https://cloudsploit.com)

# AWS / ELBv2 / ELBv2 Cross-Zone Load Balancing

## Quick Info

| | |
|-|-|
| **Plugin Title** | ELBv2 Cross-Zone Load Balancing |
| **Cloud** | AWS |
| **Category** | ELBv2 |
| **Description** | Ensures that AWS ELBv2 have cross-zone load balancing enabled. |
| **More Info** | AWS ELBv2 should have cross-zone load balancing enabled to distribute the traffic evenly across the registered instances in all enabled Availability Zones. |
| **AWS Link** | https://docs.aws.amazon.com/elasticloadbalancing/latest/classic/enable-disable-crosszone-lb.html |
| **Recommended Action** | Update AWS ELBv2 to enable cross zone load balancing |

## Detailed Remediation Steps
1. Log in to the AWS Management Console.
2. Select the "Services" option and search for EC2. </br> <img src="/resources/aws/elbv2/elbv2-cross-zone-load-blancing/step2.png"/>
3. In the "EC2 Dashboard" scroll down and look for "Load Balancers" and click on "Load Balancers" to get into "Load Balancers" dashboard.</br> <img src="/resources/aws/elbv2/elbv2-cross-zone-load-blancing/step3.png"/>
4. Select the "Load Balancer" which needs to be verified. </br> <img src="/resources/aws/elbv2/elbv2-cross-zone-load-blancing/step4.png"/>
5. On the "Load Balancers" page, scroll down and check under the "Attributes" whether the "Cross-Zone load balancing" is enabled or disabled.</br> <img src="/resources/aws/elbv2/elbv2-cross-zone-load-blancing/step5.png"/>
6. Under the Attributes tab, Click on the Eidt button.</br> <img src="/resources/aws/elbv2/elbv2-cross-zone-load-blancing/step6.png"/>
7. On the Edit Attributes page under the "Target selection configuration" section enable the Cross-Zone load balancing and Click on "Save Changes".</br> <img src="/resources/aws/elbv2/elbv2-cross-zone-load-blancing/step7.png"/>



