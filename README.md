# data.world

Collaborative data catalog platform with REST APIs for accessing public and private datasets, running SQL and SPARQL queries, managing metadata, and integrating data across projects and organizations. Provides enterprise data governance, lineage, and business glossary capabilities.

**Developer Portal:** https://developer.data.world/  
**API Base URL:** https://api.data.world/v0  
**Status Page:** https://status.data.world  
**Support:** https://dataworld.atlassian.net/servicedesk/customer/portals  

## APIs

- **REST API** - Core platform API for datasets, projects, files, users, and webhooks
- **SQL Query API** - Execute SQL queries against datasets and projects
- **SPARQL Query API** - Semantic/RDF querying via GET or POST
- **Metadata Management API** - Catalog resources, relationships, glossaries, and data quality
- **Datasets API** - Create, retrieve, update, delete, and download datasets
- **Projects API** - Manage projects and dataset links
- **Webhooks API** - Subscribe to platform events
- **Answer API** - Natural language question answering on structured data

## Authentication

Bearer token authentication using API tokens from account settings. OAuth 2.0 is supported for application development.

## SDKs

Python, R, Go, JDBC — see https://developer.data.world/docs/data-world-for-developers

## Plans

See [plans/plans.yml](plans/plans.yml) for pricing tiers (Essentials, Standard, Enterprise, Enterprise+). Enterprise pricing starts around $90K/year; contact sales for quotes.

## Rate Limits

See [rate-limits/rate-limits.yml](rate-limits/rate-limits.yml). Specific thresholds are not publicly disclosed. HTTP 429 responses are issued when limits are exceeded.

## FinOps

See [finops/finops.yml](finops/finops.yml) for cost model details and optimization guidance.
