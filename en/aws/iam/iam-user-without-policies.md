[![CloudSploit](https://cloudsploit.com/img/logo-new-big-text-100.png "CloudSploit")](https://cloudsploit.com)

# AWS / IAM / IAM User Without Permissions

## Quick Info

| | |
|-|-|
| **Plugin Title** | IAM User Without Permissions |
| **Cloud** | AWS |
| **Category** | IAM |
| **Description** | Ensure that no IAM user exists without any permissions |
| **More Info** | IAM users are created to perform any Console, CLI or API based operations on AWS cloud accounts. They are associated with policies that grant them permissions to perform required operations. An IAM user without any permission is a security risk, it is recommended to either add required permissions or delete them to adhere to compliance standards. |
| **AWS Link** | https://docs.aws.amazon.com/IAM/latest/UserGuide/best-practices.html |
| **Recommended Action** | Modify IAM user and attach new permissions |

## Detailed Remediation Steps
1. Log in to the AWS Management Console.
2. Select the "Services" option and search for IAM. </br><img src="/resources/aws/iam/iam-user-without-policies/step2.png"/>
3. Scroll down the left navigation panel and select "Users" under "Access management".</br><img src="/resources/aws/iam/iam-user-without-policies/step3.png"/>
4. Click on the IAM User name that you want to inspect.</br><img src="/resources/aws/iam/iam-user-without-policies/step4.png"/>
5. Scroll down on the IAM user configuration page and click on the "Permissions" tab.</br><img src="/resources/aws/iam/iam-user-without-policies/step5.png"/>
6. Under Permission tab Click on "Add Permission". </br><img src="/resources/aws/iam/iam-user-without-policies/step6.png"/>
7. On Add permission page Select the option "Add User to Group" or "Copy permissions" or "Attach policies directly". Attach permissions/groups/policies
and Click "Next" on bottom of the page.</br><img src="/resources/aws/iam/iam-user-without-policies/step7.png"/>
8. Review the permissions and Click "Add Permissions".</br><img src="/resources/aws/iam/iam-user-without-policies/step8.png"/>
9. Repeat steps 4 – 8 for all IAM users.
