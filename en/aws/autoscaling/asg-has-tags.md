[![CloudSploit](https://cloudsploit.com/img/logo-new-big-text-100.png "CloudSploit")](https://cloudsploit.com)

# AWS / AutoScaling / ASG have tags

## Quick Info

| | |
|-|-|
| **Plugin Title** | ASG have tags |
| **Cloud** | AWS |
| **Category** | AutoScaling |
| **Description** | Ensure that Auto Scaling Groups have tags |
| **More Info** | Tags help you to group resources together that are related to or associated with each other. It is a best practice to tag cloud resources to better organize and gain visibility into their usage. |
| **AWS Link** | https://docs.aws.amazon.com/autoscaling/ec2/userguide/ec2-auto-scaling-tagging.html |
| **Recommended Action** | Modify the autoscaling group and add tags. |

## Detailed Remediation Steps
1. Log in to the AWS Management Console.
2. Select the "Services" option and search for EC2. </br> <img src="/resources/aws/autoscaling/asg-has-tags/step2.png"/>
3. In the EC2 Management console, scroll down and click on the "Auto Scaling groups" at the bottom.</br> <img src="/resources/aws/autoscaling/asg-has-tags/step3.png"/>
4. On the "Auto Scaling groups" page, select the auto scaling group for which you want to add tags.</br> <img src="/resources/aws/autoscaling/asg-has-tags/step4.png"/>
5. On the "Auto Scaling groups" page,  under the "Details" tab scroll down to "Tags" action and Click on "Manage Tags" button.</br> <img src="/resources/aws/autoscaling/asg-has-tags/step5.png"/>
6. On Edit page click on "Add Tag" button enter the key-value for tag and Click "Save".</br> <img src="/resources/aws/autoscaling/asg-has-tags/step6.png"/>
