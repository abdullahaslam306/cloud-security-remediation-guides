[![CloudSploit](https://cloudsploit.com/img/logo-new-big-text-100.png "CloudSploit")](https://cloudsploit.com)

# AWS / Redshift / Redshift Cluster Has Tags

## Quick Info

| | |
|-|-|
| **Plugin Title** | Redshift Cluster Has Tags |
| **Cloud** | AWS |
| **Category** | Redshift |
| **Description** | Ensures that Amazon Redshift clusters Has Tags. |
| **More Info** | Tags help you to group resources together that are related to or associated with each other. It is a best practice to tag cloud resources to better organize and gain visibility into their usage. |
| **AWS Link** | https://docs.aws.amazon.com/redshift/latest/mgmt/amazon-redshift-tagging.html |
| **Recommended Action** | Update Redshift cluster and add tags. |

## Detailed Remediation Steps
1. Log into the AWS Management Console.
2. Select the "Services" option and search for Redshift. </br> <img src="/resources/aws/redshift/redshift-cluster-has-tags/step2.png"/>
3. Scroll down the left navigation panel and choose "Clusters". </br> <img src="/resources/aws/redshift/redshift-cluster-has-tags/step3.png"/>
4. Select the "Cluster" that needs to be have tags.</br> <img src="/resources/aws/redshift/redshift-cluster-has-tags/step4.png"/>
5. Choose "Properties" tab from navigation panel at bottom of page and scroll down to tags section.</br><img src="/resources/aws/redshift/redshift-cluster-has-tags/step5.png"/>
6. On Tags section Click on Add tags. </br><img src="/resources/aws/redshift/redshift-cluster-has-tags/step6.png"/>
7. On "Manage Tags" page enter the key value for the tags and Click "Save Changes". </br><img src="/resources/aws/redshift/redshift-cluster-has-tags/step7.png"/>
