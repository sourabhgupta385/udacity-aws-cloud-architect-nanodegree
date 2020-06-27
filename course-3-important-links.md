## Course: Design for Security

### Securing Access to Cloud Services

-   [Capital One breach from 2019](https://www.bloomberg.com/news/articles/2019-07-29/capital-one-data-systems-breached-by-seattle-woman-u-s-says)
-   [Imperva breach from 2018](https://www.cisomag.com/data-breach-occurred-due-to-series-of-missteps-imperva/)
-   [OneLogin 2017](https://www.onelogin.com/blog/may-31-2017-security-incident)

### Securing Access to Cloud Infrastructure

-   [CyberArk](https://www.cyberark.com/privileged-access-management/)
-   [thycotic](https://thycotic.com/resources/privileged-access-management/)
-   [AWS documentation for setting up an instance profile role](https://docs.aws.amazon.com/systems-manager/latest/userguide/setup-instance-profile.html)
-   [Security best practices for your VPC](https://aws.amazon.com/answers/networking/controlling-vpc-egress-traffic/)
-   [OpenVPN on AWS](https://aws.amazon.com/blogs/awsmarketplace/setting-up-openvpn-access-server-in-amazon-vpc/)

### Protecting Data Stored in Cloud

-   [Dynamo DB Client-Side and Server-Side Encryption guide](https://docs.aws.amazon.com/dynamodb-encryption-client/latest/devguide/client-server-side.html)
-   [S3 Client-Side and Server-Side Encryption Guide](https://docs.aws.amazon.com/AmazonS3/latest/dev/UsingEncryption.html)
-   [Detailed White Paper on KMS Best Practices](https://d0.awsstatic.com/whitepapers/aws-kms-best-practices.pdf)

### Defensive Security in the Cloud

-   [Cfripper](https://github.com/Skyscanner/cfripper)
-   [Cloudsploit](https://cloudsploit.com/opensource)
-   [cfn-lint](https://github.com/aws-cloudformation/cfn-python-lint)
-   [Chef inspec](https://github.com/inspec/inspec)
-   [Open policy agent / Regula](https://github.com/fugue/regula)
-   [Terrascan](https://github.com/cesar-rodriguez/terrascan)
-   [OWASP Top 10](https://owasp.org/www-project-top-ten/)

#### Open source tools for monitoring cloud security

-   Prowler
-   Scout2
-   CloudSploit
-   Cloud Custodian

#### Commercial tools for monitoring cloud security

-   Fugue
-   Palo Altos
-   Prisma Cloud
-   Cloud Conformity

#### Tools for scanning Vulnerabilities in Cloud Workloads

Open source tools include:

-   Clair
-   Anchore
-   Trivy
-   etc.

Commercial products include:

-   aquasec
-   sysdig
-   twistlock
-   etc.

#### Use an SIEM(Security Event Information Monitoring) Tool

Log sources can be sent to SIEM tools for creating security dashboards. Many cloud security monitoring and SIEM tools have out of the box features to look at cloud native logs such as CloudTrail and VPC flow logs and identify anomalous activity.

Example vendor tools include:

-   Splunk
-   Sumologic,
-   Lacework
-   CloudKnox
-   etc.
