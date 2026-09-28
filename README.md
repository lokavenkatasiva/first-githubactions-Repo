DevOps Master Interview Question Bank
Focus: AWS DevOps | Terraform | Kubernetes/EKS | CI/CD | Jenkins | Git | Docker | Linux | Ansible | Monitoring | Security | Production Support

1. DevOps Project & Experience
Tell me about yourself.
Tell me about your current project.
Walk me through your project flow.
Explain your project architecture from a DevOps perspective.
Explain the complete CI/CD flow that you built end-to-end.
What exactly was your role and responsibility in your project?
What was your role in the CI/CD pipeline?
What are your day-to-day responsibilities as a DevOps Engineer?
What third-party integrations have you worked on?
Explain an integration you implemented in your project.
What automation tasks have you done using Shell scripting?
Do you have Python experience? How much exposure do you have?
What type of applications have you deployed?
Have you worked on production support?
Have you handled on-call support?
Explain one production issue you handled.
How did you troubleshoot the production issue?
How did you minimize downtime?
What preventive measures did you implement after the incident?
Have you worked on any migration projects?
Have you worked on both on-premises and cloud environments?
Do you have hybrid cloud experience?
2. AWS – Core & Architecture
What AWS services have you worked on?
Design a highly available three-tier architecture in AWS.
Which AWS services would you use for a three-tier application?
Why do we use a VPC?
Why do we use multiple Availability Zones?
What is the purpose of an Internet Gateway?
What is the purpose of a NAT Gateway?
How does a NAT Gateway work internally?
What is the difference between an Internet Gateway and a NAT Gateway?
What is the difference between public and private subnets?
How do you identify whether a subnet is public or private?
How do public and private subnets route traffic?
When would you use public and private subnets?
How do two subnets communicate within the same VPC?
How would you design a highly available architecture across multiple Availability Zones?
What are the differences between ALB, NLB, and CLB?
What is AWS Elastic Load Balancer?
What is the purpose of an Application Load Balancer?
How do you create an Application Load Balancer?
How do you get the DNS URL of an ALB?
Which load balancer supports path-based routing?
Does an ALB have a static IP address?
If your application requires a static public IP address, what AWS service or solution would you use?
How would you provide static IPs for an HTTP/HTTPS application?
Can an NLB handle HTTPS/TLS traffic?
What is the difference between ALB and NLB?
At which OSI layers do ALB and NLB operate?
When would you use ALB instead of NLB?
What is the difference between On-Demand Instances and Spot Instances?
What happens when an EC2 instance in an Auto Scaling Group becomes unhealthy?
How does Auto Scaling work?
How would you troubleshoot connectivity issues between private and public subnets?
How would you troubleshoot an unreachable EC2 instance?
How do you provide cross-account access in AWS?
What is cross-account IAM access?
EC2 is in Account A and S3 is in Account B. How would you allow EC2 to access the S3 bucket?
How would you avoid storing AWS access keys on an EC2 instance?
What is Amazon S3?
How do you provide access to an S3 bucket?
What permissions and policies need to be configured for S3 access?
How would you provide temporary access to an S3 object?
How would you share an S3 object with an external customer who does not have an AWS account?
What is Amazon DynamoDB?
Why would you use DynamoDB instead of a relational database?
Why is DynamoDB used for Terraform remote state locking?
What is Amazon Route 53?
Explain the different Route 53 routing policies.
How does Route 53 perform failover during a disaster recovery scenario?
How do you redirect traffic to another AWS region during DR?
How do you optimize AWS infrastructure costs?
How would you investigate a sudden increase in AWS cloud costs?
3. AWS Networking
What is VPC Peering?
How would you enable communication between EC2 instances in private subnets across two different AWS accounts?
Why would you choose VPC Peering for this scenario?
What are the steps involved in configuring VPC Peering?
Have you worked on VPC Peering in a production environment?
Have you worked with AWS Client VPN?
Have you worked with AWS Transit Gateway?
After creating a Transit Gateway attachment, is that enough for traffic to flow?
What additional configurations are required after creating a Transit Gateway attachment?
What is AWS WAF?
Why do we use AWS WAF with an ALB?
What are the differences between Security Groups and Network ACLs?
How would you troubleshoot connectivity between AWS resources?
4. AWS IAM & Security
What is IAM?
What is the difference between IAM Users, Groups, and Roles?
Why do we use IAM Roles?
How do you provide cross-account access using IAM Roles?
How does EKS integrate with IAM?
What is the difference between RBAC and IRSA?
What is AWS Organizations?
What is an SCP?
What is the use of SCP in an AWS enterprise environment?
Is it possible to create both Allow and Deny rules in SCP?
How do Permission Boundaries work?
How do IAM Roles, Permission Boundaries, and SCP work together?
How would you manage user access across multiple AWS accounts?
What are Permission Sets in AWS IAM Identity Center?
How would you provide the same permissions to a DevOps engineer across multiple AWS accounts?
How do you ensure that an AWS cloud environment is secure?
What AWS tools or services do you use for security and compliance?
How do you securely manage secrets in AWS?
5. AWS Monitoring & Logging
What is AWS CloudWatch?
What is the use of CloudWatch?
Which CloudWatch metrics do you use for troubleshooting?
How would you configure CloudWatch alarms?
How would you configure custom metrics for an application?
What is AWS CloudTrail?
What is the difference between CloudWatch and CloudTrail?
How would you monitor an application running in AWS?
How would you troubleshoot high application latency using AWS monitoring tools?
Which ALB metrics do you monitor regularly?
What monitoring tools have you used?
Have you used CloudWatch for production monitoring?
6. Terraform – Fundamentals
What is Infrastructure as Code?
What are the benefits of Infrastructure as Code?
What is Terraform?
What is Terraform Apply?
Explain the Terraform lifecycle.
What happens during terraform init?
Does terraform init create an EC2 instance?
What are Terraform providers?
How do Terraform providers work after terraform init?
Can we use multiple providers in the same Terraform deployment?
What are Terraform meta-arguments?
What is the difference between count and for_each?
What is indexing in Terraform?
What are Terraform variables?
What are Terraform locals?
What is the difference between Terraform variables and locals?
What is a Terraform data source?
What are dependencies in Terraform?
Explain implicit and explicit dependencies in Terraform.
How does Terraform build and execute its dependency graph?
What is immutable infrastructure?
How does Terraform support immutable infrastructure?
What is the difference between Terraform and AWS CloudFormation?
7. Terraform – State & Backend
What is the Terraform State File?
Why is Terraform state required?
What is Terraform remote state?
Which remote backend have you used with Terraform?
How did you configure the Terraform remote backend?
How did you configure S3 for Terraform remote state?
Where are Terraform state and locking details stored when using S3 and DynamoDB?
Why are state files stored in S3?
Why is DynamoDB used for Terraform state locking?
How does Terraform state locking work with S3 and DynamoDB?
What happens if two engineers run terraform apply at the same time?
How do you prevent two people from running terraform apply simultaneously?
What happens if the Terraform state file is accidentally deleted?
How would you recover a deleted Terraform state file?
What happens if the Terraform state file becomes corrupted?
How would you recover from Terraform state corruption?
How would you manage existing infrastructure without unnecessarily recreating resources after state problems?
How would you identify whether existing infrastructure can be imported into Terraform state?
What is Terraform Import?
How do you manage existing AWS resources using Terraform?
8. Terraform – Drift & Troubleshooting
What is Terraform Drift?
What is configuration drift?
How does Terraform detect infrastructure drift?
How do you overcome Terraform drift?
If you manually add a tag to an EC2 instance from the AWS Console, what happens when you run terraform apply?
Your Terraform pipeline is failing because Terraform State is locked. What would you do?
Terraform Apply is stuck for a long time. How would you troubleshoot it?
What common Terraform issues have you faced?
Terraform partially created infrastructure before failing. How would you recover safely?
An Infrastructure-as-Code deployment partially succeeds and then fails. How would you safely recover without causing infrastructure drift?
If a Terraform state file is large and taking a long time to load, what could be the issue?
How would you optimize a large Terraform state file?
9. Terraform – Modules & Project Structure
What is a Terraform Module?
Why do we use Terraform modules?
How do you create an EC2 instance using a Terraform module?
How do you call a Terraform module from a root module?
How do you call one Terraform module from another module?
What is the source argument inside a Terraform module block?
What are the common inputs/variables for an EC2 module?
What is a Terraform Registry module?
What is the difference between a Terraform Registry module and a local module?
How do you use a specific or previous version of a Terraform module?
What Terraform modules have you worked on?
What is the recommended folder structure for a production-grade Terraform project?
How did you structure your Terraform folders?
How do you maintain Terraform files for Dev and Production environments?
How do you manage Terraform code across multiple environments?
If you have Dev, QA, and Production environments, how would you use the same Terraform code?
What are Terraform Workspaces?
When would you use Terraform Workspaces instead of separate folders?
How do you manage Terraform state for multiple environments?
How would you create EC2 instances in multiple AWS regions using Terraform?
What are Terraform provider aliases?
How would you create multiple EC2 instances with unique names and instance types?
How would you delete only one specific EC2 instance using Terraform?
If you have 50 EC2 instances created using Terraform, how would you reduce them to 10?
If you use count and delete the fifth instance, what problem can occur?
Why would you prefer for_each over count for stable resources?
10. Terraform – Hands-on
Write Terraform code to create 5 EC2 instances with unique names and instance types.
Delete only one specific EC2 instance using Terraform.
Write Terraform code to create an EKS cluster.
Implement conditional resource creation in Terraform.
How would you generate a random number in Terraform?
What is the Random provider?
Which Terraform block would you use to execute a shell command during terraform apply?
What is the difference between local-exec and remote-exec provisioners?
How would you increase an existing Linux volume from 500 GB to 750 GB using Terraform?
11. Kubernetes – Architecture & Fundamentals
Explain Kubernetes Architecture.
What are the Control Plane components in Kubernetes?
What are the Worker Node components in Kubernetes?
What is the role of containerd?
What is the role of kube-proxy?
What is a Kubernetes Pod?
What is a Kubernetes Service?
Why do we use Services in Kubernetes?
What are the different types of Kubernetes Services?
What is the difference between ClusterIP, NodePort, and LoadBalancer?
When would you use ClusterIP, NodePort, and LoadBalancer?
What is a Kubernetes Namespace?
What is a Custom Resource Definition (CRD)?
Why do we need CRDs?
How do you create and use a Custom Resource after defining a CRD?
What is CNI?
Which CNI plugin have you used?
How did you implement the CNI?
What is Service Discovery in Kubernetes?
What are Taints and Tolerations?
What is Node Affinity?
Explain Taints, Tolerations, and Node Affinity.
What is the difference between Deployment and StatefulSet?
What are the differences between Deployment, StatefulSet, and DaemonSet?
What are Requests and Limits in Kubernetes?
12. Kubernetes – EKS
Explain your Amazon EKS experience.
What kind of applications have you deployed in EKS?
How do you deploy applications to EKS?
What Kubernetes resources do you use while deploying applications?
What are the prerequisites for EKS cluster setup?
How do you connect to an EKS cluster?
Which commands do you use to connect to EKS?
How do developers connect to the EKS cluster?
How does Jenkins connect to the EKS cluster?
How do you connect to EKS worker nodes?
What do you do after connecting to an EKS worker node?
How do you upgrade an EKS cluster?
Explain the process of upgrading an EKS cluster.
Have you worked on the EKS control plane upgrade process?
What is the trade-off between AWS-managed node groups and self-managed node groups?
How does EKS integrate with IAM?
What type of applications do you deploy on EKS?
When would you choose EC2 over EKS?
What operations have you performed in Kubernetes apart from deployments?
13. Kubernetes – Deployment & Scaling
What is a Kubernetes Deployment?
What is the Kubernetes Deployment flow?
How do you manually scale a Kubernetes Deployment?
How can you increase the number of replicas using the CLI?
What is Horizontal Pod Autoscaler (HPA)?
How does HPA work?
On which metrics does HPA scale Pods?
What is Cluster Autoscaler?
How does Cluster Autoscaler work?
What is the difference between HPA and Cluster Autoscaler?
Explain Min, Desired, and Max node settings in an EKS node group.
How does Kubernetes ensure high availability and scalability?
How do you achieve zero downtime in Kubernetes?
How would you optimize CPU and memory requests and limits in production?
How do you determine the desired, minimum, and maximum pod count for a microservice?
How do you test an application to determine the minimum and maximum pod count?
How do you implement autoscaling when production traffic fluctuates heavily?
14. Kubernetes – Deployment Strategies
What deployment strategies are you currently using?
What is a Rolling Deployment?
What is a Blue-Green Deployment?
What is a Canary Deployment?
What is the difference between Rolling, Blue-Green, and Canary deployments?
Which deployment strategy do you use most frequently and why?
Have you implemented all three deployment strategies?
Have you implemented different deployment strategies for microservices?
Are you using Rolling Updates for critical services such as payment services?
How do Kubernetes Rolling Updates work?
How do Kubernetes Rollbacks work?
How would you implement Blue-Green deployment using Terraform and Jenkins?
How would you design a zero-downtime deployment?
How would you roll back a failed production deployment?
How do you prepare a rollback strategy before deployment?
A production deployment fails halfway through. How would you perform a rollback while minimizing downtime?
15. Kubernetes – Troubleshooting
If a Pod is down, how do you debug it?
What happens when a container crashes in Kubernetes?
What is CrashLoopBackOff?
What are the common reasons for CrashLoopBackOff?
How do you troubleshoot CrashLoopBackOff?
A Pod is in Pending state. How do you troubleshoot it?
What are the common reasons for a Pod to remain in Pending state?
Which command do you use first to troubleshoot a Pending Pod?
What does kubectl describe pod show?
If 6 Pods are running and 4 Pods are not running, how would you troubleshoot?
If only 20 out of 40 Pods were created after deployment, how would you investigate?
If a node becomes NotReady, what do you check?
You have three nodes and one node is not receiving traffic. How would you identify, troubleshoot, and fix the issue?
An application is accessible inside the cluster but not from outside. How would you troubleshoot it?
Your application is deployed and exposed, but traffic is not reaching backend Pods. How would you troubleshoot?
A service becomes inaccessible after an Ingress update. What components would you verify?
How would you troubleshoot an application returning 502 or 503 errors?
How would you troubleshoot intermittent 503 errors in Kubernetes?
How would you verify whether the issue is with the Pod, Service, Ingress, or Load Balancer?
What logs and metrics do you check during Kubernetes troubleshooting?
Why should Pod-related issues be investigated in Kubernetes rather than Jenkins?
16. Kubernetes – Networking & Request Flow
Explain the complete request flow from a client to a Kubernetes Pod.
How does a request travel from a browser to a Kubernetes Pod?
Explain the request flow for an application in Kubernetes.
What is the role of DNS in Kubernetes application access?
What is the role of Ingress?
What is the role of a Kubernetes Service?
How does Ingress route traffic to applications?
How does traffic flow from an external user/laptop to a Kubernetes application?
Can you bypass Ingress? Explain kubectl port-forward.
How would you restrict Pod-to-Pod communication in Kubernetes?
How would you restrict an EKS Pod so it can communicate only with a database and nothing else?
Write a NetworkPolicy for restricting Pod communication.
How would you troubleshoot an application that is accessible inside the cluster but not externally?
How would you troubleshoot an HTTP 503 Service Unavailable issue in production?
What is Istio?
Why do we use a Service Mesh?
17. Kubernetes – Storage & Secrets
Explain PV and PVC in Kubernetes.
How would you handle persistent storage for a stateful application running in Kubernetes?
What is a Kubernetes Secret?
Is Kubernetes Secret encrypted by default?
How do you manage secrets in Kubernetes?
How would you securely manage secrets in production?
How would you handle a database password in Kubernetes?
How would you integrate AWS Secrets Manager with Kubernetes?
How would you integrate AWS Secrets Manager with GitHub Actions?
How would AKS access Azure Key Vault without storing secrets in the cluster?
How would you rotate database credentials without causing application downtime?
18. Kubernetes – Probes
What is a Readiness Probe?
What is a Liveness Probe?
What is a Startup Probe?
Explain the difference between Readiness, Liveness, and Startup Probes.
How do Readiness and Liveness Probes work?
Write a Kubernetes Deployment YAML with requests, limits, readiness probe, and liveness probe.
Why would a Pod be Running but the application still be unavailable?
19. Kubernetes – YAML & Commands
Write a Kubernetes Deployment YAML file.
Write a Deployment YAML with requests and limits.
Write a Deployment YAML with readiness and liveness probes.
Write a Kubernetes Deployment YAML including error handling.
How do you check whether a Pod is running?
How do you open/access a Kubernetes Pod?
Which kubectl commands do you use regularly?
What troubleshooting commands do you use first?
How do you automate application validation after deployment?
How would you fail a deployment automatically if the health check fails?
20. Docker – Fundamentals
Explain Docker.
Why do we need containers?
What is the use of Docker?
What is the difference between a Container and a VM?
Explain Docker Architecture.
What are the components of Docker Architecture?
Explain the process of creating a Docker image from a microservice.
What are Docker Image Layers?
Why does every Docker instruction create a new layer?
Where are changes stored while a Docker container is running?
What is Docker Compose?
What is Docker Swarm?
What is Podman?
What are Docker networking options?
Explain Docker networking.
What are Docker volumes?
How do you inspect a running Docker container?
What does docker inspect do?
21. Docker – Dockerfile & Optimization
What are the components of a Dockerfile?
Write a Dockerfile for an application.
Write a Dockerfile for a Node.js application.
What is the difference between CMD and ENTRYPOINT?
Which one can be overridden: CMD or ENTRYPOINT?
What is the difference between Docker COPY and ADD?
When would you use COPY and ADD?
Explain Docker Multi-Stage Builds.
How do Multi-Stage Builds optimize production images?
What Docker best practices do you follow while creating Docker images?
A Docker image is very large. How would you optimize it?
A Docker image works locally but fails in production. How would you identify the root cause?
How do you optimize a Docker image for Kubernetes?
How do you push a Docker image to Amazon ECR?
Which container registry do you use to store Docker images?
22. Git
Explain your Git branching strategy.
What is the difference between Git Merge and Git Rebase?
Which one do you use in your development environment, Merge or Rebase? Why?
What is Git Rebase?
What is Git Squash?
What are Git Stash operations?
How do you resolve Git merge conflicts?
How do you revert changes in a remote repository?
How do you recover a deleted Git branch?
What is git reflog?
How do you recover a deleted commit using git reflog?
What is git reset --hard?
What is Git Cherry-pick?
When do you use Cherry-pick?
What branching strategy do you use in your organization?
How do you promote changes between environments?
23. Jenkins – Fundamentals & Architecture
Explain Jenkins.
Explain Jenkins Architecture.
What type of Jenkins pipeline have you worked on?
What is the difference between Declarative and Scripted pipelines?
What is Groovy syntax?
Have you created Jenkins pipelines from scratch?
Explain the Jenkins pipeline you worked on.
What is Jenkins Master-Agent architecture?
How does Jenkins execute stages in parallel?
What are Jenkins Shared Libraries?
Why are Jenkins Shared Libraries important in enterprise CI/CD?
How does Jenkins build triggering work?
How do you give developers access to specific Jenkins builds?
How do you provide access to the Jenkins server?
How do you configure SonarQube with Jenkins?
How do you configure the SonarQube Quality Gate?
What happens if the SonarQube Quality Gate fails?
How do you add security scanning to a Jenkins pipeline?
How do you integrate GitHub with Jenkins?
What is the integration layer between GitHub and Jenkins?
24. Jenkins – Pipeline & Troubleshooting
Explain your complete Jenkins CI/CD pipeline.
What happens after developers push code?
What happens after a code commit in your pipeline?
How would you design a reusable CI/CD workflow for Python, Node.js, and Java applications?
How would you set up reusable workflows for multiple microservices?
How would pipelines trigger only for changed microservices?
What type of tests do you perform in pipelines?
What metrics and SLAs do you define for pipeline health?
How do you troubleshoot a failed Jenkins pipeline?
If Jenkins is working locally but is not accessible through the URL, how would you troubleshoot it?
If a Jenkins deployment fails, how do you identify the root cause?
Which Jenkins logs do you check first?
How do you troubleshoot a Jenkins pipeline that suddenly starts failing without code changes?
A Jenkins pipeline is failing with a NullPointerException while accessing a JSON property. How would you troubleshoot it?
How would you reduce a CI/CD pipeline from 30 minutes to under 5 minutes?
How would you prevent two production deployments from running simultaneously?
25. CI/CD
What is the CI/CD process in your project?
What is the difference between Continuous Integration, Continuous Delivery, and Continuous Deployment?
Explain CI/CD with a real-world example.
Explain the complete CI/CD pipeline architecture.
How would you implement DevOps practices in a project that currently has manual deployments?
How would you design a multi-stage CI/CD pipeline with separate environments?
How do you manage Dev, SIT, UAT, and Production deployments?
Do you use a single CI/CD pipeline for multiple environments or separate pipelines?
How do you manage environment-specific configurations?
How do you prevent configuration drift between environments?
How do you implement approval workflows in CI/CD?
How many levels of approval are there before Production?
Who approves infrastructure changes?
What approval gates exist before Production deployment?
What happens if someone accidentally approves the wrong pipeline?
How would you handle an incorrect Terraform deployment caused by a wrong approval?
What rollback strategy would you follow?
What preventive controls would you implement to avoid deployment mistakes?
How would you design a zero-downtime CI/CD pipeline?
How would you design a GitOps workflow for multiple teams with independent release cycles?
26. SonarQube & Code Quality
What is SonarQube and what is its use?
Explain the end-to-end SonarQube flow in a CI/CD pipeline.
What is a code smell?
What is code coverage?
Give an example of a code smell detected by SonarQube.
Give an example of a security vulnerability detected by SonarQube.
How is SonarQube integrated into Jenkins?
What metrics does SonarQube check?
How do you troubleshoot a Jenkins pipeline failure caused by a SonarQube Quality Gate?
Did you only trigger SonarQube scans, or did you review and triage violations?
Give an example where you helped resolve a SonarQube finding.
What types of findings does SonarQube report?
27. Security Scanning – Checkmarx & Checkov
What is Checkmarx?
How did you integrate Checkmarx into Jenkins?
Did you review and triage Checkmarx violations?
Give an example where you helped resolve a Checkmarx finding.
What types of vulnerabilities does Checkmarx detect?
What is Checkov?
Why would you use Checkov for Terraform, Kubernetes, and Docker?
What common Checkov errors have you encountered?
After receiving a Checkov scan report, what steps do you follow before deployment?
28. Linux
How comfortable are you with Linux?
What Linux activities do you perform regularly?
What are the top Linux commands every DevOps Engineer should know?
How do you troubleshoot a Linux server?
How do you check Linux logs?
How do you access a Linux server?
How do you troubleshoot port-related issues in Linux?
How do you monitor CPU utilization in Linux?
How do you monitor context switches in Linux?
Write a Shell script to monitor CPU utilization.
Write a Shell script to send an email when CPU usage exceeds 90%.
Write a Shell script to monitor a service and automatically restart it if it goes down.
Write a Shell script to check whether a Kubernetes Pod is running.
Write a Shell script for weekly log cleanup.
How would you schedule a cleanup script every week?
What is the meaning of -mtime +7?
What is the output of:
echo hi || echo hello
Explain the sort command in Linux.
How do you find a particular file from the root level of a Linux server?
How do you search for errors or exceptions in a file along with line numbers?
29. Linux – Permissions & File Transfer
What do Linux file permissions 755 and 555 mean?
How do you interpret numeric Linux permissions such as 7, 5, 4, and 0?
If a script has permissions 755 and you execute chmod 7444 script.sh, what will happen?
What is the default SFTP port?
How would you securely transfer a file from one Linux server to another?
What is the difference between SFTP, SCP, and FTP?
30. Linux – Filesystems
How do you mount a filesystem in Linux?
How would you configure a filesystem so that it is automatically mounted after reboot?
How do you fix an /etc/fstab entry permanently?
How do you identify the correct UUID for a filesystem?
Which command identifies the filesystem UUID?
31. Ansible
What have you used Ansible for?
Have you created Ansible playbooks?
What is an Ansible Playbook?
What is an Ansible Role?
What is the difference between an Ansible Playbook and Role?
Why are Ansible Roles reusable?
How can one playbook call multiple roles?
Explain the structure of an Ansible Role.
What specific Ansible playbook have you created?
How did your Ansible playbook help reduce deployment time?
How do you handle errors in Ansible?
How do you manage secrets in Ansible?
What is the use of Jinja2 templates?
What is an Ansible inventory?
32. Monitoring – Prometheus & Grafana
What is Prometheus?
What is Grafana?
What is the use of Prometheus and Grafana?
What kind of data and metrics are collected by Prometheus?
What is the exact role of Grafana?
What monitoring dashboards/tools are you using?
Have you configured Grafana dashboards?
How do you monitor your applications?
How do you configure monitoring and alerting for application response time?
Prometheus is not receiving application metrics. How would you troubleshoot it?
How would you configure alerts when service response time exceeds a threshold?
How do you design SLO-based alerting while minimizing alert fatigue?
How do you correlate logs, metrics, and traces during a production incident?
What is the difference between logs, metrics, and traces?
33. Production Support & Incident Management
Do you have production support experience?
Do you have incident-management experience?
Explain Incident Management.
Explain Problem Management.
Explain Change Management.
Explain your incident response process.
What do you do after receiving an alert from Prometheus, Grafana, or CloudWatch?
How do you assess impact and severity?
How do you verify whether an alert is genuine?
What steps do you follow until service restoration and RCA?
How do you perform RCA after a production incident?
A production incident occurs at 2 AM. How would you lead the troubleshooting process?
How would you communicate with stakeholders during a critical incident?
How do you handle SLA requirements during incidents?
What is Business Impact Analysis?
What factors do you consider in Business Impact Analysis?
What is IT Risk Management?
What is an Operational Service Book?
How do you handle a P1 incident?
Explain the most challenging production incident you have handled.
What architectural improvements did you make after a production incident?
How do you handle cascading failures across multiple microservices?
34. Production Troubleshooting Scenarios
Users report that the application is running slowly. How would you troubleshoot the issue end-to-end?
Application response time suddenly increases after a release. How would you identify the root cause?
A deployment succeeds, but the application fails in Production. How would you troubleshoot it?
A production deployment fails halfway through. How would you recover safely?
A database migration fails during deployment. What would your recovery plan be?
A CI/CD pipeline suddenly starts failing without any code changes. Where would you begin?
A container works perfectly in Development but repeatedly crashes in Production. How would you isolate the issue?
An application cannot communicate with another microservice. How would you troubleshoot it?
Monitoring alerts indicate high CPU usage across multiple Pods. How would you investigate?
SSL certificates have expired in Production. How would you renew and validate them safely?
Secrets need to be rotated without causing application downtime. How would you approach it?
A cloud resource is causing unexpected costs. How would you identify and optimize it?
Your production deployment succeeds but users receive intermittent 5xx errors. How would you investigate?
A deployment introduces a severe performance regression. Would you immediately roll back or investigate first?
How would you design safeguards for production deployments?
How would you handle a production deployment triggered incorrectly?
How would you recover from infrastructure failure?
What recovery strategy do you follow for your application?
How do you handle application recovery after an infrastructure failure?
35. High Availability, DR & Scalability
How does Kubernetes ensure high availability and scalability?
How would you design a multi-region Kubernetes architecture for high availability?
How do you set up disaster recovery for microservices?
How does Route 53 perform failover during a DR scenario?
How would you redirect traffic to another AWS region during DR?
What are RTO and RPO?
How would you design a disaster recovery strategy with defined RTO and RPO requirements?
How would you migrate a stateful application to Kubernetes with minimal downtime?
How would you perform a zero-downtime Kubernetes cluster upgrade?
What happens to Pods when a Kubernetes node suddenly goes down?
How would you design a self-healing platform for critical production services?
36. Microservices
What are the key differences between Monolithic and Microservices architecture from a DevOps perspective?
How would you approach migrating a monolithic application to microservices?
What steps would you follow during a monolith-to-microservices migration?
What challenges would you expect during migration?
How do you decide whether a monolithic application should be converted into microservices?
Before moving to microservices, what foundational setup is important?
How would you design CI/CD for multiple microservices?
How would you set up reusable workflows for multiple microservices?
How would you handle cascading failures across multiple microservices?
37. Cloud Migration
Have you worked on any migration projects?
How would you migrate an on-premises application to AWS?
What migration strategy would you follow?
How would you plan rollback during a cloud migration?
What challenges can occur during on-premises to AWS migration?
Have you worked with on-premises infrastructure?
Have you worked with VMware vSphere?
Have you worked in both on-premises and cloud environments?
38. Performance & Capacity
How do you troubleshoot application performance degradation?
What kind of performance testing tools and services have you used?
How frequently do you perform performance testing?
How do you determine minimum and maximum Pod counts?
How do you perform capacity planning for Kubernetes?
How do you optimize CPU and memory resources?
How would you investigate a sudden increase in application latency?
How would you identify whether high latency is caused by the application or infrastructure?
A deployment succeeds but latency increases from 80 ms to 2 seconds. Walk through your debugging approach.
Your CI/CD pipeline takes 40 minutes instead of 5 minutes. How would you identify and optimize the bottleneck?
39. SRE & Operational Excellence
What is SRE?
What are the four pillars of SRE?
How do you define SLOs and SLAs?
How do you design SLO-based alerting?
How do you reduce alert fatigue?
How do you handle production incidents from an SRE perspective?
How do you correlate logs, metrics, and traces?
How do you design a self-healing platform?
How do you improve reliability after a production incident?
40. Kafka & Event-Driven Systems
What is Apache Kafka?
What are the major advantages of Kafka?
Explain a major Kafka production incident you have handled.
How does a Kafka consumer read messages/events from Kafka?
What are the commonly used Kafka ports?
How does a database application consume events from Kafka and process/update the database?
What is Confluent Cloud?
What is Confluent Platform?
What is the difference between Confluent Cloud and Confluent Platform?
How are Kafka credentials/secrets securely retrieved when establishing a connection to Kafka?
What is Azure Event Hubs?
What are the primary use cases of Azure Event Hubs?
What are the major limitations of Azure Event Hubs?
How is Azure Event Hubs different from Apache Kafka?
What common production issues can occur with Azure Event Hubs?
41. General Cloud Concepts
What is IaaS?
What is PaaS?
What is SaaS?
Explain the difference between IaaS, PaaS, and SaaS.
What is the difference between EC2 and EKS?
What is the difference between AWS VM-based deployment and container-based deployment?
42. Azure – Interview Questions
What Azure services have you worked with?
What is an Azure Virtual Machine?
What is an Azure Virtual Machine Scale Set?
What is the difference between Azure VM and VMSS?
When would you use Azure VM vs VMSS?
What Azure container services have you worked with?
Have you used Azure Container Instances?
Have you used Azure Container Apps?
How do you ensure high availability for applications in Azure and Kubernetes?
What configuration-level considerations do you take care of while implementing applications in Azure?
What monitoring and alerting mechanisms have you implemented in Azure?
Have you implemented Azure-native automation services?
Have you worked with Azure Automation Runbooks?
How would AKS access Azure Key Vault without storing secrets in the cluster?
43. Application & Build Tools
What is the difference between mvn clean install and mvn clean package?
What type of tests do you perform in CI/CD pipelines?
What is UAT?
What is the purpose of unit testing in a CI/CD pipeline?
What happens when a build fails during the pipeline?
44. Scripting & Programming
Do you have exposure to Python scripting?
How comfortable are you with Python?
What is the difference between Shell scripting and Python?
What repetitive tasks have you automated using Bash/Shell scripting?
Give a real-time example of automation you implemented.
What kind of automation scripts have you created?
Have you automated anything to make operations easier?
Were your automations built using native tools or third-party tools?
Write a Shell script to monitor CPU utilization.
Write a Shell script to monitor a Kubernetes Pod.
Write a Shell script to restart a service if it goes down.
Write a Shell script for log cleanup.
45. Advanced DevOps Architecture Scenarios
How would you design a multi-tenant EKS cluster with network, service, RBAC, and cost isolation?
How would you design a multi-region Kubernetes architecture for high availability?
How would you design GitOps for 20+ teams with independent release cycles?
How would you design reusable Terraform modules for enterprise projects?
How would you design highly secure CI/CD architecture using least privilege?
How would you secure secrets for 100+ microservices?
How would you implement runtime security beyond image vulnerability scanning?
How would you design SLO-based monitoring with minimal alert fatigue?
How would you design a self-healing platform for critical production services?
How would you design disaster recovery with defined RTO and RPO?
How would you prevent configuration drift across multiple environments?
How would you prevent race conditions when multiple teams trigger Production deployments?
How would you design a reliable rollback mechanism for Production?
How would you handle cascading failures across multiple microservices?
How would you optimize a large Terraform state and slow Terraform plan?
How would you optimize a slow CI/CD pipeline?
46. Frequently Repeated High-Priority Questions
These questions appeared repeatedly across the interview experiences:

Explain your project and your role.
Explain your complete CI/CD pipeline.
How do you troubleshoot a failed CI/CD pipeline?
What is Terraform State?
How do you manage Terraform State in a team?
What is Terraform State Locking?
What happens if Terraform State is deleted or corrupted?
What is Terraform Drift?
How do you handle Terraform Drift?
What is the difference between count and for_each?
What are Terraform Modules?
How do you manage Terraform across multiple environments?
Explain Kubernetes Architecture.
Explain the complete request flow from browser to Kubernetes Pod.
What is CrashLoopBackOff?
How do you troubleshoot CrashLoopBackOff?
What happens when a Pod is Pending?
How do you troubleshoot a Pending Pod?
What is the difference between Deployment and StatefulSet?
What are Taints, Tolerations, and Node Affinity?
What is HPA and how does it work?
How do you achieve zero downtime in Kubernetes?
How do you troubleshoot 502/503 errors?
What is the difference between ALB and NLB?
What is the difference between public and private subnets?
What is the difference between Security Groups and Network ACLs?
How do you troubleshoot an unreachable EC2 instance?
How do you manage AWS secrets securely?
How do you implement Blue-Green deployment?
How do you roll back a failed Production deployment?
Explain your production incident and RCA.
How do you monitor applications using Prometheus, Grafana, and CloudWatch?
How do you troubleshoot high application latency?
How do you manage Kubernetes Secrets?
How do you connect EKS with IAM?
How do you perform an EKS cluster upgrade?
How do you troubleshoot an application accessible inside Kubernetes but not externally?
How do you design highly available AWS infrastructure?
How do you handle production incidents and SLA requirements?
How do you secure CI/CD, Kubernetes, Terraform, and AWS?
47. Hands-On Questions to Practice
Write Terraform code to create 5 EC2 instances with unique names.
Delete one specific EC2 instance using Terraform.
Write Terraform code to create an EKS cluster.
Write a Dockerfile for a Node.js application.
Write a Kubernetes Deployment YAML.
Write a Kubernetes Deployment with requests and limits.
Write a Kubernetes Deployment with readiness and liveness probes.
Write a Kubernetes NetworkPolicy to restrict Pod communication.
Write a Jenkins Declarative Pipeline for Checkout, Build, Deploy, and Post actions.
Write a Shell script to monitor CPU utilization.
Write a Shell script to send an email when CPU usage exceeds 90%.
Write a Shell script to monitor whether a Kubernetes Pod is running.
Write a Shell script for weekly log cleanup.
Explain a Jenkins Groovy pipeline.
Explain Terraform code for multiple environments.
Explain the Terraform structure of your project.
48. Interview Preparation Focus
Highest Priority
AWS
Terraform
Kubernetes/EKS
CI/CD
Jenkins
Docker
Git
Linux
Monitoring
Production Troubleshooting
Important Supporting Topics
Ansible
AWS IAM & Security
Secrets Management
SonarQube
Checkov
Checkmarx
Shell Scripting
Networking
Route 53
ALB/NLB
Disaster Recovery
SRE
Scenario Pattern to Practice
For scenario-based questions, structure your thinking around:

Detect → Investigate → Identify Root Cause → Mitigate → Recover → Prevent Recurrence

About
No description, website, or topics provided.
Resources
Readme
Activity
Stars
1 star
Watchers
0 watching
Forks
3 forks
Report repository
Releases
No releases published
Packages
No packages published
Contributors
1
 (1)

NagaLakshmi477
Footer
