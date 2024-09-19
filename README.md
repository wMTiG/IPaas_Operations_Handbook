# Operations Handbook  
### webMethods.io Integration  
**Version 1.0** | **April 2024**

## Version History

| Version | Date       | Description                               |
|---------|------------|-------------------------------------------|
| 1.0     | April 2024 | First document release ready for Review    |

## Table of Contents

1. [Introduction](#introduction)
   - [Operational Details](#operational-details)
     - [Tenant Management](#tenant-management)
     - [Security Management](#security-management)
     - [Operational Monitoring](#operational-monitoring)
   - [Execution Results](#execution-results)
     - [Workflow Execution Results](#workflow-execution-results)
     - [Flow Service Execution Results](#flow-service-execution-results)
   - [Availability of Execution Results](#availability-of-execution-results)
   - [Audit Logs](#audit-logs)
   - [End-to-End Monitoring](#end-to-end-monitoring)
2. [References](#references)

---

## Introduction
<Introduction in relevance to the context of “webMethods.io Integration Operations in brief”>
1.	Need enablement to access right data to take right action promptly in case of any issues.
2.	Also enabled to monitor and observe the state of the system with ease to ensure minimal to no impact to Business with Integrations hosted on Webmethods.io Integration.
   
This Guide serves as a handbook for consultants, and covers the information required by operations team to be able to perform various activities as part of Operations on day-to-day basis and on regular basis on webmethods.io Integration Platform with minimal support by Webmethods Cloud Ops, using the Out of the box product features after completing this workshop.

---

## Operational Details
Below sections explain how each of the operational procedures listed can be performed on webmethods.io Integration product.
### Tenant Management
Administration activities to keep the platform up to date with latest fixes as per releases by, SoftwareAG cloud operations team, including installing fixes, upgrades, user onboarding, modifying access privileges Super-user like access.
This task includes discover tenant details with a tenant user created by SAG cloud Ops team while provisioning tenant.

Tenant management covers information about Tenant profile and tenant type, Security management and Environments and Stage setup.


### Security Management
Keep tenants safe from unprivileged users, by providing required and limited access to tenant and its assets.

For various tasks to be performed by operations team for Tenant Management and Security Management, step by step information is detailed in the sections referenced below:

#### Tenant Profile and Tenant Type Details

| S No. | Topic                                                                                                | Reference from Operational Manual                                                                                      |
|-------|------------------------------------------------------------------------------------------------------|------------------------------------------------------------------------------------------------------------------------|
| 1     | How to identify tenant type and tenant version?                                                       | Detailed in section 3.1 and 3.2 of Tenant Management - PRIME Guide - webMethods.IO_Integration_Operations_ManualPart1.docx |
| 2     | How to verify tenant profile like subscription plan details? (If required to upgrade)                 | Security Management - Role Management / User management                                                                |
#### Security Management - Role Management / User management

| S No. | Topic                                                                                                | Reference from Operational Manual                                                                                      |
|-------|------------------------------------------------------------------------------------------------------|------------------------------------------------------------------------------------------------------------------------|
| 3     | List of activities of tenant users, various roles (system defined)                                    | Detailed in section 3.3 of Tenant Management - PRIME Guide - webMethods.IO_Integration_Operations_ManualPart1.docx      |
| 4     | What are the system-defined roles and their activities?                                               |                                                                                                                        |
| 5     | How to create custom roles, what permissions to define, and how to define custom roles?               |                                                                                                                        |
| 6     | How to add roles to users while creating users and associate users to projects for deployments?       |                                                                                                                        |
| 7     | What are the system-defined roles and activities performed with these roles?                          |                                                                                                                        |
| 8     | What permissions does a tenant user have for user management?                                         |                                                                                                                        |

#### Environments and Stage Setup

| S No. | Topic                                                                                                | Reference from Operational Manual                                                                                      |
|-------|------------------------------------------------------------------------------------------------------|------------------------------------------------------------------------------------------------------------------------|
| 9     | What are the activities involved in managing environments/stages?                                     | Detailed in section 4 - Manage Environments and Stages - PRIME Guide - webMethods.IO_Integration_Operations_ManualPart1.docx |
| 10    | As part of managing environments, how to register and enable tenants to deploy assets from non-prod tenants? |                                                                                                                        |
| 11    | How to create a production environment with a provisioned production tenant?                          |                                                                                                                        |
| 12    | How to allow users to access environments?                                                            |                                                                                                                        |
| 13    | How to link environments to deploy assets from non-prod tenants to a production tenant?               |                                                                                                                        |
| 14    | How to update environments?                                                                           |                                                                                                                        |
| 15    | How to delete environments?                                                                           |                                                                                                                        |
| 16    | What are stages, how to create stages, and why must stages be created?                                |                                                                                                                        |

#### How to Know?

| S No. | Topic                                                                                                | Reference from Operational Manual                                                                                      |
|-------|------------------------------------------------------------------------------------------------------|------------------------------------------------------------------------------------------------------------------------|
| 12    | How to check the status of the tenant?                                                                | Detailed in section 5 - Troubleshooting - PRIME Guide - webMethods.IO_Integration_Operations_ManualPart1.docx           |
| 13    | How to check the status of tenants across regions?                                                    |                                                                                                                        |
| 14    | How to identify the IP address of the tenant?                                                         |                                                                                                                        |


---

## Execution Results

### Workflow Execution Results
Logs displaying statistics of workflow execution status:
- **Successful**: Workflow completed successfully.
- **Failed**: Workflow execution failed.

### Flow Service Execution Results
Logs displaying statistics of flow services execution status:
- **Running**: Service is currently being executed.
- **Failed**: Service execution failed.

---

## Availability of Execution Results
Logs are available for up to the last **30 days**. The operation team can filter logs by date range.

---

## Audit Logs
A history of actions performed by users within the tenant. Logs are available for the last **30 days** and can be downloaded in CSV or JSON format.

---

## End-to-End Monitoring
Currently, end-to-end monitoring does not support asynchronous requests. To enable this feature, an **Enterprise Plus** license is required.

---

## References

- [webMethods.io Integration API Reference](https://docs.webmethods.io/integration/)
- [Hybrid Integration](https://docs.webmethods.io/integration/release_readme/readme110#limitations)
