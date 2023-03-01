[![CloudSploit](https://cloudsploit.com/img/logo-new-big-text-100.png "CloudSploit")](https://cloudsploit.com)

# AWS / ECS / ECS Cluster Active Service

## Quick Info

| | |
|-|-|
| **Plugin Title** | ECS Cluster Active Service |
| **Cloud** | AWS |
| **Category** | ECS |
| **Description** | Ensure that ECS Cluster have active services |
| **More Info** | Amazon ECS service allows you to run and maintain a specified number of instances of a task definition simultaneously in an Amazon ECS cluster. It is recommended to have clusters with the active services to avoid any container attack surface.|
| **AWS Link** | https://docs.aws.amazon.com/AmazonECS/latest/developerguide/ecs_services.html |
| **Recommended Action** | Modify Cluster and create new service |

## Detailed Remediation Steps
1. Log into the AWS Management Console.
2. Select the "Services" option and search for ECS and choose "Elastic Container Service". </br> <img src="/resources/aws/ecs/ecs-cluster-active-service/step2.png"/>
3. In navigation pane select "Clusters".</br> <img src="/resources/aws/ecs/ecs-cluster-active-service/step3.png"/>
4. On Clusters page click on the cluster name for which you want to create service.  </br> <img src="/resources/aws/ecs/ecs-cluster-active-service/step4.png"/>
5. On Cluster Details page choose "Services" tab from navigation panel. Under "Services" tab click on "Create" button. </br> <img src="/resources/aws/ecs/ecs-cluster-active-service/step5.png"/>
6. On create cluster page enter all the required information Select Application type "Service" under deployment configuration section and Click "Save".</br> <img src="/resources/aws/ecs/ecs-cluster-active-service/step6.png"/>
