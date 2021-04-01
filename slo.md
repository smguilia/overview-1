---

copyright:

  years: 2021

lastupdated: "2021-04-01"

keywords: SLO, service level objectives

subcollection: overview

---

{:shortdesc: .shortdesc}
{:codeblock: .codeblock}
{:screen: .screen}
{:external: target="_blank" .external}
{:tip: .tip}
{:note: .note}

# {{site.data.keyword.cloud_notm}} service level objectives
{: #slo}

Service level objectives (SLOs) describe the design points that the {{site.data.keyword.cloud}} services are engineered to meet in the following areas:

* Availability
* Operations management
* Performance

The SLO is not a warranty and IBM will not issue credits for failure to meet an objective. Refer to the [Service Level Agreements (SLAs)](/docs/overview?topic=overview-slas) for commitments and credits that are issued for failure to meet any committed SLAs.

The following table describes the service level objectives (SLOs) for the {{site.data.keyword.cloud_notm}} services in a high availability configuration. As you aggregate or deploy services into a single zone, your SLO might vary. For more information about how {{site.data.keyword.cloud_notm}} is striving to ensure the highest availability of services, see [How IBM Cloud ensures high availability and disaster recovery](/docs/overview?topic=overview-zero-downtime).

## Service level objectives for {{site.data.keyword.cloud_notm}} platform services and other vital services
{: #platform-slo}

These services include our control plane and self-service interfaces, IAM service, key management service, virtual machine compute instances, block and object storage services, virtual networks service, web or Layer 7 load-balancing service, and relational DBaaS.

| Platform service | Availability target | Data durability target | High availability guidance |
|----------|---------|---------|---------|
| {{site.data.keyword.cloud_notm}} console | 99.999% | | [High availability for the platform](/docs/overview?topic=overview-zero-downtime#platform-ha) |
| {{site.data.keyword.cloud_notm}} CLI | 99.999% | | [Understanding high availability and disaster recovery for the IBM Cloud CLI](/docs/cli?topic=cli-ha-dr) |
| {{site.data.keyword.cloud_notm}} network | 99.9999% | | [High availability for the network](/docs/overview?topic=overview-zero-downtime#ha-network) |
| {{site.data.keyword.cloud_notm}} catalogs | 99.999% | | [High availability for the platform](/docs/overview?topic=overview-zero-downtime#platform-ha) |
| Identity and Access Management (IAM) | 99.999% | | [High availability for the platform](/docs/overview?topic=overview-zero-downtime#platform-ha) |
{: caption="Table 1. Service level objectives (SLOs) for the {{site.data.keyword.cloud_notm}} platform services" caption-side="bottom"}

| Compute service | Availability target | Data durability target | High availability guidance |
|----------|---------|---------|---------|
| {{site.data.keyword.vpc_short}} | 99.999% | | [Understanding high availability and disaster recovery](/docs/vpc?topic=vpc-ha-dr-vpc) |
{: caption="Table 2. Service level objectives (SLOs) for the {{site.data.keyword.cloud_notm}} compute services" caption-side="bottom"}

| Networking service | Availability target | Data durability target | High availability guidance |
|----------|---------|---------|---------|
| {{site.data.keyword.vpc_short}} (Gen 2) | 99.999% | | [Understanding high availability and disaster recovery](/docs/vpc?topic=vpc-ha-dr-vpc) |
| {{site.data.keyword.vpn_full}} | 99.999% | | [Connecting to your on-premises network](/docs/vpc?topic=vpc-vpn-onprem-example) |
| {{site.data.keyword.alb_full}} | 99.999% | | [High Availability mode](/docs/vpc?topic=vpc-nlb-vs-elb#nlb-ha-mode) |
| {{site.data.keyword.nlb_full}} | 99.999% | | [High Availability mode](/docs/vpc?topic=vpc-nlb-vs-elb#nlb-ha-mode) |
| {{site.data.keyword.vpe_full}} | 99.999% | | [Endpoints available](/docs/vpc?topic=vpc-service-endpoints-for-vpc) |
| {{site.data.keyword.cloud_notm}} service endpoints| 99.999% | | [Secure access to services using service endpoints](/docs/account?topic=account-service-endpoints-overview) |
{: caption="Table 3. Service level objectives (SLOs) for the {{site.data.keyword.cloud_notm}} networking services" caption-side="bottom"}

| Storage service | Availability target | Data durability target | High availability guidance |
|----------|---------|---------|---------|
| {{site.data.keyword.cos_full_notm}} (Gen 2) | 99.999% | 99.99999999999% | [Comparison of persistent storage options for single zone clusters](/docs/containers?topic=containers-storage_planning#persistent_storage_overview) |
| {{site.data.keyword.block_storage_is_short}} | 99.999% | 99.99999999999% | [About {{site.data.keyword.block_storage_is_short}}](/docs/vpc?topic=vpc-block-storage-about) |
{: caption="Table 4. Service level objectives (SLOs) for the {{site.data.keyword.cloud_notm}} storage services" caption-side="bottom"}

| Databases service | Availability target | Data durability target | High availability guidance |
|----------|---------|---------|---------|
| {{site.data.keyword.databases-for-postgresql_full_notm}} | 99.999% | | [High-Availability](/docs/databases-for-postgresql?topic=databases-for-postgresql-high-availability) |
{: caption="Table 5. Service level objectives (SLOs) for the {{site.data.keyword.cloud_notm}} databases services" caption-side="bottom"}

| Security service | Availability target | Data durability target | High availability guidance |
|----------|---------|---------|---------|
| {{site.data.keyword.keymanagementservicefull_notm}} | 99.999% | | [High availability and disaster recovery](/docs/key-protect?topic=key-protect-ha-dr) |
| {{site.data.keyword.hscrypto}} | 99.999% | | [High availability and disaster recovery](/docs/hs-crypto?topic=hs-crypto-ha-dr) |
{: caption="Table 6. Service level objectives (SLOs) for the {{site.data.keyword.cloud_notm}} security services" caption-side="bottom"}


## Service level objectives for high impact {{site.data.keyword.cloud_notm}} services
{: #high-impact-slo}

High impact services are not vital, but have great influence over the rest of the environment. These services are generally called upon in most deployments and might be of interest as they impact performance or usability of the environment.

| Platform service | Availability target | Data durability target | High availability guidance |
|----------|---------|---------|---------|
| {{site.data.keyword.compliance_long}} | 99.999% | | [Understanding high availability and disaster recovery for Security and Compliance Center](/docs/security-compliance?topic=security-compliance-ha-dr) |
| {{site.data.keyword.cloud-shell_notm}} | 99.999% | | [Understanding high availability and disaster recovery for Cloud Shell](/docs/cloud-shell?topic=cloud-shell-ha-dr) |
{: caption="Table 7. Service level objectives (SLOs) for the {{site.data.keyword.cloud_notm}} platform services" caption-side="bottom"}

| Compute service | Availability target | Data durability target | High availability guidance |
|----------|---------|---------|---------|
| {{site.data.keyword.openwhisk_short}} | 99.999% | | [Understanding high availability and disaster recovery for Cloud Functions](/docs/openwhisk?topic=openwhisk-ha_dr) |
| {{site.data.keyword.satellitelong_notm}} | 99.999% | | [High availability and disaster recovery for Satellite](/docs/satellite?topic=satellite-ha) |
{: caption="Table 8. Service level objectives (SLOs) for the {{site.data.keyword.cloud_notm}} compute services" caption-side="bottom"}

| Container service | Availability target | Data durability target | High availability guidance |
|----------|---------|---------|---------|
| {{site.data.keyword.registrylong_notm}} | 99.999% | | [Understanding high availability and disaster recovery for Container Registry](/docs/Registry?topic=Registry-ha-dr) |
| {{site.data.keyword.containerlong_notm}} | 99.999% | | [High availability and disaster recovery for IBM Cloud Kubernetes Service](/docs/containers?topic=containers-ha) |
| {{site.data.keyword.openshiftlong_notm}} | 99.999% | | [Understanding high availability and disaster recovery for Red Hat OpenShift on IBM Cloud](/docs/openshift?topic=openshift-ha) |
| {{site.data.keyword.codeenginefull_notm}} | 99.999% | | [High availability and disaster recovery for Code Engine](/docs/codeengine?topic=codeengine-ha-dr) |
{: caption="Table 9. Service level objectives (SLOs) for the {{site.data.keyword.cloud_notm}} container services" caption-side="bottom"}

| Networking service | Availability target | Data durability target | High availability guidance |
|----------|---------|---------|---------|
| {{site.data.keyword.dns_full_notm}} | 99.999% | | [Understanding high availability and disaster recovery for DNS Services](/docs/dns-svcs?topic=dns-svcs-ha-dr) |
| {{site.data.keyword.tg_full_notm}} | 99.999% | | [High availability and disaster recovery](/docs/transit-gateway?topic=transit-gateway-ha-dr) |
| {{site.data.keyword.cis_full_notm}} | 99.999% | | [Use Virtual Servers to build highly available and scalable web app](/docs/cloud-infrastructure?topic=solution-tutorials-highly-available-and-scalable-web-application) |
| {{site.data.keyword.dl_full_notm}} | 99.999% | | [High Availability and disaster recovery for Direct Link](/docs/dl?topic=dl-ha-dr) |
| {{site.data.keyword.fl_full}} | 99.999% | | [About IBM Cloud Flow Logs for VPC](/docs/vpc?topic=vpc-flow-logs) |
{: caption="Table 10. Service level objectives (SLOs) for the {{site.data.keyword.cloud_notm}} networking services" caption-side="bottom"}

| AI/Machine Learning service | Availability target | Data durability target | High availability guidance |
|----------|---------|---------|---------|
| {{site.data.keyword.languagetranslatorshort}} | 99.999% | | [High availability and disaster recovery](/docs/language-translator?topic=language-translator-ha-dr) |
| {{site.data.keyword.speechtotextshort}} | 99.999% | | [High availability and disaster recovery](/docs/speech-to-text?topic=speech-to-text-ha-dr) |
| {{site.data.keyword.nlushort}} | 99.999% | | [High availability and disaster recovery](/docs/natural-language-understanding?topic=natural-language-understanding-ha-dr) |
{: caption="Table 11. Service level objectives (SLOs) for the {{site.data.keyword.cloud_notm}} AI/machine learning services" caption-side="bottom"}

| Analytics service | Availability target | Data durability target | High availability guidance |
|----------|---------|---------|---------|
| {{site.data.keyword.iae_full_notm}} | 99.995% | | [Overview of IBM Analytics Engine instances](/docs/AnalyticsEngine?topic=AnalyticsEngine-IAE-overview) |
{: caption="Table 12. Service level objectives (SLOs) for the {{site.data.keyword.cloud_notm}} analytics services" caption-side="bottom"}

| Databases service | Availability target | Data durability target | High availability guidance |
|----------|---------|---------|---------|
| {{site.data.keyword.databases-for-mongodb_full_notm}} | 99.999% | | [Understanding high availability and disaster recovery for Cloud Databases](/docs/databases-for-mongodb?topic=cloud-databases-ha-dr) |
| {{site.data.keyword.databases-for-cassandra_full_notm}} | 99.999% | | [High-Availability](/docs/databases-for-cassandra?topic=databases-for-cassandra-high-availability) |
| {{site.data.keyword.databases-for-redis_full_notm}} | 99.999% | | [High-Availability](/docs/databases-for-redis?topic=databases-for-redis-high-availability) |
| {{site.data.keyword.databases-for-elasticsearch_full_notm}} | 99.999% | | [High-Availability](/docs/databases-for-elasticsearch?topic=databases-for-elasticsearch-high-availability) |
| {{site.data.keyword.messages-for-rabbitmq_full_notm}} | 99.999% | | [High-Availability](/docs/messages-for-rabbitmq?topic=messages-for-rabbitmq-high-availability) |
| {{site.data.keyword.cloudant_short_notm}} | 99.999% | | [High availability, disaster recovery, and backup in a data center](/docs/Cloudant?topic=Cloudant-ibm-cloud-public#high-availability-disaster-recovery-and-backup-in-a-data-center) |
| {{site.data.keyword.sqlquery_notm}} | 99.999% | | [Disaster recovery and backup](/docs/sql-query?topic=sql-query-disaster) |
| {{site.data.keyword.databases-for-enterprisedb_full_notm}} | 99.999% | | [High-Availability](/docs/databases-for-enterprisedb?topic=databases-for-enterprisedb-high-availability) |
| {{site.data.keyword.dashdblong_notm}} | 99.999% | | [High availability (HA)](/docs/Db2whc?topic=Db2whc-ha) |
{: caption="Table 13. Service level objectives (SLOs) for the {{site.data.keyword.cloud_notm}} databases services" caption-side="bottom"}

| Developer Tools service | Availability target | Data durability target | High availability guidance |
|----------|---------|---------|---------|
| {{site.data.keyword.contdelivery_short}} | 99.999% | | [High availability and disaster recovery](/docs/ContinuousDelivery?topic=ContinuousDelivery-ha-dr) |
| {{site.data.keyword.bpfull_notm}} | 99.999% | | [High availability](/docs/schematics?topic=schematics-high-availability) |
| {{site.data.keyword.apigw_full_notm}} | 99.999% | | [High availability and disaster recovery](/docs/api-gateway?topic=api-gateway-ha-dr) |
{: caption="Table 14. Service level objectives (SLOs) for the {{site.data.keyword.cloud_notm}} developer tools services" caption-side="bottom"}

| Logging and Monitoring service | Availability target | Data durability target | High availability guidance |
|----------|---------|---------|---------|
| {{site.data.keyword.monitoringlong_notm}} | 99.999% | | [High availability and disaster recovery](/docs/monitoring?topic=monitoring-ha-dr) |
| {{site.data.keyword.at_full_notm}} | 99.999% | | [Incident and operations management](/docs/activity-tracker?topic=activity-tracker-shared-responsibilities#incident-and-ops) |
| {{site.data.keyword.la_full_notm}} | 99.999% | | [Adoption guidelines for regulated and highly available workloads](/docs/log-analysis?topic=log-analysis-adoption) |
{: caption="Table 15. Service level objectives (SLOs) for the {{site.data.keyword.cloud_notm}} logging and monitoring services" caption-side="bottom"}

| Integration service | Availability target | Data durability target | High availability guidance |
|----------|---------|---------|---------|
| {{site.data.keyword.messagehub}} | 99.999% | | [What do you need to consider to achieve this availability?](/docs/EventStreams?topic=EventStreams-sla#what-do-you-need-to-consider-to-achieve-this-availability-) |
| {{site.data.keyword.apiconnect_short}} | 99.999% | | [Understanding high availability and disaster recovery for API Connect](/docs/apiconnect?topic=apiconnect-ha-dr) |
{: caption="Table 16. Service level objectives (SLOs) for the {{site.data.keyword.cloud_notm}} integration services" caption-side="bottom"}

| Security service | Availability target | Data durability target | High availability guidance |
|----------|---------|---------|---------|
| {{site.data.keyword.secrets-manager_full_notm}} | 99.999% | | [Understanding high availability and disaster recovery for Secrets Manager](/docs/secrets-manager?topic=secrets-manager-ha-dr) |
| {{site.data.keyword.appid_full_notm}} | 99.999% | | [Understanding high availability and disaster recovery for App ID](/docs/appid?topic=appid-ha-dr) |
| {{site.data.keyword.cloudcerts_long_notm}} | 99.999% | | [Understanding high availability and disaster recovery for Certificate Manager](/docs/certificate-manager?topic=certificate-manager-ha-dr) |
{: caption="Table 17. Service level objectives (SLOs) for the {{site.data.keyword.cloud_notm}} security services" caption-side="bottom"}


## Service level objectives for other {{site.data.keyword.cloud_notm}} services
{: #other-slo}

Services that are not covered under this SLO topic are deployed as highly available, but the service is not stress tested beyond this level. Therefore, we cannot state that the service complies with a higher SLO standard. In many cases, the services are complex offerings that rely on other services to operate. Therefore, the service availability is affected by many more factors than what is listed in the previous tables.

| Service | Availability target | 
|----------|---------|
| Any product not listed | 99.99% |
{: caption="Table 18. Service level objectives (SLOs) for other {{site.data.keyword.cloud_notm}} services" caption-side="bottom"}
