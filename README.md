# Sec Your AWS

Platform-specific tools and resources for securing your AWS environment. See the companion DevOps repository at [sec-your-devops](https://github.com/vigah/sec-your-devops)

- [Tools](#tools)
  - [IAM](#iam)
  - [Secrets](#secrets)
  - [Service Configuration & Hardening](#service-configuration--hardening)
  - [Observability](#observability)
  - [CI/CD](#cicd)
  - [Offensive](#offensive)
- [Training & Lab Environments](#training--lab-environments)
- [Additional Resources](#additional-resources)

## Tools

### IAM

- [SAML2AWS](https://github.com/Versent/saml2aws): CLI tool which enables you to login and retrieve AWS temporary credentials using a SAML IDP.
- [CloudTracker](https://github.com/duo-labs/cloudtracker): Helps you find over-privileged IAM users and roles by comparing CloudTrail logs with current IAM policies.
- [PMapper](https://github.com/nccgroup/PMapper): A tool for quickly evaluating IAM permissions in AWS.
- [Aaia](https://github.com/rams3sh/Aaia): AWS IAM visualizer and anomaly finder.
- [aws-sso-reporter](https://github.com/onemorepereira/aws-sso-reporter): Uses the AWS SSO API to list all users, accounts, permission sets etc. and dumps it into a CSV file for additional parsing or viewing.
- [awspx](https://github.com/FSecureLABS/awspx): A graph-based tool for visualizing effective access and resource relationships in AWS environments.
- [IAM Access Key Report](https://github.com/aws-samples/iam-access-key-report): A tool to enumerate data about all active IAM access keys across an AWS Organization and enrich each key with account tag information.

### Secrets

- [S3cret Scanner](https://github.com/Eilonh/s3crets_scanner): A tool designed to provide a complementary layer for the Amazon S3 Security Best Practices by proactively hunting secrets in public S3 buckets.
- [aws-vault](https://github.com/99designs/aws-vault): A vault for securely storing and accessing AWS credentials in development environments.

### Service Configuration & Hardening

- [Prowler](https://github.com/prowler-cloud/prowler): Open source security tool to perform AWS security best practices assessments, audits, incident response, continuous monitoring, hardening and forensics readiness.
- [cloud-nuke](https://github.com/gruntwork-io/cloud-nuke): A tool for cleaning up your AWS accounts by nuking (deleting) all resources within it.
- [AWS Security Toolbox](https://github.com/z0ph/aws-security-toolbox): Single Docker container combining several popular security tools.
- [CloudMapper](https://github.com/duo-labs/cloudmapper): Helps analyze your AWS environments, including auditing for security issues.
- [aws-security-viz](https://github.com/anaynayak/aws-security-viz): Visualize your AWS security groups.
- [s3tk](https://github.com/ankane/s3tk): A security toolkit for AWS S3.
- [Metabadger](https://github.com/salesforce/metabadger): Automated EC2 Instance Metadata Service upgrade to v2 (IMDSv2).
- [Remediate AWS IMDSv1](https://github.com/latacora/remediate-AWS-IMDSv1): Simple tool to identify and remediate the use of the AWS EC2 IMDSv1.
- [Sustainable Personal Accounts](https://github.com/reply-fr/sustainable-personal-accounts): Adds custom maintenance windows for AWS accounts, allowing automatic resource preparation and purging.
- [CloudJack](https://github.com/prevade/cloudjack): Route53/CloudFront vulnerability assessment utility.
- [CDK-Dia](https://github.com/pistazie/cdk-dia): Automated diagrams of AWS CDK provisioned infrastructure.
- [superwerker](https://github.com/superwerker/superwerker): A free, open-source solution that lets you quickly set up an AWS Cloud environment following best practices for security and efficiency.
- [domain-protect](https://github.com/domain-protect/domain-protect): Discover and protect against subdomain takeover vulnerabilities in AWS & Cloudflare.

### Observability

- [Security Hub Automated Response & Remediation](https://github.com/aws-solutions/aws-security-hub-automated-response-and-remediation): An add-on solution that works with AWS Security Hub to provide a ready-to-deploy architecture and a library of automated playbooks.
- [Assisted Log Enabler](https://github.com/awslabs/assisted-log-enabler-for-aws): Find AWS resources that are not logging and turn them on.
- [TrailScraper](https://github.com/flosell/trailscraper?ck_subscriber_id=1640233537): A command-line tool to get valuable information out of AWS CloudTrail.
- [AWS CloudSaga](https://github.com/awslabs/aws-cloudsaga): Test security controls and alerts within AWS, using generated alerts based on security events seen by the AWS Customer Incident Response Team (CIRT).

### CI/CD

- [GitHub Action: Configure AWS Credentials](https://github.com/aws-actions/configure-aws-credentials): Configure AWS credential environment variables for use in other GitHub Actions.

### Offensive

- [Quiet Riot](https://github.com/righteousgambit/quiet-riot): Unauthenticated enumeration of services, roles, and users in an AWS account or in every AWS account in existence.
- [aws-list-resources](https://github.com/welldone-cloud/aws-list-resources): A tool that uses the AWS Cloud Control API to list resources that are present in a given AWS account and regions.
- [Sandcastle](https://github.com/0xSearches/sandcastle): A Python script for AWS S3 bucket enumeration.
- [Pacu](https://github.com/RhinoSecurityLabs/pacu): An AWS exploitation framework.
- [LambdaLooter](https://github.com/StateFarmIns/LambdaLooter): A tool to help reduce the amount of time it takes to review AWS Lambda code.

## Training & Lab Environments

- [IAM Vulnerable](https://github.com/BishopFox/iam-vulnerable): Use Terraform to create your own vulnerable by design AWS IAM privilege escalation playground.
- [Disposable Cloud Environment](https://github.com/Optum/dce): Allows users to "lease" an AWS account for a defined period of time and with a limited budget. At the end of the lease, or if the lease's budget is reached, the account is wiped clean and returned to the account pool so it may be leased again.
- [EC2 Metadata Mock](https://github.com/aws/amazon-ec2-metadata-mock): A tool to simulate Amazon EC2 instance metadata.
- [LocalStack](https://github.com/localstack/localstack): Local AWS cloud emulator.
- [S3 Game Galaxy](https://master.d2av1kz25zeu6f.amplifyapp.com/): A series of challenges to learn S3 features.

## News & Social

- [AWS Security Digest](https://app.mailbrew.com/zoph/aws-security-digest-HrkhwqNrwBBk): A weekly AWS security digest by [Victor Grenu](https://twitter.com/zoph).
- [Last Week in AWS](https://www.lastweekinaws.com/newsletter/): Snarky takes on AWS news and announcements by [Corey Quinn](https://twitter.com/QuinnyPig).

## Additional Resources

- [AWS Security Blog](https://aws.amazon.com/blogs/security/): Official announcements, product highlights, and walk-throughs. Optional mailing list.
- [AWS Customer Security Incidents](https://github.com/ramimac/aws-customer-security-incidents): A repository tracking known breaches of AWS customers.
- [AWS Security Arsenal](https://github.com/toniblyx/my-arsenal-of-aws-security-tools): List of open source tools for AWS security: defensive, offensive, auditing, DFIR, etc.
- [AWSome Pentesting Cheatsheet](https://github.com/pop3ret/AWSome-Pentesting/blob/main/AWSome-Pentesting-Cheatsheet.md): A guide to help pentesters learn more about AWS misconfigurations and ways to abuse them.
