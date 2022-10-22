[![CloudSploit](https://cloudsploit.com/img/logo-new-big-text-100.png "CloudSploit")](https://cloudsploit.com)

# AWS / EC2 / Internet Gateway Has Tags

## Quick Info

| | |
|-|-|
| **Plugin Title** | Internet Gateway Has Tags |
| **Cloud** | AWS |
| **Category** | EC2 |
| **Description** | Ensure that Internet Gateway have tags. |
| **More Info** | Tags help you to group resources together that are related to or associated with each other. It is a best practice to tag cloud resources to better organize and gain visibility into their usage. |
| **AWS Link** | https://docs.aws.amazon.com/AWSCloudFormation/latest/UserGuide/aws-resource-ec2-internetgateway.html |
| **Recommended Action** | Modify Internet Gateway and Add new tags. |

## Detailed Remediation Steps
1. Log into the AWS Management Console.
2. Select the "Services" option and search for VPC. </br> <img src="/resources/aws/ec2/internet-gateway-has-tags/step2.png"/>
3. Scroll down the left navigation panel and choose "Internet Gateway" under "Virtual Private Cloud". </br> <img src="/resources/aws/ec2/internet-gateway-has-tags/step3.png"/>
4. Select the "Internet Gatewat" for which you want to add Tags by Clicking on Name column. </br> <img src="/resources/aws/ec2/internet-gateway-has-tags/step4.png"/>
5. Scroll down the bottom under the "Tags" tab Click on  "Manage Tags" button. </br> <img src="/resources/aws/ec2/internet-gateway-has-tags/step5.png"/>
6. On "Manage Tags" page click on  "Add new tag" button enter the key-value for the tag and Click "Save". </br><img src="/resources/aws/ec2/internet-gateway-has-tags/step6.png"/>
