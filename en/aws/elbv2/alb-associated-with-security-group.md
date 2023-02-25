[![CloudSploit](https://cloudsploit.com/img/logo-new-big-text-100.png "CloudSploit")](https://cloudsploit.com)

# AWS / ELB / ALB Associated With Security Group

## Quick Info

| | |
|-|-|
| **Plugin Title** | ALB Associated With Security Group |
| **Cloud** | AWS |
| **Category** | ELBv2 |
| **Description** | Ensure Application Load Balancers are associated with security group. |
| **More Info** | It is a security best practice to always have application load balancers associated with security groups to avoid any data loss or unauthorized access. |
| **AWS Link** | https://docs.aws.amazon.com/elasticloadbalancing/latest/application/load-balancer-update-security-groups.html |
| **Recommended Action** | Modify Application Load Balancer and Add Security Groups |

## Detailed Remediation Steps
1. Log into the AWS Management Console.
2. Select the "Services" option and search for EC2. </br> <img src="/resources/aws/elbv2/elbv2-has-tags/step2.png"/>
3. In the "EC2 Dashboard" scroll down and look for "Load Balancers" and click on "Load Balancers" to get into "Load Balancers" dashboard.</br> <img src="/resources/aws/elbv2/elbv2-has-tags/step3.png"/>
4. Select the "Load Balancer" which needs to have security group. </br> <img src="/resources/aws/elbv2/elbv2-has-tags/step4.png"/>
5. Select the "Security" tab from the bottom panel and Click on "Edit" button under security tab. </br> <img src="/resources/aws/elbv2/elbv2-has-tags/step5.png"/>
6. On "Edit Security group" page Select the security group from drop down menu or create new security group and Click "Save Changes".</br><img src="/resources/aws/elbv2/elbv2-has-tags/step6.png"/>
