---

copyright:
  years: 2017, 2020
lastupdated: "2020-07-07"

keywords: security controls, platform security, compliance, service endpoints, private endpoints

subcollection: overview

---

{:external: target="_blank" .external}
{:shortdesc: .shortdesc}
{:screen: .screen}
{:codeblock: .codeblock}
{:pre: .pre}
{:tip: .tip}
{:note: .note}
{:important: .important}

# How do I know that my data is safe?
{: #security}

<!-- STAGING ONLY CONTENT for the whole topic MEK -->

Designed with secure engineering practices, the {{site.data.keyword.cloud}} platform provides layered security controls across network and infrastructure. 
{:shortdesc}

{{site.data.keyword.cloud_notm}} ensures security readiness by adhering to security policies that are driven by best practices in IBM for systems, networking, and secure engineering. These policies include practices such as source code scanning, dynamic scanning, threat modeling, and penetration testing. {{site.data.keyword.cloud_notm}} follows the IBM Product Security Incident Response Team (PSIRT) process for security incident management. See the [IBM Security Vulnerability Management (PSIRT) ](https://www.ibm.com/security/secure-engineering/process.html){: external} site for details.

{{site.data.keyword.cloud_notm}} adds security capabilities at the platform-as-a-service (PaaS) layer in different categories: platform, data, and application. For further security details on your environment and apps in the {{site.data.keyword.Bluemix_notm}}, see [Securing applications and environments on cloud ](https://www.ibm.com/cloud/garage/architectures/securityArchitecture){: external}.

{{site.data.keyword.cloud_notm}} also provides a group of [security services](https://cloud.ibm.com/catalog?category=security#services) that can be used by application developers to secure their mobile and web apps. In addition, many of the services available in the catalog support enhanced security features such as service endpoints for using private routes, the ability to bring and manage your own encryption keys, and clearly documented data encryption and deletion policies. These elements combine to make {{site.data.keyword.cloud_notm}} a platform with clear choices for secure application development.

## Securing your connections by using service endpoints
{: #service-endpoints-support}

{{site.data.keyword.cloud_notm}} services that support the use of the service endpoint feature enable you to have enhanced control and security over your data when you use specific services from the {{site.data.keyword.cloud_notm}} catalog. Service endpoints provide the option of using private routes to {{site.data.keyword.cloud_notm}} service endpoints. Private routes are not accessible or reachable over the internet. 

By using the {{site.data.keyword.cloud_notm}} service endpoints feature, you can protect your data from threats from the public network and logically extend your private network. This capability enables an enterprise with strict security requirements to have confidence in moving workloads to the {{site.data.keyword.IBM_notm}} public cloud.

At this time, not all services support the use service endpoints to connect over a private network. Review the following table for a list of services that support this feature. For information about how to enable the feature for your account, see [Enabling VRF and service endpoints](/docs/account?topic=account-vrf-service-endpoint). And, for specific use of service endpoints per service, refer to the documentation for that service. 


<!-- dynamic table is inserted here -->
### Service Endpoint Support
{: #service-endpoint-supported-table}

| Service | Supported |
|-----|-----|
| API Connect |  |
| API Gateway |  |
| AT&T Flow Designer |  |
| AT&T IoT Data Plans |  |
| Accern-API |  |
| AccountScore |  |
| Actifio GO |  |
| Activity Tracker |  |
| Alert Notification |  |
| Alloy |  |
| Analytics Engine | ![Checkmark icon](../icons/checkmark-icon.svg) |
| Annotator for Clinical Data |  |
| Apache Spark |  |
| App Connect |  |
| App ID |  |
| Automated Accessibility Tester |  |
| Availability Monitoring |  |
| BigInsights for Apache Hadoop (Subscription) |  |
| Bitbar Testing Cloud |  |
| Block Storage for VPC |  |
| Blockchain |  |
| Blockchain Platform |  |
| Bondevalue-API |  |
| Bosch IoT Rollouts |  |
| Car Diagnostic API |  |
| Caveonix RiskForesight |  |
| Certificate Manager |  |
| Cloud Foundry Enterprise Environment |  |
| Cloud Object Storage |  |
| CloudAMQP |  |
| Cloudant |  |
| Compare and Comply |  |
| Compose Enterprise |  |
| Compose for Elasticsearch |  |
| Compose for JanusGraph |  |
| Compose for MongoDB |  |
| Compose for MySQL |  |
| Compose for PostgreSQL |  |
| Compose for RabbitMQ |  |
| Compose for Redis |  |
| Compose for RethinkDB |  |
| Compose for ScyllaDB |  |
| Compose for etcd |  |
| Consult with IBM Garage |  |
| Container Registry |  |
| Continuous Delivery |  |
| Continuous Release |  |
| Contrast Security |  |
| Cost and Asset Management |  |
| DNS Services |  |
| Data Store for Memcache |  |
| Databases for Elasticsearch |  |
| Databases for EnterpriseDB |  |
| Databases for MongoDB |  |
| Databases for PostgreSQL |  |
| Databases for Redis |  |
| Databases for etcd |  |
| Db2 |  |
| Db2 Hosted |  |
| Db2 Warehouse |  |
| Difitek |  |
| Digital Content Checker |  |
| Direct Link Dedicated |  |
| Discovery |  |
| Driver Behavior |  |
| Dwolla |  |
| ElephantSQL |  |
| Envestnet / Yodlee |  |
| Esri ArcGIS for Developers |  |
| Event Management |  |
| Event Streams | ![Checkmark icon](../icons/checkmark-icon.svg) |
| F5 BIG-IP |  |
| Floating IP for VPC |  |
| FortiGate Security Appliance |  |
| FortiGate Virtual Appliance |  |
| Functions |  |
| FundingShield - Wire Account Verification Service (WAVS) |  |
| FusionAuth |  |
| GEO Web Services |  |
| Geospatial Analytics |  |
| Globalization Pipeline |  |
| HCX |  |
| HPCaaS from Rescale |  |
| HazardHub Property Risk Data API |  |
| Health Score |  |
| Historical Instrument Analytics |  |
| Horizon 7 |  |
| HyTrust CloudControl |  |
| HyTrust DataControl |  |
| HyTrust KeyControl |  |
| Hydrogen |  |
| Hyper Protect Crypto Services |  |
| Hyper Protect DBaaS for MongoDB |  |
| Hyper Protect DBaaS for PostgreSQL |  |
| Hyper Protect Virtual Server |  |
| IBM Cloud Activity Tracker with LogDNA |  |
| IBM Cloud Data Shield |  |
| IBM Cloud Expert Services |  |
| IBM Cloud Monitoring with Sysdig |  |
| IBM Cloud Platform Group |  |
| IBM Cloud Platform OSB |  |
| IBM Cloud Private Hosted |  |
| IBM Cloud Secure Virtualization |  |
| IBM Cloud for VMware Mission Critical Workloads |  |
| IBM Cognos Dashboard Embedded |  |
| IBM Identity Mixer |  |
| IBM Log Analysis with LogDNA |  |
| IBM Spectrum Protect Plus |  |
| Image Service for VPC |  |
| InfluxCloud |  |
| Information Server |  |
| Informix |  |
| Instrument Analytics |  |
| Internet Services |  |
| Internet of Things Platform |  |
| Internet of Things Workbench |  |
| Investment Portfolio |  |
| KMIP for VMware |  |
| Key Protect |  |
| Knowledge Catalog |  |
| Knowledge Studio |  |
| Kubernetes Service | ![Checkmark icon](../icons/checkmark-icon.svg) |
| Language Translator |  |
| Lift CLI |  |
| Load Balancer for VPC |  |
| MQ |  |
| Machine Learning |  |
| Managed Backup Services |  |
| Managed Disaster Recovery Services |  |
| Managed VMware Services |  |
| Mass Data Migration |  |
| Master Data Management |  |
| Messages for RabbitMQ |  |
| Mobile Analytics |  |
| Mobile Foundation |  |
| Monitoring |  |
| Morningstar |  |
| Natural Language Classifier |  |
| Natural Language Generation APIs |  |
| Natural Language Understanding |  |
| NetApp ONTAP Select |  |
| Network ACL |  |
| Nexmo |  |
| PagerDuty |  |
| Payeezy |  |
| Personality Insights |  |
| Phunware Location Based Services |  |
| Phunware Mobile Marketing Automation |  |
| Plaid |  |
| Portfolio Optimization |  |
| Portworx Enterprise |  |
| Power Systems Virtual Server |  |
| PowerAI |  |
| Powerlytics Behavior/Propensity Model API |  |
| Powerlytics Consumer Income API |  |
| Powerlytics Investable Assets & Wealth API |  |
| Precision Location |  |
| Predictive Market Scenarios |  |
| Product Insights - Log Management |  |
| Project Coligo |  |
| Public Gateway for VPC |  |
| Push Notifications |  |
| Quovo |  |
| Rainbow |  |
| Raxak Protect |  |
| Real-Time Payments |  |
| Red Hat OpenShift on IBM Cloud | ![Checkmark icon](../icons/checkmark-icon.svg) |
| RelSci |  |
| Risk Engine |  |
| Rocket Mainframe Data |  |
| Runbook Automation |  |
| SPLICE Pre-CAT Insurance Notifications |  |
| SQL Query |  |
| SSH Key for VPC |  |
| Schematics |  |
| Secure Gateway |  |
| Security Advisor |  |
| Security Group for VPC |  |
| Simulated Historical Instrument Analytics |  |
| Simulated Instrument Analytics |  |
| Single-node Trial for Data Protection and Disaster Recovery |  |
| Single-node Trial for Migration and App Modernization |  |
| SizeUp Small Business Intelligence |  |
| Skytap On IBM Cloud |  |
| Speech to Text |  |
| Strands Business Financial Management |  |
| Streaming Analytics |  |
| Subnet |  |
| Telstra Messaging API |  |
| Text to Speech |  |
| Tone Analyzer |  |
| Toolchain |  |
| Totum Risk |  |
| TradeIt |  |
| Transit Gateway |  |
| Twilio Authy |  |
| Twilio Programmable SMS |  |
| Twilio Programmable Video |  |
| Twilio Programmable Voice |  |
| Twilio Verify |  |
| UnificationEngine |  |
| VMware Solutions |  |
| VMware vCenter Server |  |
| VMware vSphere |  |
| VPN for VPC |  |
| Veeam |  |
| Virtual Private Cloud |  |
| Virtual Private Network (VPN) |  |
| Virtual Server for VPC |  |
| Visual Recognition |  |
| Voice Agent with Watson |  |
| Watson Assistant |  |
| Watson OpenScale |  |
| Watson Studio |  |
| WealthEngine API |  |
| Weather Company Data |  |
| WebSphere Application Server |  |
| Workload Scheduler |  |
| Xignite Market Data APIs |  |
| Ylabs |  |
| Zerto |  |
| box |  |
| uCloud Multitenant Core Platform for VMware |  |
| vRealize Operations and Log Insight |  |
{: row-headers}
{: class="comparison-table"}
{: caption="Services that support the use of service endpoints" caption-side="top"}
{: summary="This table has row and column headers. The row headers identify the service. The column header identifies support for the service endpoint feature. Each cell in the table that has a checkmark means the service identified in that row supports using service endpoints."}
<!-- dynamic table ends here -->



## Securing your data in {{site.data.keyword.cloud_notm}} services
{: #platform-byok}

To ensure that you feel confident securely managing your data when you use {{site.data.keyword.cloud_notm}} services, it is important to know exactly what data is stored and encrypted and how you can delete any stored personal data. Each service documents this information for you, so that you can understand how each service stores and encrypts your data.

In addition to knowing how your data is encrypted, many {{site.data.keyword.cloud_notm}} services support data encryption by using customer-managed keys, also known as the bring-your-own-keys (BYOK). The most common use case for BYOK is using {{site.data.keyword.keymanagementservicelong}} to [bring your encryption keys to the cloud](/docs/key-protect?topic=key-protect-importing-keys). For a list of services that can be integrated with {{site.data.keyword.keymanagementserviceshort}}, see [Integrating services](/docs/key-protect?topic=key-protect-integrate-services).

If you're looking for a dedicated key management solution that supports customer-controlled, cloud-based hardware security modules (HSMs), {{site.data.keyword.cloud_notm}} services are starting to support by using [{{site.data.keyword.cloud_notm}} {{site.data.keyword.hscrypto}}](/docs/hs-crypto?topic=hs-crypto-get-started). {{site.data.keyword.hscrypto}} integrates with {{site.data.keyword.keymanagementserviceshort}} to enable keep-your-own-keys (KYOK) for {{site.data.keyword.cloud_notm}}, so your organization has more control and authority over its data. 

Each service might support different scenarios of the BYOK and KYOK capabilities. For more information, see the documentation for that service. 

<!-- Table to come to replace https://cloud.ibm.com/docs/key-protect?topic=key-protect-integrate-services when Robbie and team have global catalog metadata in place to report this via a dynamic table -->