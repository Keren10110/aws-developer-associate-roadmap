
# AWS Developer Associate Exam Study Plan

## Weeks 1-2: Core AWS Services
- **Focus:** EC2, S3, RDS, and DynamoDB.
  - [ ] EC2: Learn instance types, AMIs, and pricing models. Practice launching, connecting, and managing instances.
  - [ ] S3: Understand buckets, objects, security, and lifecycle policies. Configure S3 for static website hosting. Explore bucket creation, file management, lifecycle policies, and data protection mechanisms.
  - [ ] RDS: Explore different database engines, backups, replication, and scaling. Learn about database engines supported, instance launching, backups, and disaster recovery.
  - [ ] DynamoDB: Understand table creation, key concepts (e.g., primary keys), and performance optimization (e.g., indexes).
- **Goal:** Understand instance types, storage options, and database services.

## Weeks 3-4: High Availability and Scalability
- **Focus:** Elastic Load Balancing, Auto Scaling Groups.
  - [ ] Elastic Load Balancing (ELB): Study how ELB automatically distributes incoming application traffic across multiple targets, such as Amazon EC2 instances, containers, and IP addresses. Understand its role in handling the varying load of your application traffic in a single Availability Zone or across multiple Availability Zones.
  - [ ] Auto Scaling Groups: Learn about Auto Scaling groups which ensure you have the correct number of Amazon EC2 instances available to handle the load for your application. Dive into the creation of scaling policies based on conditions like CPU utilization or the number of requests your application receives, enabling your application to scale out or in automatically.
  - [ ] Multi-AZ Deployments for High Availability: Explore how to enhance application availability and fault tolerance by running instances in multiple Availability Zones, which are isolated locations within each region.
  - [ ] Amazon CloudWatch and Amazon SNS for Monitoring: Utilize Amazon CloudWatch to monitor the health and performance of your applications and AWS resources. Understand how to use Amazon Simple Notification Service (SNS) alongside CloudWatch to automate notifications and actions based on thresholds or events within your environment.
- **Goal:** Learn how to manage traffic and scale applications dynamically.

## Weeks 5-6: AWS Managed Services and Database
- **Focus:** Lambda, API Gateway, Elastic Beanstalk.
  - [ ] Lambda: Create simple Lambda functions, understand triggers and limits.
  - [ ] API Gateway: Create RESTful APIs and connect them to Lambda functions.
  - [ ] Elastic Beanstalk: Deploy and manage applications without worrying about the underlying infrastructure.
- **Goal:** Explore serverless architecture, RESTful APIs, and deployment models.

## Weeks 7-8: Serverless Development
- **Focus:**API Gateway, Elastic Beanstalk.
  - [ ] Serverless Framework: Deploy applications using AWS SAM and explore the benefits of serverless architecture..
  - [ ] Integration with APIs and databases: Create API Gateways and connect to DynamoDB.
- **Goal:** Explore serverless architecture.

## Weeks 9-10: Networking and Monitoring
- **Focus:** VPC, CloudWatch, and CloudTrail.
  - [ ] VPC: Set up custom VPCs, subnets, route tables, and network ACLs.
  - [ ] CloudWatch: Monitor resources and applications, create alarms.
  - [ ] X-Ray: Analyze and debug applications.
  - [ ] CloudTrail: Enable governance, compliance, and operational and risk auditing of your AWS account. Audit API usage and events.
- **Goal:** Setup secure networks and monitor AWS resources.

## Weeks 11-12: Security and Governance
- **Focus:** IAM, KMS, and AWS Cognito.
  - [ ] IAM: Deep dive into users, groups, roles, policies, and permission boundaries. Manage users, groups, roles, and permissions.
  - [ ] KMS: Create and control keys used to encrypt your data.
  - [ ] AWS Cognito: Implement user sign-up, sign-in, and access control to web and mobile apps.
- **Goal:** Understand user authentication, authorization, and encryption practices.

## Weeks 13-14: DevOps on AWS
- **Focus:** AWS CodeCommit, CodePipeline, CodeBuild, and CodeDeploy.
  - [ ] CodeCommit: Set up repositories and understand Git integration.
  - [ ] CodeBuild: Understand configurations and build specifications.
  - [ ] CodeDeploy: Learn about deploying on EC2, Lambda, and on-premises.
  - [ ] CodePipeline: Create and manage CI/CD pipelines.
- **Goal:** Learn about CI/CD pipelines and automation processes.

## Final Review and Practice Exams
- **Focus:** Review all topics and take practice exams.
- **Goal:** Identify weak areas and improve through targeted practice.
