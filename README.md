[![CloudSploit](https://cloudsploit.com/img/logo-new-big-text-100.png "CloudSploit")](https://cloudsploit.com)

# CloudSploit Security Remediation Guides

CloudSploit's remediation guides are intended to be an open-source resource for improving cloud security. Many cloud IaaS providers like AWS, Azure, and Google Cloud have a shared responsibility model. They provide the physical and architectural security, along with tools to properly secure the services they offer, but it is up to the user to configure those settings properly.

## Background

This repository is an extension of CloudSploit's [open-source scanning engine](https://github.com/cloudsploit/scans). We first released the scanning engine in 2015, and this documentation repository is a natural follow up to that tool. The goal of these guides are to provide detailed steps on remediation common security issues in cloud services.

## Table of Contents

* AWS
    * ACM
        * [ACM Certificate Validation](en/aws/acm/acm-certificate-validation.md)
    * AutoScaling
        * [ASG Multiple AZ](en/aws/autoscaling/asg-multiple-az.md)
    * CloudFront
        * [CloudFront HTTPS Only](en/aws/cloudfront/cloudfront-https-only.md)
        * [CloudFront Logging Enabled](en/aws/cloudfront/cloudfront-logging-enabled.md)
        * [Insecure CloudFront Protocols](en/aws/cloudfront/insecure-cloudfront-protocols.md)
        * [Public S3 CloudFront Origin](en/aws/cloudfront/public-s3-cloudfront-origin.md)
        * [Secure CloudFront Origin](en/aws/cloudfront/secure-cloudfront-origin.md)
    * CloudTrail
        * [CloudTrail Bucket Access Logging](en/aws/cloudtrail/cloudtrail-bucket-access-logging.md)
        * [CloudTrail Bucket Delete Policy](en/aws/cloudtrail/cloudtrail-bucket-delete-policy.md)
        * [CloudTrail Bucket Private](en/aws/cloudtrail/cloudtrail-bucket-private.md)
        * [CloudTrail Enabled](en/aws/cloudtrail/cloudtrail-enabled.md)
        * [CloudTrail Encryption](en/aws/cloudtrail/cloudtrail-encryption.md)
        * [CloudTrail File Validation](en/aws/cloudtrail/cloudtrail-file-validation.md)
        * [CloudTrail To CloudWatch](en/aws/cloudtrail/cloudtrail-to-cloudwatch.md)
    * CloudWatchLogs
        * [CloudWatch Monitoring Metrics](en/aws/cloudwatchlogs/cloudwatch-monitoring-metrics.md)
    * ConfigService
        * [Config Service Enabled](en/aws/configservice/config-service-enabled.md)
    * EC2
        * [Cross VPC Public Private Communication](en/aws/ec2/cross-vpc-public-private-communication.md)
        * [Default Security Group](en/aws/ec2/default-security-group.md)
        * [Default VPC In Use](en/aws/ec2/default-vpc-in-use.md)
        * [Detect EC2 Classic Instances](en/aws/ec2/detect-ec2-classic-instances.md)
        * [EBS Encrypted Snapshots](en/aws/ec2/ebs-encrypted-snapshots.md)
        * [EBS Encryption Enabled](en/aws/ec2/ebs-encryption-enabled.md)
        * [EC2 Instance Key Based Login](en/aws/ec2/ec2-instance-key-based-login.md)
        * [EC2 Max Instances](en/aws/ec2/ec2-max-instances.md)
        * [Elastic IP Limit](en/aws/ec2/elastic-ip-limit.md)
        * [Encrypted AMI](en/aws/ec2/encrypted-ami.md)
        * [Excessive Security Groups](en/aws/ec2/excessive-security-groups.md)
        * [Instance IAM Role](en/aws/ec2/instance-iam-role.md)
        * [Instance Limit](en/aws/ec2/instance-limit.md)
        * [NAT Multiple AZ](en/aws/ec2/nat-multiple-az.md)
        * [Network Acl Has Tags](en/aws/ec2/network-acl-has-tags.md)
        * [Open All Ports Protocols](en/aws/ec2/open-all-ports-protocols.md)
        * [Open CIFS](en/aws/ec2/open-cifs.md)
        * [Open DNS](en/aws/ec2/open-dns.md)
        * [Open Elasticsearch](en/aws/ec2/open-elasticsearch.md)
        * [Open FTP](en/aws/ec2/open-ftp.md)
        * [Open MySQL](en/aws/ec2/open-mysql.md)
        * [Open NetBIOS](en/aws/ec2/open-netbios.md)
        * [Open Oracle](en/aws/ec2/open-oracle.md)
        * [Open PostgreSQL](en/aws/ec2/open-postgresql.md)
        * [Open RDP](en/aws/ec2/open-rdp.md)
        * [Open RPC](en/aws/ec2/open-rpc.md)
        * [Open SMBoTCP](en/aws/ec2/open-smbotcp.md)
        * [Open SMTP](en/aws/ec2/open-smtp.md)
        * [Open SQL Server](en/aws/ec2/open-sql-server.md)
        * [Open SSH](en/aws/ec2/open-ssh.md)
        * [Open Telnet](en/aws/ec2/open-telnet.md)
        * [Open VNC Client](en/aws/ec2/open-vnc-client.md)
        * [Open VNC Server](en/aws/ec2/open-vnc-server.md)
        * [Overlapping Security Groups](en/aws/ec2/overlapping-security-groups.md)
        * [Public AMI](en/aws/ec2/public-ami.md)
        * [Subnet IP Availability](en/aws/ec2/subnet-ip-availability.md)
        * [VPC Elastic IP Limit](en/aws/ec2/vpc-elastic-ip-limit.md)
        * [VPC Flow Logs Enabled](en/aws/ec2/vpc-flow-logs-enabled.md)
        * [VPC Multiple Subnets](en/aws/ec2/vpc-multiple-subnets.md)
    * ELB
        * [ELB HTTPS Only](en/aws/elb/elb-https-only.md)
        * [ELB Logging Enabled](en/aws/elb/elb-logging-enabled.md)
        * [ELB No Instances](en/aws/elb/elb-no-instances.md)
        * [Insecure Ciphers](en/aws/elb/insecure-ciphers.md)
    * Firehose
        * [Firehose Delivery Streams Encrypted](en/aws/firehose/firehose-delivery-streams-encrypted.md)
    * IAM
        * [Access Keys Extra](en/aws/iam/access-keys-extra.md)
        * [Access Keys Last Used](en/aws/iam/access-keys-last-used.md)
        * [Access Keys Rotated](en/aws/iam/access-keys-rotated.md)
        * [Certificate Expiry](en/aws/iam/certificate-expiry.md)
        * [Empty Groups](en/aws/iam/empty-groups.md)
        * [IAM User Admins](en/aws/iam/iam-user-admins.md)
        * [Maximum Password Age](en/aws/iam/maximum-password-age.md)
        * [Minimum Password Length](en/aws/iam/minimum-password-length.md)
        * [No User IAM Policies](en/aws/iam/no-user-iam-policies.md)
        * [Password Expiration](en/aws/iam/password-expiration.md)
        * [Password Requires Lowercase](en/aws/iam/password-requires-lowercase.md)
        * [Password Requires Numbers](en/aws/iam/password-requires-numbers.md)
        * [Password Requires Symbols](en/aws/iam/password-requires-symbols.md)
        * [Password Requires Uppercase](en/aws/iam/password-requires-uppercase.md)
        * [Password Reuse Prevention](en/aws/iam/password-reuse-prevention.md)
        * [Root Access Keys](en/aws/iam/root-access-keys.md)
        * [Root Account In Use](en/aws/iam/root-account-in-use.md)
        * [Root MFA Enabled](en/aws/iam/root-mfa-enabled.md)
        * [SSH Keys Rotated](en/aws/iam/ssh-keys-rotated.md)
        * [Users MFA Enabled](en/aws/iam/users-mfa-enabled.md)
        * [Users Password Last Used](en/aws/iam/users-password-last-used.md)
    * KMS
        * [KMS Default Key Usage](en/aws/kms/kms-default-key-usage.md)
        * [KMS Key Policy](en/aws/kms/kms-key-policy.md)
        * [KMS Key Rotation](en/aws/kms/kms-key-rotation.md)
        * [KMS Scheduled Deletion](en/aws/kms/kms-scheduled-deletion.md)
    * Kinesis
        * [Kinesis Streams Encrypted](en/aws/kinesis/kinesis-streams-encrypted.md)
    * Lambda
        * [Lambda Old Runtimes](en/aws/lambda/lambda-old-runtimes.md)
    * RDS
        * [RDS Automated Backups](en/aws/rds/rds-automated-backups.md)
        * [RDS Encryption Enabled](en/aws/rds/rds-encryption-enabled.md)
        * [RDS Multiple AZ](en/aws/rds/rds-multiple-az.md)
        * [RDS Publicly Accessible](en/aws/rds/rds-publicly-accessible.md)
        * [RDS Restorable](en/aws/rds/rds-restorable.md)
    * Redshift
        * [Redshift Encryption Enabled](en/aws/redshift/redshift-encryption-enabled.md)
        * [Redshift Publicly Accessible](en/aws/redshift/redshift-publicly-accessible.md)
    * Route53
        * [Domain Auto Renew](en/aws/route53/domain-auto-renew.md)
        * [Domain Expiry](en/aws/route53/domain-expiry.md)
        * [Domain Transfer Lock](en/aws/route53/domain-transfer-lock.md)
    * S3
        * [S3 Bucket All Users ACL](en/aws/s3/s3-bucket-all-users-acl.md)
        * [S3 Bucket All Users Policy](en/aws/s3/s3-bucket-all-users-policy.md)
        * [S3 Bucket Logging](en/aws/s3/s3-bucket-logging.md)
        * [S3 Bucket Versioning](en/aws/s3/s3-bucket-versioning.md)
    * SES
        * [Email DKIM Enabled](en/aws/ses/email-dkim-enabled.md)
    * SNS
        * [SNS Topic Policies](en/aws/sns/sns-topic-policies.md)
    * SQS
        * [SQS Cross Account Access](en/aws/sqs/sqs-cross-account-access.md)
        * [SQS Encrypted](en/aws/sqs/sqs-encrypted.md)
    * SSM
        * [SSM Encrypted Parameters](en/aws/ssm/ssm-encrypted-parameters.md)
    * SageMaker
        * [Notebook Data Encrypted](en/aws/sagemaker/notebook-data-encrypted.md)
        * [Notebook Direct Internet Access](en/aws/sagemaker/notebook-direct-internet-access.md)
* Azure
    * Active Directory
        * [Ensure No Guest User](en/azure/activedirectory/ensure-no-guest-user.md)
        * [Minimum Password Length](en/azure/activedirectory/minimum-password-length.md)
        * [No Custom Owner Roles](en/azure/activedirectory/no-custom-owner-roles.md)
        * [Password Requires Lowercase](en/azure/activedirectory/password-requires-lowercase.md)
        * [Password Requires Numbers](en/azure/activedirectory/password-requires-numbers.md)
        * [Password Requires Symbols](en/azure/activedirectory/password-requires-symbols.md)
        * [Password Requires Uppercase](en/azure/activedirectory/password-requires-uppercase.md)
        * [Azure AD App Organisational Directory Access](en/azure/activedirectory/app-orgnaizational-directory-access.md)
    * App Service
        * [.NET Framework Version](en/azure/appservice/.net-framework-version.md)
        * [Authentication Enabled](en/azure/appservice/authentication-enabled.md)
        * [Client Certificates Enabled](en/azure/appservice/client-certificates-enabled.md)
        * [HTTP 2.0 Enabled](en/azure/appservice/http-2.0-enabled.md)
        * [HTTPS Only Enabled](en/azure/appservice/https-only-enabled.md)
        * [Identity Enabled](en/azure/appservice/identity-enabled.md)
        * [Java Version](en/azure/appservice/java-version.md)
        * [PHP Version](en/azure/appservice/php-version.md)
        * [Python Version](en/azure/appservice/python-version.md)
        * [TLS Version Check](en/azure/appservice/tls-version-check.md)
    * Azure Policy
        * [Resource Location Matches Resource Group](en/azure/azurepolicy/resource-location-matches-resource-group.md)
        * [Resources Allowed Locations](en/azure/azurepolicy/resources-allowed-locations.md)
    * Blob Service
        * [Blob Container Private Access](en/azure/blobservice/blob-container-private-access.md)
        * [Blob Service Immutable](en/azure/blobservice/blob-service-immutable.md)
    * CDN Profiles
        * [Detect Insecure Custom Origin](en/azure/cdnprofiles/detect-insecure-custom-origin.md)
        * [Endpoint Logging Enabled](en/azure/cdnprofiles/endpoint-logging-enabled.md)
    * Container Registry
        * [ACR Admin User](en/azure/containerregistry/acr-admin-user.md)
    * File Service
        * [File Service All Access ACL](en/azure/fileservice/file-service-all-access-acl.md)
    * Key Vaults
        * [Key Expiration Enabled](en/azure/keyvaults/key-expiration-enabled.md)
        * [Key Vault Recovery Enabled](en/azure/keyvaults/key-vault-recovery-enabled.md)
        * [Secret Expiration Enabled](en/azure/keyvaults/secret-expiration-enabled.md)
    * Kubernetes Service
        * [Kubernetes Latest Version](en/azure/kubernetesservice/kubernetes-latest-version.md)
        * [Kubernetes RBAC Enabled](en/azure/kubernetesservice/kubernetes-rbac-enabled.md)
    * Load Balancer
        * [LB HTTPS Only](en/azure/loadbalancer/lb-https-only.md)
        * [LB No Instances](en/azure/loadbalancer/lb-no-instances.md)
    * Log Alerts
        * [Network Security Groups Logging Enabled](en/azure/logalerts/network-security-groups-logging-enabled.md)
        * [Network Security Groups Rule Logging Enabled](en/azure/logalerts/network-security-groups-rule-logging-enabled.md)
        * [Policy Assignment Alerts Enabled](en/azure/logalerts/policy-assignment-alerts-enabled.md)
        * [SQL Server Firewall Rule Alerts Monitor](en/azure/logalerts/sql-server-firewall-rule-alerts-monitor.md)
        * [Security Policy Alerts Enabled](en/azure/logalerts/security-policy-alerts-enabled.md)
        * [Security Solution Logging](en/azure/logalerts/security-solution-logging.md)
        * [Virtual Network Alerts Monitor](en/azure/logalerts/virtual-network-alerts-monitor.md)
    * Monitor
        * [Key Vault Log Analytics Enabled](en/azure/monitor/key-vault-log-analytics-enabled.md)
        * [Load Balancer Log Analytics Enabled](en/azure/monitor/load-balancer-log-analytics-enabled.md)
        * [Log Profile Archive Data](en/azure/monitor/log-profile-archive-data.md)
        * [Log Profile Retention Policy](en/azure/monitor/log-profile-retention-policy.md)
        * [NSG Log Analytics Enabled](en/azure/monitor/nsg-log-analytics-enabled.md)
    * MySQL Server
        * [Enforce MySQL SSL Connection](en/azure/mysqlserver/enforce-mysql-ssl-connection.md)
    * Network Security Groups
        * [Default Security Group](en/azure/networksecuritygroups/default-security-group.md)
        * [Excessive Security Groups](en/azure/networksecuritygroups/excessive-security-groups.md)
        * [Network Watcher Enabled](en/azure/networksecuritygroups/network-watcher-enabled.md)
        * [Open All Ports](en/azure/networksecuritygroups/open-all-ports.md)
        * [Open CIFS](en/azure/networksecuritygroups/open-cifs.md)
        * [Open DNS](en/azure/networksecuritygroups/open-dns.md)
        * [Open FTP](en/azure/networksecuritygroups/open-ftp.md)
        * [Open Hadoop HDFS NameNode Metadata Service](en/azure/networksecuritygroups/open-hadoop-hdfs-namenode-metadata-service.md)
        * [Open Hadoop HDFS NameNode WebUI](en/azure/networksecuritygroups/open-hadoop-hdfs-namenode-webui.md)
        * [Open Kibana](en/azure/networksecuritygroups/open-kibana.md)
        * [Open MySQL](en/azure/networksecuritygroups/open-mysql.md)
        * [Open NetBIOS](en/azure/networksecuritygroups/open-netbios.md)
        * [Open Oracle](en/azure/networksecuritygroups/open-oracle.md)
        * [Open Oracle Auto Data Warehouse](en/azure/networksecuritygroups/open-oracle-auto-data-warehouse.md)
        * [Open PostgreSQL](en/azure/networksecuritygroups/open-postgresql.md)
        * [Open RDP](en/azure/networksecuritygroups/open-rdp.md)
        * [Open RPC](en/azure/networksecuritygroups/open-rpc.md)
        * [Open SMBoTCP](en/azure/networksecuritygroups/open-smbotcp.md)
        * [Open SMTP](en/azure/networksecuritygroups/open-smtp.md)
        * [Open SQLServer](en/azure/networksecuritygroups/open-sqlserver.md)
        * [Open SSH](en/azure/networksecuritygroups/open-ssh.md)
        * [Open Telnet](en/azure/networksecuritygroups/open-telnet.md)
        * [Open VNC Client](en/azure/networksecuritygroups/open-vnc-client.md)
        * [Open VNC Server](en/azure/networksecuritygroups/open-vnc-server.md)
    * PostgreSQL Server
        * [Connection Throttling Enabled](en/azure/postgresqlserver/connection-throttling-enabled.md)
        * [Enforce PostgreSQL SSL Connection](en/azure/postgresqlserver/enforce-postgresql-ssl-connection.md)
        * [Log Checkpoints Enabled](en/azure/postgresqlserver/log-checkpoints-enabled.md)
        * [Log Connections Enabled](en/azure/postgresqlserver/log-connections-enabled.md)
        * [Log Disconnections Enabled](en/azure/postgresqlserver/log-disconnections-enabled.md)
        * [Log Duration Enabled](en/azure/postgresqlserver/log-duration-enabled.md)
        * [Log Retention Period](en/azure/postgresqlserver/log-retention-period.md)
    * Queue Service
        * [Queue Service All Access ACL](en/azure/queueservice/queue-service-all-access-acl.md)
    * Resources
        * [Management Lock Enabled](en/azure/resources/management-lock-enabled.md)
        * [Resources Usage Limits](en/azure/resources/resources-usage-limits.md)
    * SQL Databases
        * [DB Restorable](en/azure/sqldatabases/db-restorable.md)
        * [Database Auditing Enabled](en/azure/sqldatabases/database-auditing-enabled.md)
        * [SQL DB Multiple AZ](en/azure/sqldatabases/sql-db-multiple-az.md)
    * SQL Server
        * [Advanced Data Security Enabled](en/azure/sqlserver/advanced-data-security-enabled.md)
        * [Audit Action Groups Enabled](en/azure/sqlserver/audit-action-groups-enabled.md)
        * [Audit Retention Policy](en/azure/sqlserver/audit-retention-policy.md)
        * [Azure Active Directory Admin Enabled](en/azure/sqlserver/azure-active-directory-admin-enabled.md)
        * [Email Account Admins Enabled](en/azure/sqlserver/email-account-admins-enabled.md)
        * [SQL Server Public Access](en/azure/sqlserver/sql-server-public-access.md)
        * [Send Alerts Enabled](en/azure/sqlserver/send-alerts-enabled.md)
        * [Server Auditing Enabled](en/azure/sqlserver/server-auditing-enabled.md)
        * [TDE Protector Encrypted](en/azure/sqlserver/tde-protector-encrypted.md)
    * Security Center
        * [Admin Security Alerts Enabled](en/azure/securitycenter/admin-security-alerts-enabled.md)
        * [Application Whitelisting Enabled](en/azure/securitycenter/application-whitelisting-enabled.md)
        * [Auto Provisioning Enabled](en/azure/securitycenter/auto-provisioning-enabled.md)
        * [High Severity Alerts Enabled](en/azure/securitycenter/high-severity-alerts-enabled.md)
        * [Monitor Blob Encryption](en/azure/securitycenter/monitor-blob-encryption.md)
        * [Monitor Disk Encryption](en/azure/securitycenter/monitor-disk-encryption.md)
        * [Monitor Endpoint Protection](en/azure/securitycenter/monitor-endpoint-protection.md)
        * [Monitor JIT Network Access](en/azure/securitycenter/monitor-jit-network-access.md)
        * [Monitor NSG Enabled](en/azure/securitycenter/monitor-nsg-enabled.md)
        * [Monitor SQL Auditing](en/azure/securitycenter/monitor-sql-auditing.md)
        * [Monitor SQL Encryption](en/azure/securitycenter/monitor-sql-encryption.md)
        * [Monitor System Updates](en/azure/securitycenter/monitor-system-updates.md)
        * [Monitor VM Vulnerability](en/azure/securitycenter/monitor-vm-vulnerability.md)
        * [Security Configuration Monitoring](en/azure/securitycenter/security-configuration-monitoring.md)
        * [Security Contacts Enabled](en/azure/securitycenter/security-contacts-enabled.md)
        * [Standard Pricing Enabled](en/azure/securitycenter/standard-pricing-enabled.md)
    * Storage Accounts
        * [Blob Service Encryption](en/azure/storageaccounts/blob-service-encryption.md)
        * [File Service Encryption](en/azure/storageaccounts/file-service-encryption.md)
        * [Log Container Public Access](en/azure/storageaccounts/log-container-public-access.md)
        * [Log Storage Encryption](en/azure/storageaccounts/log-storage-encryption.md)
        * [Network Access Default Action](en/azure/storageaccounts/network-access-default-action.md)
        * [Storage Accounts AAD Enabled](en/azure/storageaccounts/storage-accounts-aad-enabled.md)
        * [Storage Accounts Encryption](en/azure/storageaccounts/storage-accounts-encryption.md)
        * [Storage Accounts HTTPS](en/azure/storageaccounts/storage-accounts-https.md)
        * [Trusted MS Access Enabled](en/azure/storageaccounts/trusted-ms-access-enabled.md)
    * Table Service
        * [Table Service All Access ACL](en/azure/tableservice/table-service-all-access-acl.md)
    * Virtual Machines
        * [Classic Instances](en/azure/virtualmachines/classic-instances.md)
        * [Scale Set Multi Az](en/azure/virtualmachines/scale-set-multi-az.md)
        * [Scale Sets Autoscale Enabled](en/azure/virtualmachines/scale-sets-autoscale-enabled.md)
        * [VM Agent Enabled](en/azure/virtualmachines/vm-agent-enabled.md)
        * [VM Auto Update Enabled](en/azure/virtualmachines/vm-auto-update-enabled.md)
        * [VM Availability Set Enabled](en/azure/virtualmachines/vm-availability-set-enabled.md)
        * [VM Availability Set Limit](en/azure/virtualmachines/vm-availability-set-limit.md)
        * [VM Data Disk Encryption](en/azure/virtualmachines/vm-data-disk-encryption.md)
        * [VM Endpoint Protection](en/azure/virtualmachines/vm-endpoint-protection.md)
        * [VM Instance Limit](en/azure/virtualmachines/vm-instance-limit.md)
        * [VM OS Disk Encryption](en/azure/virtualmachines/vm-os-disk-encryption.md)
    * Virtual Networks
        * [Multiple Subnets](en/azure/virtualnetworks/multiple-subnets.md)
* Google
    * CLB
        * [CLB CDN Enabled](en/google/clb/clb-cdn-enabled.md)
        * [CLB HTTPS Only](en/google/clb/clb-https-only.md)
        * [CLB No Instances](en/google/clb/clb-no-instances.md)
        * [Security Policy Enabled](en/google/clb/security-policy-enabled.md)
    * Compute
        * [Autoscale Enabled](en/google/compute/autoscale-enabled.md)
        * [CSEK Encryption Enabled](en/google/compute/csek-encryption-enabled.md)
        * [Connect Serial Ports Disabled](en/google/compute/connect-serial-ports-disabled.md)
        * [IP Forwarding Disabled](en/google/compute/ip-forwarding-disabled.md)
        * [Instance Level SSH Only](en/google/compute/instance-level-ssh-only.md)
        * [Instances Multi AZ](en/google/compute/instances-multi-az.md)
        * [OS Login Enabled](en/google/compute/os-login-enabled.md)
        * [VM Instances Least Privilege](en/google/compute/vm-instances-least-privilege.md)
        * [VM Max Instances](en/google/compute/vm-max-instances.md)
    * Cryptographic Keys
        * [Key Rotation](en/google/cryptographickeys/key-rotation.md)
    * DNS
        * [DNS Security Enabled](en/google/dns/dns-security-enabled.md)
        * [DNS Security Signing Algorithm](en/google/dns/dns-security-signing-algorithm.md)
    * IAM
        * [Corporate Emails Only](en/google/iam/corporate-emails-only.md)
        * [KMS User Separation](en/google/iam/kms-user-separation.md)
        * [Service Account Admin](en/google/iam/service-account-admin.md)
        * [Service Account Key Rotation](en/google/iam/service-account-key-rotation.md)
        * [Service Account Managed Keys](en/google/iam/service-account-managed-keys.md)
        * [Service Account Separation](en/google/iam/service-account-separation.md)
        * [Service Account User](en/google/iam/service-account-user.md)
        * [Service Limits](en/google/iam/service-limits.md)
    * Kubernetes
        * [Alias IP Ranges Enabled](en/google/kubernetes/alias-ip-ranges-enabled.md)
        * [Automatic Node Repair Enabled](en/google/kubernetes/automatic-node-repair-enabled.md)
        * [Automatic Node Upgrades Enabled](en/google/kubernetes/automatic-node-upgrades-enabled.md)
        * [Basic Authentication Disabled](en/google/kubernetes/basic-authentication-disabled.md)
        * [COS Image Enabled](en/google/kubernetes/cos-image-enabled.md)
        * [Cluster Labels Added](en/google/kubernetes/cluster-labels-added.md)
        * [Cluster Least Privilege](en/google/kubernetes/cluster-least-privilege.md)
        * [Default Service Account](en/google/kubernetes/default-service-account.md)
        * [Legacy Authorization Disabled](en/google/kubernetes/legacy-authorization-disabled.md)
        * [Logging Enabled](en/google/kubernetes/logging-enabled.md)
        * [Master Authorized Network](en/google/kubernetes/master-authorized-network.md)
        * [Monitoring Enabled](en/google/kubernetes/monitoring-enabled.md)
        * [Network Policy Enabled](en/google/kubernetes/network-policy-enabled.md)
        * [Pod Security Policy Enabled](en/google/kubernetes/pod-security-policy-enabled.md)
        * [Private Cluster Enabled](en/google/kubernetes/private-cluster-enabled.md)
        * [Private Endpoint](en/google/kubernetes/private-endpoint.md)
        * [Web Dashboard Disabled](en/google/kubernetes/web-dashboard-disabled.md)
    * Logging
        * [Audit Configuration Logging](en/google/logging/audit-configuration-logging.md)
        * [Audit Logging Enabled](en/google/logging/audit-logging-enabled.md)
        * [Custom Role Logging](en/google/logging/custom-role-logging.md)
        * [Log Sinks Enabled](en/google/logging/log-sinks-enabled.md)
        * [Project Ownership Logging](en/google/logging/project-ownership-logging.md)
        * [SQL Configuration Logging](en/google/logging/sql-configuration-logging.md)
        * [Storage Permissions Logging](en/google/logging/storage-permissions-logging.md)
        * [VPC Firewall Rule Logging](en/google/logging/vpc-firewall-rule-logging.md)
        * [VPC Network Logging](en/google/logging/vpc-network-logging.md)
        * [VPC Network Route Logging](en/google/logging/vpc-network-route-logging.md)
    * SQL
        * [Any Host Root Access](en/google/sql/any-host-root-access.md)
        * [DB Automated Backups](en/google/sql/db-automated-backups.md)
        * [DB Multiple AZ](en/google/sql/db-multiple-az.md)
        * [DB Publicly Accessible](en/google/sql/db-publicly-accessible.md)
        * [DB Restorable](en/google/sql/db-restorable.md)
        * [Database SSL Enabled](en/google/sql/database-ssl-enabled.md)
    * Storage
        * [Bucket Logging](en/google/storage/bucket-logging.md)
        * [Bucket Versioning](en/google/storage/bucket-versioning.md)
        * [Storage Bucket All Users Policy](en/google/storage/storage-bucket-all-users-policy.md)
    * VPC Network
        * [Default VPC In Use](en/google/vpcnetwork/default-vpc-in-use.md)
        * [Excessive Firewall Rules](en/google/vpcnetwork/excessive-firewall-rules.md)
        * [Flow Logs Enabled](en/google/vpcnetwork/flow-logs-enabled.md)
        * [Multiple Subnets](en/google/vpcnetwork/multiple-subnets.md)
        * [Open All Ports](en/google/vpcnetwork/open-all-ports.md)
        * [Open CIFS](en/google/vpcnetwork/open-cifs.md)
        * [Open DNS](en/google/vpcnetwork/open-dns.md)
        * [Open FTP](en/google/vpcnetwork/open-ftp.md)
        * [Open Hadoop HDFS NameNode Metadata Service](en/google/vpcnetwork/open-hadoop-hdfs-namenode-metadata-service.md)
        * [Open Hadoop HDFS NameNode WebUI](en/google/vpcnetwork/open-hadoop-hdfs-namenode-webui.md)
        * [Open Kibana](en/google/vpcnetwork/open-kibana.md)
        * [Open MySQL](en/google/vpcnetwork/open-mysql.md)
        * [Open NetBIOS](en/google/vpcnetwork/open-netbios.md)
        * [Open Oracle](en/google/vpcnetwork/open-oracle.md)
        * [Open Oracle Auto Data Warehouse](en/google/vpcnetwork/open-oracle-auto-data-warehouse.md)
        * [Open PostgreSQL](en/google/vpcnetwork/open-postgresql.md)
        * [Open RDP](en/google/vpcnetwork/open-rdp.md)
        * [Open RPC](en/google/vpcnetwork/open-rpc.md)
        * [Open SMBoTCP](en/google/vpcnetwork/open-smbotcp.md)
        * [Open SMTP](en/google/vpcnetwork/open-smtp.md)
        * [Open SQLServer](en/google/vpcnetwork/open-sqlserver.md)
        * [Open SSH](en/google/vpcnetwork/open-ssh.md)
        * [Open Telnet](en/google/vpcnetwork/open-telnet.md)
        * [Open VNC Client](en/google/vpcnetwork/open-vnc-client.md)
        * [Open VNC Server](en/google/vpcnetwork/open-vnc-server.md)
        * [Private Access Enabled](en/google/vpcnetwork/private-access-enabled.md)
* GitHub
    * Orgs
        * [Org Default Permission](en/github/orgs/org-default-permission.md)
        * [Org Excessive Owners](en/github/orgs/org-excessive-owners.md)
        * [Org MFA Required](en/github/orgs/org-mfa-required.md)
        * [Org Plan Limit](en/github/orgs/org-plan-limit.md)
    * Repos
        * [Repo Deploy Keys Rotated](en/github/repos/repo-deploy-keys-rotated.md)
        * [Repo Outside Collaborators](en/github/repos/repo-outside-collaborators.md)
    * Users
        * [GPG Keys Rotated](en/github/users/gpg-keys-rotated.md)
        * [Public Keys Rotated](en/github/users/public-keys-rotated.md)
        * [User MFA Enabled](en/github/users/user-mfa-enabled.md)
        * [User Private Emails](en/github/users/user-private-emails.md)
* Oracle
    * Audit
        * [Log Retention Period](en/oracle/audit/log-retention-period.md)
    * Block Storage
        * [Block Storage Policy Protection](en/oracle/blockstorage/block-storage-policy-protection.md)
        * [Block Volume Backup Enabled](en/oracle/blockstorage/block-volume-backup-enabled.md)
        * [Block Volume Restorable](en/oracle/blockstorage/block-volume-restorable.md)
        * [Volume Groups Restorable](en/oracle/blockstorage/volume-groups-restorable.md)
    * Compute
        * [Autoscale Enabled](en/oracle/compute/autoscale-enabled.md)
        * [Boot Volume Backup Enabled](en/oracle/compute/boot-volume-backup-enabled.md)
        * [Boot Volume Restorable](en/oracle/compute/boot-volume-restorable.md)
        * [Boot Volume Transit Encryption](en/oracle/compute/boot-volume-transit-encryption.md)
        * [Instance Max Count](en/oracle/compute/instance-max-count.md)
        * [Instance Monitoring Enabled](en/oracle/compute/instance-monitoring-enabled.md)
        * [Instance Policy Protection](en/oracle/compute/instance-policy-protection.md)
        * [Instance Pool Multiple AD](en/oracle/compute/instance-pool-multiple-ad.md)
    * Database
        * [DB Network Security Groups Enabled](en/oracle/database/db-network-security-groups-enabled.md)
        * [DB Private Subnet Only](en/oracle/database/db-private-subnet-only.md)
        * [Database Backup Enabled](en/oracle/database/database-backup-enabled.md)
        * [Database Policy Protection](en/oracle/database/database-policy-protection.md)
    * File Storage
        * [File Storage Policy Protection](en/oracle/filestorage/file-storage-policy-protection.md)
        * [NFS Public Access](en/oracle/filestorage/nfs-public-access.md)
    * Identity
        * [Empty Groups](en/oracle/identity/empty-groups.md)
        * [Excessive Policies](en/oracle/identity/excessive-policies.md)
        * [Excessive Policy Statements](en/oracle/identity/excessive-policy-statements.md)
        * [Minimum Password Length](en/oracle/identity/minimum-password-length.md)
        * [Password Requires Lowercase](en/oracle/identity/password-requires-lowercase.md)
        * [Password Requires Numbers](en/oracle/identity/password-requires-numbers.md)
        * [Password Requires Symbols](en/oracle/identity/password-requires-symbols.md)
        * [Password Requires Uppercase](en/oracle/identity/password-requires-uppercase.md)
        * [Policy Least Privilege](en/oracle/identity/policy-least-privilege.md)
        * [Users MFA Enabled](en/oracle/identity/users-mfa-enabled.md)
    * Networking
        * [Default Security List](en/oracle/networking/default-security-list.md)
        * [Excessive Security Lists](en/oracle/networking/excessive-security-lists.md)
        * [LB Network Security Groups Enabled](en/oracle/networking/lb-network-security-groups-enabled.md)
        * [Load Balancer HTTPS Only](en/oracle/networking/load-balancer-https-only.md)
        * [Load Balancer No Instances](en/oracle/networking/load-balancer-no-instances.md)
        * [Open All Ports Protocols](en/oracle/networking/open-all-ports-protocols.md)
        * [Open Autonomous Data Warehouse](en/oracle/networking/open-autonomous-data-warehouse.md)
        * [Open CIFS](en/oracle/networking/open-cifs.md)
        * [Open DNS](en/oracle/networking/open-dns.md)
        * [Open FTP](en/oracle/networking/open-ftp.md)
        * [Open Hadoop HDFS NameNode Metadata Service](en/oracle/networking/open-hadoop-hdfs-namenode-metadata-service.md)
        * [Open Hadoop HDFS NameNode WebUI](en/oracle/networking/open-hadoop-hdfs-namenode-webui.md)
        * [Open Kibana](en/oracle/networking/open-kibana.md)
        * [Open MySQL](en/oracle/networking/open-mysql.md)
        * [Open NetBIOS](en/oracle/networking/open-netbios.md)
        * [Open Oracle](en/oracle/networking/open-oracle.md)
        * [Open PostgreSQL](en/oracle/networking/open-postgresql.md)
        * [Open RDP](en/oracle/networking/open-rdp.md)
        * [Open RPC](en/oracle/networking/open-rpc.md)
        * [Open SMBoTCP](en/oracle/networking/open-smbotcp.md)
        * [Open SMTP](en/oracle/networking/open-smtp.md)
        * [Open SQLServer](en/oracle/networking/open-sqlserver.md)
        * [Open SSH](en/oracle/networking/open-ssh.md)
        * [Open Telnet](en/oracle/networking/open-telnet.md)
        * [Open VNC Client](en/oracle/networking/open-vnc-client.md)
        * [Open VNC Server](en/oracle/networking/open-vnc-server.md)
        * [Stateless Security Rules](en/oracle/networking/stateless-security-rules.md)
        * [Subnet Multi AD](en/oracle/networking/subnet-multi-ad.md)
        * [VCN Multiple Subnets](en/oracle/networking/vcn-multiple-subnets.md)
        * [WAF Public IP Enabled](en/oracle/networking/waf-public-ip-enabled.md)
    * Object Store
        * [Bucket Public Access Type](en/oracle/objectstore/bucket-public-access-type.md)
        * [Object Store Policy Protection](en/oracle/objectstore/object-store-policy-protection.md)
        * [Pre-Authenticated Requests Access](en/oracle/objectstore/pre-authenticated-requests-access.md)
        * [Pre-Authenticated Requests Expiry](en/oracle/objectstore/pre-authenticated-requests-expiry.md)


## Contributing

Please see the [contributor's guide](.github/CONTRIBUTING.md).