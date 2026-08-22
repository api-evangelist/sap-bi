# SAP Business Intelligence (sap-bi)

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **Not from the company, and here with a question?** You are welcome here — we would rather be the
> front line and point you the right way than have a good report go nowhere. What this repository
> can answer is narrow, though, so it is worth knowing who you are actually looking for:
>
> - **A question about how the API works, an account, billing, or a bug in the service** — that is
>   the company's own support, not us. We profile this API; we do not operate it and cannot see
>   your account.
> - **A bug in an open-source project we only catalog** — file it on that project's own repository.
>   This has happened with a real and correct bug report that reached us instead of the people who
>   could fix it, which helped nobody.
> - **Anything about this listing itself** — the description, the tags, the rating, a missing or
>   wrong artifact — is ours. Open an issue here.
> - **Not sure, or something general about API Evangelist or APIs.io** — open an issue on the
>   [APIs.io Inbox](https://github.com/api-search/inbox) and we will route it.
>
> **This repository contains no software, and we will never ask you to download anything.** There is
> no build, release, installer, or binary here — only text and machine-readable API descriptions, so
> there is nothing here that can be "corrupt" or need "repairing". Any issue, comment, or email
> claiming otherwise and offering a download link is not from us and is hostile. Do not follow the
> link; it is a lure. Report it to GitHub and, if you like, tell us at
> [info@apievangelist.com](mailto:info@apievangelist.com) so we can take it down.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

Collection of APIs for SAP Business Intelligence (BI) platform, including analytics, reporting, and data visualization services.

**APIs.json:** [https://api.sap.com/business-intelligence](https://api.sap.com/business-intelligence)

## Tags

- Analytics
- Business Intelligence
- Data Visualization
- Reporting
- SAP

## Timestamps

- **Created:** 2024
- **Modified:** 2026-05-19

## APIs

### SAP Analytics Cloud API

REST API for SAP Analytics Cloud enabling data integration, story management, and analytics operations.

- **Human URL:** [https://help.sap.com/docs/SAP_ANALYTICS_CLOUD](https://help.sap.com/docs/SAP_ANALYTICS_CLOUD)
- **Base URL:** `https://[tenant].sapanalytics.cloud/api/v1`

#### Tags

- Analytics
- Cloud
- Dashboards

#### Properties

- [Documentation](https://help.sap.com/docs/SAP_ANALYTICS_CLOUD/14cac91febef464dbb1efce20e3f1613/147c1fd5bb3-4f8ba65b37acf1d6dbce.html)
- [OpenAPI](https://api.sap.com/api/API_ANALYTICS_CLOUD/overview) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Authentication](https://help.sap.com/docs/SAP_ANALYTICS_CLOUD/00f68c2e08b941f081002fd3691d86a7/c7e7c53f91bb41f8bd1440afd47ca49e.html)
- [Swagger](https://[tenant].sapanalytics.cloud/api/v1/swagger-ui.html)
- [OpenAPI](openapi/sap-bi-analytics-cloud-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/sap-bi-analytics-cloud.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/sap-bi-analytics-cloud.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### SAP BusinessObjects BI Platform REST API

RESTful web services for SAP BusinessObjects BI Platform administration, content management, and reporting.

- **Human URL:** [https://help.sap.com/docs/SAP_BUSINESSOBJECTS_BUSINESS_INTELLIGENCE_PLATFORM](https://help.sap.com/docs/SAP_BUSINESSOBJECTS_BUSINESS_INTELLIGENCE_PLATFORM)
- **Base URL:** `https://[server]:[port]/biprws`

#### Tags

- BusinessObjects
- Platform Administration
- Reports

#### Properties

- [Documentation](https://help.sap.com/docs/SAP_BUSINESSOBJECTS_BUSINESS_INTELLIGENCE_PLATFORM/ca1da879759d4c76894329a42c5b88c3/5051e4f36d6d1014b3fc9283b0e91070.html)
- [OpenAPI](https://api.sap.com/api/BOBJ_BIPLATFORM/overview) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [S D K  Documentation](https://help.sap.com/docs/SAP_BUSINESSOBJECTS_BUSINESS_INTELLIGENCE_PLATFORM/ca1da879759d4c76894329a42c5b88c3/49e9e7f26d6d1014910c91fa5b0c2cc3.html)
- [Authentication](https://help.sap.com/docs/SAP_BUSINESSOBJECTS_BUSINESS_INTELLIGENCE_PLATFORM/ca1da879759d4c76894329a42c5b88c3/4f0990926d6d1014a74b9c23f567b6f4.html)
- [OpenAPI](openapi/sap-bi-businessobjects-platform-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/sap-bi-businessobjects-platform.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/sap-bi-businessobjects-platform.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### SAP HANA XS Advanced API

APIs for building analytics applications on SAP HANA XS Advanced platform.

- **Human URL:** [https://help.sap.com/docs/SAP_HANA_PLATFORM](https://help.sap.com/docs/SAP_HANA_PLATFORM)
- **Base URL:** `https://[host]:[port]`

#### Tags

- Analytics
- Database
- HANA
- XS Advanced

#### Properties

- [Documentation](https://help.sap.com/docs/SAP_HANA_PLATFORM/4505d0bdaf4948449b7f7379d24d0f0d/df19a03dc07e4ba19db4e0006c1da429.html)
- [Developer  Guide](https://help.sap.com/docs/SAP_HANA_PLATFORM/4505d0bdaf4948449b7f7379d24d0f0d/3ec885c07e844d9fb4f40e3c4af0adb8.html)
- [API Reference](https://help.sap.com/docs/SAP_HANA_PLATFORM/4505d0bdaf4948449b7f7379d24d0f0d/c102c07e04c541cc906f5fcdb3e02105.html)
- [Postman Collection](collections/sap-bi-analytics-cloud.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/sap-bi-analytics-cloud.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/sap-bi-businessobjects-platform.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/sap-bi-businessobjects-platform.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/sap-bi-bw4hana-odata.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/sap-bi-bw4hana-odata.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/sap-bi-datasphere.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/sap-bi-datasphere.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### SAP BW/4HANA OData API

OData services for accessing SAP BW/4HANA data warehouse content and metadata.

- **Human URL:** [https://help.sap.com/docs/SAP_BW4HANA](https://help.sap.com/docs/SAP_BW4HANA)
- **Base URL:** `https://[server]:[port]/sap/opu/odata/sap/`

#### Tags

- BW/4HANA
- Data Warehouse
- ETL
- OData

#### Properties

- [Documentation](https://help.sap.com/docs/SAP_BW4HANA/107a6e8a38b74ede94c833ca3b7b6f51/5e467a851e874e48afcfa4cc88b5dd28.html)
- [O Data  Reference](https://api.sap.com/package/SAPBW4HANA/odata)
- [Integration  Guide](https://help.sap.com/docs/SAP_BW4HANA/107a6e8a38b74ede94c833ca3b7b6f51/3801c14d27f046a79eed60a22ac6bd23.html)
- [OpenAPI](openapi/sap-bi-bw4hana-odata-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/sap-bi-bw4hana-odata.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/sap-bi-bw4hana-odata.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### SAP Datasphere API

APIs for SAP Datasphere (formerly SAP Data Warehouse Cloud) for data integration and analytics.

- **Human URL:** [https://help.sap.com/docs/SAP_DATASPHERE](https://help.sap.com/docs/SAP_DATASPHERE)
- **Base URL:** `https://[tenant].datasphere.cloud.sap/api/v1`

#### Tags

- Cloud
- Data Integration
- Data Warehouse
- Datasphere

#### Properties

- [Documentation](https://help.sap.com/docs/SAP_DATASPHERE/9f804b8efa8043539289f42f372c4862/7f1a91f95e794a5e9f29abce8856c8cf.html)
- [OpenAPI](https://api.sap.com/api/datasphere/overview) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [API Reference](https://help.sap.com/docs/SAP_DATASPHERE/c8a54ee704e94e15926551293243fd1d/6c35457c1fc54a47b39aa5cdbc16d5e7.html)
- [Authentication](https://help.sap.com/docs/SAP_DATASPHERE/9f804b8efa8043539289f42f372c4862/3de81838d5cd43ee91576a3b0b4e5e36.html)
- [OpenAPI](openapi/sap-bi-datasphere-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/sap-bi-datasphere.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/sap-bi-datasphere.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### SAP Crystal Reports API

APIs for embedding and automating SAP Crystal Reports in applications.

- **Human URL:** [https://help.sap.com/docs/SAP_CRYSTAL_REPORTS](https://help.sap.com/docs/SAP_CRYSTAL_REPORTS)
- **Base URL:** `https://[server]/crystal/`

#### Tags

- Crystal Reports
- Embedded Analytics
- Reporting

#### Properties

- [Documentation](https://help.sap.com/docs/SAP_CRYSTAL_REPORTS/9e08a56e98d446b58af012538c121ff9/4650e1fe6d6d1014b3fc9283b0e91070.html)
- [S D K  Guide](https://help.sap.com/docs/SAP_CRYSTAL_REPORTS/9e08a56e98d446b58af012538c121ff9/461aff6a6d6d1014910c91fa5b0c2cc3.html)
- [Integration  Samples](https://wiki.scn.sap.com/wiki/display/BOBJ/Crystal+Reports+Developer+Center)
- [Postman Collection](collections/sap-bi-analytics-cloud.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/sap-bi-analytics-cloud.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/sap-bi-businessobjects-platform.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/sap-bi-businessobjects-platform.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/sap-bi-bw4hana-odata.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/sap-bi-bw4hana-odata.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/sap-bi-datasphere.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/sap-bi-datasphere.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [GitHub Organization](https://github.com/SAP)
- [Portal](https://api.sap.com/)
- [Authentication](https://help.sap.com/docs/SAP_CLOUD_PLATFORM/65de2977205c403bbc107264b8eccf4b/3670474a58c24ac2b082e76cbbd9dc19.html)
- [Support](https://support.sap.com/en/index.html)
- [Community](https://community.sap.com/)
- [Terms of Service](https://www.sap.com/about/legal/terms-of-use.html)
- [Privacy Policy](https://www.sap.com/about/legal/privacy.html)
- [OpenAPI](openapi/sap-bi-analytics-cloud-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [OpenAPI](openapi/sap-bi-businessobjects-platform-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [OpenAPI](openapi/sap-bi-bw4hana-odata-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [OpenAPI](openapi/sap-bi-datasphere-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [JSON-LD](json-ld/sap-bi-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [JSON Schema](json-schema/sap-bi-story-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/sap-bi-report-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/sap-bi-data-source-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Structure](json-structure/sap-bi-story-structure.json)
- [JSON Structure](json-structure/sap-bi-space-structure.json)
- [Spectral Rules](rules/sap-bi-rules.yml)
- [Vocabulary](vocabulary/sap-bi-vocabulary.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
