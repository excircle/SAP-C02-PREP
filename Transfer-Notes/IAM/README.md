# IAM Essentials

1.) When to use certain IAM constructs

- Users: For long-term usage
- Roles: For short-term credentials (Uses STS)

2.) Difference between Instance & Service Roles
- Instance refers to EC2 instance
- Service role refers to services such as: API Gateway, Lamda Functions, and CodeDeploy

3.) What are IAM Policy types
```sql
("What are the 3 types of IAM Policies?", "AWS Managed, Customer Managed, In-Line policies")
```

4.) What is a resource-based policy?

- Policy that is directly integrated into a resource
- Example: S3 Bucket policy, SQS Queue policy

5.) An IAM Role always has 5 things:
    - Effect
    - Action
    - Resource
    - Conditions
    - Policy Variables

6.) Explicit "DENY" Effects have precedence over "ALLOW"

7.) There are two AWS resources for analyzing IAM policies:
    - AWS Access Advisor: To see permissions granted and when last granted
    - AWS Access Analyzer: To Analyze resouces that are shared with an external entity

8.) What AWS Tool can help you determine when the last time an IAM policy was used?
    - Access Advisor

9.) How can you determine if other accounts have access to your S3 Bucket?
    - Access Analyzer

10.) When you assume a role in AWS, you give up your original IAM perms and take the permissions of the assumed role.

11.) An example of when a resource-based policy would be ideal is when someone needs to perform actions in their own account, and have the output of their action be reflected in someone elses account (Example: Your accounts DB data needing to be written to another accounts S3 bucket).

    - Your account needs IAM User policy allowing access to DB
    - Their account needs Resource-Based Policy to allow you to write to their S3 bucket.
    - Why is this best? Because the Resource-Based Policy will not require you to abandon your DB perms
    - A role based policy would

12.) What is an IAM permission boundry?

    - A IAM permission boundry is an IAM policy that explicitly lists the maximum permissions an entity can have
    - If a boundry existed allowing (S3:*, ec2:*) - Then a newly created IAM policy granting (aks:*) would fail EVEN IF the newer IAM policy was created successfully and without errors.

13.) Major Feature of IAM Access Analyzer

    - IAM Access Analyzer uses a concept known as a "Zone of Trust" to define undesirable access to your AWS Resources
    - IAM Access Analyzer can perform Policy Validation against a policy (even check for best practices)
    - IAM Access Analyzer can generate a policy based on access activity
        - This is accomplished by reviewing CloudTrail Logs
        - This will review 90 days of logs