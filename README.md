# AWS-Certified-Cloud-Practitioner-CLF-C02


# AWS Practioneer Question #

# 1. A company needs to keep sensitive data in its own data center due to compliance but would still like to deploy resources using AWS. Which Cloud deployment model does this refer to?


1.on-primise

2. Private

3. hybrid

4. public


ans 3 Hybrid

Overall explanation
Correct option:

Hybrid Cloud

A hybrid deployment is a way to connect infrastructure and applications between cloud-based resources and existing resources that are not located in the cloud. The most common method of hybrid deployment is between the cloud and existing on-premises infrastructure to extend, and grow, an organization's infrastructure into the cloud while connecting cloud resources to the internal system.

Overview of Cloud Computing Deployment Models:  via - https://aws.amazon.com/types-of-cloud-computing/

Incorrect options:

Public Cloud - A public cloud-based application is fully deployed in the cloud and all parts of the application run in the cloud. Applications in the cloud have either been created in the cloud or have been migrated from an existing infrastructure to take advantage of the benefits of cloud computing.

Private Cloud - Unlike a Public cloud, a Private cloud enables businesses to avail IT services that are provisioned and customized according to their precise needs. The business can further avail the IT services securely and reliably over a private IT infrastructure.

On-premises - This is not a cloud deployment model. When an enterprise opts for on-premises, it needs to create, upgrade, and scale the on-premise IT infrastructure by investing in sophisticated hardware, compatible software, and robust services. Also, the business needs to deploy dedicated IT staff to upkeep, scale, and manage the on-premise infrastructure continuously.

Reference:

https://docs.aws.amazon.com/whitepapers/latest/public-sector-cloud-transformation/selecting-the-right-cloud-for-workloads-differences-between-public-private-and-hybrid.html

# 2. A corporation would like to simplify access management to multiple AWS accounts as well as facilitate AWS Single Sign-On (AWS SSO) access to its AWS accounts. As a Cloud Practitioner, which AWS service would you use for this task?

1. AWS identity and access management

2. AWS Iam Identity center

3. AWs Cognito

4. aws cli

ans 2 aws IAM identity center

Overall explanation
Correct option:

AWS IAM Identity Center

AWS IAM Identity Center is the successor to AWS Single Sign-On (AWS SSO). It is built on top of AWS Identity and Access Management (IAM) to simplify access management to multiple AWS accounts, AWS applications, and other SAML-enabled cloud applications. In IAM Identity Center, you create or connect, your workforce users for use across AWS. You can choose to manage access just to your AWS accounts, just to your cloud applications, or to both.

You can create users directly in IAM Identity Center, or you can bring them from your existing workforce directory. With IAM Identity Center, you get a unified administration experience to define, customize, and assign fine-grained access. Your workforce users get a user portal to access their assigned AWS accounts or cloud applications.

You can use IAM Identity Center to quickly and easily assign and manage your employees’ access to multiple AWS accounts, SAML-enabled cloud applications (such as Salesforce, Microsoft 365, and Box), and custom-built in-house applications, all from a central place.

How AWS IAM Identity Center works:  via - https://aws.amazon.com/iam/identity-center/

Incorrect options:

AWS Cognito - Amazon Cognito lets you add user sign-up, sign-in, and access control to your web and mobile apps quickly and easily. With Amazon Cognito, you also have the option to authenticate users through social identity providers such as Facebook, Twitter, or Amazon, with SAML identity solutions, or by using your own identity system. It is an identity management solution for customers/developers building B2C or B2B apps for their customers.

AWS Identity and Access Management (AWS IAM) - AWS Identity and Access Management (AWS IAM) enables you to securely control access to AWS services and resources for your users. Using AWS IAM, you can create and manage AWS users and groups, and use permissions to allow and deny their access to AWS resources. It is not used to log in but to manage users and roles.

AWS Command Line Interface (CLI) - The AWS Command Line Interface (CLI) is a unified tool to manage your AWS services. With just one tool to download and configure, you can control multiple AWS services from the command line and automate them through scripts. It is not a central user portal.




# 3. Question 3 Which Amazon Elastic Compute Cloud (Amazon EC2) Auto Scaling feature can help with fault tolerance?

1. Distributing load to Amazon EC2 instances
2. Lower cost by adjusting the number of Amazon EC2 instances
3.Replacing unhealthy Amazon EC2 instances
4. Having the right amount of computing capacity

  ANS 3

  Overall explanation
Correct option:

Replacing unhealthy Amazon EC2 instances

Amazon EC2 Auto Scaling helps you maintain application availability and allows you to automatically add or remove Amazon EC2 instances according to the conditions you define. You can use the fleet management features of Amazon EC2 Auto Scaling to maintain the health and availability of your fleet. You can also use the dynamic and predictive scaling features of Amazon EC2 Auto Scaling to add or remove EC2 instances.

Amazon EC2 Auto Scaling can detect when an instance is unhealthy, terminate it, and replace it with a new one.

Incorrect options:

Lower cost by adjusting the number of Amazon EC2 instances - Amazon EC2 Auto Scaling adds instances only when needed, and can scale across purchase options to optimize performance and cost. However, this will not help with fault tolerance.

Distributing load to Amazon EC2 instances - Even though this helps with fault tolerance and is often used with Amazon EC2 Auto Scaling, it is a feature of Elastic Load Balancing (ELB) and not an Amazon EC2 Auto Scaling. Elastic Load Balancing automatically distributes incoming application traffic across multiple targets, such as Amazon EC2 instances, containers, IP addresses, and Lambda functions. It can handle the varying load of your application traffic in a single Availability Zone (AZ) or across multiple Availability Zones (AZs).

Having the right amount of computing capacity - Amazon EC2 Auto Scaling ensures that your application always has the right amount of computing capacity, so your application can handle the workload.

Reference:


# Question 4 Which AWS tool can provide best practice recommendations for performance, service limits, and cost optimization?

1. AWS Health Dashboard - Service health
2. AWS Trusted Advisor
3. Amazon CloudWatch
4. Amazon Inspector

#### Overall explanation
Correct option:
AWS Trusted Advisor

AWS Trusted Advisor is an online resource to help you reduce cost, increase performance, and improve security by optimizing your AWS environment. AWS Trusted Advisor provides real-time guidance to help you provision your resources following AWS best practices.

How AWS Trusted Advisor works:  via - https://aws.amazon.com/premiumsupport/technology/trusted-advisor/

Incorrect options:

Amazon Inspector - Amazon Inspector is an automated security assessment service that helps improve the security and compliance of applications deployed on your Amazon EC2 instances. Amazon Inspector automatically assesses applications for exposure, vulnerabilities, and deviations from best practices. Nevertheless, it does not provide best practice recommendations.

AWS Health Dashboard - Service health - AWS Health Dashboard - Service health publishes most up-to-the-minute information on the status and availability of all AWS services in tabular form for all Regions that AWS is present in. It does not provide best practice recommendations.

Amazon CloudWatch - Amazon CloudWatch is a monitoring and observability service built for DevOps engineers, developers, site reliability engineers (SREs), and IT managers. Amazon CloudWatch provides data and actionable insights to monitor applications, respond to system-wide performance changes, optimize resource utilization, and get a unified view of operational health. This is an excellent service for building Resilient systems. Think resource performance monitoring, events, and alerts; think Amazon CloudWatch. Amazon CloudWatch does not provide best practice recommendations.

Reference:

https://aws.amazon.com/premiumsupport/technology/trusted-advisor/

Domain
Security and Compliance

  # Question 5 According to the AWS Well-Architected Framework, which of the following statements are recommendations in the Operational Excellence pillar? (Select two)

1. Use serverless architectures
2. Anticipate failure
3. Make frequent, small, reversible changes
4. Enable traceability
5. Automatically recover from failure

Overall explanation
Correct options: 2,3
Anticipate failure
and 
Make frequent, small, reversible changes

The Operational Excellence pillar includes the ability to run and monitor systems to deliver business value and to continually improve supporting processes and procedures.

Perform “pre-mortem” exercises to identify potential sources of failure so that they can be removed or mitigated. Test your failure scenarios and validate your understanding of their impact. Test your response procedures to ensure that they are effective, and that teams are familiar with their execution. Set up regular game days to test workloads and team responses to simulated events.

Design workloads to allow components to be updated regularly. Make changes in small increments that can be reversed if they fail (without affecting customers when possible).

The AWS Well-Architected Framework helps you understand the pros and cons of the decisions you make while building systems on AWS. By using the Framework you will learn architectural best practices for designing and operating reliable, secure, efficient, and cost-effective systems in the cloud. It provides a way for you to consistently measure your architectures against best practices and identify areas for improvement.

The AWS Well-Architected Framework is based on six pillars — Operational Excellence, Security, Reliability, Performance Efficiency, Cost Optimization, and Sustainability.

Overview of the six pillars of the AWS Well-Architected Framework:

 via - https://aws.amazon.com/architecture/well-architected/

Incorrect options:

Enable traceability - Monitor, alert, and audit actions and changes to your environment in real-time. Integrate logs and metrics with systems to automatically respond and take action. It is a design principle of the Security pillar.

Automatically recover from failure - By monitoring a system for key performance indicators (KPIs), you can trigger automation when a threshold is breached. This allows for automatic notification and tracking of failures, and for automated recovery processes that work around or repair the failure. With more sophisticated automation, it's possible to anticipate and remediate failures before they occur. It is a design principle of the Reliability pillar.

Use serverless architectures - In the cloud, serverless architectures remove the need for you to run and maintain servers to carry out traditional compute activities. For example, storage services can act as static websites, removing the need for web servers, and event services can host your code for you. This not only removes the operational burden of managing these servers but also can lower transactional costs because these managed services operate at a cloud scale. It is a design principle of the Performance Efficiency pillar.

Reference:

https://wa.aws.amazon.com/index.en.html

# Question 6 A company based in Sydney hosts its application on an Amazon Elastic Compute Cloud (Amazon EC2) instance in ap-southeast-2. They would like to deploy the same Amazon EC2 instances in eu-south-1. Which of the following AWS entities can address this use case?

1. Elastic Load Balancing (ELB)
2. Amazon Machine Image (AMI)
3. Amazon EBS Elastic Volume snapshots
4. AWS Lambda

Overall explanation
Correct option: 2

Amazon Machine Image (AMI)

An Amazon Machine Image (AMI) provides the information required to launch an instance. You must specify an Amazon Machine Image (AMI) when you launch an instance. You can launch multiple instances from a single Amazon Machine Image (AMI) when you need multiple instances with the same configuration.

How to use an Amazon Machine Image (AMI): 
https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/AMIs.html

Incorrect options:

Elastic Load Balancing (ELB) - Elastic Load Balancing (ELB) automatically distributes incoming application traffic across multiple targets, such as Amazon EC2 instances, containers, IP addresses, and Lambda functions. It can handle the varying load of your application traffic in a single Availability Zone (AZ) or across multiple Availability Zones (AZs). It cannot be used to deploy the same EC2 instances across different Availability Zones (AZs).

AWS Lambda - AWS Lambda lets you run code without provisioning or managing servers. It cannot be used to deploy the same EC2 instances across different Availability Zones (AZs).

Amazon EBS Elastic Volume snapshots - An Amazon EBS snapshot is a point-in-time copy of your Amazon EBS volume. EBS snapshots are one of the components of an AMI, but EBS snapshots alone cannot be used to deploy the same EC2 instances across different Availability Zones (AZs).

Reference:

https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/AMIs.html

# Question 7 A production company would like to establish an AWS managed virtual private network (VPN) service between its on-premises network and AWS. Which item needs to be set up on the company's side?

1. A security group
2. A VPC endpoint interface
3. A virtual private gateway (VGW)
4. A customer gateway

Overall explanation
Correct option: 4
A customer gateway

### A customer gateway device is a physical or software appliance on your side of a Site-to-Site VPN connection. You or your network administrator must configure the device to work with the Site-to-Site VPN connection.
You can enable access to your remote network from your VPC by creating an AWS Site-to-Site VPN (Site-to-Site VPN) connection, and configuring routing to pass traffic through the connection.
More on customer gateway device:  via - https://docs.aws.amazon.com/vpn/latest/s2svpn/your-cgw.html

Incorrect options:

### A security group - A security group acts as a virtual firewall for your instance to control inbound and outbound traffic. It is not a component of a connection between on-premises network and AWS.
### A VPC endpoint interface - An interface VPC endpoint (interface endpoint) enables you to connect to services powered by AWS PrivateLink. It is not a component of a connection between on-premises network and AWS.

### A virtual private gateway (VGW) - A virtual private gateway (VGW) device is a physical or software appliance on AWS side of a Site-to-Site VPN connection.

# Question 8 A Cloud Practitioner would like to get operational insights of its resources to quickly identify any issues that might impact applications using those resources. Which AWS service can help with this task?

1. AWS Trusted Advisor
2. AWS Systems Manager
3. Amazon Inspector
4. AWS Health Dashboard - Your Account Health

Overall explanation
### Correct option: 2
AWS Systems Manager

AWS Systems Manager allows you to centralize operational data from multiple AWS services and automate tasks across your AWS resources. You can create logical groups of resources such as applications, different layers of an application stack, or production versus development environments.

With AWS Systems Manager, you can select a resource group and view its recent API activity, resource configuration changes, related notifications, operational alerts, software inventory, and patch compliance status. You can also take action on each resource group depending on your operational needs. AWS Systems Manager provides a central place to view and manage your AWS resources, so you can have complete visibility and control over your operations.

How AWS Systems Manager works:  via - https://aws.amazon.com/systems-manager/

Incorrect options:

Amazon Inspector - Amazon Inspector is an automated security assessment service that helps improve the security and compliance of applications deployed on AWS. It is not used to get operational insights of AWS resources.

AWS Health Dashboard - Your Account Health - AWS Health Dashboard - Your Account Health provides alerts and remediation guidance when AWS is experiencing events that may impact you. It is not used to get operational insights of AWS resources.

AWS Trusted Advisor - AWS Trusted Advisor is an online resource to help you reduce cost, increase performance, and improve security by optimizing your AWS environment. AWS Trusted Advisor provides real-time guidance to help you provision your resources following AWS best practices. It is not used to get operational insights of AWS resources.

# Question 9 Which AWS serverless service allows you to prepare data for analytics?

1. Amazon Athena
2. Amazon Redshift
3. Amazon EMR
4. AWS Glue

Overall explanation
### Correct option: 4
AWS Glue

AWS Glue is a fully managed extract, transform, and load (ETL) service that makes it easy for customers to prepare and load their data for analytics. AWS Glue job is meant to be used for batch ETL data processing.

How AWS Glue works:  via - https://aws.amazon.com/glue/

Incorrect options:

Amazon Athena - Amazon Athena is an interactive query service that makes it easy to analyze data in Amazon Simple Storage Service (Amazon S3) using standard SQL. Athena is serverless, so there is no infrastructure to manage, and you pay only for the queries that you run. Amazon Athena is used for analytics and not to prepare data for analytics.

Amazon Redshift - Amazon Redshift is a fast and scalable data warehouse that makes it simple and cost-effective to analyze all your data across your data warehouse and data lake. Redshift is used for analytics and not to prepare data for analytics.

Amazon EMR - Amazon EMR provides a managed Hadoop framework that makes it easy, fast, and cost-effective to process vast amounts of data across dynamically scalable Amazon EC2 instances. EMR is used for analytics and not to prepare data for analytics.

Reference:

https://aws.amazon.com/glue/

# Question 10 Which of the following billing timeframes is applied when running a Windows EC2 on-demand instance?

1. Pay per minute

2. Pay per hour

3. Pay per day
   
4. Pay per second

Overall explanation
### Correct option: 4
Pay per second

With On-Demand instances, you only pay for the Amazon EC2 instances you use. The use of On-Demand instances frees you from the costs and complexities of planning, purchasing, and maintaining hardware and transforms what are commonly large fixed costs into much smaller variable costs.

When running a Windows EC2 on-demand instance, pay-per-second pricing is applied.

Incorrect options:

Pay per hour - When running an Amazon Windows EC2 On-demand instance, pay-per-second pricing is applied. Windows-based EC2 instances used to follow pay-per-hour pricing earlier.

Pay per minute - Pay per minute pricing is not available for Windows EC2 on-demand instances, or any other type of on-demand EC2 instance.

Pay per day - Pay per day pricing is not available for Windows EC2 on-demand instances, or any other type of on-demand EC2 instance.

Reference:

https://aws.amazon.com/ec2/pricing/

# Question 11 A company would like to reserve Amazon Elastic Compute Cloud (Amazon EC2) compute capacity for three years to reduce costs. The company also plans to increase their workloads during this period. As a Cloud Practitioner, which Amazon Elastic Compute Cloud (Amazon EC2) reserved instance (RI) type would you recommend?

1. Convertible reserved instance (RI)

2. Standard reserved instance (RI)

3. Adaptable reserved instances (RI)

4. Scheduled reserved instance (RI)

Overall explanation
### Correct option: 1
Convertible reserved instance (RI)

Purchase convertible reserved instance (RI) if you need additional flexibility, such as the ability to use different instance families, operating systems, or tenancies over the reserved instance (RI) term. Convertible reserved instance (RI) provides you with a significant discount (up to 54%) compared to an on-demand instance and can be purchased for a 1-year or 3-year term.

Convertible reserved instance (RI) can be useful when workloads are likely to change. In this case, a convertible reserved instance (RI) enables you to adapt as needs evolve while still obtaining discounts and capacity reservation.

Amazon EC2 Pricing Options Overview:  via - https://aws.amazon.com/ec2/pricing/

Incorrect options:

Standard reserved instance (RI) - Standard reserved instance (RI) provides you with a significant discount (up to 72%) compared to on-demand instance pricing, and can be purchased for a 1-year or 3-year term. Standard reserved instance (RI) do not offer as much flexibility as convertible reserved instance (RI), such as not being able to change the instance family type; and therefore are not best-suited for this use case.

Review the differences between standard reserved instance (RI) and convertible reserved instance (RI): https://docs.aws.amazon.com/whitepapers/latest/cost-optimization-reservation-models/standard-vs.-convertible-offering-classes.html

Scheduled reserved instance (RI) - AWS does not support scheduled reserved instance (RI), so this option is ruled out.

Adaptable reserved instances (RI) - Adaptable reserved instance (RI) is not a valid type of reserved instance (RI). It is a distractor


# Question 12 Which AWS service can be used to subscribe to an RSS feed to be notified of the status of all AWS service interruptions?

1. Amazon Simple Notification Service (Amazon SNS)
2. AWS Lambda
3. AWS Health Dashboard - Service Health
4. AWS Health Dashboard - Your Account Health

Overall explanation
### Correct option: 3

AWS Health Dashboard - Service Health

The AWS Health Dashboard – Service health is the single place to learn about the availability and operations of AWS services. You can view the overall status of AWS services, and you can sign in to view personalized communications about your particular AWS account or organization.

You can check on this page https://health.aws.amazon.com/health/status to get current status information.

The AWS Health Dashboard – Service health offers the possibility to subscribe to an RSS feed to be notified of interruptions to each service.

Incorrect options:

Amazon Simple Notification Service (Amazon SNS) - Amazon Simple Notification Service (Amazon SNS) is a highly available, durable, secure, fully managed pub/sub messaging service that enables you to decouple microservices, distributed systems, and serverless applications. It can be used to deliver notifications, but it does not provide the current services' status.

AWS Health Dashboard - Your Account Health - Your AWS Health Dashboard – Your Account Health provides alerts and remediation guidance when AWS is experiencing events that may impact you.

AWS Lambda - AWS Lambda lets you run code without provisioning or managing servers. It does not provide all AWS services' status.

Reference:

https://health.aws.amazon.com/health/status






