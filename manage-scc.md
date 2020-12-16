---
copyright:
  years: 2020
lastupdated: "2020-12-11"

keywords: security and compliance for the platform, security for IBM Cloud, compliance for IBM Cloud, goals, config rules, rules, posture

subcollection: overview

---

{:external: target="_blank" .external}
{:note: .note}
{:term: .term}
{:shortdesc: .shortdesc}
{:table: .aria-labeledby="caption"}


# Managing security and compliance in {{site.data.keyword.cloud_notm}}
{: #manage-security-compliance}

{{site.data.keyword.cloud}} is integrated with the {{site.data.keyword.compliance_short}} to help you manage security and compliance for your organization.
{: shortdesc}

With the {{site.data.keyword.compliance_short}}, you can accomplish the following tasks:

* Monitor for controls and goals that pertain to platform services.
* Define rules that can help to standardize resource configuration.

## Monitoring security and compliance posture
{: #monitor-platform}

As a security or compliance focal, you can use [goals](#x2117978){: term} of specific platform services to help ensure that your organization is adhering to the external and internal standards for your industry. By using the {{site.data.keyword.compliance_short}} to validate the resource configurations in your account against a [profile](#x2034950){: term}, you can identify potential issues as they arise.

All of the goals for the platform are added to the {{site.data.keyword.cloud_notm}} Best Practices Controls 1.0 profile but can also be mapped to other profiles.
{: note}

To start monitoring your resources, see [Getting started with {{site.data.keyword.compliance_short}}](/docs/security-compliance?topic-security-compliance-getting-started).

### Available goals for platform services
{: #platform-available-goals}

#### Identity and Access Management
{: #iam-goals}

* Check whether password policy requires at least one uppercase letter
* Check whether password policy requires at least one lowercase letter
* Check whether password policy requires at least one number
* Check whether password policy requires minimum length of 8 chars that meets expectation
* Check whether password policy prevents password reuse
* Check whether the password may only contain printable ASCII characters (in the range 33 -126)
* Check whether passwod policy cannot contain: spaces, or any of \;:("?)<>
* Check whether the usage of a password meter coaches user to create a stronger password than the minimum
* Check whether IAM instance roles are used for {{site.data.keyword.IBM_notm}} resource access from instances
* Check whether a support role has been created to manage incidents with {{site.data.keyword.cloud_notm}} support
* Do not set up access API keys during initial user setup for all IAM users that have a console password
* Check whether multi-factor authentication (MFA) is enabled for all users under account
* Check whether contact email is maintained
* Check whether contact phone number is maintained
* Check whether IAM users are attached to access groups
* Check whether IAM policies are attached only to groups or roles
* Check whether MFA is enabled at the account level
* Check whether MFA is enabled for the owner account
* Check whether security questions are registered for the owner account
* Check whether authorized IP ranges are configured for the owner account
* Check whether more than allowed number of admins are configured per account
* Check whether IAM does not allow public access to COS (not applicable to ACLs managed using S3 APIs)
* Check whether no owner account API key exists
* Check whether access keys are rotated for every specific period # (days)
* Check whether owner account has logged in the past 30 days
* Check whether user list visibility restrictions are configured
* Check whether API key creation is limited and configured
* Check whether service ID creation is limited and configured

## Governing resource configuration for platform servcies
{: #govern-platform}

As a security or compliance focal, you can use the {{site.data.keyword.compliance_short}} to define configuration rules for the platform services that you're working with in {{site.data.keyword.cloud_notm}}.

[Config rules](#x3084914){: term} are used to enforce the configuration standards that you want to implement across your accounts. For more details about the data that you can use to create a rule, review the following table.

| Platform service | Resource kind | Property | Operator | Value | Description |
|---------------|---------------|----------|---------------|-------|-------------|
| Billing | account-trait | eu_supported | is_false | - | Indicates whether the account has the eu_supported flag enabled. |
| Billing | account-trait | hipaa_accepted | is_false | - | Indicates whether the account has the hipaa_accepted flag enabled. |
| IAM Access Groups Service | service | public_access_enabled | is_false | - | Indicates whether the public access feature is enabled. |
{: caption="Table 1. Rule properties for platform services caption-side="top"}

See [What is a config rule?](/docs/security-compliance?topic=security-compliance-what-is-rule) for more information. 
