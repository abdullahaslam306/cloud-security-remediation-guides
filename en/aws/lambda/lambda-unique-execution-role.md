[![CloudSploit](https://cloudsploit.com/img/logo-new-big-text-100.png "CloudSploit")](https://cloudsploit.com)

# AWS / Lambda / Lambda Unique Execution Role

## Quick Info

| | |
|-|-|
| **Plugin Title** | Lambda Unique Execution Role |
| **Cloud** | AWS |
| **Category** | Lambda |
| **Description** | Ensure that AWS Lambda functions do not share the same execution role. |
| **More Info** | An execution role grants required permission to Lambda function to access AWS services and resources. It is recommended to associate the unique IAM role for each Lambda function to follow the principle of least privilege access. |
| **AWS Link** | https://docs.aws.amazon.com/lambda/latest/dg/lambda-intro-execution-role.html |
| **Recommended Action** | Modify Lambda function and add new execution role. |

## Detailed Remediation Steps
1. Log into the AWS Management Console.
2. Select the "Services" option and search for Lambda. </br> <img src="/resources/aws/lambda/lambda-unique-execution-role/step2.png"/>
3. Scroll down the left navigation panel and choose "Functions".</br> <img src="/resources/aws/lambda/lambda-unique-execution-role/step3.png"/>
4. Select the Lambda function for whcich you need to change execution role.</br> <img src="/resources/aws/lambda/lambda-unique-execution-role/step4.png"/>
5. On the "Lambda Functions" page scroll down and choose "Configuration".</br> <img src="/resources/aws/lambda/lambda-unique-execution-role/step5.png"/>
6. Scroll down the "Configuration" tab and choose "Permissiona" tab and Click on Edit button under "Execution Role" section.</br> <img src="/resources/aws/lambda/lambda-unique-execution-role/step6.png"/>
7. On Edit Basic settings page scroll to the bottom of page under Execution Role Select "Create a new role from AWS policy templates".</br> <img src="/resources/aws/lambda/lambda-unique-execution-role/step7.png"/>
8. Enter the Role name and select policy template then click "Save".</br> <img src="/resources/aws/lambda/lambda-unique-execution-role/step8.png"/>
9. Repeat step number 4-8 to ensure tags on remaining Lambda functions.
