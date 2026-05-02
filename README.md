# Salesforce

Salesforce is a global leader in customer relationship management (CRM) software and cloud-based applications. The Salesforce Platform provides a comprehensive suite of APIs for sales, service, marketing, commerce, integration, analytics, and platform development including Agentforce AI capabilities.

## APIs

| API | Description |
|---|---|
| [Salesforce REST API](https://developer.salesforce.com/docs/atlas.en-us.api_rest.meta/api_rest) | Core REST API for CRUD operations on Salesforce records via SOQL |
| [Salesforce Bulk API 2.0](https://developer.salesforce.com/docs/atlas.en-us.api_asynch.meta/api_asynch) | Async bulk data loading for large record sets |
| [Salesforce Streaming API](https://developer.salesforce.com/docs/atlas.en-us.api_streaming.meta/api_streaming) | Real-time event streaming via PushTopic, CDC, and Platform Events |
| [Salesforce Metadata API](https://developer.salesforce.com/docs/atlas.en-us.api_meta.meta/api_meta) | Org customization deployment and retrieval for CI/CD |
| [Salesforce Connect REST API](https://developer.salesforce.com/docs/atlas.en-us.chatterapi.meta/chatterapi) | Chatter, Files, and Experience Cloud features |
| [Marketing Cloud REST API](https://developer.salesforce.com/docs/marketing/marketing-cloud/guide/rest-api.html) | Email, SMS, journeys, and subscriber management |
| [Salesforce B2C Commerce API](https://developer.salesforce.com/docs/commerce/b2c-commerce/guide/b2c-commerce-api.html) | Headless commerce storefront API |
| [Agentforce API](https://developer.salesforce.com/agentforce) | Build and deploy autonomous AI agents |
| [MuleSoft Anypoint Platform API](https://docs.mulesoft.com/mule-runtime/latest/) | Integration and API management |

## Resources

- **Developer Portal**: [developer.salesforce.com](https://developer.salesforce.com)
- **API Library**: [developer.salesforce.com/docs/apis](https://developer.salesforce.com/docs/apis)
- **Trailhead**: [trailhead.salesforce.com](https://trailhead.salesforce.com)
- **Postman Collection**: [Salesforce Platform APIs](https://www.postman.com/salesforce-developers/salesforce-developers)
- **GitHub Org (forcedotcom)**: [github.com/forcedotcom](https://github.com/forcedotcom)
- **GitHub Org (salesforcecli)**: [github.com/salesforcecli](https://github.com/salesforcecli)
- **CLI**: [Salesforce CLI](https://github.com/salesforcecli/cli)
- **Status**: [status.salesforce.com](https://status.salesforce.com)

## Artifacts

### OpenAPI Specs
- [salesforcecom-rest-openapi.yml](openapi/salesforcecom-rest-openapi.yml) — Salesforce REST API (14 operations: CRUD, SOQL, SOSL, Composite)

### Spectral Rules
- [salesforcecom-rules.yml](rules/salesforcecom-rules.yml) — API style and compliance rules

### Capabilities
- [crm-data-management.yaml](capabilities/crm-data-management.yaml) — CRM record CRUD + SOQL query + SOSL search workflow
- [shared/salesforce-rest.yaml](capabilities/shared/salesforce-rest.yaml) — Base Salesforce REST API consumed definition

### JSON Schema
- [salesforcecom-sobject-schema.json](json-schema/salesforcecom-sobject-schema.json) — Salesforce sObject record schema
- [salesforcecom-query-result-schema.json](json-schema/salesforcecom-query-result-schema.json) — SOQL query result schema

### JSON Structure
- [salesforcecom-sobject-structure.json](json-structure/salesforcecom-sobject-structure.json) — sObject structure documentation

### JSON-LD
- [salesforcecom-context.jsonld](json-ld/salesforcecom-context.jsonld) — Linked data context for CRM objects

### Examples
- [salesforcecom-query-accounts-example.json](examples/salesforcecom-query-accounts-example.json) — SOQL query for Technology accounts
- [salesforcecom-create-contact-example.json](examples/salesforcecom-create-contact-example.json) — Create contact request/response

### Vocabulary
- [salesforcecom-vocabulary.yml](vocabulary/salesforcecom-vocabulary.yml) — Salesforce platform terminology

## Maintained By

[Kin Lane](mailto:kin@apievangelist.com) — [API Evangelist](https://apievangelist.com)
