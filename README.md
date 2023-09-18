# AWS Certified Solutions Architect Professional

This repository is dedicated to preparing for the AWS Certified Solutions Architect Professional Exam.

This repository will contain documentation and code to demonstrate functional knowledge of AWS Solutions Architect (SA) skills.

The examples in this repository will be written in both Python & Golang.

# Exam Outline

| Domain                                   | Exam Percentage |
| ---------------------------------------- | --------------- |
| Domain 1: Design Solutions for Organizational Complexity  | 26%             |
| Domain 2: Design for New Solutions                       | 29%             |
| Domain 3: Continuous Improvement for Existing Solutions | 25%             |
| Domain 4: Accelerate Workload Migration and Modernization | 18%             |

# Table of Contents

| Domain | Subject              | Contents |
| ------ | -------------------- | -------- |

# TO-DO

| Action Item                           | Description                                                                                                                                                                                                                        | Status      |
| ------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ----------- |


# Domain 1: Design Solutions for Origanizational Complexity

### Knowledge Points 1.1: Architect network connectivity strategies.

| Point | Description |
| - | - |
| AWS Global Infrastructure | Regions, Zones, Edges, etc |
| AWS networking concepts | Network knowledge pertaining to: Amazon VPC, AWS Direct Connect, AWS VPN, transitive routing, AWS container services |
| Hybrid DNS concepts | DNS knowledge pertaining to: Amazon Route 53 Resolver, on-premises DNS integration |
| Network segmentation | For example, subnetting, IP addressing, connectivity among VPCs |
| Network traffic monitoring | Knowledge pertaining to VPC Flow Logs, Amazon CloudWatch, Amazon GuardDuty, AWS Network Firewall, AWS Traffic Mirroring, AWS Network Insights, Amazon CloudTrail, AWS WAF |



| Skills | Description/Example |
| - | - |
| Evaluating connectivity options for VPCs and on-premises networks | HA VPNs, AWS Direct-Connect, etc |
| Selecting AWS Regions and Availability Zones based on network and latency requirements | |
| Troubleshooting traffic flows by using AWS tools | Demonstrate skills with CloudTrail and CloudWatch |
| Using service endpoints for service integrations | Allowing an EC2 Instance to connect to an S3 Bucket |
| 

### Knowledge Points 1.2: Prescribe security controls.

| Point | Description |
| - | - |
| IAM and AWS IAM Identity Center (AWS Single Sign-On) | AWS IAM Identity Center is a successor to AWS Single Sign-On. Know the difference. |
| Route tables, security groups, and network ACLs | |
| Encryption keys and certificate management | Security knowledge on AWS KMS, AWS ACM |
| AWS security, identity, and compliance| Security knowledge on AWS CloudTrail, AWS IAM Analyzer, AWS Security Hub, Amazon Inspector |

| Skills | Description/Example |
| - | - |
| Evaluating cross-account access management | <CHECK> Check/Create IAM policy accross accounts. Allow accounts to communicate between accounts. |
| Integrating with third-party identity providers | AWS Congnito Identity Pools (Federation) |
| Encryption strategies for data at rest and data in transit | AWS KMS for at-rest data, AWS ACM for in-flight comms |
| Centralized security event notifications and auditing | |

### Task Statement 1.3: Design reliable and resilient architectures.

| Point | Description |
| - | - |
| Recovery time objectives (RTOs) and recovery point objectives (RPOs) | Know the difference |
| Disaster recovery strategies (for example, using AWS Elastic Disaster Recovery, pilot light, warm standby, and multi-site |
| Data backup and restoration | <CHECK> S3 for storage, EBS, possibly EMR |

| Skills | Description/Example |
| - | - |
| Designing disaster recovery solutions Using RTO and RPO | |
| Implementing auto recovery from failure | <CHECK> Using Auto-Scaling Groups, Load Balancers, and CloudWatch |
| Developing optimal scale-up and scale-out architecture | <CHECK> Using Auto-Scaling Groups, Load Balancers, and CloudWatch |
| Designing an effective backup and restoration strategy | |


### Task Statement 1.4: Design a multi-account AWS environment.

| Point | Description |
| - | - |
| AWS Organizations and AWS Control Tower | Knowledge of org management |
| Multi-account event notifications | Use of CloudTrail + CloudWatch |
| AWS resource sharing across environments | Use of IAM and possibly VPC Peering |

| Skills | Description/Example |
| - | - |
| Evaluating the most appropriate account structure for organizational requirements | VPC, Org, and IAM design |
| Recommending a strategy for central logging and event notifications | S3, Amazon Athena, and possibly EMR |
| Developing a multi-account governance model | |

### Task Statement 1.5: Determine cost optimization and visibility strategies.

| Point | Description |
| - | - |
| AWS cost and usage monitoring tools | AWS Trusted Advisor, AWS Pricing Calculator, AWS Cost Explorer, AWS Budgets |
| AWS purchasing options | Using Reserved Instances, Savings Plans, Spot Instances |
| AWS rightsizing visibility tools |  AWS Compute Optimizer, Amazon S3 Storage Lens |

| Skills | Description/Example |
| - | - |
| Monitoring cost and usage with AWS tools | AWS Trusted Advisor, AWS Pricing Calculator, AWS Cost Explorer, AWS Budgets |
| Developing tagging strategy to maps costs to business units | |
| Understanding how purchasing options affect cost and performance ||




