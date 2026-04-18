# ServiceNow (servicenow)
ServiceNow provides cloud-based platform services that automate enterprise IT operations.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/servicenow/refs/heads/main/apis.yml)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - Automation, Cloud Services, Digital Workflows, Enterprise Platform, IT Service Management, ITSM, Processes, T1, Workflow Automation, Workflows

## Timestamps

- **Created:** 2025-01-08
- **Modified:** 2026-04-18

## APIs

### ServiceNow Table API
The ServiceNow Table API provides endpoints to perform create, read, update, and delete (CRUD) operations on records within any ServiceNow table. It is the primary REST interface for interacting with ServiceNow platform data such as incidents, problems, changes, and custom tables.

**Human URL:** [https://www.servicenow.com/docs/bundle/yokohama-api-reference/page/integrate/inbound-rest/concept/c_TableAPI.html](https://www.servicenow.com/docs/bundle/yokohama-api-reference/page/integrate/inbound-rest/concept/c_TableAPI.html)

#### Tags:

 - CRUD, Data, ITSM, Records, Tables

#### Properties

- [Documentation](https://www.servicenow.com/docs/bundle/yokohama-api-reference/page/integrate/inbound-rest/concept/c_TableAPI.html)
- [APIReference](https://www.servicenow.com/docs/bundle/xanadu-api-reference/page/integrate/inbound-rest/concept/c_TableAPI.html)
- [OpenAPI](openapi/servicenow-table-api-openapi.yml)

### ServiceNow Aggregate API
The ServiceNow Aggregate API provides endpoints to compute aggregate statistics (count, average, min, max, sum) against records in any ServiceNow table. It supports grouping and filtering results, making it useful for reporting and dashboard data retrieval.

**Human URL:** [https://www.servicenow.com/docs/bundle/yokohama-api-reference/page/integrate/inbound-rest/concept/c_AggregateAPI.html](https://www.servicenow.com/docs/bundle/yokohama-api-reference/page/integrate/inbound-rest/concept/c_AggregateAPI.html)

#### Tags:

 - Aggregation, Analytics, Reporting, Statistics, Tables

#### Properties

- [Documentation](https://www.servicenow.com/docs/bundle/yokohama-api-reference/page/integrate/inbound-rest/concept/c_AggregateAPI.html)
- [OpenAPI](openapi/servicenow-aggregate-api-openapi.yml)

### ServiceNow Attachment API
The ServiceNow Attachment API enables uploading, retrieving, and deleting file attachments associated with records in ServiceNow tables. It supports uploading files via multipart/form-data or binary streams and allows up to 1024 MB file size by default.

**Human URL:** [https://www.servicenow.com/docs/bundle/yokohama-api-reference/page/integrate/inbound-rest/concept/c_AttachmentAPI.html](https://www.servicenow.com/docs/bundle/yokohama-api-reference/page/integrate/inbound-rest/concept/c_AttachmentAPI.html)

#### Tags:

 - Attachments, Files, Records, Upload

#### Properties

- [Documentation](https://www.servicenow.com/docs/bundle/yokohama-api-reference/page/integrate/inbound-rest/concept/c_AttachmentAPI.html)
- [OpenAPI](openapi/servicenow-attachment-api-openapi.yml)

### ServiceNow Import Set API
The ServiceNow Import Set API allows external systems to push data into ServiceNow import set tables, which can then be synchronously or asynchronously transformed and loaded into target tables.

**Human URL:** [https://www.servicenow.com/docs/bundle/yokohama-api-reference/page/integrate/inbound-rest/concept/c_ImportSetAPI.html](https://www.servicenow.com/docs/bundle/yokohama-api-reference/page/integrate/inbound-rest/concept/c_ImportSetAPI.html)

#### Tags:

 - Data Loading, ETL, Import, Integration

#### Properties

- [Documentation](https://www.servicenow.com/docs/bundle/yokohama-api-reference/page/integrate/inbound-rest/concept/c_ImportSetAPI.html)
- [OpenAPI](openapi/servicenow-import-set-api-openapi.yml)

### ServiceNow Batch API
The ServiceNow Batch API enables sending multiple REST API requests in a single HTTP call, reducing network overhead and improving integration performance.

**Human URL:** [https://www.servicenow.com/docs/bundle/yokohama-api-reference/page/integrate/inbound-rest/concept/batch-api.html](https://www.servicenow.com/docs/bundle/yokohama-api-reference/page/integrate/inbound-rest/concept/batch-api.html)

#### Tags:

 - Batch, Integration, Performance, REST

#### Properties

- [Documentation](https://www.servicenow.com/docs/bundle/yokohama-api-reference/page/integrate/inbound-rest/concept/batch-api.html)

### ServiceNow Change Management API
The ServiceNow Change Management API provides REST endpoints for creating, retrieving, updating, and managing change requests and their associated tasks and approvals.

**Human URL:** [https://www.servicenow.com/docs/bundle/yokohama-api-reference/page/integrate/inbound-rest/concept/change-management-api.html](https://www.servicenow.com/docs/bundle/yokohama-api-reference/page/integrate/inbound-rest/concept/change-management-api.html)

#### Tags:

 - Change Management, IT Operations, ITSM, Workflows

#### Properties

- [Documentation](https://www.servicenow.com/docs/bundle/yokohama-api-reference/page/integrate/inbound-rest/concept/change-management-api.html)
- [APIReference](https://www.servicenow.com/docs/bundle/xanadu-api-reference/page/integrate/inbound-rest/concept/change-management-api.html)
- [OpenAPI](openapi/servicenow-change-management-api-openapi.yml)

### ServiceNow Knowledge Management API
The ServiceNow Knowledge Management REST API provides endpoints for searching and retrieving knowledge articles, including most-viewed and featured articles.

**Human URL:** [https://www.servicenow.com/docs/bundle/yokohama-api-reference/page/integrate/inbound-rest/concept/knowledge-api.html](https://www.servicenow.com/docs/bundle/yokohama-api-reference/page/integrate/inbound-rest/concept/knowledge-api.html)

#### Tags:

 - Articles, Knowledge Base, Knowledge Management, Self-Service

#### Properties

- [Documentation](https://www.servicenow.com/docs/bundle/yokohama-api-reference/page/integrate/inbound-rest/concept/knowledge-api.html)
- [APIReference](https://www.servicenow.com/docs/bundle/xanadu-api-reference/page/integrate/inbound-rest/concept/knowledge-api.html)

### ServiceNow Service Catalog API
The ServiceNow Service Catalog API provides REST endpoints for browsing catalog categories and items, retrieving catalog item details and variables, and submitting catalog requests.

**Human URL:** [https://www.servicenow.com/docs/bundle/yokohama-api-reference/page/integrate/inbound-rest/concept/c_ServiceCatalogAPI.html](https://www.servicenow.com/docs/bundle/yokohama-api-reference/page/integrate/inbound-rest/concept/c_ServiceCatalogAPI.html)

#### Tags:

 - ITSM, Requests, Self-Service, Service Catalog

#### Properties

- [Documentation](https://www.servicenow.com/docs/bundle/yokohama-api-reference/page/integrate/inbound-rest/concept/c_ServiceCatalogAPI.html)
- [APIReference](https://www.servicenow.com/docs/bundle/xanadu-api-reference/page/integrate/inbound-rest/concept/c_ServiceCatalogAPI.html)
- [OpenAPI](openapi/servicenow-service-catalog-api-openapi.yml)

### ServiceNow CMDB Instance API
The ServiceNow CMDB Instance API provides REST endpoints for retrieving configuration item (CI) records from the Configuration Management Database by class name and sys_id.

**Human URL:** [https://www.servicenow.com/docs/bundle/yokohama-api-reference/page/integrate/inbound-rest/concept/cmdb-instance-api.html](https://www.servicenow.com/docs/bundle/yokohama-api-reference/page/integrate/inbound-rest/concept/cmdb-instance-api.html)

#### Tags:

 - Assets, CMDB, Configuration Management, IT Operations

#### Properties

- [Documentation](https://www.servicenow.com/docs/bundle/yokohama-api-reference/page/integrate/inbound-rest/concept/cmdb-instance-api.html)
- [APIReference](https://www.servicenow.com/docs/bundle/xanadu-api-reference/page/integrate/inbound-rest/concept/cmdb-instance-api.html)
- [OpenAPI](openapi/servicenow-cmdb-instance-api-openapi.yml)

### ServiceNow Contact API
The ServiceNow Contact API provides endpoints for retrieving and updating Customer Service Management (CSM) contact records.

**Human URL:** [https://www.servicenow.com/docs/r/xanadu/api-reference/rest-apis/contact-api.html](https://www.servicenow.com/docs/r/xanadu/api-reference/rest-apis/contact-api.html)

#### Tags:

 - Contacts, CSM, Customer Service, Records

#### Properties

- [Documentation](https://www.servicenow.com/docs/r/xanadu/api-reference/rest-apis/contact-api.html)
- [OpenAPI](openapi/contact-api-openapi.yaml)

### ServiceNow Trouble Ticket Open API
The ServiceNow Trouble Ticket Open API provides endpoints to create, update, and retrieve data from Case, Incident, and Service Problem Case tables.

**Human URL:** [https://www.servicenow.com/docs/bundle/yokohama-api-reference/page/integrate/inbound-rest/concept/c_RESTAPI.html](https://www.servicenow.com/docs/bundle/yokohama-api-reference/page/integrate/inbound-rest/concept/c_RESTAPI.html)

#### Tags:

 - Customer Service, Incidents, TM Forum, Trouble Tickets

#### Properties

- [Documentation](https://www.servicenow.com/docs/bundle/yokohama-api-reference/page/integrate/inbound-rest/concept/c_RESTAPI.html)
- [OpenAPI](openapi/trouble-ticket-openapi.yaml)

### ServiceNow Identification and Reconciliation API
The ServiceNow Identification and Reconciliation API provides a REST endpoint for creating or updating configuration items (CIs) in the CMDB using the platform's identification and reconciliation engine.

**Human URL:** [https://www.servicenow.com/docs/bundle/yokohama-api-reference/page/integrate/inbound-rest/concept/c_IdentifyReconcileAPI.html](https://www.servicenow.com/docs/bundle/yokohama-api-reference/page/integrate/inbound-rest/concept/c_IdentifyReconcileAPI.html)

#### Tags:

 - CMDB, Configuration Management, Discovery, Reconciliation

#### Properties

- [Documentation](https://www.servicenow.com/docs/bundle/yokohama-api-reference/page/integrate/inbound-rest/concept/c_IdentifyReconcileAPI.html)
- [APIReference](https://www.servicenow.com/docs/bundle/xanadu-api-reference/page/integrate/inbound-rest/concept/c_IdentifyReconcileAPI.html)

### ServiceNow Performance Analytics API
The ServiceNow Performance Analytics API provides REST endpoints for retrieving performance analytics data including scores, breakdowns, and widget data.

**Human URL:** [https://www.servicenow.com/docs/bundle/yokohama-api-reference/page/integrate/inbound-rest/concept/c_PerformanceAnalyticsAPI.html](https://www.servicenow.com/docs/bundle/yokohama-api-reference/page/integrate/inbound-rest/concept/c_PerformanceAnalyticsAPI.html)

#### Tags:

 - Analytics, Dashboards, Performance, Reporting

#### Properties

- [Documentation](https://www.servicenow.com/docs/bundle/yokohama-api-reference/page/integrate/inbound-rest/concept/c_PerformanceAnalyticsAPI.html)

### ServiceNow Scripted REST APIs
ServiceNow Scripted REST APIs allow developers to create custom REST API endpoints on the Now Platform using server-side JavaScript.

**Human URL:** [https://www.servicenow.com/docs/bundle/yokohama-api-reference/page/integrate/custom-web-services/concept/c_CustomWebServices.html](https://www.servicenow.com/docs/bundle/yokohama-api-reference/page/integrate/custom-web-services/concept/c_CustomWebServices.html)

#### Tags:

 - Custom APIs, Integration, Platform, Scripting

#### Properties

- [Documentation](https://www.servicenow.com/docs/bundle/yokohama-api-reference/page/integrate/custom-web-services/concept/c_CustomWebServices.html)

### ServiceNow GraphQL API
The ServiceNow GraphQL API framework allows developers to create custom GraphQL API schemas on the Now Platform for querying record data.

**Human URL:** [https://docs.servicenow.com/bundle/tokyo-application-development/page/integrate/graphql/concept/scripted-graph-ql.html](https://docs.servicenow.com/bundle/tokyo-application-development/page/integrate/graphql/concept/scripted-graph-ql.html)

#### Tags:

 - Custom APIs, GraphQL, Integration, Platform

#### Properties

- [Documentation](https://docs.servicenow.com/bundle/tokyo-application-development/page/integrate/graphql/concept/scripted-graph-ql.html)
- [GettingStarted](https://www.servicenow.com/community/developer-articles/getting-started-graphql-api-framework/ta-p/2312207)

### ServiceNow Application Service API
The ServiceNow Application Service API provides REST endpoints to create, modify, and update application services in the CMDB.

**Human URL:** [https://www.servicenow.com/docs/bundle/yokohama-api-reference/page/integrate/inbound-rest/concept/application-service-api.html](https://www.servicenow.com/docs/bundle/yokohama-api-reference/page/integrate/inbound-rest/concept/application-service-api.html)

#### Tags:

 - Application Services, CMDB, IT Operations, Service Mapping

#### Properties

- [Documentation](https://www.servicenow.com/docs/bundle/yokohama-api-reference/page/integrate/inbound-rest/concept/application-service-api.html)

### ServiceNow Case API
The ServiceNow Case API provides REST endpoints for creating, retrieving, and updating Customer Service Management (CSM) case records.

**Human URL:** [https://www.servicenow.com/docs/bundle/yokohama-api-reference/page/integrate/inbound-rest/concept/case-api.html](https://www.servicenow.com/docs/bundle/yokohama-api-reference/page/integrate/inbound-rest/concept/case-api.html)

#### Tags:

 - Cases, CSM, Customer Service, Support

#### Properties

- [Documentation](https://www.servicenow.com/docs/bundle/yokohama-api-reference/page/integrate/inbound-rest/concept/case-api.html)

### ServiceNow Account API
The ServiceNow Account API provides REST endpoints for retrieving and managing customer account records within Customer Service Management (CSM).

**Human URL:** [https://www.servicenow.com/docs/bundle/yokohama-api-reference/page/integrate/inbound-rest/concept/account-api.html](https://www.servicenow.com/docs/bundle/yokohama-api-reference/page/integrate/inbound-rest/concept/account-api.html)

#### Tags:

 - Accounts, CSM, Customer Service, Records

#### Properties

- [Documentation](https://www.servicenow.com/docs/bundle/yokohama-api-reference/page/integrate/inbound-rest/concept/account-api.html)

### ServiceNow Consumer API
The ServiceNow Consumer API provides REST endpoints for retrieving and updating CSM consumer records.

**Human URL:** [https://www.servicenow.com/docs/bundle/yokohama-api-reference/page/integrate/inbound-rest/concept/c_RESTAPI.html](https://www.servicenow.com/docs/bundle/yokohama-api-reference/page/integrate/inbound-rest/concept/c_RESTAPI.html)

#### Tags:

 - Consumers, CSM, Customer Service, Self-Service

#### Properties

- [Documentation](https://www.servicenow.com/docs/bundle/yokohama-api-reference/page/integrate/inbound-rest/concept/c_RESTAPI.html)

### ServiceNow CSM Attachment API
The ServiceNow CSM Attachment API provides REST endpoints for uploading and managing file attachments on Customer Service Management records.

**Human URL:** [https://www.servicenow.com/docs/bundle/yokohama-api-reference/page/integrate/inbound-rest/concept/attachment_csm-api.html](https://www.servicenow.com/docs/bundle/yokohama-api-reference/page/integrate/inbound-rest/concept/attachment_csm-api.html)

#### Tags:

 - Attachments, CSM, Customer Service, Files

#### Properties

- [Documentation](https://www.servicenow.com/docs/bundle/yokohama-api-reference/page/integrate/inbound-rest/concept/attachment_csm-api.html)

### ServiceNow Email API
The ServiceNow Email API provides REST endpoints for sending email messages from the Now Platform.

**Human URL:** [https://www.servicenow.com/docs/bundle/yokohama-api-reference/page/integrate/inbound-rest/concept/email-api.html](https://www.servicenow.com/docs/bundle/yokohama-api-reference/page/integrate/inbound-rest/concept/email-api.html)

#### Tags:

 - Email, Messaging, Notifications, Platform

#### Properties

- [Documentation](https://www.servicenow.com/docs/bundle/yokohama-api-reference/page/integrate/inbound-rest/concept/email-api.html)

### ServiceNow CI/CD API
The ServiceNow CI/CD API provides REST endpoints for integrating ServiceNow application development with continuous integration and continuous delivery pipelines.

**Human URL:** [https://www.servicenow.com/docs/bundle/yokohama-api-reference/page/integrate/inbound-rest/concept/cicd-api.html](https://www.servicenow.com/docs/bundle/yokohama-api-reference/page/integrate/inbound-rest/concept/cicd-api.html)

#### Tags:

 - Automation, CI/CD, Deployment, DevOps

#### Properties

- [Documentation](https://www.servicenow.com/docs/bundle/yokohama-api-reference/page/integrate/inbound-rest/concept/cicd-api.html)

### ServiceNow CI/CD Update Set API
The ServiceNow CI/CD Update Set API provides REST methods to create, retrieve, preview, commit, and back out update sets.

**Human URL:** [https://www.servicenow.com/docs/bundle/yokohama-api-reference/page/integrate/inbound-rest/concept/cicd-update-set-api.html](https://www.servicenow.com/docs/bundle/yokohama-api-reference/page/integrate/inbound-rest/concept/cicd-update-set-api.html)

#### Tags:

 - CI/CD, Deployment, DevOps, Update Sets

#### Properties

- [Documentation](https://www.servicenow.com/docs/bundle/yokohama-api-reference/page/integrate/inbound-rest/concept/cicd-update-set-api.html)

### ServiceNow DevOps API
The ServiceNow DevOps API provides REST endpoints for integrating external DevOps toolchains with ServiceNow's DevOps Change Velocity product.

**Human URL:** [https://www.servicenow.com/docs/bundle/yokohama-api-reference/page/integrate/inbound-rest/concept/devops-api.html](https://www.servicenow.com/docs/bundle/yokohama-api-reference/page/integrate/inbound-rest/concept/devops-api.html)

#### Tags:

 - Change Velocity, CI/CD, DevOps, Pipelines

#### Properties

- [Documentation](https://www.servicenow.com/docs/bundle/yokohama-api-reference/page/integrate/inbound-rest/concept/devops-api.html)

### ServiceNow DevOps Config API
The ServiceNow DevOps Config API provides REST endpoints for managing DevOps configuration data and policies.

**Human URL:** [https://www.servicenow.com/docs/bundle/yokohama-api-reference/page/integrate/inbound-rest/concept/devops-config-api.html](https://www.servicenow.com/docs/bundle/yokohama-api-reference/page/integrate/inbound-rest/concept/devops-config-api.html)

#### Tags:

 - Automation, Change Management, Configuration, DevOps

#### Properties

- [Documentation](https://www.servicenow.com/docs/bundle/yokohama-api-reference/page/integrate/inbound-rest/concept/devops-config-api.html)

### ServiceNow CMDB Meta API
The ServiceNow CMDB Meta API provides REST endpoints for retrieving metadata about CMDB classes, including their attributes, relationships, and hierarchy.

**Human URL:** [https://www.servicenow.com/docs/bundle/yokohama-api-reference/page/integrate/inbound-rest/concept/cmdb-meta-api.html](https://www.servicenow.com/docs/bundle/yokohama-api-reference/page/integrate/inbound-rest/concept/cmdb-meta-api.html)

#### Tags:

 - CMDB, Configuration Management, Metadata, Schema

#### Properties

- [Documentation](https://www.servicenow.com/docs/bundle/yokohama-api-reference/page/integrate/inbound-rest/concept/cmdb-meta-api.html)

### ServiceNow CMDB Data Ingestion API
The ServiceNow CMDB Data Ingestion API provides REST endpoints for bulk ingesting configuration item data into the CMDB from external data sources.

**Human URL:** [https://www.servicenow.com/docs/bundle/yokohama-api-reference/page/integrate/inbound-rest/concept/cmdb-ingest-api.html](https://www.servicenow.com/docs/bundle/yokohama-api-reference/page/integrate/inbound-rest/concept/cmdb-ingest-api.html)

#### Tags:

 - CMDB, Configuration Management, Data Ingestion, Integration

#### Properties

- [Documentation](https://www.servicenow.com/docs/bundle/yokohama-api-reference/page/integrate/inbound-rest/concept/cmdb-ingest-api.html)

### ServiceNow MetricBase Time Series API
The ServiceNow MetricBase Time Series API provides REST endpoints for storing, retrieving, and transforming time series metric data on the Now Platform.

**Human URL:** [https://www.servicenow.com/docs/bundle/yokohama-api-reference/page/integrate/inbound-rest/concept/Clotho-Time-Series-API.html](https://www.servicenow.com/docs/bundle/yokohama-api-reference/page/integrate/inbound-rest/concept/Clotho-Time-Series-API.html)

#### Tags:

 - ITOM, Metrics, Monitoring, Time Series

#### Properties

- [Documentation](https://www.servicenow.com/docs/bundle/yokohama-api-reference/page/integrate/inbound-rest/concept/Clotho-Time-Series-API.html)

### ServiceNow Interaction Management API
The ServiceNow Interaction Management API provides REST endpoints for creating and managing customer interactions across multiple channels.

**Human URL:** [https://www.servicenow.com/docs/bundle/yokohama-api-reference/page/integrate/inbound-rest/concept/interaction-management-api.html](https://www.servicenow.com/docs/bundle/yokohama-api-reference/page/integrate/inbound-rest/concept/interaction-management-api.html)

#### Tags:

 - Agent Workspace, Customer Service, Interactions, Omnichannel

#### Properties

- [Documentation](https://www.servicenow.com/docs/bundle/yokohama-api-reference/page/integrate/inbound-rest/concept/interaction-management-api.html)

### ServiceNow Voice Interaction Resource API
The ServiceNow Voice Interaction Resource API provides REST endpoints for integrating telephony and voice systems with ServiceNow.

**Human URL:** [https://www.servicenow.com/docs/bundle/yokohama-api-reference/page/integrate/inbound-rest/concept/voice-interaction-resource-api.html](https://www.servicenow.com/docs/bundle/yokohama-api-reference/page/integrate/inbound-rest/concept/voice-interaction-resource-api.html)

#### Tags:

 - Contact Center, Interactions, Telephony, Voice

#### Properties

- [Documentation](https://www.servicenow.com/docs/bundle/yokohama-api-reference/page/integrate/inbound-rest/concept/voice-interaction-resource-api.html)

### ServiceNow User Role Inheritance API
The ServiceNow User Role Inheritance API provides REST endpoints for querying the role inheritance hierarchy for users and groups.

**Human URL:** [https://www.servicenow.com/docs/bundle/yokohama-api-reference/page/integrate/inbound-rest/concept/user-role-inheritance-api.html](https://www.servicenow.com/docs/bundle/yokohama-api-reference/page/integrate/inbound-rest/concept/user-role-inheritance-api.html)

#### Tags:

 - Access Control, Roles, Security, Users

#### Properties

- [Documentation](https://www.servicenow.com/docs/bundle/yokohama-api-reference/page/integrate/inbound-rest/concept/user-role-inheritance-api.html)

### ServiceNow HR API
The ServiceNow HR API provides REST endpoints for managing Human Resources Service Delivery (HRSD) data including employee cases, lifecycle events, and HR service requests.

**Human URL:** [https://www.servicenow.com/docs/bundle/yokohama-api-reference/page/integrate/inbound-rest/concept/hr-core-api.html](https://www.servicenow.com/docs/bundle/yokohama-api-reference/page/integrate/inbound-rest/concept/hr-core-api.html)

#### Tags:

 - Employee Services, HR Service Delivery, HRSD, Human Resources

#### Properties

- [Documentation](https://www.servicenow.com/docs/bundle/yokohama-api-reference/page/integrate/inbound-rest/concept/hr-core-api.html)

### ServiceNow Event Management Topic Open API
The ServiceNow Event Management Topic Open API provides REST endpoints for managing event topics and subscriptions within IT Operations Management.

**Human URL:** [https://www.servicenow.com/docs/bundle/yokohama-api-reference/page/integrate/inbound-rest/concept/event_management_topic-api.html](https://www.servicenow.com/docs/bundle/yokohama-api-reference/page/integrate/inbound-rest/concept/event_management_topic-api.html)

#### Tags:

 - Alerts, Event Management, ITOM, Monitoring

#### Properties

- [Documentation](https://www.servicenow.com/docs/bundle/yokohama-api-reference/page/integrate/inbound-rest/concept/event_management_topic-api.html)
- [AsyncAPI](asyncapi/servicenow-events-asyncapi.yml)

### ServiceNow Predictive Intelligence API
The ServiceNow Predictive Intelligence API provides REST endpoints for accessing machine learning prediction models on the Now Platform.

**Human URL:** [https://www.servicenow.com/docs/bundle/yokohama-api-reference/page/integrate/inbound-rest/concept/agent-intelligence-api.html](https://www.servicenow.com/docs/bundle/yokohama-api-reference/page/integrate/inbound-rest/concept/agent-intelligence-api.html)

#### Tags:

 - AI, Classification, Machine Learning, Predictions

#### Properties

- [Documentation](https://www.servicenow.com/docs/bundle/yokohama-api-reference/page/integrate/inbound-rest/concept/agent-intelligence-api.html)

### ServiceNow AWA Agent API
The ServiceNow AWA Agent API provides REST endpoints for managing agent availability, presence, and capacity within Advanced Work Assignment (AWA).

**Human URL:** [https://www.servicenow.com/docs/bundle/yokohama-api-reference/page/integrate/inbound-rest/concept/agent-api.html](https://www.servicenow.com/docs/bundle/yokohama-api-reference/page/integrate/inbound-rest/concept/agent-api.html)

#### Tags:

 - Agent Workspace, Queues, Routing, Workforce Management

#### Properties

- [Documentation](https://www.servicenow.com/docs/bundle/yokohama-api-reference/page/integrate/inbound-rest/concept/agent-api.html)

### ServiceNow AWA Offer Work API
The ServiceNow AWA Offer Work API provides REST endpoints to assign or transfer work items to agents through the Advanced Work Assignment engine.

**Human URL:** [https://www.servicenow.com/docs/bundle/yokohama-api-reference/page/integrate/inbound-rest/concept/awa-offer-work-api.html](https://www.servicenow.com/docs/bundle/yokohama-api-reference/page/integrate/inbound-rest/concept/awa-offer-work-api.html)

#### Tags:

 - Agent Workspace, Queues, Routing, Work Assignment

#### Properties

- [Documentation](https://www.servicenow.com/docs/bundle/yokohama-api-reference/page/integrate/inbound-rest/concept/awa-offer-work-api.html)

### ServiceNow Virtual Agent Bot Integration API
The ServiceNow Virtual Agent Bot Integration API provides REST endpoints for integrating external messaging platforms and chatbot frameworks with ServiceNow Virtual Agent.

**Human URL:** [https://www.servicenow.com/docs/bundle/yokohama-api-reference/page/integrate/inbound-rest/concept/bot-api.html](https://www.servicenow.com/docs/bundle/yokohama-api-reference/page/integrate/inbound-rest/concept/bot-api.html)

#### Tags:

 - Chatbot, Conversational AI, Self-Service, Virtual Agent

#### Properties

- [Documentation](https://www.servicenow.com/docs/bundle/yokohama-api-reference/page/integrate/inbound-rest/concept/bot-api.html)

### ServiceNow Openframe API
The ServiceNow Openframe API provides REST endpoints that enable Contact Center as a Service (CCaaS) providers to create and update interaction records.

**Human URL:** [https://www.servicenow.com/docs/bundle/yokohama-api-reference/page/integrate/inbound-rest/concept/openframe-api.html](https://www.servicenow.com/docs/bundle/yokohama-api-reference/page/integrate/inbound-rest/concept/openframe-api.html)

#### Tags:

 - CCaaS, Contact Center, Integration, Telephony

#### Properties

- [Documentation](https://www.servicenow.com/docs/bundle/yokohama-api-reference/page/integrate/inbound-rest/concept/openframe-api.html)

### ServiceNow AI Assets API
The ServiceNow AI Assets API provides REST endpoints to retrieve, update, and create AI assets such as systems, data sets, prompts, and models.

**Human URL:** [https://www.servicenow.com/docs/bundle/yokohama-api-reference/page/integrate/inbound-rest/concept/ai-assets-api.html](https://www.servicenow.com/docs/bundle/yokohama-api-reference/page/integrate/inbound-rest/concept/ai-assets-api.html)

#### Tags:

 - AI Governance, Artificial Intelligence, Machine Learning, Platform

#### Properties

- [Documentation](https://www.servicenow.com/docs/bundle/yokohama-api-reference/page/integrate/inbound-rest/concept/ai-assets-api.html)

### ServiceNow Lead API
The ServiceNow Lead API provides REST endpoints to create, update, and retrieve marketing leads and their associated lead line items.

**Human URL:** [https://www.servicenow.com/docs/bundle/yokohama-api-reference/page/integrate/inbound-rest/concept/c_RESTAPI.html](https://www.servicenow.com/docs/bundle/yokohama-api-reference/page/integrate/inbound-rest/concept/c_RESTAPI.html)

#### Tags:

 - CRM, Leads, Marketing, Sales

#### Properties

- [Documentation](https://www.servicenow.com/docs/bundle/yokohama-api-reference/page/integrate/inbound-rest/concept/c_RESTAPI.html)

### ServiceNow Sales Agreement API
The ServiceNow Sales Agreement API provides REST methods for creating new sales agreements and retrieving existing sales agreements by sys_id.

**Human URL:** [https://www.servicenow.com/docs/bundle/yokohama-api-reference/page/integrate/inbound-rest/concept/c_RESTAPI.html](https://www.servicenow.com/docs/bundle/yokohama-api-reference/page/integrate/inbound-rest/concept/c_RESTAPI.html)

#### Tags:

 - Agreements, Contracts, CRM, Sales

#### Properties

- [Documentation](https://www.servicenow.com/docs/bundle/yokohama-api-reference/page/integrate/inbound-rest/concept/c_RESTAPI.html)

### ServiceNow Agent Client Collector API
The ServiceNow Agent Client Collector (ACC) API provides REST endpoints for managing agent client collectors used in IT Operations Management.

**Human URL:** [https://www.servicenow.com/docs/bundle/yokohama-api-reference/page/integrate/inbound-rest/concept/agnt_clnt_cll-api.html](https://www.servicenow.com/docs/bundle/yokohama-api-reference/page/integrate/inbound-rest/concept/agnt_clnt_cll-api.html)

#### Tags:

 - Agents, Discovery, ITOM, Monitoring

#### Properties

- [Documentation](https://www.servicenow.com/docs/bundle/yokohama-api-reference/page/integrate/inbound-rest/concept/agnt_clnt_cll-api.html)

### ServiceNow Agent Mapping API
The ServiceNow Agent Mapping API provides REST endpoints for managing agent mapping configurations.

**Human URL:** [https://www.servicenow.com/docs/bundle/yokohama-api-reference/page/integrate/inbound-rest/concept/agent-mapping-api.html](https://www.servicenow.com/docs/bundle/yokohama-api-reference/page/integrate/inbound-rest/concept/agent-mapping-api.html)

#### Tags:

 - Agent Workspace, Integration, Mapping, Routing

#### Properties

- [Documentation](https://www.servicenow.com/docs/bundle/yokohama-api-reference/page/integrate/inbound-rest/concept/agent-mapping-api.html)

### ServiceNow Automation Center API
The ServiceNow Automation Center API provides REST endpoints for managing and executing automation workflows on the Now Platform.

**Human URL:** [https://www.servicenow.com/docs/bundle/yokohama-api-reference/page/integrate/inbound-rest/concept/auto-api.html](https://www.servicenow.com/docs/bundle/yokohama-api-reference/page/integrate/inbound-rest/concept/auto-api.html)

#### Tags:

 - Automation, Orchestration, Platform, Workflows

#### Properties

- [Documentation](https://www.servicenow.com/docs/bundle/yokohama-api-reference/page/integrate/inbound-rest/concept/auto-api.html)

### ServiceNow AP Invoice API
The ServiceNow AP Invoice API provides REST endpoints for managing accounts payable invoice records on the Now Platform.

**Human URL:** [https://www.servicenow.com/docs/bundle/yokohama-api-reference/page/integrate/inbound-rest/concept/ap-invoice-api.html](https://www.servicenow.com/docs/bundle/yokohama-api-reference/page/integrate/inbound-rest/concept/ap-invoice-api.html)

#### Tags:

 - Accounts Payable, Finance, Invoices, Procurement

#### Properties

- [Documentation](https://www.servicenow.com/docs/bundle/yokohama-api-reference/page/integrate/inbound-rest/concept/ap-invoice-api.html)

### ServiceNow CSM Order API
The ServiceNow CSM Order API provides REST endpoints for managing order records within Customer Service Management.

**Human URL:** [https://www.servicenow.com/docs/bundle/yokohama-api-reference/page/integrate/inbound-rest/concept/order_csm-api.html](https://www.servicenow.com/docs/bundle/yokohama-api-reference/page/integrate/inbound-rest/concept/order_csm-api.html)

#### Tags:

 - Commerce, CSM, Customer Service, Orders

#### Properties

- [Documentation](https://www.servicenow.com/docs/bundle/yokohama-api-reference/page/integrate/inbound-rest/concept/order_csm-api.html)

### ServiceNow CI Lifecycle Management API
The ServiceNow CI Lifecycle Management API provides REST endpoints for managing the lifecycle states of configuration items (CIs) in the CMDB.

**Human URL:** [https://www.servicenow.com/docs/bundle/yokohama-api-reference/page/integrate/inbound-rest/concept/ci-lifecycle-management-api.html](https://www.servicenow.com/docs/bundle/yokohama-api-reference/page/integrate/inbound-rest/concept/ci-lifecycle-management-api.html)

#### Tags:

 - CMDB, Configuration Management, IT Operations, Lifecycle

#### Properties

- [Documentation](https://www.servicenow.com/docs/bundle/yokohama-api-reference/page/integrate/inbound-rest/concept/ci-lifecycle-management-api.html)

### ServiceNow Alarm Management Open API
The ServiceNow Alarm Management Open API provides REST endpoints for managing alarm records within IT Operations Management.

**Human URL:** [https://www.servicenow.com/docs/bundle/yokohama-api-reference/page/integrate/inbound-rest/concept/alarm-open-api.html](https://www.servicenow.com/docs/bundle/yokohama-api-reference/page/integrate/inbound-rest/concept/alarm-open-api.html)

#### Tags:

 - Alerts, Event Management, ITOM, Monitoring

#### Properties

- [Documentation](https://www.servicenow.com/docs/bundle/yokohama-api-reference/page/integrate/inbound-rest/concept/alarm-open-api.html)

### ServiceNow SAM Software Usage Data Integration API
The ServiceNow SAM Software Usage Data Integration API provides REST endpoints for importing software usage and metering data into Software Asset Management.

**Human URL:** [https://www.servicenow.com/docs/bundle/yokohama-api-reference/page/integrate/inbound-rest/concept/sam_soft_us_int-api.html](https://www.servicenow.com/docs/bundle/yokohama-api-reference/page/integrate/inbound-rest/concept/sam_soft_us_int-api.html)

#### Tags:

 - ITAM, Licensing, Software Asset Management, Usage Tracking

#### Properties

- [Documentation](https://www.servicenow.com/docs/bundle/yokohama-api-reference/page/integrate/inbound-rest/concept/sam_soft_us_int-api.html)

### ServiceNow Product Catalog Open API
The ServiceNow Product Catalog Open API provides REST endpoints for managing product catalog data based on the TM Forum TMF620 specification.

**Human URL:** [https://www.servicenow.com/docs/bundle/yokohama-api-reference/page/integrate/inbound-rest/concept/product-catalog-open-api.html](https://www.servicenow.com/docs/bundle/yokohama-api-reference/page/integrate/inbound-rest/concept/product-catalog-open-api.html)

#### Tags:

 - Commerce, Product Catalog, Telecommunications, TMF

#### Properties

- [Documentation](https://www.servicenow.com/docs/bundle/yokohama-api-reference/page/integrate/inbound-rest/concept/product-catalog-open-api.html)

### ServiceNow Service Catalog Open API
The ServiceNow Service Catalog Open API provides REST endpoints for managing service catalog data based on the TM Forum TMF633 specification.

**Human URL:** [https://www.servicenow.com/docs/bundle/yokohama-api-reference/page/integrate/inbound-rest/concept/service-catalog-open-api.html](https://www.servicenow.com/docs/bundle/yokohama-api-reference/page/integrate/inbound-rest/concept/service-catalog-open-api.html)

#### Tags:

 - Commerce, Service Catalog, Telecommunications, TMF

#### Properties

- [Documentation](https://www.servicenow.com/docs/bundle/yokohama-api-reference/page/integrate/inbound-rest/concept/service-catalog-open-api.html)

### ServiceNow Product Order Open API
The ServiceNow Product Order Open API provides REST endpoints for managing product orders based on the TM Forum TMF622 specification.

**Human URL:** [https://www.servicenow.com/docs/bundle/yokohama-api-reference/page/integrate/inbound-rest/concept/tmf622_product_ordering-api.html](https://www.servicenow.com/docs/bundle/yokohama-api-reference/page/integrate/inbound-rest/concept/tmf622_product_ordering-api.html)

#### Tags:

 - Commerce, Product Ordering, Telecommunications, TMF

#### Properties

- [Documentation](https://www.servicenow.com/docs/bundle/yokohama-api-reference/page/integrate/inbound-rest/concept/tmf622_product_ordering-api.html)

### ServiceNow Service Order Open API
The ServiceNow Service Order Open API provides REST endpoints for managing service orders based on the TM Forum TMF641 specification.

**Human URL:** [https://www.servicenow.com/docs/bundle/yokohama-api-reference/page/integrate/inbound-rest/concept/service-order-open-api.html](https://www.servicenow.com/docs/bundle/yokohama-api-reference/page/integrate/inbound-rest/concept/service-order-open-api.html)

#### Tags:

 - Commerce, Service Ordering, Telecommunications, TMF

#### Properties

- [Documentation](https://www.servicenow.com/docs/bundle/yokohama-api-reference/page/integrate/inbound-rest/concept/service-order-open-api.html)

### ServiceNow Resource Inventory Open API
The ServiceNow Resource Inventory Open API provides REST endpoints for managing resource inventory data based on TM Forum specifications.

**Human URL:** [https://www.servicenow.com/docs/bundle/yokohama-api-reference/page/integrate/inbound-rest/concept/resource-inventory-api.html](https://www.servicenow.com/docs/bundle/yokohama-api-reference/page/integrate/inbound-rest/concept/resource-inventory-api.html)

#### Tags:

 - Inventory, Resources, Telecommunications, TMF

#### Properties

- [Documentation](https://www.servicenow.com/docs/bundle/yokohama-api-reference/page/integrate/inbound-rest/concept/resource-inventory-api.html)

### ServiceNow Product Inventory Open API
The ServiceNow Product Inventory Open API provides REST endpoints for managing product inventory data based on TM Forum specifications.

**Human URL:** [https://www.servicenow.com/docs/bundle/yokohama-api-reference/page/integrate/inbound-rest/concept/product-inventory-open-api.html](https://www.servicenow.com/docs/bundle/yokohama-api-reference/page/integrate/inbound-rest/concept/product-inventory-open-api.html)

#### Tags:

 - Inventory, Products, Telecommunications, TMF

#### Properties

- [Documentation](https://www.servicenow.com/docs/bundle/yokohama-api-reference/page/integrate/inbound-rest/concept/product-inventory-open-api.html)

### ServiceNow Service Test Management Open API
The ServiceNow Service Test Management Open API provides REST endpoints for managing service test records based on TM Forum specifications.

**Human URL:** [https://www.servicenow.com/docs/bundle/yokohama-api-reference/page/integrate/inbound-rest/concept/service-test-management-api.html](https://www.servicenow.com/docs/bundle/yokohama-api-reference/page/integrate/inbound-rest/concept/service-test-management-api.html)

#### Tags:

 - Quality, Service Testing, Telecommunications, TMF

#### Properties

- [Documentation](https://www.servicenow.com/docs/bundle/yokohama-api-reference/page/integrate/inbound-rest/concept/service-test-management-api.html)

### ServiceNow Project Portfolio Management API
The ServiceNow Project Portfolio Management API provides REST endpoints for managing projects, demands, and resource plans within Strategic Portfolio Management (SPM).

**Human URL:** [https://www.servicenow.com/docs/bundle/yokohama-api-reference/page/integrate/inbound-rest/concept/ppm-api.html](https://www.servicenow.com/docs/bundle/yokohama-api-reference/page/integrate/inbound-rest/concept/ppm-api.html)

#### Tags:

 - Governance, PPM, Project Management, Strategic Portfolio Management

#### Properties

- [Documentation](https://www.servicenow.com/docs/bundle/yokohama-api-reference/page/integrate/inbound-rest/concept/ppm-api.html)

## Common Properties

- [JSONLD](json-ld/servicenow-context.jsonld)
- [JSONSchema](json-schema/servicenow-incident-schema.json)
- [JSONSchema](json-schema/servicenow-change-request-schema.json)
- [JSONSchema](json-schema/servicenow-configuration-item-schema.json)
- [JSONSchema](json-schema/servicenow-catalog-request-schema.json)
- [JSONSchema](json-schema/servicenow-user-schema.json)
- [Portal](https://developer.servicenow.com)
- [Blog](https://www.servicenow.com/community/developer-blog/bg-p/developer-blog)
- [Events](https://www.servicenow.com/community/events/ct-p/TopLevel_Events)
- [Community](https://www.servicenow.com/community/)
- [Documentation](https://www.servicenow.com/docs/)
- [APIReference](https://www.servicenow.com/docs/bundle/yokohama-api-reference/page/integrate/inbound-rest/concept/c_RESTAPI.html)
- [GettingStarted](https://developer.servicenow.com/dev.do#!/learn/learning-plans/tokyo/new_to_servicenow/app_store_learnv2_rest_tokyo_rest_api_explorer)
- [Authentication](https://www.servicenow.com/docs/bundle/yokohama-platform-security/page/administer/security/concept/c_OAuthApplications.html)
- [RateLimits](https://www.servicenow.com/docs/bundle/yokohama-api-reference/page/integrate/inbound-rest/concept/c_RESTAPI.html)
- [StatusPage](https://status.servicenow.com)
- [Support](https://support.servicenow.com)
- [Pricing](https://www.servicenow.com/products/pricing.html)
- [TermsOfService](https://www.servicenow.com/terms-of-use.html)
- [PrivacyPolicy](https://www.servicenow.com/privacy-statement.html)
- [ChangeLog](https://www.servicenow.com/docs/bundle/yokohama-release-notes/page/release-notes/family-release-notes.html)
- [GitHubOrganization](https://github.com/ServiceNow)
- [GitHubOrganization](https://github.com/ServiceNowDevProgram)
- [GitHubRepository](https://github.com/ServiceNow/sdk)
- [SDK](https://www.npmjs.com/package/@servicenow/sdk)
- [Documentation](https://www.servicenow.com/docs/bundle/yokohama-application-development/page/build/servicenow-sdk/concept/servicenow-sdk-landing.html)
- [StackOverflow](https://stackoverflow.com/questions/tagged/servicenow)
- [SignUp](https://developer.servicenow.com/dev.do)
- [Login](https://developer.servicenow.com/dev.do)
- [YouTube](https://www.youtube.com/user/serviceaborad)
- [RateLimits](https://www.servicenow.com/docs/bundle/yokohama-api-reference/page/integrate/inbound-rest/concept/inbound-REST-API-rate-limiting.html)
- [Documentation](https://www.servicenow.com/docs/bundle/yokohama-api-reference/page/integrate/inbound-rest/concept/use-REST-API-Explorer.html)
- [Documentation](https://www.servicenow.com/docs/bundle/yokohama-api-reference/page/integrate/inbound-rest/task/export-openapi-specification.html)
- [GitHubRepository](https://github.com/ServiceNow/PySNC)
- [SDK](https://pypi.org/project/pysnc/)
- [Documentation](https://servicenow.github.io/PySNC/)
- [Authentication](https://www.servicenow.com/docs/bundle/yokohama-api-reference/page/integrate/inbound-rest/task/t_EnableOAuthWithREST.html)
- [X](https://x.com/ServiceNow)
- [LinkedIn](https://www.linkedin.com/company/servicenow)
- [GettingStarted](https://www.servicenow.com/university/training-and-certification.html)
- [Documentation](https://www.servicenow.com/products/api-integrations.html)
- [APIReference](https://developer.servicenow.com/dev.do#!/reference/api/yokohama/rest/)
- [JSONLD](json-ld/contact-context.jsonld)
- [JSONLD](json-ld/servicenow-aggregate-context.jsonld)
- [JSONLD](json-ld/servicenow-attachment-context.jsonld)
- [JSONLD](json-ld/servicenow-change-management-context.jsonld)
- [JSONLD](json-ld/servicenow-cmdb-instance-context.jsonld)
- [JSONLD](json-ld/servicenow-import-set-context.jsonld)
- [JSONLD](json-ld/servicenow-service-catalog-context.jsonld)
- [JSONLD](json-ld/servicenow-table-context.jsonld)
- [JSONLD](json-ld/trouble-ticket-context.jsonld)
- [SpectralRules](rules/servicenow-spectral-rules.yml)
- [Vocabulary](vocabulary/servicenow-vocabulary.yaml)
- [NaftikoCapability](capabilities/itsm-operations.yaml)
- [NaftikoCapability](capabilities/customer-service.yaml)
- [NaftikoCapability](capabilities/data-integration-and-configuration.yaml)

## Features

| Name | Description |
|------|-------------|
| Table-Driven Architecture | Universal Table API for CRUD operations on any ServiceNow table including incidents, changes, and custom tables. |
| IT Service Management | Complete ITSM capabilities with dedicated APIs for incident, change, problem, and knowledge management. |
| Configuration Management Database | CMDB APIs for managing configuration items, relationships, and service mappings with identification and reconciliation. |
| Service Catalog And Self-Service | Service Catalog APIs for browsing items, submitting requests, and managing cart operations. |
| Customer Service Management | CSM APIs for cases, contacts, accounts, and consumer management with omnichannel routing. |
| Advanced Work Assignment | AWA APIs for intelligent work routing, agent management, and capacity-based assignment. |
| Virtual Agent Integration | Bot Integration APIs for connecting external messaging platforms with ServiceNow conversational AI. |
| CI/CD And DevOps | CI/CD and DevOps APIs for automated application deployment, testing, and change velocity management. |
| Event Management | Event Management APIs for ingesting alerts and events from external monitoring systems. |
| Predictive Intelligence | ML-powered APIs for automated classification, assignment, and prioritization of records. |

## Use Cases

| Name | Description |
|------|-------------|
| Incident Management Automation | Automate incident creation, assignment, escalation, and resolution through Table and Predictive Intelligence APIs. |
| Change Management Integration | Integrate external CI/CD pipelines with ServiceNow change management for automated change request workflows. |
| CMDB Synchronization | Keep the CMDB in sync with external discovery and monitoring tools using Identification and Reconciliation APIs. |
| Self-Service Portal Integration | Build custom portals that browse service catalogs, submit requests, and track order status. |
| Customer Service Orchestration | Manage customer cases, contacts, and interactions across channels with CSM and Virtual Agent APIs. |
| IT Operations Monitoring | Ingest events and metrics from monitoring tools for centralized alert management and correlation. |
| Data Migration And ETL | Load data from external sources using Import Set APIs with transform maps for automated field mapping. |
| Workforce Optimization | Manage agent availability and route work items based on skills and capacity using AWA APIs. |

## Integrations

| Name | Description |
|------|-------------|
| Jira | Bidirectional synchronization of incidents and issues between ServiceNow and Atlassian Jira. |
| Microsoft Teams | Virtual Agent and notification integration for managing IT requests directly from Microsoft Teams. |
| Slack | Conversational IT support and incident management through Slack channel integrations. |
| Jenkins | CI/CD pipeline integration for automated change request creation and deployment tracking. |
| Azure DevOps | DevOps pipeline integration for change velocity and automated deployment workflows. |
| Splunk | Event and alert ingestion from Splunk for centralized IT operations monitoring. |
| PagerDuty | Incident alerting and on-call management integration for streamlined incident response. |
| AWS | Cloud resource discovery and CMDB synchronization for AWS infrastructure management. |

## Artifacts

Machine-readable API specifications organized by format.

### OpenAPI

- [ServiceNow Table API OpenAPI](openapi/servicenow-table-api-openapi.yml)
- [ServiceNow Import Set API OpenAPI](openapi/servicenow-import-set-api-openapi.yml)
- [Contact API OpenAPI](openapi/contact-api-openapi.yaml)
- [Trouble Ticket OpenAPI](openapi/trouble-ticket-openapi.yaml)
- [ServiceNow CMDB Instance API OpenAPI](openapi/servicenow-cmdb-instance-api-openapi.yml)
- [ServiceNow Service Catalog API OpenAPI](openapi/servicenow-service-catalog-api-openapi.yml)
- [ServiceNow Change Management API OpenAPI](openapi/servicenow-change-management-api-openapi.yml)
- [ServiceNow Aggregate API OpenAPI](openapi/servicenow-aggregate-api-openapi.yml)
- [ServiceNow Attachment API OpenAPI](openapi/servicenow-attachment-api-openapi.yml)

### AsyncAPI

- [ServiceNow Events AsyncAPI](asyncapi/servicenow-events-asyncapi.yml)

### JSON-LD

- [ServiceNow Context](json-ld/servicenow-context.jsonld)
- [Contact Context](json-ld/contact-context.jsonld)
- [ServiceNow Aggregate Context](json-ld/servicenow-aggregate-context.jsonld)
- [ServiceNow Attachment Context](json-ld/servicenow-attachment-context.jsonld)
- [ServiceNow Change Management Context](json-ld/servicenow-change-management-context.jsonld)
- [ServiceNow CMDB Instance Context](json-ld/servicenow-cmdb-instance-context.jsonld)
- [ServiceNow Import Set Context](json-ld/servicenow-import-set-context.jsonld)
- [ServiceNow Service Catalog Context](json-ld/servicenow-service-catalog-context.jsonld)
- [ServiceNow Table Context](json-ld/servicenow-table-context.jsonld)
- [Trouble Ticket Context](json-ld/trouble-ticket-context.jsonld)

## Capabilities

Naftiko capabilities organized as shared per-API definitions composed into customer-facing workflows.

### Shared Per-API Definitions

- [ServiceNow Table](capabilities/shared/table.yaml) -- 11 operations for table record CRUD
- [ServiceNow Aggregate](capabilities/shared/aggregate.yaml) -- 2 operations for aggregate statistics
- [ServiceNow Attachment](capabilities/shared/attachment.yaml) -- 9 operations for file attachment management
- [ServiceNow Change Management](capabilities/shared/change-management.yaml) -- 19 operations for change request lifecycle
- [ServiceNow CMDB Instance](capabilities/shared/cmdb-instance.yaml) -- 4 operations for CI retrieval
- [ServiceNow Import Set](capabilities/shared/import-set.yaml) -- 4 operations for data import and transformation
- [ServiceNow Service Catalog](capabilities/shared/service-catalog.yaml) -- 16 operations for catalog browsing and ordering
- [ServiceNow Contact](capabilities/shared/contact.yaml) -- 6 operations for CSM contact management
- [ServiceNow Trouble Ticket](capabilities/shared/trouble-ticket.yaml) -- 8 operations for trouble ticket management

### Workflow Capabilities

| Workflow | APIs Combined | Tools | Persona |
|----------|--------------|-------|---------|
| [ITSM Operations](capabilities/itsm-operations.yaml) | Table, Aggregate, Change Management, Trouble Ticket | 17 | ITSM administrators and service desk agents |
| [Customer Service](capabilities/customer-service.yaml) | Contact, Service Catalog, Trouble Ticket | 10 | Customer service agents and self-service portals |
| [Data Integration And Configuration](capabilities/data-integration-and-configuration.yaml) | Import Set, CMDB Instance, Attachment | 7 | Integration engineers and CMDB administrators |

## Vocabulary

- [ServiceNow Vocabulary](vocabulary/servicenow-vocabulary.yaml) -- Unified taxonomy mapping 9 resources, 44 operations, and 35 schemas across operational (OpenAPI) and capability (Naftiko) dimensions

## Rules

- [ServiceNow Spectral Rules](rules/servicenow-spectral-rules.yml) -- 21 rules enforcing ServiceNow API conventions

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
