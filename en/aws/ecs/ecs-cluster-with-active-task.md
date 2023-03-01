[![CloudSploit](https://cloudsploit.com/img/logo-new-big-text-100.png "CloudSploit")](https://cloudsploit.com)

# AWS / ECS / ECS Cluster Service With Active Task

## Quick Info

| | |
|-|-|
| **Plugin Title** | ECS Cluster Service With Active Task |
| **Cloud** | AWS |
| **Category** | ECS |
| **Description** | Ensure ECS clusters have services with running tasks. |
| **More Info** | A task is the instantiation of a task definition within a cluster. Amazon ECS service instantiates and maintains the specified number of tasks simultaneously in a cluster. As a best practice, ensure you always have running tasks in a cluster.|
| **AWS Link** | https://docs.aws.amazon.com/AmazonECS/latest/developerguide/ecs_services.html |
| **Recommended Action** | Modify Cluster services and add tasks |

## Detailed Remediation Steps
1. Log into the AWS Management Console.
2. Select the "Services" option and search for ECS and choose "Elastic Container Service". </br> <img src="/resources/aws/ecs/ecs-cluster-active-service/step2.png"/>
3. In navigation pane select "Clusters".</br> <img src="/resources/aws/ecs/ecs-cluster-active-service/step3.png"/>
4. On Clusters page click on the cluster name for which you want to create service and task.  </br> <img src="/resources/aws/ecs/ecs-cluster-active-service/step4.png"/>
5. On Cluster Details page choose "Services" tab from navigation panel. Under "Services" tab click on "Create" button. </br> <img src="/resources/aws/ecs/ecs-cluster-active-service/step5.png"/>
6. On create Service page enter all the required information Select Application type "Service" under deployment configuration section to create a service and Click "Create".</br> <img src="/resources/aws/ecs/ecs-cluster-active-service/step6.png"/>
7. Then On Cluster Details page choose "Tasks" tab from navigation panel. Under "Tabs" tab click on "Run new task" button.</br> <img src="/resources/aws/ecs/ecs-cluster-active-service/step7.png"/>
8. On Run Task page enter all the required information Select Application type "Task" under deployment configuration section to create a task and Click "Create" from bottom of page.</br><img src="/resources/aws/ecs/ecs-cluster-active-service/step8.png"/>