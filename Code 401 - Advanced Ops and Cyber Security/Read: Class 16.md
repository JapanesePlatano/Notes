# Cloud Identity and Access Management (IAM) with AWS

What were the three commands used for the attack?

1.aws ec2 describe-instances: This command was used to obtain the metadata of running instances in the compromised AWS environment.

2.aws ec2 authorize-security-group-ingress: This command allowed the attacker to set up security group rules to allow ingress traffic.

3.aws s3 sync: This command enabled the attacker to copy data from S3 buckets to a remote server.

What misconfiguration of AWS components allowed the attacker to access sensitive data?

The attacker exploited an over-permissive IAM role that allowed access to sensitive data stored in S3 buckets.

What are two of the AWS Governance practices that could have prevented such an attack?

1.Least Privilege Principle: Ensuring that IAM roles have the minimum permissions necessary for their function.

2. Regular Auditing and Monitoring: Implementing continuous monitoring and regular audits of IAM roles and permissions to detect and remediate over-permissive policies.

## Things I want to know more about

N/A
