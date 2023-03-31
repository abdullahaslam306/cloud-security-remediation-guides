[![CloudSploit](https://cloudsploit.com/img/logo-new-big-text-100.png "CloudSploit")](https://cloudsploit.com)

# AWS / DynamoDB / DynamoDB Unused Table

## Quick Info

| | |
|-|-|
| **Plugin Title** | DynamoDB Unused Table |
| **Cloud** | AWS |
| **Category** | DynamoDB |
| **Description** | Ensures that Amazon DynamoDB unused tables are removed. |
| **More Info** | A DynamoDB table is considered unused if its item count is zero. As a best practice, delete unused tables for operational efficiency and better resource management. This will also prevent resource wastage and unnecessary costs. |
| **AWS Link** | https://docs.aws.amazon.com/amazondynamodb/latest/developerguide/WorkingWithTables.Basics.html |
| **Recommended Action** | Identify unused tables and remove them |

## Detailed Remediation Steps 
1. Log into the AWS Management Console.
2. Select the "Services" option and search for "DynamoDB" and click on "DynamoDB".</br> <img src="/resources/aws/dynamodb-unused-table/step2.png"/>
3. On "DynamoDB Dashboard" page Click on "Tables" from left navigation panel.</br> <img src="/resources/aws/dynamodb-unused-table/step3.png"/>
4. Click on the name of the DynamoDB table that you want to examine.</br> <img src="/resources/aws/dynamodb-unused-table/step4.png"/>
5. Select the Overview tab to access the general configuration settings available for the selected table..</br> <img src="/resources/aws/dynamodb-unused-table/step5.png"/>
6. In the Items summary section, check the Item count parameter value. If the Item count parameter value is set to 0 (zero), the selected Amazon DynamoDB table is not in use anymore and can be safely removed from your AWS cloud account.</br> <img src="/resources/aws/dynamodb-unused-table/step6.png"/>
7. Click Action dropdown on top of the page and choose "Delete Table".</br> <img src="/resources/aws/dynamodb-unused-table/step7.png"/> 
8. On the popup enter confirm in the textbox and Click on Delete button.</br> <img src="/resources/aws/dynamodb-unused-table/step8.png"/> 


