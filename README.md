# ServiceNow (servicenow)

ServiceNow provides cloud-based platform services that automate enterprise IT operations.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/servicenow/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/servicenow/refs/heads/main/apis.yml)

## Scope

- **Position:** Consuming
- **Access:** 3rd-Party

## Tags

- Automation
- Cloud Services
- Digital Workflows
- Enterprise Platform
- IT Service Management
- ITSM
- Processes
- T1
- Workflow Automation
- Workflows

## Timestamps

- **Created:** 2025-01-08
- **Modified:** 2026-05-19

## APIs

### ServiceNow Table API

The ServiceNow Table API provides endpoints to perform create, read, update, and delete (CRUD) operations on records within any ServiceNow table. It is the primary REST interface for interacting with ServiceNow platform data such as incidents, problems, changes, and custom tables.

- **Human URL:** [https://www.servicenow.com/docs/bundle/yokohama-api-reference/page/integrate/inbound-rest/concept/c_TableAPI.html](https://www.servicenow.com/docs/bundle/yokohama-api-reference/page/integrate/inbound-rest/concept/c_TableAPI.html)
- **Base URL:** `https://{instance}.service-now.com/api/now/table`

#### Tags

- CRUD
- Data
- ITSM
- Records
- Tables

#### Properties

- [Documentation](https://www.servicenow.com/docs/bundle/yokohama-api-reference/page/integrate/inbound-rest/concept/c_TableAPI.html)
- [API Reference](https://www.servicenow.com/docs/bundle/xanadu-api-reference/page/integrate/inbound-rest/concept/c_TableAPI.html)
- [OpenAPI](openapi/servicenow-table-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/servicenow-table-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/servicenow-table-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### ServiceNow Aggregate API

The ServiceNow Aggregate API provides endpoints to compute aggregate statistics (count, average, min, max, sum) against records in any ServiceNow table. It supports grouping and filtering results, making it useful for reporting and dashboard data retrieval.

- **Human URL:** [https://www.servicenow.com/docs/bundle/yokohama-api-reference/page/integrate/inbound-rest/concept/c_AggregateAPI.html](https://www.servicenow.com/docs/bundle/yokohama-api-reference/page/integrate/inbound-rest/concept/c_AggregateAPI.html)
- **Base URL:** `https://{instance}.service-now.com/api/now/stats`

#### Tags

- Aggregation
- Analytics
- Reporting
- Statistics
- Tables

#### Properties

- [Documentation](https://www.servicenow.com/docs/bundle/yokohama-api-reference/page/integrate/inbound-rest/concept/c_AggregateAPI.html)
- [OpenAPI](openapi/servicenow-aggregate-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/servicenow-aggregate-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/servicenow-aggregate-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### ServiceNow Attachment API

The ServiceNow Attachment API enables uploading, retrieving, and deleting file attachments associated with records in ServiceNow tables. It supports uploading files via multipart/form-data or binary streams and allows up to 1024 MB file size by default.

- **Human URL:** [https://www.servicenow.com/docs/bundle/yokohama-api-reference/page/integrate/inbound-rest/concept/c_AttachmentAPI.html](https://www.servicenow.com/docs/bundle/yokohama-api-reference/page/integrate/inbound-rest/concept/c_AttachmentAPI.html)
- **Base URL:** `https://{instance}.service-now.com/api/now/attachment`

#### Tags

- Attachments
- Files
- Records
- Upload

#### Properties

- [Documentation](https://www.servicenow.com/docs/bundle/yokohama-api-reference/page/integrate/inbound-rest/concept/c_AttachmentAPI.html)
- [OpenAPI](openapi/servicenow-attachment-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/servicenow-attachment-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/servicenow-attachment-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### ServiceNow Import Set API

The ServiceNow Import Set API allows external systems to push data into ServiceNow import set tables, which can then be synchronously or asynchronously transformed and loaded into target tables. It is commonly used for integrating external data sources with ServiceNow using transform maps.

- **Human URL:** [https://www.servicenow.com/docs/bundle/yokohama-api-reference/page/integrate/inbound-rest/concept/c_ImportSetAPI.html](https://www.servicenow.com/docs/bundle/yokohama-api-reference/page/integrate/inbound-rest/concept/c_ImportSetAPI.html)
- **Base URL:** `https://{instance}.service-now.com/api/now/import`

#### Tags

- Data Loading
- ETL
- Import
- Integration

#### Properties

- [Documentation](https://www.servicenow.com/docs/bundle/yokohama-api-reference/page/integrate/inbound-rest/concept/c_ImportSetAPI.html)
- [OpenAPI](openapi/servicenow-import-set-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/servicenow-import-set-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/servicenow-import-set-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### ServiceNow Batch API

The ServiceNow Batch API enables sending multiple REST API requests in a single HTTP call, reducing network overhead and improving integration performance. Each request in the batch is executed independently, and the API returns a stream of corresponding responses.

- **Human URL:** [https://www.servicenow.com/docs/bundle/yokohama-api-reference/page/integrate/inbound-rest/concept/batch-api.html](https://www.servicenow.com/docs/bundle/yokohama-api-reference/page/integrate/inbound-rest/concept/batch-api.html)
- **Base URL:** `https://{instance}.service-now.com/api/now/v1/batch`

#### Tags

- Batch
- Integration
- Performance
- REST

#### Properties

- [Documentation](https://www.servicenow.com/docs/bundle/yokohama-api-reference/page/integrate/inbound-rest/concept/batch-api.html)
- [Postman Collection](collections/servicenow-aggregate-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/servicenow-aggregate-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/servicenow-attachment-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/servicenow-attachment-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/servicenow-change-management-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/servicenow-change-management-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/servicenow-cmdb-instance-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/servicenow-cmdb-instance-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/servicenow-import-set-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/servicenow-import-set-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/servicenow-service-catalog-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/servicenow-service-catalog-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/servicenow-table-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/servicenow-table-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### ServiceNow Change Management API

The ServiceNow Change Management API provides REST endpoints for creating, retrieving, updating, and managing change requests and their associated tasks and approvals. It supports the full change lifecycle including normal, standard, and emergency change types.

- **Human URL:** [https://www.servicenow.com/docs/bundle/yokohama-api-reference/page/integrate/inbound-rest/concept/change-management-api.html](https://www.servicenow.com/docs/bundle/yokohama-api-reference/page/integrate/inbound-rest/concept/change-management-api.html)
- **Base URL:** `https://{instance}.service-now.com/api/sn_chg_rest/v1/change`

#### Tags

- Change Management
- IT Operations
- ITSM
- Workflows

#### Properties

- [Documentation](https://www.servicenow.com/docs/bundle/yokohama-api-reference/page/integrate/inbound-rest/concept/change-management-api.html)
- [API Reference](https://www.servicenow.com/docs/bundle/xanadu-api-reference/page/integrate/inbound-rest/concept/change-management-api.html)
- [OpenAPI](openapi/servicenow-change-management-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/servicenow-change-management-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/servicenow-change-management-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### ServiceNow Knowledge Management API

The ServiceNow Knowledge Management REST API provides endpoints for searching and retrieving knowledge articles, including most-viewed and featured articles. It supports public and authenticated access to knowledge bases and requires the Knowledge API (sn_km_api) plugin to be activated.

- **Human URL:** [https://www.servicenow.com/docs/bundle/yokohama-api-reference/page/integrate/inbound-rest/concept/knowledge-api.html](https://www.servicenow.com/docs/bundle/yokohama-api-reference/page/integrate/inbound-rest/concept/knowledge-api.html)
- **Base URL:** `https://{instance}.service-now.com/api/sn_km_api/knowledge`

#### Tags

- Articles
- Knowledge Base
- Knowledge Management
- Self-Service

#### Properties

- [Documentation](https://www.servicenow.com/docs/bundle/yokohama-api-reference/page/integrate/inbound-rest/concept/knowledge-api.html)
- [API Reference](https://www.servicenow.com/docs/bundle/xanadu-api-reference/page/integrate/inbound-rest/concept/knowledge-api.html)
- [Postman Collection](collections/servicenow-aggregate-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/servicenow-aggregate-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/servicenow-attachment-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/servicenow-attachment-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/servicenow-change-management-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/servicenow-change-management-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/servicenow-cmdb-instance-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/servicenow-cmdb-instance-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/servicenow-import-set-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/servicenow-import-set-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/servicenow-service-catalog-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/servicenow-service-catalog-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/servicenow-table-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/servicenow-table-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### ServiceNow Service Catalog API

The ServiceNow Service Catalog API provides REST endpoints for browsing catalog categories and items, retrieving catalog item details and variables, and submitting catalog requests. It enables external applications and portals to integrate with ServiceNow's self-service request capabilities.

- **Human URL:** [https://www.servicenow.com/docs/bundle/yokohama-api-reference/page/integrate/inbound-rest/concept/c_ServiceCatalogAPI.html](https://www.servicenow.com/docs/bundle/yokohama-api-reference/page/integrate/inbound-rest/concept/c_ServiceCatalogAPI.html)
- **Base URL:** `https://{instance}.service-now.com/api/sn_sc/servicecatalog`

#### Tags

- ITSM
- Requests
- Self-Service
- Service Catalog

#### Properties

- [Documentation](https://www.servicenow.com/docs/bundle/yokohama-api-reference/page/integrate/inbound-rest/concept/c_ServiceCatalogAPI.html)
- [API Reference](https://www.servicenow.com/docs/bundle/xanadu-api-reference/page/integrate/inbound-rest/concept/c_ServiceCatalogAPI.html)
- [OpenAPI](openapi/servicenow-service-catalog-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/servicenow-service-catalog-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/servicenow-service-catalog-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### ServiceNow CMDB Instance API

The ServiceNow CMDB Instance API provides REST endpoints for retrieving configuration item (CI) records from the Configuration Management Database by class name and sys_id. It is used to query and access infrastructure and application CI data stored in ServiceNow's CMDB.

- **Human URL:** [https://www.servicenow.com/docs/bundle/yokohama-api-reference/page/integrate/inbound-rest/concept/cmdb-instance-api.html](https://www.servicenow.com/docs/bundle/yokohama-api-reference/page/integrate/inbound-rest/concept/cmdb-instance-api.html)
- **Base URL:** `https://{instance}.service-now.com/api/now/cmdb/instance`

#### Tags

- Assets
- CMDB
- Configuration Management
- IT Operations

#### Properties

- [Documentation](https://www.servicenow.com/docs/bundle/yokohama-api-reference/page/integrate/inbound-rest/concept/cmdb-instance-api.html)
- [API Reference](https://www.servicenow.com/docs/bundle/xanadu-api-reference/page/integrate/inbound-rest/concept/cmdb-instance-api.html)
- [OpenAPI](openapi/servicenow-cmdb-instance-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/servicenow-cmdb-instance-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/servicenow-cmdb-instance-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### ServiceNow Identification and Reconciliation API

The ServiceNow Identification and Reconciliation API provides a REST endpoint for creating or updating configuration items (CIs) in the CMDB using the platform's identification and reconciliation engine. It ensures that CI data from external discovery sources is correctly identified, deduplicated, and reconciled against existing CMDB records.

- **Human URL:** [https://www.servicenow.com/docs/bundle/yokohama-api-reference/page/integrate/inbound-rest/concept/c_IdentifyReconcileAPI.html](https://www.servicenow.com/docs/bundle/yokohama-api-reference/page/integrate/inbound-rest/concept/c_IdentifyReconcileAPI.html)
- **Base URL:** `https://{instance}.service-now.com/api/now/identifyreconcile`

#### Tags

- CMDB
- Configuration Management
- Discovery
- Reconciliation

#### Properties

- [Documentation](https://www.servicenow.com/docs/bundle/yokohama-api-reference/page/integrate/inbound-rest/concept/c_IdentifyReconcileAPI.html)
- [API Reference](https://www.servicenow.com/docs/bundle/xanadu-api-reference/page/integrate/inbound-rest/concept/c_IdentifyReconcileAPI.html)
- [Postman Collection](collections/servicenow-aggregate-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/servicenow-aggregate-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/servicenow-attachment-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/servicenow-attachment-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/servicenow-change-management-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/servicenow-change-management-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/servicenow-cmdb-instance-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/servicenow-cmdb-instance-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/servicenow-import-set-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/servicenow-import-set-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/servicenow-service-catalog-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/servicenow-service-catalog-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/servicenow-table-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/servicenow-table-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### ServiceNow Performance Analytics API

The ServiceNow Performance Analytics API provides REST endpoints for retrieving performance analytics data including scores, breakdowns, and widget data. It enables integration with external dashboards and reporting tools to access historical and real-time KPI data collected by the Now Platform.

- **Human URL:** [https://www.servicenow.com/docs/bundle/yokohama-api-reference/page/integrate/inbound-rest/concept/c_PerformanceAnalyticsAPI.html](https://www.servicenow.com/docs/bundle/yokohama-api-reference/page/integrate/inbound-rest/concept/c_PerformanceAnalyticsAPI.html)
- **Base URL:** `https://{instance}.service-now.com/api/now/pa`

#### Tags

- Analytics
- Dashboards
- Performance
- Reporting

#### Properties

- [Documentation](https://www.servicenow.com/docs/bundle/yokohama-api-reference/page/integrate/inbound-rest/concept/c_PerformanceAnalyticsAPI.html)
- [Postman Collection](collections/servicenow-aggregate-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/servicenow-aggregate-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/servicenow-attachment-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/servicenow-attachment-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/servicenow-change-management-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/servicenow-change-management-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/servicenow-cmdb-instance-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/servicenow-cmdb-instance-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/servicenow-import-set-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/servicenow-import-set-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/servicenow-service-catalog-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/servicenow-service-catalog-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/servicenow-table-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/servicenow-table-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### ServiceNow Contact API

The ServiceNow Contact API provides endpoints for retrieving and updating Customer Service Management (CSM) contact records. It also supports generating new social media profile records when creating a contact, and requires the Customer Service plugin (com.sn_customerservice).

- **Human URL:** [https://www.servicenow.com/docs/r/xanadu/api-reference/rest-apis/contact-api.html](https://www.servicenow.com/docs/r/xanadu/api-reference/rest-apis/contact-api.html)
- **Base URL:** `https://{instance}.service-now.com/api/now/contact`

#### Tags

- Contacts
- CSM
- Customer Service
- Records

#### Properties

- [Documentation](https://www.servicenow.com/docs/r/xanadu/api-reference/rest-apis/contact-api.html)
- [OpenAPI](openapi/contact-api-openapi.yaml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)

### ServiceNow Trouble Ticket Open API

The ServiceNow Trouble Ticket Open API provides endpoints to create, update, and retrieve data from Case, Incident, and Service Problem Case tables. It is a ServiceNow implementation of the TM Forum Trouble Ticket Management API REST specification for managing ticket information between external ticketing systems and the ServiceNow AI Platform.

- **Human URL:** [https://www.servicenow.com/docs/bundle/yokohama-api-reference/page/integrate/inbound-rest/concept/c_RESTAPI.html](https://www.servicenow.com/docs/bundle/yokohama-api-reference/page/integrate/inbound-rest/concept/c_RESTAPI.html)
- **Base URL:** `https://{instance}.service-now.com/api/now/troubleticket`

#### Tags

- Customer Service
- Incidents
- TM Forum
- Trouble Tickets

#### Properties

- [Documentation](https://www.servicenow.com/docs/bundle/yokohama-api-reference/page/integrate/inbound-rest/concept/c_RESTAPI.html)
- [OpenAPI](openapi/trouble-ticket-openapi.yaml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)

### ServiceNow Scripted REST APIs

ServiceNow Scripted REST APIs allow developers to create custom REST API endpoints on the Now Platform using server-side JavaScript. They support custom request processing logic, authentication, and response handling, enabling organizations to expose business-specific functionality as web services to external consumers.

- **Human URL:** [https://www.servicenow.com/docs/bundle/yokohama-api-reference/page/integrate/custom-web-services/concept/c_CustomWebServices.html](https://www.servicenow.com/docs/bundle/yokohama-api-reference/page/integrate/custom-web-services/concept/c_CustomWebServices.html)
- **Base URL:** `https://{instance}.service-now.com/api/{namespace}/{api_id}`

#### Tags

- Custom APIs
- Integration
- Platform
- Scripting

#### Properties

- [Documentation](https://www.servicenow.com/docs/bundle/yokohama-api-reference/page/integrate/custom-web-services/concept/c_CustomWebServices.html)
- [Postman Collection](collections/servicenow-aggregate-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/servicenow-aggregate-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/servicenow-attachment-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/servicenow-attachment-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/servicenow-change-management-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/servicenow-change-management-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/servicenow-cmdb-instance-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/servicenow-cmdb-instance-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/servicenow-import-set-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/servicenow-import-set-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/servicenow-service-catalog-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/servicenow-service-catalog-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/servicenow-table-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/servicenow-table-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### ServiceNow GraphQL API

The ServiceNow GraphQL API framework allows developers to create custom GraphQL API schemas on the Now Platform for querying record data from components or external systems. It supports defining resolvers with server-side scripts and enables flexible, client-driven queries as an alternative to REST-based integration.

- **Human URL:** [https://docs.servicenow.com/bundle/tokyo-application-development/page/integrate/graphql/concept/scripted-graph-ql.html](https://docs.servicenow.com/bundle/tokyo-application-development/page/integrate/graphql/concept/scripted-graph-ql.html)
- **Base URL:** `https://{instance}.service-now.com/api/now/graphql`

#### Tags

- Custom APIs
- GraphQL
- Integration
- Platform

#### Properties

- [Documentation](https://docs.servicenow.com/bundle/tokyo-application-development/page/integrate/graphql/concept/scripted-graph-ql.html)
- [Getting Started](https://www.servicenow.com/community/developer-articles/getting-started-graphql-api-framework/ta-p/2312207)
- [Postman Collection](collections/servicenow-aggregate-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/servicenow-aggregate-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/servicenow-attachment-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/servicenow-attachment-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/servicenow-change-management-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/servicenow-change-management-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/servicenow-cmdb-instance-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/servicenow-cmdb-instance-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/servicenow-import-set-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/servicenow-import-set-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/servicenow-service-catalog-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/servicenow-service-catalog-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/servicenow-table-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/servicenow-table-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### ServiceNow Application Service API

The ServiceNow Application Service API provides REST endpoints to create, modify, and update application services in the CMDB. It requires users to have the app_service_admin role and enables programmatic management of business application service mappings and their associated configuration items.

- **Human URL:** [https://www.servicenow.com/docs/bundle/yokohama-api-reference/page/integrate/inbound-rest/concept/application-service-api.html](https://www.servicenow.com/docs/bundle/yokohama-api-reference/page/integrate/inbound-rest/concept/application-service-api.html)
- **Base URL:** `https://{instance}.service-now.com/api/now/cmdb/app_service`

#### Tags

- Application Services
- CMDB
- IT Operations
- Service Mapping

#### Properties

- [Documentation](https://www.servicenow.com/docs/bundle/yokohama-api-reference/page/integrate/inbound-rest/concept/application-service-api.html)
- [Postman Collection](collections/servicenow-aggregate-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/servicenow-aggregate-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/servicenow-attachment-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/servicenow-attachment-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/servicenow-change-management-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/servicenow-change-management-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/servicenow-cmdb-instance-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/servicenow-cmdb-instance-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/servicenow-import-set-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/servicenow-import-set-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/servicenow-service-catalog-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/servicenow-service-catalog-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/servicenow-table-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/servicenow-table-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### ServiceNow Case API

The ServiceNow Case API provides REST endpoints for creating, retrieving, and updating Customer Service Management (CSM) case records. It supports the full case lifecycle including case creation, assignment, escalation, and resolution within the CSM application.

- **Human URL:** [https://www.servicenow.com/docs/bundle/yokohama-api-reference/page/integrate/inbound-rest/concept/case-api.html](https://www.servicenow.com/docs/bundle/yokohama-api-reference/page/integrate/inbound-rest/concept/case-api.html)
- **Base URL:** `https://{instance}.service-now.com/api/sn_customerservice/case`

#### Tags

- Cases
- CSM
- Customer Service
- Support

#### Properties

- [Documentation](https://www.servicenow.com/docs/bundle/yokohama-api-reference/page/integrate/inbound-rest/concept/case-api.html)
- [Postman Collection](collections/servicenow-aggregate-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/servicenow-aggregate-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/servicenow-attachment-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/servicenow-attachment-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/servicenow-change-management-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/servicenow-change-management-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/servicenow-cmdb-instance-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/servicenow-cmdb-instance-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/servicenow-import-set-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/servicenow-import-set-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/servicenow-service-catalog-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/servicenow-service-catalog-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/servicenow-table-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/servicenow-table-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### ServiceNow Account API

The ServiceNow Account API provides REST endpoints for retrieving and managing customer account records within Customer Service Management (CSM). It enables external systems to query and update account information used for B2B customer relationship tracking.

- **Human URL:** [https://www.servicenow.com/docs/bundle/yokohama-api-reference/page/integrate/inbound-rest/concept/account-api.html](https://www.servicenow.com/docs/bundle/yokohama-api-reference/page/integrate/inbound-rest/concept/account-api.html)
- **Base URL:** `https://{instance}.service-now.com/api/now/account`

#### Tags

- Accounts
- CSM
- Customer Service
- Records

#### Properties

- [Documentation](https://www.servicenow.com/docs/bundle/yokohama-api-reference/page/integrate/inbound-rest/concept/account-api.html)
- [Postman Collection](collections/servicenow-aggregate-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/servicenow-aggregate-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/servicenow-attachment-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/servicenow-attachment-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/servicenow-change-management-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/servicenow-change-management-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/servicenow-cmdb-instance-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/servicenow-cmdb-instance-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/servicenow-import-set-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/servicenow-import-set-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/servicenow-service-catalog-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/servicenow-service-catalog-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/servicenow-table-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/servicenow-table-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### ServiceNow Consumer API

The ServiceNow Consumer API provides REST endpoints for retrieving and updating CSM consumer records. It supports managing individual consumer profiles and can generate new social media profile records when creating a consumer entry within the Customer Service Management application.

- **Human URL:** [https://www.servicenow.com/docs/bundle/yokohama-api-reference/page/integrate/inbound-rest/concept/c_RESTAPI.html](https://www.servicenow.com/docs/bundle/yokohama-api-reference/page/integrate/inbound-rest/concept/c_RESTAPI.html)
- **Base URL:** `https://{instance}.service-now.com/api/now/consumer`

#### Tags

- Consumers
- CSM
- Customer Service
- Self-Service

#### Properties

- [Documentation](https://www.servicenow.com/docs/bundle/yokohama-api-reference/page/integrate/inbound-rest/concept/c_RESTAPI.html)
- [Postman Collection](collections/servicenow-aggregate-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/servicenow-aggregate-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/servicenow-attachment-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/servicenow-attachment-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/servicenow-change-management-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/servicenow-change-management-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/servicenow-cmdb-instance-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/servicenow-cmdb-instance-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/servicenow-import-set-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/servicenow-import-set-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/servicenow-service-catalog-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/servicenow-service-catalog-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/servicenow-table-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/servicenow-table-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### ServiceNow CSM Attachment API

The ServiceNow CSM Attachment API provides REST endpoints for uploading and managing file attachments on Customer Service Management records such as cases and interactions. It extends the base Attachment API with CSM-specific functionality and access controls.

- **Human URL:** [https://www.servicenow.com/docs/bundle/yokohama-api-reference/page/integrate/inbound-rest/concept/attachment_csm-api.html](https://www.servicenow.com/docs/bundle/yokohama-api-reference/page/integrate/inbound-rest/concept/attachment_csm-api.html)
- **Base URL:** `https://{instance}.service-now.com/api/sn_customerservice/attachment`

#### Tags

- Attachments
- CSM
- Customer Service
- Files

#### Properties

- [Documentation](https://www.servicenow.com/docs/bundle/yokohama-api-reference/page/integrate/inbound-rest/concept/attachment_csm-api.html)
- [Postman Collection](collections/servicenow-aggregate-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/servicenow-aggregate-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/servicenow-attachment-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/servicenow-attachment-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/servicenow-change-management-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/servicenow-change-management-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/servicenow-cmdb-instance-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/servicenow-cmdb-instance-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/servicenow-import-set-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/servicenow-import-set-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/servicenow-service-catalog-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/servicenow-service-catalog-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/servicenow-table-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/servicenow-table-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### ServiceNow Email API

The ServiceNow Email API provides REST endpoints for sending email messages from the Now Platform. It allows external systems and integrations to trigger email notifications and communications through ServiceNow's email infrastructure.

- **Human URL:** [https://www.servicenow.com/docs/bundle/yokohama-api-reference/page/integrate/inbound-rest/concept/email-api.html](https://www.servicenow.com/docs/bundle/yokohama-api-reference/page/integrate/inbound-rest/concept/email-api.html)
- **Base URL:** `https://{instance}.service-now.com/api/now/email`

#### Tags

- Email
- Messaging
- Notifications
- Platform

#### Properties

- [Documentation](https://www.servicenow.com/docs/bundle/yokohama-api-reference/page/integrate/inbound-rest/concept/email-api.html)
- [Postman Collection](collections/servicenow-aggregate-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/servicenow-aggregate-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/servicenow-attachment-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/servicenow-attachment-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/servicenow-change-management-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/servicenow-change-management-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/servicenow-cmdb-instance-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/servicenow-cmdb-instance-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/servicenow-import-set-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/servicenow-import-set-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/servicenow-service-catalog-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/servicenow-service-catalog-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/servicenow-table-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/servicenow-table-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### ServiceNow CI/CD API

The ServiceNow CI/CD API provides REST endpoints for integrating ServiceNow application development with continuous integration and continuous delivery pipelines. It supports operations such as applying changes, running ATF test suites, activating plugins, and managing application installations from external CI/CD tools.

- **Human URL:** [https://www.servicenow.com/docs/bundle/yokohama-api-reference/page/integrate/inbound-rest/concept/cicd-api.html](https://www.servicenow.com/docs/bundle/yokohama-api-reference/page/integrate/inbound-rest/concept/cicd-api.html)
- **Base URL:** `https://{instance}.service-now.com/api/sn_cicd`

#### Tags

- Automation
- CI/CD
- Deployment
- DevOps

#### Properties

- [Documentation](https://www.servicenow.com/docs/bundle/yokohama-api-reference/page/integrate/inbound-rest/concept/cicd-api.html)
- [Postman Collection](collections/servicenow-aggregate-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/servicenow-aggregate-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/servicenow-attachment-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/servicenow-attachment-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/servicenow-change-management-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/servicenow-change-management-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/servicenow-cmdb-instance-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/servicenow-cmdb-instance-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/servicenow-import-set-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/servicenow-import-set-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/servicenow-service-catalog-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/servicenow-service-catalog-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/servicenow-table-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/servicenow-table-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### ServiceNow CI/CD Update Set API

The ServiceNow CI/CD Update Set API provides REST methods to create, retrieve, preview, commit, and back out update sets. It enables automated deployment workflows by allowing CI/CD pipelines to manage update set transfers between ServiceNow instances.

- **Human URL:** [https://www.servicenow.com/docs/bundle/yokohama-api-reference/page/integrate/inbound-rest/concept/cicd-update-set-api.html](https://www.servicenow.com/docs/bundle/yokohama-api-reference/page/integrate/inbound-rest/concept/cicd-update-set-api.html)
- **Base URL:** `https://{instance}.service-now.com/api/sn_cicd/update_set`

#### Tags

- CI/CD
- Deployment
- DevOps
- Update Sets

#### Properties

- [Documentation](https://www.servicenow.com/docs/bundle/yokohama-api-reference/page/integrate/inbound-rest/concept/cicd-update-set-api.html)
- [Postman Collection](collections/servicenow-aggregate-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/servicenow-aggregate-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/servicenow-attachment-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/servicenow-attachment-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/servicenow-change-management-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/servicenow-change-management-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/servicenow-cmdb-instance-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/servicenow-cmdb-instance-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/servicenow-import-set-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/servicenow-import-set-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/servicenow-service-catalog-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/servicenow-service-catalog-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/servicenow-table-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/servicenow-table-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### ServiceNow DevOps API

The ServiceNow DevOps API provides REST endpoints for integrating external DevOps toolchains with ServiceNow's DevOps Change Velocity product. It enables automated change request creation, artifact and package tracking, and pipeline orchestration from tools such as Jenkins, Azure DevOps, and GitLab.

- **Human URL:** [https://www.servicenow.com/docs/bundle/yokohama-api-reference/page/integrate/inbound-rest/concept/devops-api.html](https://www.servicenow.com/docs/bundle/yokohama-api-reference/page/integrate/inbound-rest/concept/devops-api.html)
- **Base URL:** `https://{instance}.service-now.com/api/sn_devops`

#### Tags

- Change Velocity
- CI/CD
- DevOps
- Pipelines

#### Properties

- [Documentation](https://www.servicenow.com/docs/bundle/yokohama-api-reference/page/integrate/inbound-rest/concept/devops-api.html)
- [Postman Collection](collections/servicenow-aggregate-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/servicenow-aggregate-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/servicenow-attachment-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/servicenow-attachment-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/servicenow-change-management-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/servicenow-change-management-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/servicenow-cmdb-instance-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/servicenow-cmdb-instance-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/servicenow-import-set-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/servicenow-import-set-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/servicenow-service-catalog-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/servicenow-service-catalog-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/servicenow-table-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/servicenow-table-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### ServiceNow DevOps Config API

The ServiceNow DevOps Config API provides REST endpoints for managing DevOps configuration data and policies. It supports configuration validation and compliance checks as part of the DevOps change acceleration workflow.

- **Human URL:** [https://www.servicenow.com/docs/bundle/yokohama-api-reference/page/integrate/inbound-rest/concept/devops-config-api.html](https://www.servicenow.com/docs/bundle/yokohama-api-reference/page/integrate/inbound-rest/concept/devops-config-api.html)
- **Base URL:** `https://{instance}.service-now.com/api/sn_devops_config`

#### Tags

- Automation
- Change Management
- Configuration
- DevOps

#### Properties

- [Documentation](https://www.servicenow.com/docs/bundle/yokohama-api-reference/page/integrate/inbound-rest/concept/devops-config-api.html)
- [Postman Collection](collections/servicenow-aggregate-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/servicenow-aggregate-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/servicenow-attachment-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/servicenow-attachment-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/servicenow-change-management-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/servicenow-change-management-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/servicenow-cmdb-instance-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/servicenow-cmdb-instance-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/servicenow-import-set-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/servicenow-import-set-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/servicenow-service-catalog-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/servicenow-service-catalog-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/servicenow-table-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/servicenow-table-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### ServiceNow CMDB Meta API

The ServiceNow CMDB Meta API provides REST endpoints for retrieving metadata about CMDB classes, including their attributes, relationships, and hierarchy. It enables developers to programmatically discover the CMDB data model and schema for building integrations and reporting tools.

- **Human URL:** [https://www.servicenow.com/docs/bundle/yokohama-api-reference/page/integrate/inbound-rest/concept/cmdb-meta-api.html](https://www.servicenow.com/docs/bundle/yokohama-api-reference/page/integrate/inbound-rest/concept/cmdb-meta-api.html)
- **Base URL:** `https://{instance}.service-now.com/api/now/cmdb/meta`

#### Tags

- CMDB
- Configuration Management
- Metadata
- Schema

#### Properties

- [Documentation](https://www.servicenow.com/docs/bundle/yokohama-api-reference/page/integrate/inbound-rest/concept/cmdb-meta-api.html)
- [Postman Collection](collections/servicenow-aggregate-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/servicenow-aggregate-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/servicenow-attachment-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/servicenow-attachment-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/servicenow-change-management-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/servicenow-change-management-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/servicenow-cmdb-instance-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/servicenow-cmdb-instance-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/servicenow-import-set-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/servicenow-import-set-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/servicenow-service-catalog-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/servicenow-service-catalog-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/servicenow-table-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/servicenow-table-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### ServiceNow CMDB Data Ingestion API

The ServiceNow CMDB Data Ingestion API provides REST endpoints for bulk ingesting configuration item data into the CMDB from external data sources. It supports high-volume CI data loading with built-in identification and reconciliation processing.

- **Human URL:** [https://www.servicenow.com/docs/bundle/yokohama-api-reference/page/integrate/inbound-rest/concept/cmdb-ingest-api.html](https://www.servicenow.com/docs/bundle/yokohama-api-reference/page/integrate/inbound-rest/concept/cmdb-ingest-api.html)
- **Base URL:** `https://{instance}.service-now.com/api/now/cmdb/ingest`

#### Tags

- CMDB
- Configuration Management
- Data Ingestion
- Integration

#### Properties

- [Documentation](https://www.servicenow.com/docs/bundle/yokohama-api-reference/page/integrate/inbound-rest/concept/cmdb-ingest-api.html)
- [Postman Collection](collections/servicenow-aggregate-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/servicenow-aggregate-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/servicenow-attachment-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/servicenow-attachment-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/servicenow-change-management-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/servicenow-change-management-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/servicenow-cmdb-instance-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/servicenow-cmdb-instance-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/servicenow-import-set-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/servicenow-import-set-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/servicenow-service-catalog-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/servicenow-service-catalog-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/servicenow-table-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/servicenow-table-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### ServiceNow MetricBase Time Series API

The ServiceNow MetricBase Time Series API (formerly Clotho) provides REST endpoints for storing, retrieving, and transforming time series metric data on the Now Platform. It is used by IT Operations Management to ingest and query monitoring data such as CPU usage, memory utilization, and custom metrics.

- **Human URL:** [https://www.servicenow.com/docs/bundle/yokohama-api-reference/page/integrate/inbound-rest/concept/Clotho-Time-Series-API.html](https://www.servicenow.com/docs/bundle/yokohama-api-reference/page/integrate/inbound-rest/concept/Clotho-Time-Series-API.html)
- **Base URL:** `https://{instance}.service-now.com/api/now/clotho`

#### Tags

- ITOM
- Metrics
- Monitoring
- Time Series

#### Properties

- [Documentation](https://www.servicenow.com/docs/bundle/yokohama-api-reference/page/integrate/inbound-rest/concept/Clotho-Time-Series-API.html)
- [Postman Collection](collections/servicenow-aggregate-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/servicenow-aggregate-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/servicenow-attachment-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/servicenow-attachment-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/servicenow-change-management-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/servicenow-change-management-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/servicenow-cmdb-instance-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/servicenow-cmdb-instance-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/servicenow-import-set-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/servicenow-import-set-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/servicenow-service-catalog-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/servicenow-service-catalog-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/servicenow-table-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/servicenow-table-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### ServiceNow Interaction Management API

The ServiceNow Interaction Management API provides REST endpoints for creating and managing customer interactions across multiple channels. It supports omnichannel routing and enables external contact center systems to create and update interaction records in ServiceNow Agent Workspace.

- **Human URL:** [https://www.servicenow.com/docs/bundle/yokohama-api-reference/page/integrate/inbound-rest/concept/interaction-management-api.html](https://www.servicenow.com/docs/bundle/yokohama-api-reference/page/integrate/inbound-rest/concept/interaction-management-api.html)
- **Base URL:** `https://{instance}.service-now.com/api/interaction`

#### Tags

- Agent Workspace
- Customer Service
- Interactions
- Omnichannel

#### Properties

- [Documentation](https://www.servicenow.com/docs/bundle/yokohama-api-reference/page/integrate/inbound-rest/concept/interaction-management-api.html)
- [Postman Collection](collections/servicenow-aggregate-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/servicenow-aggregate-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/servicenow-attachment-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/servicenow-attachment-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/servicenow-change-management-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/servicenow-change-management-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/servicenow-cmdb-instance-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/servicenow-cmdb-instance-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/servicenow-import-set-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/servicenow-import-set-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/servicenow-service-catalog-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/servicenow-service-catalog-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/servicenow-table-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/servicenow-table-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### ServiceNow Voice Interaction Resource API

The ServiceNow Voice Interaction Resource API provides REST endpoints for integrating telephony and voice systems with ServiceNow. It enables Contact Center as a Service (CCaaS) providers to manage voice interactions and route calls to agents within Agent Workspace.

- **Human URL:** [https://www.servicenow.com/docs/bundle/yokohama-api-reference/page/integrate/inbound-rest/concept/voice-interaction-resource-api.html](https://www.servicenow.com/docs/bundle/yokohama-api-reference/page/integrate/inbound-rest/concept/voice-interaction-resource-api.html)
- **Base URL:** `https://{instance}.service-now.com/api/now/voice`

#### Tags

- Contact Center
- Interactions
- Telephony
- Voice

#### Properties

- [Documentation](https://www.servicenow.com/docs/bundle/yokohama-api-reference/page/integrate/inbound-rest/concept/voice-interaction-resource-api.html)
- [Postman Collection](collections/servicenow-aggregate-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/servicenow-aggregate-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/servicenow-attachment-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/servicenow-attachment-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/servicenow-change-management-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/servicenow-change-management-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/servicenow-cmdb-instance-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/servicenow-cmdb-instance-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/servicenow-import-set-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/servicenow-import-set-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/servicenow-service-catalog-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/servicenow-service-catalog-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/servicenow-table-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/servicenow-table-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### ServiceNow User Role Inheritance API

The ServiceNow User Role Inheritance API provides REST endpoints for querying the role inheritance hierarchy for users and groups. It enables external systems to determine effective roles and permissions assigned through direct assignment or group membership inheritance.

- **Human URL:** [https://www.servicenow.com/docs/bundle/yokohama-api-reference/page/integrate/inbound-rest/concept/user-role-inheritance-api.html](https://www.servicenow.com/docs/bundle/yokohama-api-reference/page/integrate/inbound-rest/concept/user-role-inheritance-api.html)
- **Base URL:** `https://{instance}.service-now.com/api/now/user_role_inheritance`

#### Tags

- Access Control
- Roles
- Security
- Users

#### Properties

- [Documentation](https://www.servicenow.com/docs/bundle/yokohama-api-reference/page/integrate/inbound-rest/concept/user-role-inheritance-api.html)
- [Postman Collection](collections/servicenow-aggregate-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/servicenow-aggregate-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/servicenow-attachment-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/servicenow-attachment-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/servicenow-change-management-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/servicenow-change-management-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/servicenow-cmdb-instance-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/servicenow-cmdb-instance-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/servicenow-import-set-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/servicenow-import-set-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/servicenow-service-catalog-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/servicenow-service-catalog-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/servicenow-table-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/servicenow-table-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### ServiceNow HR API

The ServiceNow HR API provides REST endpoints for managing Human Resources Service Delivery (HRSD) data including employee cases, lifecycle events, and HR service requests. It enables integration with external HR systems such as Workday and SuccessFactors for employee data synchronization.

- **Human URL:** [https://www.servicenow.com/docs/bundle/yokohama-api-reference/page/integrate/inbound-rest/concept/hr-core-api.html](https://www.servicenow.com/docs/bundle/yokohama-api-reference/page/integrate/inbound-rest/concept/hr-core-api.html)
- **Base URL:** `https://{instance}.service-now.com/api/sn_hr_core`

#### Tags

- Employee Services
- HR Service Delivery
- HRSD
- Human Resources

#### Properties

- [Documentation](https://www.servicenow.com/docs/bundle/yokohama-api-reference/page/integrate/inbound-rest/concept/hr-core-api.html)
- [Postman Collection](collections/servicenow-aggregate-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/servicenow-aggregate-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/servicenow-attachment-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/servicenow-attachment-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/servicenow-change-management-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/servicenow-change-management-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/servicenow-cmdb-instance-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/servicenow-cmdb-instance-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/servicenow-import-set-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/servicenow-import-set-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/servicenow-service-catalog-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/servicenow-service-catalog-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/servicenow-table-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/servicenow-table-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### ServiceNow Event Management Topic Open API

The ServiceNow Event Management Topic Open API provides REST endpoints for managing event topics and subscriptions within IT Operations Management. It enables external monitoring tools to publish events and subscribe to event notifications using a topic-based messaging pattern.

- **Human URL:** [https://www.servicenow.com/docs/bundle/yokohama-api-reference/page/integrate/inbound-rest/concept/event_management_topic-api.html](https://www.servicenow.com/docs/bundle/yokohama-api-reference/page/integrate/inbound-rest/concept/event_management_topic-api.html)
- **Base URL:** `https://{instance}.service-now.com/api/em/topic`

#### Tags

- Alerts
- Event Management
- ITOM
- Monitoring

#### Properties

- [Documentation](https://www.servicenow.com/docs/bundle/yokohama-api-reference/page/integrate/inbound-rest/concept/event_management_topic-api.html)
- [AsyncAPI](asyncapi/servicenow-events-asyncapi.yml) — [AsyncAPI Specification](https://www.asyncapi.com/docs/reference/specification/latest)
- [Postman Collection](collections/servicenow-aggregate-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/servicenow-aggregate-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/servicenow-attachment-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/servicenow-attachment-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/servicenow-change-management-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/servicenow-change-management-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/servicenow-cmdb-instance-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/servicenow-cmdb-instance-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/servicenow-import-set-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/servicenow-import-set-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/servicenow-service-catalog-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/servicenow-service-catalog-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/servicenow-table-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/servicenow-table-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### ServiceNow Predictive Intelligence API

The ServiceNow Predictive Intelligence API provides REST endpoints for accessing machine learning prediction models on the Now Platform. It supports classification, similarity matching, and regression predictions to automate categorization, assignment, and prioritization of records such as incidents and cases.

- **Human URL:** [https://www.servicenow.com/docs/bundle/yokohama-api-reference/page/integrate/inbound-rest/concept/agent-intelligence-api.html](https://www.servicenow.com/docs/bundle/yokohama-api-reference/page/integrate/inbound-rest/concept/agent-intelligence-api.html)
- **Base URL:** `https://{instance}.service-now.com/api/now/agent_intelligence`

#### Tags

- AI
- Classification
- Machine Learning
- Predictions

#### Properties

- [Documentation](https://www.servicenow.com/docs/bundle/yokohama-api-reference/page/integrate/inbound-rest/concept/agent-intelligence-api.html)
- [Postman Collection](collections/servicenow-aggregate-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/servicenow-aggregate-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/servicenow-attachment-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/servicenow-attachment-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/servicenow-change-management-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/servicenow-change-management-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/servicenow-cmdb-instance-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/servicenow-cmdb-instance-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/servicenow-import-set-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/servicenow-import-set-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/servicenow-service-catalog-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/servicenow-service-catalog-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/servicenow-table-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/servicenow-table-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### ServiceNow AWA Agent API

The ServiceNow AWA Agent API provides REST endpoints for managing agent availability, presence, and capacity within Advanced Work Assignment (AWA). It enables external systems to query and update agent status for work routing and workforce management purposes.

- **Human URL:** [https://www.servicenow.com/docs/bundle/yokohama-api-reference/page/integrate/inbound-rest/concept/agent-api.html](https://www.servicenow.com/docs/bundle/yokohama-api-reference/page/integrate/inbound-rest/concept/agent-api.html)
- **Base URL:** `https://{instance}.service-now.com/api/now/awa/agent`

#### Tags

- Agent Workspace
- Queues
- Routing
- Workforce Management

#### Properties

- [Documentation](https://www.servicenow.com/docs/bundle/yokohama-api-reference/page/integrate/inbound-rest/concept/agent-api.html)
- [Postman Collection](collections/servicenow-aggregate-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/servicenow-aggregate-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/servicenow-attachment-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/servicenow-attachment-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/servicenow-change-management-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/servicenow-change-management-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/servicenow-cmdb-instance-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/servicenow-cmdb-instance-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/servicenow-import-set-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/servicenow-import-set-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/servicenow-service-catalog-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/servicenow-service-catalog-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/servicenow-table-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/servicenow-table-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### ServiceNow AWA Offer Work API

The ServiceNow AWA Offer Work API provides REST endpoints to assign or transfer work items to agents through the Advanced Work Assignment engine. It enables programmatic distribution of tasks, cases, and interactions to available agents based on capacity and skills.

- **Human URL:** [https://www.servicenow.com/docs/bundle/yokohama-api-reference/page/integrate/inbound-rest/concept/awa-offer-work-api.html](https://www.servicenow.com/docs/bundle/yokohama-api-reference/page/integrate/inbound-rest/concept/awa-offer-work-api.html)
- **Base URL:** `https://{instance}.service-now.com/api/now/awa/offerwork`

#### Tags

- Agent Workspace
- Queues
- Routing
- Work Assignment

#### Properties

- [Documentation](https://www.servicenow.com/docs/bundle/yokohama-api-reference/page/integrate/inbound-rest/concept/awa-offer-work-api.html)
- [Postman Collection](collections/servicenow-aggregate-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/servicenow-aggregate-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/servicenow-attachment-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/servicenow-attachment-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/servicenow-change-management-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/servicenow-change-management-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/servicenow-cmdb-instance-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/servicenow-cmdb-instance-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/servicenow-import-set-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/servicenow-import-set-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/servicenow-service-catalog-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/servicenow-service-catalog-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/servicenow-table-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/servicenow-table-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### ServiceNow Virtual Agent Bot Integration API

The ServiceNow Virtual Agent Bot Integration API provides REST endpoints for integrating external messaging platforms and chatbot frameworks with ServiceNow Virtual Agent. It enables sending and receiving conversational messages to automate employee and customer self-service through AI-powered virtual agents.

- **Human URL:** [https://www.servicenow.com/docs/bundle/yokohama-api-reference/page/integrate/inbound-rest/concept/bot-api.html](https://www.servicenow.com/docs/bundle/yokohama-api-reference/page/integrate/inbound-rest/concept/bot-api.html)
- **Base URL:** `https://{instance}.service-now.com/api/sn_va_as_service`

#### Tags

- Chatbot
- Conversational AI
- Self-Service
- Virtual Agent

#### Properties

- [Documentation](https://www.servicenow.com/docs/bundle/yokohama-api-reference/page/integrate/inbound-rest/concept/bot-api.html)
- [Postman Collection](collections/servicenow-aggregate-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/servicenow-aggregate-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/servicenow-attachment-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/servicenow-attachment-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/servicenow-change-management-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/servicenow-change-management-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/servicenow-cmdb-instance-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/servicenow-cmdb-instance-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/servicenow-import-set-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/servicenow-import-set-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/servicenow-service-catalog-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/servicenow-service-catalog-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/servicenow-table-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/servicenow-table-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### ServiceNow Openframe API

The ServiceNow Openframe API provides REST endpoints that enable Contact Center as a Service (CCaaS) providers to create and update interaction records without using the Operation Handler. It supports third-party telephony integration with ServiceNow Agent Workspace through an open framework.

- **Human URL:** [https://www.servicenow.com/docs/bundle/yokohama-api-reference/page/integrate/inbound-rest/concept/openframe-api.html](https://www.servicenow.com/docs/bundle/yokohama-api-reference/page/integrate/inbound-rest/concept/openframe-api.html)
- **Base URL:** `https://{instance}.service-now.com/api/now/openframe`

#### Tags

- CCaaS
- Contact Center
- Integration
- Telephony

#### Properties

- [Documentation](https://www.servicenow.com/docs/bundle/yokohama-api-reference/page/integrate/inbound-rest/concept/openframe-api.html)
- [Postman Collection](collections/servicenow-aggregate-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/servicenow-aggregate-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/servicenow-attachment-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/servicenow-attachment-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/servicenow-change-management-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/servicenow-change-management-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/servicenow-cmdb-instance-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/servicenow-cmdb-instance-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/servicenow-import-set-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/servicenow-import-set-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/servicenow-service-catalog-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/servicenow-service-catalog-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/servicenow-table-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/servicenow-table-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### ServiceNow AI Assets API

The ServiceNow AI Assets API provides REST endpoints to retrieve, update, and create AI assets such as systems, data sets, prompts, and models. It supports AI governance and inventory management by enabling programmatic tracking of AI components deployed across the organization.

- **Human URL:** [https://www.servicenow.com/docs/bundle/yokohama-api-reference/page/integrate/inbound-rest/concept/ai-assets-api.html](https://www.servicenow.com/docs/bundle/yokohama-api-reference/page/integrate/inbound-rest/concept/ai-assets-api.html)
- **Base URL:** `https://{instance}.service-now.com/api/now/ai/assets`

#### Tags

- AI Governance
- Artificial Intelligence
- Machine Learning
- Platform

#### Properties

- [Documentation](https://www.servicenow.com/docs/bundle/yokohama-api-reference/page/integrate/inbound-rest/concept/ai-assets-api.html)
- [Postman Collection](collections/servicenow-aggregate-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/servicenow-aggregate-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/servicenow-attachment-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/servicenow-attachment-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/servicenow-change-management-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/servicenow-change-management-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/servicenow-cmdb-instance-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/servicenow-cmdb-instance-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/servicenow-import-set-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/servicenow-import-set-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/servicenow-service-catalog-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/servicenow-service-catalog-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/servicenow-table-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/servicenow-table-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### ServiceNow Lead API

The ServiceNow Lead API provides REST endpoints to create, update, and retrieve marketing leads and their associated lead line items. It enables integration with external marketing automation and CRM systems to manage the lead lifecycle within ServiceNow.

- **Human URL:** [https://www.servicenow.com/docs/bundle/yokohama-api-reference/page/integrate/inbound-rest/concept/c_RESTAPI.html](https://www.servicenow.com/docs/bundle/yokohama-api-reference/page/integrate/inbound-rest/concept/c_RESTAPI.html)
- **Base URL:** `https://{instance}.service-now.com/api/sn_lead`

#### Tags

- CRM
- Leads
- Marketing
- Sales

#### Properties

- [Documentation](https://www.servicenow.com/docs/bundle/yokohama-api-reference/page/integrate/inbound-rest/concept/c_RESTAPI.html)
- [Postman Collection](collections/servicenow-aggregate-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/servicenow-aggregate-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/servicenow-attachment-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/servicenow-attachment-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/servicenow-change-management-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/servicenow-change-management-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/servicenow-cmdb-instance-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/servicenow-cmdb-instance-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/servicenow-import-set-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/servicenow-import-set-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/servicenow-service-catalog-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/servicenow-service-catalog-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/servicenow-table-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/servicenow-table-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### ServiceNow Sales Agreement API

The ServiceNow Sales Agreement API provides REST methods for creating new sales agreements and retrieving existing sales agreements by sys_id. It supports contract management workflows within ServiceNow's sales operations capabilities.

- **Human URL:** [https://www.servicenow.com/docs/bundle/yokohama-api-reference/page/integrate/inbound-rest/concept/c_RESTAPI.html](https://www.servicenow.com/docs/bundle/yokohama-api-reference/page/integrate/inbound-rest/concept/c_RESTAPI.html)
- **Base URL:** `https://{instance}.service-now.com/api/sn_sales_agreement`

#### Tags

- Agreements
- Contracts
- CRM
- Sales

#### Properties

- [Documentation](https://www.servicenow.com/docs/bundle/yokohama-api-reference/page/integrate/inbound-rest/concept/c_RESTAPI.html)
- [Postman Collection](collections/servicenow-aggregate-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/servicenow-aggregate-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/servicenow-attachment-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/servicenow-attachment-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/servicenow-change-management-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/servicenow-change-management-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/servicenow-cmdb-instance-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/servicenow-cmdb-instance-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/servicenow-import-set-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/servicenow-import-set-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/servicenow-service-catalog-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/servicenow-service-catalog-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/servicenow-table-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/servicenow-table-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### ServiceNow Agent Client Collector API

The ServiceNow Agent Client Collector (ACC) API provides REST endpoints for managing agent client collectors used in IT Operations Management. It enables programmatic interaction with ACC agents for discovery, monitoring, and data collection from infrastructure components.

- **Human URL:** [https://www.servicenow.com/docs/bundle/yokohama-api-reference/page/integrate/inbound-rest/concept/agnt_clnt_cll-api.html](https://www.servicenow.com/docs/bundle/yokohama-api-reference/page/integrate/inbound-rest/concept/agnt_clnt_cll-api.html)
- **Base URL:** `https://{instance}.service-now.com/api/now/acc`

#### Tags

- Agents
- Discovery
- ITOM
- Monitoring

#### Properties

- [Documentation](https://www.servicenow.com/docs/bundle/yokohama-api-reference/page/integrate/inbound-rest/concept/agnt_clnt_cll-api.html)
- [Postman Collection](collections/servicenow-aggregate-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/servicenow-aggregate-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/servicenow-attachment-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/servicenow-attachment-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/servicenow-change-management-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/servicenow-change-management-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/servicenow-cmdb-instance-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/servicenow-cmdb-instance-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/servicenow-import-set-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/servicenow-import-set-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/servicenow-service-catalog-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/servicenow-service-catalog-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/servicenow-table-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/servicenow-table-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### ServiceNow Agent Mapping API

The ServiceNow Agent Mapping API provides REST endpoints for managing agent mapping configurations. It enables external systems to create and manage mappings between external agent identifiers and ServiceNow agent records for routing and assignment purposes.

- **Human URL:** [https://www.servicenow.com/docs/bundle/yokohama-api-reference/page/integrate/inbound-rest/concept/agent-mapping-api.html](https://www.servicenow.com/docs/bundle/yokohama-api-reference/page/integrate/inbound-rest/concept/agent-mapping-api.html)
- **Base URL:** `https://{instance}.service-now.com/api/now/agent_mapping`

#### Tags

- Agent Workspace
- Integration
- Mapping
- Routing

#### Properties

- [Documentation](https://www.servicenow.com/docs/bundle/yokohama-api-reference/page/integrate/inbound-rest/concept/agent-mapping-api.html)
- [Postman Collection](collections/servicenow-aggregate-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/servicenow-aggregate-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/servicenow-attachment-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/servicenow-attachment-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/servicenow-change-management-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/servicenow-change-management-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/servicenow-cmdb-instance-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/servicenow-cmdb-instance-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/servicenow-import-set-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/servicenow-import-set-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/servicenow-service-catalog-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/servicenow-service-catalog-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/servicenow-table-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/servicenow-table-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### ServiceNow Automation Center API

The ServiceNow Automation Center API provides REST endpoints for managing and executing automation workflows on the Now Platform. It supports programmatic control of automation tasks, enabling external systems to trigger, monitor, and manage automated processes.

- **Human URL:** [https://www.servicenow.com/docs/bundle/yokohama-api-reference/page/integrate/inbound-rest/concept/auto-api.html](https://www.servicenow.com/docs/bundle/yokohama-api-reference/page/integrate/inbound-rest/concept/auto-api.html)
- **Base URL:** `https://{instance}.service-now.com/api/sn_automation_center`

#### Tags

- Automation
- Orchestration
- Platform
- Workflows

#### Properties

- [Documentation](https://www.servicenow.com/docs/bundle/yokohama-api-reference/page/integrate/inbound-rest/concept/auto-api.html)
- [Postman Collection](collections/servicenow-aggregate-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/servicenow-aggregate-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/servicenow-attachment-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/servicenow-attachment-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/servicenow-change-management-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/servicenow-change-management-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/servicenow-cmdb-instance-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/servicenow-cmdb-instance-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/servicenow-import-set-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/servicenow-import-set-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/servicenow-service-catalog-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/servicenow-service-catalog-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/servicenow-table-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/servicenow-table-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### ServiceNow AP Invoice API

The ServiceNow AP Invoice API provides REST endpoints for managing accounts payable invoice records on the Now Platform. It enables external financial systems to create, retrieve, and update invoice data for procurement and payment processing workflows.

- **Human URL:** [https://www.servicenow.com/docs/bundle/yokohama-api-reference/page/integrate/inbound-rest/concept/ap-invoice-api.html](https://www.servicenow.com/docs/bundle/yokohama-api-reference/page/integrate/inbound-rest/concept/ap-invoice-api.html)
- **Base URL:** `https://{instance}.service-now.com/api/now/ap/invoice`

#### Tags

- Accounts Payable
- Finance
- Invoices
- Procurement

#### Properties

- [Documentation](https://www.servicenow.com/docs/bundle/yokohama-api-reference/page/integrate/inbound-rest/concept/ap-invoice-api.html)
- [Postman Collection](collections/servicenow-aggregate-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/servicenow-aggregate-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/servicenow-attachment-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/servicenow-attachment-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/servicenow-change-management-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/servicenow-change-management-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/servicenow-cmdb-instance-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/servicenow-cmdb-instance-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/servicenow-import-set-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/servicenow-import-set-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/servicenow-service-catalog-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/servicenow-service-catalog-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/servicenow-table-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/servicenow-table-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### ServiceNow CSM Order API

The ServiceNow CSM Order API provides REST endpoints for managing order records within Customer Service Management. It enables external systems to create, retrieve, and update customer orders and associated order line items.

- **Human URL:** [https://www.servicenow.com/docs/bundle/yokohama-api-reference/page/integrate/inbound-rest/concept/order_csm-api.html](https://www.servicenow.com/docs/bundle/yokohama-api-reference/page/integrate/inbound-rest/concept/order_csm-api.html)
- **Base URL:** `https://{instance}.service-now.com/api/sn_customerservice/order`

#### Tags

- Commerce
- CSM
- Customer Service
- Orders

#### Properties

- [Documentation](https://www.servicenow.com/docs/bundle/yokohama-api-reference/page/integrate/inbound-rest/concept/order_csm-api.html)
- [Postman Collection](collections/servicenow-aggregate-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/servicenow-aggregate-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/servicenow-attachment-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/servicenow-attachment-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/servicenow-change-management-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/servicenow-change-management-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/servicenow-cmdb-instance-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/servicenow-cmdb-instance-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/servicenow-import-set-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/servicenow-import-set-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/servicenow-service-catalog-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/servicenow-service-catalog-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/servicenow-table-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/servicenow-table-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### ServiceNow CI Lifecycle Management API

The ServiceNow CI Lifecycle Management API provides REST endpoints for managing the lifecycle states of configuration items (CIs) in the CMDB. It enables programmatic tracking and transition of CI states from procurement through deployment, operation, and retirement.

- **Human URL:** [https://www.servicenow.com/docs/bundle/yokohama-api-reference/page/integrate/inbound-rest/concept/ci-lifecycle-management-api.html](https://www.servicenow.com/docs/bundle/yokohama-api-reference/page/integrate/inbound-rest/concept/ci-lifecycle-management-api.html)
- **Base URL:** `https://{instance}.service-now.com/api/now/cmdb/ci_lifecycle`

#### Tags

- CMDB
- Configuration Management
- IT Operations
- Lifecycle

#### Properties

- [Documentation](https://www.servicenow.com/docs/bundle/yokohama-api-reference/page/integrate/inbound-rest/concept/ci-lifecycle-management-api.html)
- [Postman Collection](collections/servicenow-aggregate-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/servicenow-aggregate-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/servicenow-attachment-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/servicenow-attachment-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/servicenow-change-management-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/servicenow-change-management-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/servicenow-cmdb-instance-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/servicenow-cmdb-instance-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/servicenow-import-set-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/servicenow-import-set-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/servicenow-service-catalog-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/servicenow-service-catalog-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/servicenow-table-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/servicenow-table-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### ServiceNow Alarm Management Open API

The ServiceNow Alarm Management Open API provides REST endpoints for managing alarm records within IT Operations Management. It supports creating, retrieving, and updating alarm data from external monitoring systems, enabling centralized alarm management on the Now Platform.

- **Human URL:** [https://www.servicenow.com/docs/bundle/yokohama-api-reference/page/integrate/inbound-rest/concept/alarm-open-api.html](https://www.servicenow.com/docs/bundle/yokohama-api-reference/page/integrate/inbound-rest/concept/alarm-open-api.html)
- **Base URL:** `https://{instance}.service-now.com/api/now/alarm`

#### Tags

- Alerts
- Event Management
- ITOM
- Monitoring

#### Properties

- [Documentation](https://www.servicenow.com/docs/bundle/yokohama-api-reference/page/integrate/inbound-rest/concept/alarm-open-api.html)
- [Postman Collection](collections/servicenow-aggregate-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/servicenow-aggregate-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/servicenow-attachment-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/servicenow-attachment-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/servicenow-change-management-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/servicenow-change-management-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/servicenow-cmdb-instance-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/servicenow-cmdb-instance-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/servicenow-import-set-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/servicenow-import-set-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/servicenow-service-catalog-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/servicenow-service-catalog-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/servicenow-table-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/servicenow-table-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### ServiceNow SAM Software Usage Data Integration API

The ServiceNow SAM Software Usage Data Integration API provides REST endpoints for importing software usage and metering data into Software Asset Management. It enables third-party software usage tracking tools to feed consumption data into ServiceNow for license compliance and optimization.

- **Human URL:** [https://www.servicenow.com/docs/bundle/yokohama-api-reference/page/integrate/inbound-rest/concept/sam_soft_us_int-api.html](https://www.servicenow.com/docs/bundle/yokohama-api-reference/page/integrate/inbound-rest/concept/sam_soft_us_int-api.html)
- **Base URL:** `https://{instance}.service-now.com/api/sam/software_usage`

#### Tags

- ITAM
- Licensing
- Software Asset Management
- Usage Tracking

#### Properties

- [Documentation](https://www.servicenow.com/docs/bundle/yokohama-api-reference/page/integrate/inbound-rest/concept/sam_soft_us_int-api.html)
- [Postman Collection](collections/servicenow-aggregate-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/servicenow-aggregate-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/servicenow-attachment-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/servicenow-attachment-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/servicenow-change-management-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/servicenow-change-management-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/servicenow-cmdb-instance-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/servicenow-cmdb-instance-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/servicenow-import-set-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/servicenow-import-set-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/servicenow-service-catalog-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/servicenow-service-catalog-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/servicenow-table-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/servicenow-table-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### ServiceNow Product Catalog Open API

The ServiceNow Product Catalog Open API provides REST endpoints for managing product catalog data based on the TM Forum TMF620 specification. It enables querying and managing product specifications, offerings, and categories for telecommunications and order management workflows.

- **Human URL:** [https://www.servicenow.com/docs/bundle/yokohama-api-reference/page/integrate/inbound-rest/concept/product-catalog-open-api.html](https://www.servicenow.com/docs/bundle/yokohama-api-reference/page/integrate/inbound-rest/concept/product-catalog-open-api.html)
- **Base URL:** `https://{instance}.service-now.com/api/sn_ind_tmt_orm/catalogManagement/v4`

#### Tags

- Commerce
- Product Catalog
- Telecommunications
- TMF

#### Properties

- [Documentation](https://www.servicenow.com/docs/bundle/yokohama-api-reference/page/integrate/inbound-rest/concept/product-catalog-open-api.html)
- [Postman Collection](collections/servicenow-aggregate-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/servicenow-aggregate-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/servicenow-attachment-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/servicenow-attachment-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/servicenow-change-management-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/servicenow-change-management-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/servicenow-cmdb-instance-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/servicenow-cmdb-instance-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/servicenow-import-set-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/servicenow-import-set-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/servicenow-service-catalog-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/servicenow-service-catalog-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/servicenow-table-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/servicenow-table-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### ServiceNow Service Catalog Open API

The ServiceNow Service Catalog Open API provides REST endpoints for managing service catalog data based on the TM Forum TMF633 specification. It supports querying and managing service specifications and service candidates for telecommunications service management.

- **Human URL:** [https://www.servicenow.com/docs/bundle/yokohama-api-reference/page/integrate/inbound-rest/concept/service-catalog-open-api.html](https://www.servicenow.com/docs/bundle/yokohama-api-reference/page/integrate/inbound-rest/concept/service-catalog-open-api.html)
- **Base URL:** `https://{instance}.service-now.com/api/sn_ind_tmt_orm/serviceCatalogManagement/v4`

#### Tags

- Commerce
- Service Catalog
- Telecommunications
- TMF

#### Properties

- [Documentation](https://www.servicenow.com/docs/bundle/yokohama-api-reference/page/integrate/inbound-rest/concept/service-catalog-open-api.html)
- [Postman Collection](collections/servicenow-aggregate-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/servicenow-aggregate-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/servicenow-attachment-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/servicenow-attachment-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/servicenow-change-management-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/servicenow-change-management-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/servicenow-cmdb-instance-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/servicenow-cmdb-instance-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/servicenow-import-set-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/servicenow-import-set-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/servicenow-service-catalog-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/servicenow-service-catalog-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/servicenow-table-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/servicenow-table-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### ServiceNow Product Order Open API

The ServiceNow Product Order Open API provides REST endpoints for managing product orders based on the TM Forum TMF622 specification. It enables creating, retrieving, and updating product orders for telecommunications order management workflows.

- **Human URL:** [https://www.servicenow.com/docs/bundle/yokohama-api-reference/page/integrate/inbound-rest/concept/tmf622_product_ordering-api.html](https://www.servicenow.com/docs/bundle/yokohama-api-reference/page/integrate/inbound-rest/concept/tmf622_product_ordering-api.html)
- **Base URL:** `https://{instance}.service-now.com/api/sn_ind_tmt_orm/productOrderingManagement/v4`

#### Tags

- Commerce
- Product Ordering
- Telecommunications
- TMF

#### Properties

- [Documentation](https://www.servicenow.com/docs/bundle/yokohama-api-reference/page/integrate/inbound-rest/concept/tmf622_product_ordering-api.html)
- [Postman Collection](collections/servicenow-aggregate-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/servicenow-aggregate-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/servicenow-attachment-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/servicenow-attachment-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/servicenow-change-management-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/servicenow-change-management-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/servicenow-cmdb-instance-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/servicenow-cmdb-instance-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/servicenow-import-set-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/servicenow-import-set-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/servicenow-service-catalog-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/servicenow-service-catalog-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/servicenow-table-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/servicenow-table-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### ServiceNow Service Order Open API

The ServiceNow Service Order Open API provides REST endpoints for managing service orders based on the TM Forum TMF641 specification. It enables creating, retrieving, and updating service orders for telecommunications service ordering workflows.

- **Human URL:** [https://www.servicenow.com/docs/bundle/yokohama-api-reference/page/integrate/inbound-rest/concept/service-order-open-api.html](https://www.servicenow.com/docs/bundle/yokohama-api-reference/page/integrate/inbound-rest/concept/service-order-open-api.html)
- **Base URL:** `https://{instance}.service-now.com/api/sn_ind_tmt_orm/serviceOrderingManagement/v4`

#### Tags

- Commerce
- Service Ordering
- Telecommunications
- TMF

#### Properties

- [Documentation](https://www.servicenow.com/docs/bundle/yokohama-api-reference/page/integrate/inbound-rest/concept/service-order-open-api.html)
- [Postman Collection](collections/servicenow-aggregate-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/servicenow-aggregate-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/servicenow-attachment-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/servicenow-attachment-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/servicenow-change-management-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/servicenow-change-management-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/servicenow-cmdb-instance-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/servicenow-cmdb-instance-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/servicenow-import-set-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/servicenow-import-set-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/servicenow-service-catalog-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/servicenow-service-catalog-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/servicenow-table-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/servicenow-table-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### ServiceNow Resource Inventory Open API

The ServiceNow Resource Inventory Open API provides REST endpoints for managing resource inventory data based on TM Forum specifications. It supports querying and managing physical and logical resource records for telecommunications network inventory management.

- **Human URL:** [https://www.servicenow.com/docs/bundle/yokohama-api-reference/page/integrate/inbound-rest/concept/resource-inventory-api.html](https://www.servicenow.com/docs/bundle/yokohama-api-reference/page/integrate/inbound-rest/concept/resource-inventory-api.html)
- **Base URL:** `https://{instance}.service-now.com/api/sn_ind_tmt_orm/resourceInventoryManagement/v4`

#### Tags

- Inventory
- Resources
- Telecommunications
- TMF

#### Properties

- [Documentation](https://www.servicenow.com/docs/bundle/yokohama-api-reference/page/integrate/inbound-rest/concept/resource-inventory-api.html)
- [Postman Collection](collections/servicenow-aggregate-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/servicenow-aggregate-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/servicenow-attachment-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/servicenow-attachment-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/servicenow-change-management-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/servicenow-change-management-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/servicenow-cmdb-instance-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/servicenow-cmdb-instance-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/servicenow-import-set-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/servicenow-import-set-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/servicenow-service-catalog-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/servicenow-service-catalog-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/servicenow-table-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/servicenow-table-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### ServiceNow Product Inventory Open API

The ServiceNow Product Inventory Open API provides REST endpoints for managing product inventory data based on TM Forum specifications. It supports querying and managing product instances and their lifecycle states for telecommunications product inventory management.

- **Human URL:** [https://www.servicenow.com/docs/bundle/yokohama-api-reference/page/integrate/inbound-rest/concept/product-inventory-open-api.html](https://www.servicenow.com/docs/bundle/yokohama-api-reference/page/integrate/inbound-rest/concept/product-inventory-open-api.html)
- **Base URL:** `https://{instance}.service-now.com/api/sn_ind_tmt_orm/productInventoryManagement/v4`

#### Tags

- Inventory
- Products
- Telecommunications
- TMF

#### Properties

- [Documentation](https://www.servicenow.com/docs/bundle/yokohama-api-reference/page/integrate/inbound-rest/concept/product-inventory-open-api.html)
- [Postman Collection](collections/servicenow-aggregate-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/servicenow-aggregate-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/servicenow-attachment-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/servicenow-attachment-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/servicenow-change-management-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/servicenow-change-management-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/servicenow-cmdb-instance-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/servicenow-cmdb-instance-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/servicenow-import-set-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/servicenow-import-set-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/servicenow-service-catalog-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/servicenow-service-catalog-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/servicenow-table-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/servicenow-table-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### ServiceNow Service Test Management Open API

The ServiceNow Service Test Management Open API provides REST endpoints for managing service test records based on TM Forum specifications. It supports creating and managing service test definitions and results for telecommunications service quality assurance.

- **Human URL:** [https://www.servicenow.com/docs/bundle/yokohama-api-reference/page/integrate/inbound-rest/concept/service-test-management-api.html](https://www.servicenow.com/docs/bundle/yokohama-api-reference/page/integrate/inbound-rest/concept/service-test-management-api.html)
- **Base URL:** `https://{instance}.service-now.com/api/sn_ind_tmt_orm/serviceTestManagement/v4`

#### Tags

- Quality
- Service Testing
- Telecommunications
- TMF

#### Properties

- [Documentation](https://www.servicenow.com/docs/bundle/yokohama-api-reference/page/integrate/inbound-rest/concept/service-test-management-api.html)
- [Postman Collection](collections/servicenow-aggregate-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/servicenow-aggregate-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/servicenow-attachment-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/servicenow-attachment-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/servicenow-change-management-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/servicenow-change-management-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/servicenow-cmdb-instance-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/servicenow-cmdb-instance-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/servicenow-import-set-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/servicenow-import-set-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/servicenow-service-catalog-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/servicenow-service-catalog-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/servicenow-table-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/servicenow-table-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### ServiceNow Project Portfolio Management API

The ServiceNow Project Portfolio Management API provides REST endpoints for managing projects, demands, and resource plans within Strategic Portfolio Management (SPM). It enables external systems to create, retrieve, and update project portfolio data for governance and planning purposes.

- **Human URL:** [https://www.servicenow.com/docs/bundle/yokohama-api-reference/page/integrate/inbound-rest/concept/ppm-api.html](https://www.servicenow.com/docs/bundle/yokohama-api-reference/page/integrate/inbound-rest/concept/ppm-api.html)
- **Base URL:** `https://{instance}.service-now.com/api/now/ppm`

#### Tags

- Governance
- PPM
- Project Management
- Strategic Portfolio Management

#### Properties

- [Documentation](https://www.servicenow.com/docs/bundle/yokohama-api-reference/page/integrate/inbound-rest/concept/ppm-api.html)
- [Postman Collection](collections/servicenow-aggregate-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/servicenow-aggregate-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/servicenow-attachment-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/servicenow-attachment-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/servicenow-change-management-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/servicenow-change-management-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/servicenow-cmdb-instance-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/servicenow-cmdb-instance-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/servicenow-import-set-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/servicenow-import-set-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/servicenow-service-catalog-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/servicenow-service-catalog-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/servicenow-table-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/servicenow-table-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [Arazzo Workflows](arazzo/) — [Arazzo Specification](https://spec.openapis.org/arazzo/latest.html)
- [JSON-LD](json-ld/servicenow-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [JSON Schema](json-schema/servicenow-incident-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/servicenow-change-request-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/servicenow-configuration-item-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/servicenow-catalog-request-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/servicenow-user-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [Website](https://www.servicenow.com/)
- [Portal](https://developer.servicenow.com)
- [Blog](https://www.servicenow.com/community/developer-blog/bg-p/developer-blog)
- [Events](https://www.servicenow.com/community/events/ct-p/TopLevel_Events)
- [Forums](https://www.servicenow.com/community/developer-forum/bd-p/developer-forum)
- [Community](https://www.servicenow.com/community/)
- [Documentation](https://www.servicenow.com/docs/)
- [API Reference](https://www.servicenow.com/docs/bundle/yokohama-api-reference/page/integrate/inbound-rest/concept/c_RESTAPI.html)
- [Getting Started](https://developer.servicenow.com/dev.do#!/learn/learning-plans/tokyo/new_to_servicenow/app_store_learnv2_rest_tokyo_rest_api_explorer)
- [Authentication](https://www.servicenow.com/docs/bundle/yokohama-platform-security/page/administer/security/concept/c_OAuthApplications.html)
- [Rate Limits](https://www.servicenow.com/docs/bundle/yokohama-api-reference/page/integrate/inbound-rest/concept/c_RESTAPI.html)
- [Status Page](https://status.servicenow.com)
- [Support](https://support.servicenow.com)
- [Pricing](https://www.servicenow.com/products/pricing.html)
- [Terms of Service](https://www.servicenow.com/terms-of-use.html)
- [Privacy Policy](https://www.servicenow.com/privacy-statement.html)
- [Changelog](https://www.servicenow.com/docs/bundle/yokohama-release-notes/page/release-notes/family-release-notes.html)
- [GitHub Organization](https://github.com/ServiceNow)
- [GitHub Organization](https://github.com/ServiceNowDevProgram)
- [GitHub Repository](https://github.com/ServiceNow/sdk)
- [SDK](https://www.npmjs.com/package/@servicenow/sdk)
- [Documentation](https://www.servicenow.com/docs/bundle/yokohama-application-development/page/build/servicenow-sdk/concept/servicenow-sdk-landing.html)
- [Stack Overflow](https://stackoverflow.com/questions/tagged/servicenow)
- [Sign Up](https://developer.servicenow.com/dev.do)
- [Login](https://developer.servicenow.com/dev.do)
- [YouTube](https://www.youtube.com/user/serviceaborad)
- [Rate Limits](https://www.servicenow.com/docs/bundle/yokohama-api-reference/page/integrate/inbound-rest/concept/inbound-REST-API-rate-limiting.html)
- [Documentation](https://www.servicenow.com/docs/bundle/yokohama-api-reference/page/integrate/inbound-rest/concept/use-REST-API-Explorer.html)
- [Documentation](https://www.servicenow.com/docs/bundle/yokohama-api-reference/page/integrate/inbound-rest/task/export-openapi-specification.html)
- [GitHub Repository](https://github.com/ServiceNow/PySNC)
- [SDK](https://pypi.org/project/pysnc/)
- [Documentation](https://servicenow.github.io/PySNC/)
- [Authentication](https://www.servicenow.com/docs/bundle/yokohama-api-reference/page/integrate/inbound-rest/task/t_EnableOAuthWithREST.html)
- [X (Twitter)](https://x.com/ServiceNow)
- [LinkedIn](https://www.linkedin.com/company/servicenow)
- [Getting Started](https://www.servicenow.com/university/training-and-certification.html)
- [Documentation](https://www.servicenow.com/products/api-integrations.html)
- [API Reference](https://developer.servicenow.com/dev.do#!/reference/api/yokohama/rest/)
- [JSON-LD](json-ld/contact-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [JSON-LD](json-ld/servicenow-aggregate-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [JSON-LD](json-ld/servicenow-attachment-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [JSON-LD](json-ld/servicenow-change-management-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [JSON-LD](json-ld/servicenow-cmdb-instance-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [JSON-LD](json-ld/servicenow-import-set-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [JSON-LD](json-ld/servicenow-service-catalog-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [JSON-LD](json-ld/servicenow-table-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [JSON-LD](json-ld/trouble-ticket-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [Spectral Rules](rules/servicenow-spectral-rules.yml)
- [Vocabulary](vocabulary/servicenow-vocabulary.yaml)
- [Features](undefined)
- [Use Cases](undefined)
- [Integrations](undefined)
- [Agent Skill](https://github.com/ServiceNow/saai-skill-feedback)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
