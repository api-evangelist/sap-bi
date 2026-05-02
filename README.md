# SAP Business Intelligence

Collection of APIs for SAP Business Intelligence (BI) platform, including analytics, reporting, and data visualization services.

**URL:** https://api.sap.com/business-intelligence

## Tags

Analytics, Business Intelligence, Data Visualization, Reporting, SAP

## Timestamps

- **Created:** 2024
- **Modified:** 2026-05-02

## APIs

### SAP Analytics Cloud API

REST API for SAP Analytics Cloud enabling data integration, story management, and analytics operations.

- **Base URL:** https://[tenant].sapanalytics.cloud/api/v1
- **Human URL:** https://help.sap.com/docs/SAP_ANALYTICS_CLOUD
- **OpenAPI:** [openapi/sap-bi-analytics-cloud-openapi.yml](openapi/sap-bi-analytics-cloud-openapi.yml)

### SAP BusinessObjects BI Platform REST API

RESTful web services for SAP BusinessObjects BI Platform administration, content management, and reporting.

- **Base URL:** https://[server]:[port]/biprws
- **Human URL:** https://help.sap.com/docs/SAP_BUSINESSOBJECTS_BUSINESS_INTELLIGENCE_PLATFORM
- **OpenAPI:** [openapi/sap-bi-businessobjects-platform-openapi.yml](openapi/sap-bi-businessobjects-platform-openapi.yml)

### SAP BW/4HANA OData API

OData services for accessing SAP BW/4HANA data warehouse content and metadata.

- **Base URL:** https://[server]:[port]/sap/opu/odata/sap/
- **Human URL:** https://help.sap.com/docs/SAP_BW4HANA
- **OpenAPI:** [openapi/sap-bi-bw4hana-odata-openapi.yml](openapi/sap-bi-bw4hana-odata-openapi.yml)

### SAP Datasphere API

APIs for SAP Datasphere (formerly SAP Data Warehouse Cloud) for data integration and analytics.

- **Base URL:** https://[tenant].datasphere.cloud.sap/api/v1
- **Human URL:** https://help.sap.com/docs/SAP_DATASPHERE
- **OpenAPI:** [openapi/sap-bi-datasphere-openapi.yml](openapi/sap-bi-datasphere-openapi.yml)

### SAP Crystal Reports API

APIs for embedding and automating SAP Crystal Reports in applications.

- **Human URL:** https://help.sap.com/docs/SAP_CRYSTAL_REPORTS

## Artifacts

### OpenAPI Specifications

| API | File |
|-----|------|
| SAP Analytics Cloud API | [openapi/sap-bi-analytics-cloud-openapi.yml](openapi/sap-bi-analytics-cloud-openapi.yml) |
| SAP BusinessObjects BI Platform REST API | [openapi/sap-bi-businessobjects-platform-openapi.yml](openapi/sap-bi-businessobjects-platform-openapi.yml) |
| SAP BW/4HANA OData API | [openapi/sap-bi-bw4hana-odata-openapi.yml](openapi/sap-bi-bw4hana-odata-openapi.yml) |
| SAP Datasphere API | [openapi/sap-bi-datasphere-openapi.yml](openapi/sap-bi-datasphere-openapi.yml) |

### Capabilities

Workflow-oriented Naftiko capability compositions:

| Workflow | Description |
|----------|-------------|
| [Analytics and Reporting](capabilities/analytics-and-reporting.yaml) | Story authoring, report scheduling, and content governance (Analytics Cloud + BusinessObjects) |
| [Data Warehouse Access](capabilities/data-warehouse-access.yaml) | BW/4HANA InfoProvider browsing and Datasphere space/connection management |

**Shared per-API definitions (`capabilities/shared/`):**

- [analytics-cloud.yaml](capabilities/shared/analytics-cloud.yaml) — SAP Analytics Cloud API
- [businessobjects-platform.yaml](capabilities/shared/businessobjects-platform.yaml) — SAP BusinessObjects BI Platform
- [bw4hana-odata.yaml](capabilities/shared/bw4hana-odata.yaml) — SAP BW/4HANA OData API
- [datasphere.yaml](capabilities/shared/datasphere.yaml) — SAP Datasphere API

### Rules

- [rules/sap-bi-rules.yml](rules/sap-bi-rules.yml) — Spectral ruleset for SAP Business Intelligence API conventions

### JSON Schema

- [json-schema/sap-bi-story-schema.json](json-schema/sap-bi-story-schema.json)
- [json-schema/sap-bi-report-schema.json](json-schema/sap-bi-report-schema.json)
- [json-schema/sap-bi-data-source-schema.json](json-schema/sap-bi-data-source-schema.json)

### JSON Structure

- [json-structure/sap-bi-story-structure.json](json-structure/sap-bi-story-structure.json)
- [json-structure/sap-bi-space-structure.json](json-structure/sap-bi-space-structure.json)

### JSON-LD

- [json-ld/sap-bi-context.jsonld](json-ld/sap-bi-context.jsonld)

### Examples

- [examples/sap-bi-list-stories-example.json](examples/sap-bi-list-stories-example.json)
- [examples/sap-bi-list-spaces-example.json](examples/sap-bi-list-spaces-example.json)

### Vocabulary

- [vocabulary/sap-bi-vocabulary.yml](vocabulary/sap-bi-vocabulary.yml)

## Common Resources

- **Portal:** https://api.sap.com/
- **Authentication:** https://help.sap.com/docs/SAP_CLOUD_PLATFORM/65de2977205c403bbc107264b8eccf4b/3670474a58c24ac2b082e76cbbd9dc19.html
- **Support:** https://support.sap.com/en/index.html
- **Community:** https://community.sap.com/
- **Terms of Service:** https://www.sap.com/about/legal/terms-of-use.html
- **Privacy Policy:** https://www.sap.com/about/legal/privacy.html

## Maintainers

- **Kin Lane** — kin@apievangelist.com
