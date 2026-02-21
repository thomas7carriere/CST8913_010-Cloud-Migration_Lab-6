Introduction

This lab focused on cloud services offered by the three largest cloud providers: Amazon Web Services (AWS), Microsoft Azure, and Google Cloud. Thirty use cases were analyzed to identify the corresponding cloud service from each provider that best met the criteria. Comparisons were then performed between the services offered by each provider for select use cases.

Use Case #3 – Managed Relational Database Services

For use case #3, AWS and Google Cloud provide Amazon RDS and Google Cloud SQL, which are both capable of supporting MySQL, PostgreSQL, and SQL Server.

Azure does not offer a single standalone service that supports all three database systems; therefore, several services would need to be employed:

Azure SQL Database for SQL Server

Azure Database for MySQL for MySQL

Azure Database for PostgreSQL for PostgreSQL

This highlights a structural difference in how Azure separates database offerings compared to AWS and Google Cloud.

Use Case #25 – Desktop as a Service (DaaS)

For use case #25, AWS and Azure both provide DaaS offerings with:

Amazon WorkSpaces

Azure Virtual Desktop

Google Cloud does not provide a strongly equivalent standalone service. However, by pairing Google Compute Engine (GCE) with a Virtual Desktop Infrastructure (VDI) provider, a similar outcome can be achieved.

One potential benefit of a Google Cloud solution is that GCE provides very granular control of resources, allowing clients to optimize virtual machines for their needs and potentially reduce hosting costs.

Use Case #30 – Real-Time Communication Services

For use case #30, AWS offers Simple Notification Service (SNS), which provides support for:

SMS

Email

Push notifications to devices

Azure and Google do not provide a single service with all these capabilities.

Azure Solution

A combination of:

Azure Notification Hubs (push notifications and app alerts)

Azure Communication Services (SMS and email)

can be used to meet the requirements.

Google Cloud Solution

Google provides Firebase Cloud Messaging, which supports push notifications. However, Google does not provide a strong native service for real-time communication via SMS and email.

In this case, a third-party service such as Twilio can be integrated with Firebase Cloud Messaging to bridge the gap in requirements.

Naming Conventions Across Cloud Providers

The naming conventions used for each service depend upon the provider.

AWS often uses more abstract names with deeper meaning.

Azure and Google Cloud tend to use more straightforward, descriptive names.

AWS Example

Elastic Beanstalk (PaaS service for deploying and scaling web applications)

“Elastic” refers to the service’s ability to automatically scale.

“Beanstalk” suggests a clear path to grow and develop an application, inspired by the fairy tale Jack and the Beanstalk.

Google Example

Pub/Sub clearly describes its fully managed publisher/subscriber messaging model.

Azure Example

Azure Virtual Machines clearly describes the service used to create virtual machines hosted on Azure infrastructure.

For clarity and unambiguity, Azure appears to have the most consistent and easily understandable naming conventions.
