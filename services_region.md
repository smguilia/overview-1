---
copyright:
  years: 2015, 2021
lastupdate: "2021-01-11"

keywords: location, regions, data centers, service location, service availability, multizone regions, MZR

subcollection: account

---
{:external: target="_blank" .external}
{:shortdesc: .shortdesc}


# Service and infrastructure availability by location
{: #services_region}

{{site.data.keyword.Bluemix}} makes it easy for you to implement, host, and scale services, infrastructure, and apps so you can focus on your application logic and application design.
{:shortdesc}

IBM provides SDKs and APIs for all services that are general availablity. Check out the reference docs in the [API & SDK reference library](/docs?tab=api-docs). 

Not all services and infrastructure are available for purchase in every {{site.data.keyword.Bluemix_notm}} location. 

## Services
{: #paas-services}

Some services are available to purchase in a location, but that service's data might be hosted in a different location. The following table shows the services that are provided by IBM. For the full list of resources that are available, see the [catalog](https://cloud.ibm.com/catalog){: external}  in the {{site.data.keyword.Bluemix_notm}} console.

Services that are hosted globally create resources that operate across multiple locations. For example, with {{site.data.keyword.cos_full_notm}}, you can choose to deploy data in a single data center, or even a combination of locations by selecting the endpoint where your application sends REST API requests.| Service |  Dallas |  Washington DC | 
|-----|-----|-----|
| API Connect | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) |
| API Gateway | Hosted Globally | Hosted Globally |
| Analytics Engine | ![Checkmark icon](../icons/checkmark-icon.svg) |  |
| Annotator for Clinical Data | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) |
| App Configuration | ![Checkmark icon](../icons/checkmark-icon.svg) |  |
| App Connect | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) |
| App ID | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) |
| Auto Scale for VPC | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) |
| Block Storage for VPC | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) |
| Blockchain | ![Checkmark icon](../icons/checkmark-icon.svg) |  |
| Blockchain Platform | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) |
| Caveonix RiskForesight | ![Checkmark icon](../icons/checkmark-icon.svg) |  |
| Certificate Manager | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) |
| Cloud Foundry Enterprise Environment | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) |
| Cloudant | Hosted Globally | Hosted Globally |
| Code Engine | ![Checkmark icon](../icons/checkmark-icon.svg) |  |
| Compose Enterprise | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) |
| Compose for JanusGraph | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) |
| Compose for MySQL | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) |
| Compose for RethinkDB | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) |
| Compose for ScyllaDB | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) |
| Consult with IBM Garage | Hosted Globally | Hosted Globally |
| Container Registry | Hosted Globally | Hosted Globally |
| Continuous Delivery | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) |
| Cost and Asset Management | ![Checkmark icon](../icons/checkmark-icon.svg) |  |
| DNS Services | Hosted Globally | Hosted Globally |
| Databases for Cassandra | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) |
| Databases for Elasticsearch | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) |
| Databases for EnterpriseDB | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) |
| Databases for MongoDB | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) |
| Databases for PostgreSQL | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) |
| Databases for Redis | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) |
| Databases for etcd | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) |
| Db2 | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) |
| Db2 Hosted | ![Checkmark icon](../icons/checkmark-icon.svg) |  |
| Db2 Warehouse | ![Checkmark icon](../icons/checkmark-icon.svg) |  |
| Direct Link Connect | Hosted Globally | Hosted Globally |
| Direct Link Dedicated (2.0) | Hosted Globally | Hosted Globally |
| Event Streams | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) |
| F5 BIG-IP | ![Checkmark icon](../icons/checkmark-icon.svg) |  |
| Floating IP for VPC | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) |
| Flow Logs for VPC | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) |
| FortiGate Security Appliance | ![Checkmark icon](../icons/checkmark-icon.svg) |  |
| FortiGate Virtual Appliance | ![Checkmark icon](../icons/checkmark-icon.svg) |  |
| Functions | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) |
| HCX | ![Checkmark icon](../icons/checkmark-icon.svg) |  |
| Historical Instrument Analytics | ![Checkmark icon](../icons/checkmark-icon.svg) |  |
| Horizon 7 | ![Checkmark icon](../icons/checkmark-icon.svg) |  |
| HyTrust CloudControl | ![Checkmark icon](../icons/checkmark-icon.svg) |  |
| HyTrust DataControl | ![Checkmark icon](../icons/checkmark-icon.svg) |  |
| HyTrust KeyControl | ![Checkmark icon](../icons/checkmark-icon.svg) |  |
| Hyper Protect Crypto Services | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) |
| Hyper Protect DBaaS for MongoDB | ![Checkmark icon](../icons/checkmark-icon.svg) |  |
| Hyper Protect DBaaS for PostgreSQL | ![Checkmark icon](../icons/checkmark-icon.svg) |  |
| Hyper Protect Virtual Server | Hosted Globally | Hosted Globally |
| IBM Cloud Activity Tracker with LogDNA | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) |
| IBM Cloud Data Shield | Hosted Globally | Hosted Globally |
| IBM Cloud Expert Services | ![Checkmark icon](../icons/checkmark-icon.svg) |  |
| IBM Cloud Monitoring with Sysdig | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) |
| IBM Cloud Platform Group | Hosted Globally | Hosted Globally |
| IBM Cloud Private Hosted | ![Checkmark icon](../icons/checkmark-icon.svg) |  |
| IBM Cloud Satellite | ![Checkmark icon](../icons/checkmark-icon.svg) |  |
| IBM Cloud Secure Virtualization | ![Checkmark icon](../icons/checkmark-icon.svg) |  |
| IBM Cloud for VMware Mission Critical Workloads | ![Checkmark icon](../icons/checkmark-icon.svg) |  |
| IBM Cognos Dashboard Embedded | ![Checkmark icon](../icons/checkmark-icon.svg) |  |
| IBM Log Analysis with LogDNA | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) |
| IBM Spectrum Protect Plus | ![Checkmark icon](../icons/checkmark-icon.svg) |  |
| Image Service for VPC | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) |
| Information Server | ![Checkmark icon](../icons/checkmark-icon.svg) |  |
| Informix | ![Checkmark icon](../icons/checkmark-icon.svg) |  |
| Instrument Analytics | ![Checkmark icon](../icons/checkmark-icon.svg) |  |
| Internet Services | Hosted Globally | Hosted Globally |
| Internet of Things Platform | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) |
| Investment Portfolio | ![Checkmark icon](../icons/checkmark-icon.svg) |  |
| KMIP for VMware | ![Checkmark icon](../icons/checkmark-icon.svg) |  |
| Key Protect | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) |
| Knowledge Studio | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) |
| Kubernetes Service | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) |
| Language Translator | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) |
| Lift CLI | ![Checkmark icon](../icons/checkmark-icon.svg) |  |
| Load Balancer for VPC | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) |
| MQ | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) |
| Machine Learning | ![Checkmark icon](../icons/checkmark-icon.svg) |  |
| Managed Backup Services | ![Checkmark icon](../icons/checkmark-icon.svg) |  |
| Managed Disaster Recovery Services | ![Checkmark icon](../icons/checkmark-icon.svg) |  |
| Managed VMware Services | ![Checkmark icon](../icons/checkmark-icon.svg) |  |
| Mass Data Migration | Hosted Globally | Hosted Globally |
| Master Data Management | ![Checkmark icon](../icons/checkmark-icon.svg) |  |
| Master Data Management on Cloud (Hosted) | ![Checkmark icon](../icons/checkmark-icon.svg) |  |
| Messages for RabbitMQ | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) |
| Natural Language Classifier | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) |
| Natural Language Understanding | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) |
| NetApp ONTAP Select | ![Checkmark icon](../icons/checkmark-icon.svg) |  |
| Network ACL | Hosted Globally | Hosted Globally |
| Object Storage | Hosted Globally | Hosted Globally |
| Portfolio Optimization | ![Checkmark icon](../icons/checkmark-icon.svg) |  |
| Power Systems Virtual Server | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) |
| Predictive Market Scenarios | ![Checkmark icon](../icons/checkmark-icon.svg) |  |
| Public Gateway | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) |
| Push Notifications | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) |
| Real-Time Payments | ![Checkmark icon](../icons/checkmark-icon.svg) |  |
| Red Hat OpenShift on IBM Cloud | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) |
| SQL Query | ![Checkmark icon](../icons/checkmark-icon.svg) |  |
| SSH Key for VPC | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) |
| Schematics | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) |
| Secrets Manager | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) |
| Secure Gateway | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) |
| Security Advisor | ![Checkmark icon](../icons/checkmark-icon.svg) |  |
| Security Group for VPC | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) |
| Simulated Historical Instrument Analytics | ![Checkmark icon](../icons/checkmark-icon.svg) |  |
| Simulated Instrument Analytics | ![Checkmark icon](../icons/checkmark-icon.svg) |  |
| Single-node Trial for Data Protection and Disaster Recovery | ![Checkmark icon](../icons/checkmark-icon.svg) |  |
| Single-node Trial for Migration and App Modernization | ![Checkmark icon](../icons/checkmark-icon.svg) |  |
| Speech to Text | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) |
| Streaming Analytics | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) |
| Subnet | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) |
| Text to Speech | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) |
| Tone Analyzer | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) |
| Toolchain | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) |
| Transit Gateway | Hosted Globally | Hosted Globally |
| VMware Solutions | Hosted Globally | Hosted Globally |
| VMware vCenter Server | ![Checkmark icon](../icons/checkmark-icon.svg) |  |
| VMware vSphere | ![Checkmark icon](../icons/checkmark-icon.svg) |  |
| VPN for VPC | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) |
| Veeam | ![Checkmark icon](../icons/checkmark-icon.svg) |  |
| Virtual Private Cloud | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) |
| Virtual Private Endpoint for VPC | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) |
| Virtual Server for VPC | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) |
| Voice Agent with Watson | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) |
| Watson Assistant | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) |
| Watson Discovery | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) |
| Watson Knowledge Catalog | ![Checkmark icon](../icons/checkmark-icon.svg) |  |
| Watson OpenScale | ![Checkmark icon](../icons/checkmark-icon.svg) |  |
| Watson Studio | ![Checkmark icon](../icons/checkmark-icon.svg) |  |
| WebSphere Application Server | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) |
| Zerto | ![Checkmark icon](../icons/checkmark-icon.svg) |  |
| vRealize Operations and Log Insight | ![Checkmark icon](../icons/checkmark-icon.svg) |  |
{: row-headers}
{: caption="Table 1. Service availability - Americas" caption-side="top"}
{: #paas-table1}
{: tab-title="Americas"}
{: tab-group="PaaS"}
{: class="simple-tab-table"}
{: summary="Use the buttons for the countries to change the context of the table. This table has row and column headers. The row headers identify the service. The column headers indentify where that service is located. To understand where a service is located in the table, navigate to the row, and find the for the location you are interested in."}



| Service |  Osaka |  Seoul |  Singapore |  Sydney |  Tokyo | 
|-----|-----|-----|-----|-----|-----|
| API Connect |  |  |  | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) |
| API Gateway | Hosted Globally | Hosted Globally | Hosted Globally | Hosted Globally | Hosted Globally |
| Analytics Engine |  |  |  |  | ![Checkmark icon](../icons/checkmark-icon.svg) |
| Annotator for Clinical Data |  |  |  |  |  |
| App Configuration |  |  |  |  |  |
| App Connect |  |  |  | ![Checkmark icon](../icons/checkmark-icon.svg) |  |
| App ID |  |  |  | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) |
| Auto Scale for VPC | ![Checkmark icon](../icons/checkmark-icon.svg) |  |  | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) |
| Block Storage for VPC |  |  |  | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) |
| Blockchain |  |  |  | ![Checkmark icon](../icons/checkmark-icon.svg) |  |
| Blockchain Platform |  |  |  | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) |
| Caveonix RiskForesight |  |  |  |  |  |
| Certificate Manager |  |  |  | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) |
| Cloud Foundry Enterprise Environment |  |  |  | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) |
| Cloudant | Hosted Globally | Hosted Globally | Hosted Globally | Hosted Globally | Hosted Globally |
| Code Engine |  |  |  |  |  |
| Compose Enterprise |  |  |  | ![Checkmark icon](../icons/checkmark-icon.svg) |  |
| Compose for JanusGraph |  |  |  | ![Checkmark icon](../icons/checkmark-icon.svg) |  |
| Compose for MySQL |  |  |  | ![Checkmark icon](../icons/checkmark-icon.svg) |  |
| Compose for RethinkDB |  |  |  | ![Checkmark icon](../icons/checkmark-icon.svg) |  |
| Compose for ScyllaDB |  |  |  | ![Checkmark icon](../icons/checkmark-icon.svg) |  |
| Consult with IBM Garage | Hosted Globally | Hosted Globally | Hosted Globally | Hosted Globally | Hosted Globally |
| Container Registry | Hosted Globally | Hosted Globally | Hosted Globally | Hosted Globally | Hosted Globally |
| Continuous Delivery |  |  |  | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) |
| Cost and Asset Management |  |  |  |  |  |
| DNS Services | Hosted Globally | Hosted Globally | Hosted Globally | Hosted Globally | Hosted Globally |
| Databases for Cassandra |  |  |  | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) |
| Databases for Elasticsearch |  |  |  | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) |
| Databases for EnterpriseDB |  |  |  | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) |
| Databases for MongoDB |  |  |  | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) |
| Databases for PostgreSQL |  |  |  | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) |
| Databases for Redis |  |  |  | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) |
| Databases for etcd |  |  |  | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) |
| Db2 |  |  |  | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) |
| Db2 Hosted |  |  |  | ![Checkmark icon](../icons/checkmark-icon.svg) |  |
| Db2 Warehouse |  |  |  | ![Checkmark icon](../icons/checkmark-icon.svg) |  |
| Direct Link Connect | Hosted Globally | Hosted Globally | Hosted Globally | Hosted Globally | Hosted Globally |
| Direct Link Dedicated (2.0) | Hosted Globally | Hosted Globally | Hosted Globally | Hosted Globally | Hosted Globally |
| Event Streams |  |  |  | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) |
| F5 BIG-IP |  |  |  |  |  |
| Floating IP for VPC | ![Checkmark icon](../icons/checkmark-icon.svg) |  |  | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) |
| Flow Logs for VPC | ![Checkmark icon](../icons/checkmark-icon.svg) |  |  | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) |
| FortiGate Security Appliance |  |  |  |  |  |
| FortiGate Virtual Appliance |  |  |  |  |  |
| Functions |  |  |  |  | ![Checkmark icon](../icons/checkmark-icon.svg) |
| HCX |  |  |  |  |  |
| Historical Instrument Analytics |  |  |  |  |  |
| Horizon 7 |  |  |  |  |  |
| HyTrust CloudControl |  |  |  |  |  |
| HyTrust DataControl |  |  |  |  |  |
| HyTrust KeyControl |  |  |  |  |  |
| Hyper Protect Crypto Services |  |  |  | ![Checkmark icon](../icons/checkmark-icon.svg) |  |
| Hyper Protect DBaaS for MongoDB |  |  |  | ![Checkmark icon](../icons/checkmark-icon.svg) |  |
| Hyper Protect DBaaS for PostgreSQL |  |  |  | ![Checkmark icon](../icons/checkmark-icon.svg) |  |
| Hyper Protect Virtual Server | Hosted Globally | Hosted Globally | Hosted Globally | Hosted Globally | Hosted Globally |
| IBM Cloud Activity Tracker with LogDNA |  |  |  | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) |
| IBM Cloud Data Shield | Hosted Globally | Hosted Globally | Hosted Globally | Hosted Globally | Hosted Globally |
| IBM Cloud Expert Services |  |  |  |  |  |
| IBM Cloud Monitoring with Sysdig |  |  |  | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) |
| IBM Cloud Platform Group | Hosted Globally | Hosted Globally | Hosted Globally | Hosted Globally | Hosted Globally |
| IBM Cloud Private Hosted |  |  |  |  |  |
| IBM Cloud Satellite |  |  |  |  |  |
| IBM Cloud Secure Virtualization |  |  |  |  |  |
| IBM Cloud for VMware Mission Critical Workloads |  |  |  |  |  |
| IBM Cognos Dashboard Embedded |  |  |  |  |  |
| IBM Log Analysis with LogDNA |  |  |  | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) |
| IBM Spectrum Protect Plus |  |  |  |  |  |
| Image Service for VPC | ![Checkmark icon](../icons/checkmark-icon.svg) |  |  | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) |
| Information Server |  |  |  | ![Checkmark icon](../icons/checkmark-icon.svg) |  |
| Informix |  |  |  | ![Checkmark icon](../icons/checkmark-icon.svg) |  |
| Instrument Analytics |  |  |  |  |  |
| Internet Services | Hosted Globally | Hosted Globally | Hosted Globally | Hosted Globally | Hosted Globally |
| Internet of Things Platform |  |  |  |  |  |
| Investment Portfolio |  |  |  |  |  |
| KMIP for VMware |  |  |  |  |  |
| Key Protect | ![Checkmark icon](../icons/checkmark-icon.svg) |  |  | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) |
| Knowledge Studio |  |  |  | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) |
| Kubernetes Service | ![Checkmark icon](../icons/checkmark-icon.svg) |  |  | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) |
| Language Translator |  |  |  | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) |
| Lift CLI |  |  |  |  |  |
| Load Balancer for VPC | ![Checkmark icon](../icons/checkmark-icon.svg) |  |  | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) |
| MQ |  |  |  | ![Checkmark icon](../icons/checkmark-icon.svg) |  |
| Machine Learning |  |  |  |  | ![Checkmark icon](../icons/checkmark-icon.svg) |
| Managed Backup Services |  |  |  |  |  |
| Managed Disaster Recovery Services |  |  |  |  |  |
| Managed VMware Services |  |  |  |  |  |
| Mass Data Migration | Hosted Globally | Hosted Globally | Hosted Globally | Hosted Globally | Hosted Globally |
| Master Data Management |  |  |  |  |  |
| Master Data Management on Cloud (Hosted) |  |  |  | ![Checkmark icon](../icons/checkmark-icon.svg) |  |
| Messages for RabbitMQ |  |  |  | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) |
| Natural Language Classifier |  |  |  | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) |
| Natural Language Understanding |  |  |  | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) |
| NetApp ONTAP Select |  |  |  |  |  |
| Network ACL | Hosted Globally | Hosted Globally | Hosted Globally | Hosted Globally | Hosted Globally |
| Object Storage | Hosted Globally | Hosted Globally | Hosted Globally | Hosted Globally | Hosted Globally |
| Portfolio Optimization |  |  |  |  |  |
| Power Systems Virtual Server |  |  |  |  |  |
| Predictive Market Scenarios |  |  |  |  |  |
| Public Gateway | ![Checkmark icon](../icons/checkmark-icon.svg) |  |  | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) |
| Push Notifications |  |  |  | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) |
| Real-Time Payments |  |  |  |  |  |
| Red Hat OpenShift on IBM Cloud |  |  |  | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) |
| SQL Query |  |  |  |  |  |
| SSH Key for VPC | ![Checkmark icon](../icons/checkmark-icon.svg) |  |  | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) |
| Schematics |  |  |  |  |  |
| Secrets Manager |  |  |  | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) |
| Secure Gateway |  |  |  | ![Checkmark icon](../icons/checkmark-icon.svg) |  |
| Security Advisor |  |  |  |  |  |
| Security Group for VPC | ![Checkmark icon](../icons/checkmark-icon.svg) |  |  | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) |
| Simulated Historical Instrument Analytics |  |  |  |  |  |
| Simulated Instrument Analytics |  |  |  |  |  |
| Single-node Trial for Data Protection and Disaster Recovery |  |  |  |  |  |
| Single-node Trial for Migration and App Modernization |  |  |  |  |  |
| Speech to Text |  |  |  | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) |
| Streaming Analytics |  |  |  | ![Checkmark icon](../icons/checkmark-icon.svg) |  |
| Subnet | ![Checkmark icon](../icons/checkmark-icon.svg) |  |  | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) |
| Text to Speech |  |  |  | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) |
| Tone Analyzer |  |  |  | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) |
| Toolchain |  |  |  | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) |
| Transit Gateway | Hosted Globally | Hosted Globally | Hosted Globally | Hosted Globally | Hosted Globally |
| VMware Solutions | Hosted Globally | Hosted Globally | Hosted Globally | Hosted Globally | Hosted Globally |
| VMware vCenter Server |  |  |  |  |  |
| VMware vSphere |  |  |  |  |  |
| VPN for VPC | ![Checkmark icon](../icons/checkmark-icon.svg) |  |  | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) |
| Veeam |  |  |  |  |  |
| Virtual Private Cloud | ![Checkmark icon](../icons/checkmark-icon.svg) |  |  | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) |
| Virtual Private Endpoint for VPC | ![Checkmark icon](../icons/checkmark-icon.svg) |  |  | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) |
| Virtual Server for VPC | ![Checkmark icon](../icons/checkmark-icon.svg) |  |  | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) |
| Voice Agent with Watson |  |  |  |  |  |
| Watson Assistant |  |  |  | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) |
| Watson Discovery |  |  |  | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) |
| Watson Knowledge Catalog |  |  |  |  | ![Checkmark icon](../icons/checkmark-icon.svg) |
| Watson OpenScale |  |  |  |  |  |
| Watson Studio |  |  |  |  | ![Checkmark icon](../icons/checkmark-icon.svg) |
| WebSphere Application Server |  |  |  | ![Checkmark icon](../icons/checkmark-icon.svg) |  |
| Zerto |  |  |  |  |  |
| vRealize Operations and Log Insight |  |  |  |  |  |
{: row-headers}
{: caption="Table 2. Service availability - Asia Pacific" caption-side="top"}
{: #paas-table2}
{: tab-title="Asia Pacific"}
{: tab-group="PaaS"}
{: class="simple-tab-table"}
{: summary="Use the buttons for the countries to change the context of the table. This table has row and column headers. The row headers identify the service. The column headers indentify where that service is located. To understand where a service is located in the table, navigate to the row, and find the for the location you are interested in."}



| Service |  London |  Frankfurt | 
|-----|-----|-----|
| API Connect | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) |
| API Gateway | Hosted Globally | Hosted Globally |
| Analytics Engine | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) |
| Annotator for Clinical Data |  |  |
| App Configuration | ![Checkmark icon](../icons/checkmark-icon.svg) |  |
| App Connect | ![Checkmark icon](../icons/checkmark-icon.svg) |  |
| App ID | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) |
| Auto Scale for VPC | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) |
| Block Storage for VPC | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) |
| Blockchain | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) |
| Blockchain Platform | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) |
| Caveonix RiskForesight |  |  |
| Certificate Manager | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) |
| Cloud Foundry Enterprise Environment | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) |
| Cloudant | Hosted Globally | Hosted Globally |
| Code Engine |  | ![Checkmark icon](../icons/checkmark-icon.svg) |
| Compose Enterprise | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) |
| Compose for JanusGraph | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) |
| Compose for MySQL | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) |
| Compose for RethinkDB | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) |
| Compose for ScyllaDB | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) |
| Consult with IBM Garage | Hosted Globally | Hosted Globally |
| Container Registry | Hosted Globally | Hosted Globally |
| Continuous Delivery | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) |
| Cost and Asset Management |  |  |
| DNS Services | Hosted Globally | Hosted Globally |
| Databases for Cassandra | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) |
| Databases for Elasticsearch | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) |
| Databases for EnterpriseDB | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) |
| Databases for MongoDB | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) |
| Databases for PostgreSQL | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) |
| Databases for Redis | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) |
| Databases for etcd | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) |
| Db2 | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) |
| Db2 Hosted | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) |
| Db2 Warehouse | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) |
| Direct Link Connect | Hosted Globally | Hosted Globally |
| Direct Link Dedicated (2.0) | Hosted Globally | Hosted Globally |
| Event Streams | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) |
| F5 BIG-IP |  |  |
| Floating IP for VPC | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) |
| Flow Logs for VPC | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) |
| FortiGate Security Appliance |  |  |
| FortiGate Virtual Appliance |  |  |
| Functions | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) |
| HCX |  |  |
| Historical Instrument Analytics |  |  |
| Horizon 7 |  |  |
| HyTrust CloudControl |  |  |
| HyTrust DataControl |  |  |
| HyTrust KeyControl |  |  |
| Hyper Protect Crypto Services | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) |
| Hyper Protect DBaaS for MongoDB |  | ![Checkmark icon](../icons/checkmark-icon.svg) |
| Hyper Protect DBaaS for PostgreSQL |  | ![Checkmark icon](../icons/checkmark-icon.svg) |
| Hyper Protect Virtual Server | Hosted Globally | Hosted Globally |
| IBM Cloud Activity Tracker with LogDNA | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) |
| IBM Cloud Data Shield | Hosted Globally | Hosted Globally |
| IBM Cloud Expert Services |  |  |
| IBM Cloud Monitoring with Sysdig | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) |
| IBM Cloud Platform Group | Hosted Globally | Hosted Globally |
| IBM Cloud Private Hosted |  |  |
| IBM Cloud Satellite |  |  |
| IBM Cloud Secure Virtualization |  |  |
| IBM Cloud for VMware Mission Critical Workloads |  |  |
| IBM Cognos Dashboard Embedded | ![Checkmark icon](../icons/checkmark-icon.svg) |  |
| IBM Log Analysis with LogDNA | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) |
| IBM Spectrum Protect Plus |  |  |
| Image Service for VPC | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) |
| Information Server | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) |
| Informix | ![Checkmark icon](../icons/checkmark-icon.svg) |  |
| Instrument Analytics |  |  |
| Internet Services | Hosted Globally | Hosted Globally |
| Internet of Things Platform | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) |
| Investment Portfolio |  |  |
| KMIP for VMware |  |  |
| Key Protect | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) |
| Knowledge Studio | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) |
| Kubernetes Service | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) |
| Language Translator | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) |
| Lift CLI |  |  |
| Load Balancer for VPC | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) |
| MQ | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) |
| Machine Learning | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) |
| Managed Backup Services |  |  |
| Managed Disaster Recovery Services |  |  |
| Managed VMware Services |  |  |
| Mass Data Migration | Hosted Globally | Hosted Globally |
| Master Data Management |  |  |
| Master Data Management on Cloud (Hosted) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) |
| Messages for RabbitMQ | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) |
| Natural Language Classifier | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) |
| Natural Language Understanding | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) |
| NetApp ONTAP Select |  |  |
| Network ACL | Hosted Globally | Hosted Globally |
| Object Storage | Hosted Globally | Hosted Globally |
| Portfolio Optimization |  |  |
| Power Systems Virtual Server |  |  |
| Predictive Market Scenarios |  |  |
| Public Gateway | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) |
| Push Notifications | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) |
| Real-Time Payments |  |  |
| Red Hat OpenShift on IBM Cloud | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) |
| SQL Query |  | ![Checkmark icon](../icons/checkmark-icon.svg) |
| SSH Key for VPC | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) |
| Schematics |  | ![Checkmark icon](../icons/checkmark-icon.svg) |
| Secrets Manager | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) |
| Secure Gateway | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) |
| Security Advisor | ![Checkmark icon](../icons/checkmark-icon.svg) |  |
| Security Group for VPC | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) |
| Simulated Historical Instrument Analytics |  |  |
| Simulated Instrument Analytics |  |  |
| Single-node Trial for Data Protection and Disaster Recovery |  |  |
| Single-node Trial for Migration and App Modernization |  |  |
| Speech to Text | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) |
| Streaming Analytics | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) |
| Subnet | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) |
| Text to Speech | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) |
| Tone Analyzer | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) |
| Toolchain | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) |
| Transit Gateway | Hosted Globally | Hosted Globally |
| VMware Solutions | Hosted Globally | Hosted Globally |
| VMware vCenter Server |  |  |
| VMware vSphere |  |  |
| VPN for VPC | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) |
| Veeam |  |  |
| Virtual Private Cloud | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) |
| Virtual Private Endpoint for VPC | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) |
| Virtual Server for VPC | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) |
| Voice Agent with Watson |  | ![Checkmark icon](../icons/checkmark-icon.svg) |
| Watson Assistant | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) |
| Watson Discovery | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) |
| Watson Knowledge Catalog | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) |
| Watson OpenScale |  | ![Checkmark icon](../icons/checkmark-icon.svg) |
| Watson Studio | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) |
| WebSphere Application Server | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) |
| Zerto |  |  |
| vRealize Operations and Log Insight |  |  |
{: row-headers}
{: caption="Table 3. Service availability - Europe" caption-side="top"}
{: #paas-table3}
{: tab-title="Europe"}
{: tab-group="PaaS"}
{: class="simple-tab-table"}
{: summary="Use the buttons for the countries to change the context of the table. This table has row and column headers. The row headers identify the service. The column headers indentify where that service is located. To understand where a service is located in the table, navigate to the row, and find the for the location you are interested in."}



## Infrastructure
{: #iaas-service-infra}

Infrastructure services are available to be deployed in data centers. Each column header that ends with a number represents a data center or multi-zone region (MZR). Columns marked (MZR) represent a location where resources are automatically deployed and managed across several data centers.### Americas
{: #iaas-service-americas}

The following infrastructure resources are available in North and South America. Match the resource row with the column representing the data center or multi-zone region. A check mark indicates the resource is available in that location. The Dallas (MZR) and Washington DC (MZR) columns represent multi-zone regions where deployment is managed automatically across several data centers.

| Service |  sao01 |
|-----|-----|
| Bare Metal Server | ![Checkmark icon](../icons/checkmark-icon.svg) |
| Block Storage | ![Checkmark icon](../icons/checkmark-icon.svg) |
| Cloud HSM | |
| Cloud Migration | |
| Container Security Services | |
| Content Delivery Network | ![Checkmark icon](../icons/checkmark-icon.svg) |
| Direct Link Connect on Classic | |
| Direct Link Dedicated Hosting on Classic | ![Checkmark icon](../icons/checkmark-icon.svg) |
| Direct Link Dedicated on Classic | ![Checkmark icon](../icons/checkmark-icon.svg) |
| Direct Link Exchange on Classic | |
| Domain Name Registration | |
| Email Delivery, powered by Sendgrid | |
| File Storage | ![Checkmark icon](../icons/checkmark-icon.svg) |
| FortiGate Security Appliance | ![Checkmark icon](../icons/checkmark-icon.svg) |
| Gateway Appliance | ![Checkmark icon](../icons/checkmark-icon.svg) |
| Hardware Firewall | ![Checkmark icon](../icons/checkmark-icon.svg) |
| IBM Cloud Backup | ![Checkmark icon](../icons/checkmark-icon.svg) |
| IPSec VPN | ![Checkmark icon](../icons/checkmark-icon.svg) |
| Load Balancers | ![Checkmark icon](../icons/checkmark-icon.svg) |
| Managed Network Security Services | |
| Object Storage | |
| Professional Services for Government | |
| SSL Certificates | ![Checkmark icon](../icons/checkmark-icon.svg) |
| Subnets | ![Checkmark icon](../icons/checkmark-icon.svg) |
| VLAN | |
| Virtual Server for Classic | ![Checkmark icon](../icons/checkmark-icon.svg) |
{: row-headers}
{: caption="Table 4. Americas infrastructure availability - Brazil" caption-side="top"}
{: #iaas-table1}
{: tab-title="Brazil"}
{: tab-group="Americas"}
{: class="comparison-tab-table"}
{: summary="Use the buttons for the countries to change the context of the table. This table has row and column headers. The row headers identify the service. The column headers indentify where that service is located. To understand where a service is located in the table, navigate to the row, and find the for the location you are interested in."}


| Service |  mon01 | tor01 |
|-----|-----|-----|
| Bare Metal Server | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) |
| Block Storage | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) |
| Cloud HSM | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) |
| Cloud Migration | | |
| Container Security Services | | |
| Content Delivery Network | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) |
| Direct Link Connect on Classic | | |
| Direct Link Dedicated Hosting on Classic | | ![Checkmark icon](../icons/checkmark-icon.svg) |
| Direct Link Dedicated on Classic | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) |
| Direct Link Exchange on Classic | | |
| Domain Name Registration | | |
| Email Delivery, powered by Sendgrid | | |
| File Storage | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) |
| FortiGate Security Appliance | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) |
| Gateway Appliance | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) |
| Hardware Firewall | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) |
| IBM Cloud Backup | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) |
| IPSec VPN | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) |
| Load Balancers | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) |
| Managed Network Security Services | | |
| Object Storage | | |
| Professional Services for Government | | |
| SSL Certificates | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) |
| Subnets | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) |
| VLAN | | |
| Virtual Server for Classic | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) |
{: row-headers}
{: caption="Table 5. Americas infrastructure availability - Canada" caption-side="top"}
{: #iaas-table2}
{: tab-title="Canada"}
{: tab-group="Americas"}
{: class="comparison-tab-table"}
{: summary="Use the buttons for the countries to change the context of the table. This table has row and column headers. The row headers identify the service. The column headers indentify where that service is located. To understand where a service is located in the table, navigate to the row, and find the for the location you are interested in."}


| Service |  mex01 |
|-----|-----|
| Bare Metal Server | ![Checkmark icon](../icons/checkmark-icon.svg) |
| Block Storage | ![Checkmark icon](../icons/checkmark-icon.svg) |
| Cloud HSM | |
| Cloud Migration | |
| Container Security Services | |
| Content Delivery Network | ![Checkmark icon](../icons/checkmark-icon.svg) |
| Direct Link Connect on Classic | |
| Direct Link Dedicated Hosting on Classic | |
| Direct Link Dedicated on Classic | ![Checkmark icon](../icons/checkmark-icon.svg) |
| Direct Link Exchange on Classic | |
| Domain Name Registration | |
| Email Delivery, powered by Sendgrid | |
| File Storage | ![Checkmark icon](../icons/checkmark-icon.svg) |
| FortiGate Security Appliance | ![Checkmark icon](../icons/checkmark-icon.svg) |
| Gateway Appliance | ![Checkmark icon](../icons/checkmark-icon.svg) |
| Hardware Firewall | ![Checkmark icon](../icons/checkmark-icon.svg) |
| IBM Cloud Backup | ![Checkmark icon](../icons/checkmark-icon.svg) |
| IPSec VPN | ![Checkmark icon](../icons/checkmark-icon.svg) |
| Load Balancers | ![Checkmark icon](../icons/checkmark-icon.svg) |
| Managed Network Security Services | |
| Object Storage | |
| Professional Services for Government | |
| SSL Certificates | ![Checkmark icon](../icons/checkmark-icon.svg) |
| Subnets | ![Checkmark icon](../icons/checkmark-icon.svg) |
| VLAN | |
| Virtual Server for Classic | ![Checkmark icon](../icons/checkmark-icon.svg) |
{: row-headers}
{: caption="Table 6. Americas infrastructure availability - Mexico" caption-side="top"}
{: #iaas-table3}
{: tab-title="Mexico"}
{: tab-group="Americas"}
{: class="comparison-tab-table"}
{: summary="Use the buttons for the countries to change the context of the table. This table has row and column headers. The row headers identify the service. The column headers indentify where that service is located. To understand where a service is located in the table, navigate to the row, and find the for the location you are interested in."}


| Service |  us-south | dal10 | dal05 | dal06 | dal07 | dal09 | dal12 | dal13 | hou01 | hou02 | sea01 | sjc01 | sjc03 | sjc04 | us-east | wdc01 | wdc04 | wdc06 | wdc07 |
|-----|-----|-----|-----|-----|-----|-----|-----|-----|-----|-----|-----|-----|-----|-----|-----|-----|-----|-----|-----|
| Bare Metal Server | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | | | | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | | | | | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) |
| Block Storage | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | | | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) |
| Cloud HSM | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | | | | ![Checkmark icon](../icons/checkmark-icon.svg) | | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) |
| Cloud Migration | | | | | | | | | | | | | | | | | | | |
| Container Security Services | | | | | | | | | | | | | | | | | | | |
| Content Delivery Network | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) |
| Direct Link Connect on Classic | ![Checkmark icon](../icons/checkmark-icon.svg) | | | | | | | | | | | | | | ![Checkmark icon](../icons/checkmark-icon.svg) | | | | |
| Direct Link Dedicated Hosting on Classic | | ![Checkmark icon](../icons/checkmark-icon.svg) | | | | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | | | | | ![Checkmark icon](../icons/checkmark-icon.svg) | | | | ![Checkmark icon](../icons/checkmark-icon.svg) | | |
| Direct Link Dedicated on Classic | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | | | | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | | | | | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) |
| Direct Link Exchange on Classic | ![Checkmark icon](../icons/checkmark-icon.svg) | | | | | | | | | | | | | | ![Checkmark icon](../icons/checkmark-icon.svg) | | | | |
| Domain Name Registration | | | | | | | | | | | | | | | | | | | |
| Email Delivery, powered by Sendgrid | | | | | | | | | | | | | | | | | | | |
| File Storage | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | | | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) |
| FortiGate Security Appliance | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) |
| Gateway Appliance | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) |
| Hardware Firewall | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) |
| IBM Cloud Backup | | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) |
| IPSec VPN | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) |
| Load Balancers | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) |
| Managed Network Security Services | | | | | | | | | | | | | | | | | | | |
| Object Storage | ![Checkmark icon](../icons/checkmark-icon.svg) | | | | | | | | | | | | | | | | | | |
| Professional Services for Government | | | | | | | | | | | | | | | | | | | |
| SSL Certificates | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) |
| Subnets | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) |
| VLAN | | | | | | | | | | | | | | | | | | | |
| Virtual Server for Classic | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) |
{: row-headers}
{: caption="Table 7. Americas infrastructure availability - United States" caption-side="top"}
{: #iaas-table4}
{: tab-title="United States"}
{: tab-group="Americas"}
{: class="comparison-tab-table"}
{: summary="Use the buttons for the countries to change the context of the table. This table has row and column headers. The row headers identify the service. The column headers indentify where that service is located. To understand where a service is located in the table, navigate to the row, and find the for the location you are interested in."}


### Asia Pacific
{: #iaas-service-asia}

The following infrastructure resources are available in Asia and the Pacific region. Match the resource row with the column representing the data center or multi-zone region. A check mark indicates the resource is available in that location. The Sydney (MZR) and Tokyo (MZR) columns represent multi-zone regions where deployment is managed automatically across several data centers.

| Service |  mel01 | au-syd | syd01 | syd04 | syd05 |
|-----|-----|-----|-----|-----|-----|
| Bare Metal Server | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) |
| Block Storage | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) |
| Cloud HSM | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | |
| Cloud Migration | | | | | |
| Container Security Services | | | | | |
| Content Delivery Network | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) |
| Direct Link Connect on Classic | | ![Checkmark icon](../icons/checkmark-icon.svg) | | | |
| Direct Link Dedicated Hosting on Classic | ![Checkmark icon](../icons/checkmark-icon.svg) | | ![Checkmark icon](../icons/checkmark-icon.svg) | | ![Checkmark icon](../icons/checkmark-icon.svg) |
| Direct Link Dedicated on Classic | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) |
| Direct Link Exchange on Classic | | ![Checkmark icon](../icons/checkmark-icon.svg) | | | |
| Domain Name Registration | | | | | |
| Email Delivery, powered by Sendgrid | | | | | |
| File Storage | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) |
| FortiGate Security Appliance | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) |
| Gateway Appliance | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) |
| Hardware Firewall | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) |
| IBM Cloud Backup | ![Checkmark icon](../icons/checkmark-icon.svg) | | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) |
| IPSec VPN | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) |
| Load Balancers | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) |
| Managed Network Security Services | | | | | |
| Object Storage | | | | | |
| Professional Services for Government | | | | | |
| SSL Certificates | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) |
| Subnets | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) |
| VLAN | | | | | |
| Virtual Server for Classic | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) |
{: row-headers}
{: caption="Table 8. Asia Pacific infrastructure availability - Australia" caption-side="top"}
{: #iaas-table5}
{: tab-title="Australia"}
{: tab-group="Asia Pacific"}
{: class="comparison-tab-table"}
{: summary="Use the buttons for the countries to change the context of the table. This table has row and column headers. The row headers identify the service. The column headers indentify where that service is located. To understand where a service is located in the table, navigate to the row, and find the for the location you are interested in."}


| Service |  hkg02 |
|-----|-----|
| Bare Metal Server | |
| Block Storage | ![Checkmark icon](../icons/checkmark-icon.svg) |
| Cloud HSM | |
| Cloud Migration | |
| Container Security Services | |
| Content Delivery Network | ![Checkmark icon](../icons/checkmark-icon.svg) |
| Direct Link Connect on Classic | |
| Direct Link Dedicated Hosting on Classic | |
| Direct Link Dedicated on Classic | |
| Direct Link Exchange on Classic | |
| Domain Name Registration | |
| Email Delivery, powered by Sendgrid | |
| File Storage | ![Checkmark icon](../icons/checkmark-icon.svg) |
| FortiGate Security Appliance | ![Checkmark icon](../icons/checkmark-icon.svg) |
| Gateway Appliance | ![Checkmark icon](../icons/checkmark-icon.svg) |
| Hardware Firewall | ![Checkmark icon](../icons/checkmark-icon.svg) |
| IBM Cloud Backup | ![Checkmark icon](../icons/checkmark-icon.svg) |
| IPSec VPN | ![Checkmark icon](../icons/checkmark-icon.svg) |
| Load Balancers | ![Checkmark icon](../icons/checkmark-icon.svg) |
| Managed Network Security Services | |
| Object Storage | |
| Professional Services for Government | |
| SSL Certificates | ![Checkmark icon](../icons/checkmark-icon.svg) |
| Subnets | ![Checkmark icon](../icons/checkmark-icon.svg) |
| VLAN | |
| Virtual Server for Classic | ![Checkmark icon](../icons/checkmark-icon.svg) |
{: row-headers}
{: caption="Table 9. Asia Pacific infrastructure availability - Hong Kong" caption-side="top"}
{: #iaas-table6}
{: tab-title="Hong Kong"}
{: tab-group="Asia Pacific"}
{: class="comparison-tab-table"}
{: summary="Use the buttons for the countries to change the context of the table. This table has row and column headers. The row headers identify the service. The column headers indentify where that service is located. To understand where a service is located in the table, navigate to the row, and find the for the location you are interested in."}


| Service |  che01 |
|-----|-----|
| Bare Metal Server | ![Checkmark icon](../icons/checkmark-icon.svg) |
| Block Storage | ![Checkmark icon](../icons/checkmark-icon.svg) |
| Cloud HSM | ![Checkmark icon](../icons/checkmark-icon.svg) |
| Cloud Migration | |
| Container Security Services | |
| Content Delivery Network | ![Checkmark icon](../icons/checkmark-icon.svg) |
| Direct Link Connect on Classic | ![Checkmark icon](../icons/checkmark-icon.svg) |
| Direct Link Dedicated Hosting on Classic | |
| Direct Link Dedicated on Classic | ![Checkmark icon](../icons/checkmark-icon.svg) |
| Direct Link Exchange on Classic | |
| Domain Name Registration | |
| Email Delivery, powered by Sendgrid | |
| File Storage | ![Checkmark icon](../icons/checkmark-icon.svg) |
| FortiGate Security Appliance | ![Checkmark icon](../icons/checkmark-icon.svg) |
| Gateway Appliance | ![Checkmark icon](../icons/checkmark-icon.svg) |
| Hardware Firewall | ![Checkmark icon](../icons/checkmark-icon.svg) |
| IBM Cloud Backup | ![Checkmark icon](../icons/checkmark-icon.svg) |
| IPSec VPN | ![Checkmark icon](../icons/checkmark-icon.svg) |
| Load Balancers | ![Checkmark icon](../icons/checkmark-icon.svg) |
| Managed Network Security Services | |
| Object Storage | |
| Professional Services for Government | |
| SSL Certificates | ![Checkmark icon](../icons/checkmark-icon.svg) |
| Subnets | ![Checkmark icon](../icons/checkmark-icon.svg) |
| VLAN | |
| Virtual Server for Classic | ![Checkmark icon](../icons/checkmark-icon.svg) |
{: row-headers}
{: caption="Table 10. Asia Pacific infrastructure availability - India" caption-side="top"}
{: #iaas-table7}
{: tab-title="India"}
{: tab-group="Asia Pacific"}
{: class="comparison-tab-table"}
{: summary="Use the buttons for the countries to change the context of the table. This table has row and column headers. The row headers identify the service. The column headers indentify where that service is located. To understand where a service is located in the table, navigate to the row, and find the for the location you are interested in."}


| Service |  jp-tok | tok01 | tok02 | tok04 | tok05 |
|-----|-----|-----|-----|-----|-----|
| Bare Metal Server | ![Checkmark icon](../icons/checkmark-icon.svg) | | ![Checkmark icon](../icons/checkmark-icon.svg) | | ![Checkmark icon](../icons/checkmark-icon.svg) |
| Block Storage | ![Checkmark icon](../icons/checkmark-icon.svg) | | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) |
| Cloud HSM | ![Checkmark icon](../icons/checkmark-icon.svg) | | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | |
| Cloud Migration | | | | | |
| Container Security Services | | | | | |
| Content Delivery Network | ![Checkmark icon](../icons/checkmark-icon.svg) | | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) |
| Direct Link Connect on Classic | ![Checkmark icon](../icons/checkmark-icon.svg) | | | ![Checkmark icon](../icons/checkmark-icon.svg) | |
| Direct Link Dedicated Hosting on Classic | | | ![Checkmark icon](../icons/checkmark-icon.svg) | | |
| Direct Link Dedicated on Classic | ![Checkmark icon](../icons/checkmark-icon.svg) | | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) |
| Direct Link Exchange on Classic | ![Checkmark icon](../icons/checkmark-icon.svg) | | | | |
| Domain Name Registration | | | | | |
| Email Delivery, powered by Sendgrid | | | | | |
| File Storage | ![Checkmark icon](../icons/checkmark-icon.svg) | | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) |
| FortiGate Security Appliance | ![Checkmark icon](../icons/checkmark-icon.svg) | | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) |
| Gateway Appliance | ![Checkmark icon](../icons/checkmark-icon.svg) | | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) |
| Hardware Firewall | ![Checkmark icon](../icons/checkmark-icon.svg) | | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) |
| IBM Cloud Backup | | | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) |
| IPSec VPN | ![Checkmark icon](../icons/checkmark-icon.svg) | | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) |
| Load Balancers | ![Checkmark icon](../icons/checkmark-icon.svg) | | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) |
| Managed Network Security Services | | | | | |
| Object Storage | | | | | |
| Professional Services for Government | | | | | |
| SSL Certificates | ![Checkmark icon](../icons/checkmark-icon.svg) | | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) |
| Subnets | ![Checkmark icon](../icons/checkmark-icon.svg) | | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) |
| VLAN | | | | | |
| Virtual Server for Classic | ![Checkmark icon](../icons/checkmark-icon.svg) | | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) |
{: row-headers}
{: caption="Table 11. Asia Pacific infrastructure availability - Japan" caption-side="top"}
{: #iaas-table8}
{: tab-title="Japan"}
{: tab-group="Asia Pacific"}
{: class="comparison-tab-table"}
{: summary="Use the buttons for the countries to change the context of the table. This table has row and column headers. The row headers identify the service. The column headers indentify where that service is located. To understand where a service is located in the table, navigate to the row, and find the for the location you are interested in."}


| Service |  seo01 |
|-----|-----|
| Bare Metal Server | |
| Block Storage | ![Checkmark icon](../icons/checkmark-icon.svg) |
| Cloud HSM | |
| Cloud Migration | |
| Container Security Services | |
| Content Delivery Network | ![Checkmark icon](../icons/checkmark-icon.svg) |
| Direct Link Connect on Classic | |
| Direct Link Dedicated Hosting on Classic | ![Checkmark icon](../icons/checkmark-icon.svg) |
| Direct Link Dedicated on Classic | ![Checkmark icon](../icons/checkmark-icon.svg) |
| Direct Link Exchange on Classic | |
| Domain Name Registration | |
| Email Delivery, powered by Sendgrid | |
| File Storage | ![Checkmark icon](../icons/checkmark-icon.svg) |
| FortiGate Security Appliance | ![Checkmark icon](../icons/checkmark-icon.svg) |
| Gateway Appliance | ![Checkmark icon](../icons/checkmark-icon.svg) |
| Hardware Firewall | ![Checkmark icon](../icons/checkmark-icon.svg) |
| IBM Cloud Backup | ![Checkmark icon](../icons/checkmark-icon.svg) |
| IPSec VPN | ![Checkmark icon](../icons/checkmark-icon.svg) |
| Load Balancers | ![Checkmark icon](../icons/checkmark-icon.svg) |
| Managed Network Security Services | |
| Object Storage | |
| Professional Services for Government | |
| SSL Certificates | ![Checkmark icon](../icons/checkmark-icon.svg) |
| Subnets | ![Checkmark icon](../icons/checkmark-icon.svg) |
| VLAN | |
| Virtual Server for Classic | ![Checkmark icon](../icons/checkmark-icon.svg) |
{: row-headers}
{: caption="Table 12. Asia Pacific infrastructure availability - Korea" caption-side="top"}
{: #iaas-table9}
{: tab-title="Korea"}
{: tab-group="Asia Pacific"}
{: class="comparison-tab-table"}
{: summary="Use the buttons for the countries to change the context of the table. This table has row and column headers. The row headers identify the service. The column headers indentify where that service is located. To understand where a service is located in the table, navigate to the row, and find the for the location you are interested in."}


| Service |  sng01 |
|-----|-----|
| Bare Metal Server | |
| Block Storage | ![Checkmark icon](../icons/checkmark-icon.svg) |
| Cloud HSM | |
| Cloud Migration | |
| Container Security Services | |
| Content Delivery Network | ![Checkmark icon](../icons/checkmark-icon.svg) |
| Direct Link Connect on Classic | |
| Direct Link Dedicated Hosting on Classic | ![Checkmark icon](../icons/checkmark-icon.svg) |
| Direct Link Dedicated on Classic | ![Checkmark icon](../icons/checkmark-icon.svg) |
| Direct Link Exchange on Classic | |
| Domain Name Registration | |
| Email Delivery, powered by Sendgrid | |
| File Storage | ![Checkmark icon](../icons/checkmark-icon.svg) |
| FortiGate Security Appliance | ![Checkmark icon](../icons/checkmark-icon.svg) |
| Gateway Appliance | ![Checkmark icon](../icons/checkmark-icon.svg) |
| Hardware Firewall | ![Checkmark icon](../icons/checkmark-icon.svg) |
| IBM Cloud Backup | ![Checkmark icon](../icons/checkmark-icon.svg) |
| IPSec VPN | ![Checkmark icon](../icons/checkmark-icon.svg) |
| Load Balancers | ![Checkmark icon](../icons/checkmark-icon.svg) |
| Managed Network Security Services | |
| Object Storage | |
| Professional Services for Government | |
| SSL Certificates | ![Checkmark icon](../icons/checkmark-icon.svg) |
| Subnets | ![Checkmark icon](../icons/checkmark-icon.svg) |
| VLAN | |
| Virtual Server for Classic | ![Checkmark icon](../icons/checkmark-icon.svg) |
{: row-headers}
{: caption="Table 13. Asia Pacific infrastructure availability - Singapore" caption-side="top"}
{: #iaas-table10}
{: tab-title="Singapore"}
{: tab-group="Asia Pacific"}
{: class="comparison-tab-table"}
{: summary="Use the buttons for the countries to change the context of the table. This table has row and column headers. The row headers identify the service. The column headers indentify where that service is located. To understand where a service is located in the table, navigate to the row, and find the for the location you are interested in."}


### Europe
{: #iaas-service-europe}

The following infrastructure resources are available in Europe. Match the resource row with the column representing the data center or multi-zone region. A check mark indicates the resource is available in that location. The London (MZR) and Frankfurt (MZR) columns represent multi-zone regions where deployment is managed automatically across several data centers.

| Service |  par01 |
|-----|-----|
| Bare Metal Server | ![Checkmark icon](../icons/checkmark-icon.svg) |
| Block Storage | ![Checkmark icon](../icons/checkmark-icon.svg) |
| Cloud HSM | ![Checkmark icon](../icons/checkmark-icon.svg) |
| Cloud Migration | |
| Container Security Services | |
| Content Delivery Network | ![Checkmark icon](../icons/checkmark-icon.svg) |
| Direct Link Connect on Classic | |
| Direct Link Dedicated Hosting on Classic | ![Checkmark icon](../icons/checkmark-icon.svg) |
| Direct Link Dedicated on Classic | ![Checkmark icon](../icons/checkmark-icon.svg) |
| Direct Link Exchange on Classic | |
| Domain Name Registration | |
| Email Delivery, powered by Sendgrid | |
| File Storage | ![Checkmark icon](../icons/checkmark-icon.svg) |
| FortiGate Security Appliance | ![Checkmark icon](../icons/checkmark-icon.svg) |
| Gateway Appliance | ![Checkmark icon](../icons/checkmark-icon.svg) |
| Hardware Firewall | ![Checkmark icon](../icons/checkmark-icon.svg) |
| IBM Cloud Backup | ![Checkmark icon](../icons/checkmark-icon.svg) |
| IPSec VPN | ![Checkmark icon](../icons/checkmark-icon.svg) |
| Load Balancers | ![Checkmark icon](../icons/checkmark-icon.svg) |
| Managed Network Security Services | |
| Object Storage | |
| Professional Services for Government | |
| SSL Certificates | ![Checkmark icon](../icons/checkmark-icon.svg) |
| Subnets | ![Checkmark icon](../icons/checkmark-icon.svg) |
| VLAN | |
| Virtual Server for Classic | ![Checkmark icon](../icons/checkmark-icon.svg) |
{: row-headers}
{: caption="Table 14. Europe infrastructure availability - France" caption-side="top"}
{: #iaas-table11}
{: tab-title="France"}
{: tab-group="Europe"}
{: class="comparison-tab-table"}
{: summary="Use the buttons for the countries to change the context of the table. This table has row and column headers. The row headers identify the service. The column headers indentify where that service is located. To understand where a service is located in the table, navigate to the row, and find the for the location you are interested in."}


| Service |  eu-de | fra02 | fra04 | fra05 |
|-----|-----|-----|-----|-----|
| Bare Metal Server | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) |
| Block Storage | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) |
| Cloud HSM | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | | |
| Cloud Migration | | | | |
| Container Security Services | | | | |
| Content Delivery Network | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) |
| Direct Link Connect on Classic | ![Checkmark icon](../icons/checkmark-icon.svg) | | | |
| Direct Link Dedicated Hosting on Classic | | ![Checkmark icon](../icons/checkmark-icon.svg) | | |
| Direct Link Dedicated on Classic | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) |
| Direct Link Exchange on Classic | ![Checkmark icon](../icons/checkmark-icon.svg) | | | |
| Domain Name Registration | | | | |
| Email Delivery, powered by Sendgrid | | | | |
| File Storage | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) |
| FortiGate Security Appliance | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) |
| Gateway Appliance | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) |
| Hardware Firewall | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) |
| IBM Cloud Backup | | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) |
| IPSec VPN | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) |
| Load Balancers | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) |
| Managed Network Security Services | | | | |
| Object Storage | | | | |
| Professional Services for Government | | | | |
| SSL Certificates | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) |
| Subnets | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) |
| VLAN | | | | |
| Virtual Server for Classic | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) |
{: row-headers}
{: caption="Table 15. Europe infrastructure availability - Germany" caption-side="top"}
{: #iaas-table12}
{: tab-title="Germany"}
{: tab-group="Europe"}
{: class="comparison-tab-table"}
{: summary="Use the buttons for the countries to change the context of the table. This table has row and column headers. The row headers identify the service. The column headers indentify where that service is located. To understand where a service is located in the table, navigate to the row, and find the for the location you are interested in."}


| Service |  mil01 |
|-----|-----|
| Bare Metal Server | ![Checkmark icon](../icons/checkmark-icon.svg) |
| Block Storage | ![Checkmark icon](../icons/checkmark-icon.svg) |
| Cloud HSM | |
| Cloud Migration | |
| Container Security Services | |
| Content Delivery Network | ![Checkmark icon](../icons/checkmark-icon.svg) |
| Direct Link Connect on Classic | |
| Direct Link Dedicated Hosting on Classic | |
| Direct Link Dedicated on Classic | ![Checkmark icon](../icons/checkmark-icon.svg) |
| Direct Link Exchange on Classic | |
| Domain Name Registration | |
| Email Delivery, powered by Sendgrid | |
| File Storage | ![Checkmark icon](../icons/checkmark-icon.svg) |
| FortiGate Security Appliance | ![Checkmark icon](../icons/checkmark-icon.svg) |
| Gateway Appliance | ![Checkmark icon](../icons/checkmark-icon.svg) |
| Hardware Firewall | ![Checkmark icon](../icons/checkmark-icon.svg) |
| IBM Cloud Backup | ![Checkmark icon](../icons/checkmark-icon.svg) |
| IPSec VPN | ![Checkmark icon](../icons/checkmark-icon.svg) |
| Load Balancers | ![Checkmark icon](../icons/checkmark-icon.svg) |
| Managed Network Security Services | |
| Object Storage | |
| Professional Services for Government | |
| SSL Certificates | ![Checkmark icon](../icons/checkmark-icon.svg) |
| Subnets | ![Checkmark icon](../icons/checkmark-icon.svg) |
| VLAN | |
| Virtual Server for Classic | ![Checkmark icon](../icons/checkmark-icon.svg) |
{: row-headers}
{: caption="Table 16. Europe infrastructure availability - Italy" caption-side="top"}
{: #iaas-table13}
{: tab-title="Italy"}
{: tab-group="Europe"}
{: class="comparison-tab-table"}
{: summary="Use the buttons for the countries to change the context of the table. This table has row and column headers. The row headers identify the service. The column headers indentify where that service is located. To understand where a service is located in the table, navigate to the row, and find the for the location you are interested in."}


| Service |  ams01 | ams03 |
|-----|-----|-----|
| Bare Metal Server | | ![Checkmark icon](../icons/checkmark-icon.svg) |
| Block Storage | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) |
| Cloud HSM | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) |
| Cloud Migration | | |
| Container Security Services | | |
| Content Delivery Network | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) |
| Direct Link Connect on Classic | | |
| Direct Link Dedicated Hosting on Classic | | |
| Direct Link Dedicated on Classic | | ![Checkmark icon](../icons/checkmark-icon.svg) |
| Direct Link Exchange on Classic | | |
| Domain Name Registration | | |
| Email Delivery, powered by Sendgrid | | |
| File Storage | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) |
| FortiGate Security Appliance | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) |
| Gateway Appliance | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) |
| Hardware Firewall | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) |
| IBM Cloud Backup | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) |
| IPSec VPN | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) |
| Load Balancers | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) |
| Managed Network Security Services | | |
| Object Storage | | |
| Professional Services for Government | | |
| SSL Certificates | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) |
| Subnets | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) |
| VLAN | | |
| Virtual Server for Classic | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) |
{: row-headers}
{: caption="Table 17. Europe infrastructure availability - Netherlands" caption-side="top"}
{: #iaas-table14}
{: tab-title="Netherlands"}
{: tab-group="Europe"}
{: class="comparison-tab-table"}
{: summary="Use the buttons for the countries to change the context of the table. This table has row and column headers. The row headers identify the service. The column headers indentify where that service is located. To understand where a service is located in the table, navigate to the row, and find the for the location you are interested in."}


| Service |  osl01 |
|-----|-----|
| Bare Metal Server | |
| Block Storage | ![Checkmark icon](../icons/checkmark-icon.svg) |
| Cloud HSM | |
| Cloud Migration | |
| Container Security Services | |
| Content Delivery Network | ![Checkmark icon](../icons/checkmark-icon.svg) |
| Direct Link Connect on Classic | |
| Direct Link Dedicated Hosting on Classic | |
| Direct Link Dedicated on Classic | ![Checkmark icon](../icons/checkmark-icon.svg) |
| Direct Link Exchange on Classic | |
| Domain Name Registration | |
| Email Delivery, powered by Sendgrid | |
| File Storage | ![Checkmark icon](../icons/checkmark-icon.svg) |
| FortiGate Security Appliance | ![Checkmark icon](../icons/checkmark-icon.svg) |
| Gateway Appliance | ![Checkmark icon](../icons/checkmark-icon.svg) |
| Hardware Firewall | ![Checkmark icon](../icons/checkmark-icon.svg) |
| IBM Cloud Backup | ![Checkmark icon](../icons/checkmark-icon.svg) |
| IPSec VPN | ![Checkmark icon](../icons/checkmark-icon.svg) |
| Load Balancers | ![Checkmark icon](../icons/checkmark-icon.svg) |
| Managed Network Security Services | |
| Object Storage | |
| Professional Services for Government | |
| SSL Certificates | ![Checkmark icon](../icons/checkmark-icon.svg) |
| Subnets | ![Checkmark icon](../icons/checkmark-icon.svg) |
| VLAN | |
| Virtual Server for Classic | ![Checkmark icon](../icons/checkmark-icon.svg) |
{: row-headers}
{: caption="Table 18. Europe infrastructure availability - Norway" caption-side="top"}
{: #iaas-table15}
{: tab-title="Norway"}
{: tab-group="Europe"}
{: class="comparison-tab-table"}
{: summary="Use the buttons for the countries to change the context of the table. This table has row and column headers. The row headers identify the service. The column headers indentify where that service is located. To understand where a service is located in the table, navigate to the row, and find the for the location you are interested in."}


| Service |  eu-gb | lon02 | lon04 | lon05 | lon06 |
|-----|-----|-----|-----|-----|-----|
| Bare Metal Server | ![Checkmark icon](../icons/checkmark-icon.svg) | | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) |
| Block Storage | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) |
| Cloud HSM | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | | |
| Cloud Migration | | | | | |
| Container Security Services | | | | | |
| Content Delivery Network | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) |
| Direct Link Connect on Classic | ![Checkmark icon](../icons/checkmark-icon.svg) | | | | |
| Direct Link Dedicated Hosting on Classic | | ![Checkmark icon](../icons/checkmark-icon.svg) | | | ![Checkmark icon](../icons/checkmark-icon.svg) |
| Direct Link Dedicated on Classic | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) |
| Direct Link Exchange on Classic | ![Checkmark icon](../icons/checkmark-icon.svg) | | | | |
| Domain Name Registration | | | | | |
| Email Delivery, powered by Sendgrid | | | | | |
| File Storage | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) |
| FortiGate Security Appliance | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) |
| Gateway Appliance | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) |
| Hardware Firewall | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) |
| IBM Cloud Backup | | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) |
| IPSec VPN | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) |
| Load Balancers | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) |
| Managed Network Security Services | | | | | |
| Object Storage | ![Checkmark icon](../icons/checkmark-icon.svg) | | | | |
| Professional Services for Government | | | | | |
| SSL Certificates | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) |
| Subnets | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) |
| VLAN | | | | | |
| Virtual Server for Classic | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) | ![Checkmark icon](../icons/checkmark-icon.svg) |
{: row-headers}
{: caption="Table 19. Europe infrastructure availability - United Kingdom" caption-side="top"}
{: #iaas-table16}
{: tab-title="United Kingdom"}
{: tab-group="Europe"}
{: class="comparison-tab-table"}
{: summary="Use the buttons for the countries to change the context of the table. This table has row and column headers. The row headers identify the service. The column headers indentify where that service is located. To understand where a service is located in the table, navigate to the row, and find the for the location you are interested in."}


