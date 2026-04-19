# Amplitude (amplitude)
Amplitude is a digital analytics platform that helps product teams understand user behavior, run experiments, and drive growth. It provides a suite of APIs for event ingestion, user management, cohort syncing, taxonomy governance, A/B testing, and data export. Amplitude is widely used by product, data, and engineering teams to build better digital experiences through data-driven insights.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/amplitude/refs/heads/main/apis.yml)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - A/B Testing, Analytics, Experimentation, Feature Flags, Product Analytics, User Behavior

## Timestamps

- **Created:** 2026-04-19
- **Modified:** 2026-04-19

## APIs

### Amplitude HTTP V2 API
The Amplitude HTTP V2 API enables developers to send event data directly from servers or clients to Amplitude's analytics platform. It supports uploading individual or batched events along with user properties, event properties, and group properties. This API is the primary method for server-side event ingestion and is designed for high-throughput data collection with built-in validation and error reporting.

**Human URL:** [https://amplitude.com/docs/apis/analytics/http-v2](https://amplitude.com/docs/apis/analytics/http-v2)

#### Tags:

 - Analytics, Events, Ingestion, Tracking

#### Properties

- [Documentation](https://amplitude.com/docs/apis/analytics/http-v2)
- [OpenAPI](openapi/amplitude-http-v2-api-openapi.yml)

### Amplitude Batch Event Upload API
The Amplitude Batch Event Upload API is optimized for high-volume server-side event ingestion. It accepts batches of events up to 20MB per request and is designed for use cases where data volume may exceed the limits of the standard HTTP V2 API. The API uses the same event structure as the HTTP V2 API and is recommended for data pipelines processing millions of events.

**Human URL:** [https://amplitude.com/docs/apis/analytics/batch-event-upload](https://amplitude.com/docs/apis/analytics/batch-event-upload)

#### Tags:

 - Analytics, Batch, Events, Ingestion

#### Properties

- [Documentation](https://amplitude.com/docs/apis/analytics/batch-event-upload)

### Amplitude Identify API
The Amplitude Identify API allows developers to update user properties for a specific user without needing to send an accompanying event. This is useful for setting or modifying user attributes such as demographics, subscription status, or preferences outside of the normal event tracking flow. The API supports operations like set, unset, append, and prepend on user properties.

**Human URL:** [https://amplitude.com/docs/apis/analytics/identify](https://amplitude.com/docs/apis/analytics/identify)

#### Tags:

 - Analytics, Identity, Properties, Users

#### Properties

- [Documentation](https://amplitude.com/docs/apis/analytics/identify)
- [OpenAPI](openapi/amplitude-identify-api-openapi.yml)

### Amplitude Group Identify API
The Amplitude Group Identify API allows developers to set or update properties on groups within Amplitude. Groups are entities such as companies, teams, or accounts that users belong to. This API enables B2B analytics use cases by attaching account-level properties to groups for segmentation and reporting purposes.

**Human URL:** [https://amplitude.com/docs/apis/analytics/group-identify](https://amplitude.com/docs/apis/analytics/group-identify)

#### Tags:

 - Analytics, Groups, Identity, Properties

#### Properties

- [Documentation](https://amplitude.com/docs/apis/analytics/group-identify)

### Amplitude Dashboard REST API
The Amplitude Dashboard REST API provides programmatic access to the same data displayed in Amplitude's dashboard charts and graphs. It returns results in JSON format and supports queries filtered by event types, user segments, cohorts, and date ranges. Developers can use this API to build custom reporting tools, export chart data, or integrate Amplitude analytics into external dashboards and business intelligence systems.

**Human URL:** [https://amplitude.com/docs/apis/analytics/dashboard-rest](https://amplitude.com/docs/apis/analytics/dashboard-rest)

#### Tags:

 - Analytics, Dashboards, Metrics, Reporting

#### Properties

- [Documentation](https://amplitude.com/docs/apis/analytics/dashboard-rest)
- [OpenAPI](openapi/amplitude-dashboard-rest-api-openapi.yml)

### Amplitude Export API
The Amplitude Export API enables bulk export of raw event data for a given project within a specified date range. Results are returned as zipped archives of JSON files containing complete event records with timestamps, user properties, device information, and attribution data. This API is commonly used for data warehousing, offline analysis, and feeding event data into external processing pipelines.

**Human URL:** [https://amplitude.com/docs/apis/analytics/export](https://amplitude.com/docs/apis/analytics/export)

#### Tags:

 - Analytics, Data, Events, Export

#### Properties

- [Documentation](https://amplitude.com/docs/apis/analytics/export)
- [OpenAPI](openapi/amplitude-export-api-openapi.yml)

### Amplitude Behavioral Cohorts API
The Amplitude Behavioral Cohorts API allows developers to list, export, and upload cohorts in Amplitude. Cohorts are groups of users defined by shared behavioral patterns or properties. This API supports downloading cohort membership lists, creating new cohorts from external data, and retrieving cohort metadata. It is commonly used for syncing audience segments with marketing platforms, CRMs, and other downstream tools.

**Human URL:** [https://amplitude.com/docs/apis/analytics/behavioral-cohorts](https://amplitude.com/docs/apis/analytics/behavioral-cohorts)

#### Tags:

 - Analytics, Cohorts, Segmentation, Users

#### Properties

- [Documentation](https://amplitude.com/docs/apis/analytics/behavioral-cohorts)
- [OpenAPI](openapi/amplitude-behavioral-cohorts-api-openapi.yml)

### Amplitude Taxonomy API
The Amplitude Taxonomy API provides programmatic management of your analytics tracking plan. It supports creating, reading, updating, and deleting event categories, event types, event properties, and user properties. This API is essential for data governance workflows, enabling teams to maintain a consistent and well-organized event taxonomy across their instrumentation without needing to use the Amplitude UI directly.

**Human URL:** [https://amplitude.com/docs/apis/analytics/taxonomy](https://amplitude.com/docs/apis/analytics/taxonomy)

#### Tags:

 - Analytics, Data Governance, Events, Taxonomy

#### Properties

- [Documentation](https://amplitude.com/docs/apis/analytics/taxonomy)
- [OpenAPI](openapi/amplitude-taxonomy-api-openapi.yml)

### Amplitude Attribution API
The Amplitude Attribution API allows developers to send attribution campaign events to Amplitude from ad networks, attribution providers, or custom marketing tools. It associates users with the campaigns, channels, and creatives that drove their acquisition or re-engagement. This API is used to enrich Amplitude user profiles with marketing attribution data for campaign performance analysis and ROI measurement.

**Human URL:** [https://amplitude.com/docs/apis/analytics/attribution](https://amplitude.com/docs/apis/analytics/attribution)

#### Tags:

 - Analytics, Attribution, Campaigns, Marketing

#### Properties

- [Documentation](https://amplitude.com/docs/apis/analytics/attribution)
- [OpenAPI](openapi/amplitude-attribution-api-openapi.yml)

### Amplitude Chart Annotations API
The Amplitude Chart Annotations API enables developers to programmatically create, retrieve, update, and delete annotations on Amplitude charts. Annotations mark significant events such as product releases, marketing campaigns, or incidents on timeline-based charts. This API allows teams to automate annotation management as part of their deployment or release pipelines, ensuring that important context is always visible alongside analytics data.

**Human URL:** [https://amplitude.com/docs/apis/analytics/chart-annotations](https://amplitude.com/docs/apis/analytics/chart-annotations)

#### Tags:

 - Analytics, Annotations, Charts, Reporting

#### Properties

- [Documentation](https://amplitude.com/docs/apis/analytics/chart-annotations)
- [OpenAPI](openapi/amplitude-chart-annotations-api-openapi.yml)

### Amplitude Releases API
The Amplitude Releases API allows developers to programmatically track software releases and deployments in Amplitude. By recording release events, teams can correlate product changes with analytics metrics to understand the impact of each deployment on user behavior, retention, and engagement.

**Human URL:** [https://amplitude.com/docs/apis/analytics/releases](https://amplitude.com/docs/apis/analytics/releases)

#### Tags:

 - Analytics, Deployments, Releases, Tracking

#### Properties

- [Documentation](https://amplitude.com/docs/apis/analytics/releases)

### Amplitude Session Replay API
The Amplitude Session Replay API enables developers to upload and manage session replay data for playback within Amplitude. Session replays provide qualitative insights by recording user interactions and pairing them with quantitative analytics data. This API is used for server-side ingestion of session replay events and metadata.

**Human URL:** [https://amplitude.com/docs/apis/analytics/session-replay](https://amplitude.com/docs/apis/analytics/session-replay)

#### Tags:

 - Analytics, Replay, Sessions, User Experience

#### Properties

- [Documentation](https://amplitude.com/docs/apis/analytics/session-replay)

### Amplitude User Profile API
The Amplitude User Profile API serves user profiles that include user properties, computed user properties, a list of cohort IDs the user belongs to, and personalized recommendations. It enables real-time access to enriched user data for powering personalization engines, in-app experiences, and targeted content delivery. This API is particularly useful for retrieving recommendation results generated by Amplitude's machine learning models.

**Human URL:** [https://amplitude.com/docs/apis/analytics/user-profile](https://amplitude.com/docs/apis/analytics/user-profile)

#### Tags:

 - Analytics, Profiles, Recommendations, Users

#### Properties

- [Documentation](https://amplitude.com/docs/apis/analytics/user-profile)
- [OpenAPI](openapi/amplitude-user-profile-api-openapi.yml)

### Amplitude User Mapping API
The Amplitude User Mapping (Aliasing) API allows developers to merge users with different user IDs together in Amplitude. This is useful when a user initially interacts with a product anonymously and later creates an account, or when users have multiple identifiers across different systems. The API maps these distinct identities into a single unified user profile to ensure accurate analytics and attribution.

**Human URL:** [https://amplitude.com/docs/apis/analytics/user-mapping](https://amplitude.com/docs/apis/analytics/user-mapping)

#### Tags:

 - Aliasing, Analytics, Identity, Users

#### Properties

- [Documentation](https://amplitude.com/docs/apis/analytics/user-mapping)
- [OpenAPI](openapi/amplitude-user-mapping-api-openapi.yml)

### Amplitude User Privacy API
The Amplitude User Privacy API provides endpoints for managing user data in compliance with privacy regulations such as GDPR and CCPA. It supports requesting the deletion or suppression of user data by user ID or device ID, enabling organizations to fulfill data subject rights requests and maintain regulatory compliance.

**Human URL:** [https://amplitude.com/docs/apis/analytics/user-privacy](https://amplitude.com/docs/apis/analytics/user-privacy)

#### Tags:

 - Compliance, GDPR, Privacy, Users

#### Properties

- [Documentation](https://amplitude.com/docs/apis/analytics/user-privacy)

### Amplitude SCIM API
The Amplitude SCIM API implements the System for Cross-domain Identity Management (SCIM) 2.0 standard for automated user provisioning and deprovisioning. It allows identity providers such as Okta, Azure AD, and OneLogin to automatically create, update, and deactivate user accounts in Amplitude. This API is essential for enterprise organizations that need centralized user lifecycle management and compliance with security policies.

**Human URL:** [https://amplitude.com/docs/apis/analytics/scim](https://amplitude.com/docs/apis/analytics/scim)

#### Tags:

 - Access Management, Identity, Provisioning, Users

#### Properties

- [Documentation](https://amplitude.com/docs/apis/analytics/scim)
- [OpenAPI](openapi/amplitude-scim-api-openapi.yml)

### Amplitude Data Subject Access Request API
The Amplitude Data Subject Access Request (DSAR) API enables organizations to programmatically handle privacy requests in compliance with GDPR, CCPA, and other data protection regulations. It supports submitting deletion requests for user data based on user IDs or device IDs. This API allows companies to automate their privacy compliance workflows and ensure timely processing of data subject requests at scale.

**Human URL:** [https://amplitude.com/docs/apis/analytics/ccpa-dsar](https://amplitude.com/docs/apis/analytics/ccpa-dsar)

#### Tags:

 - CCPA, Compliance, GDPR, Privacy

#### Properties

- [Documentation](https://amplitude.com/docs/apis/analytics/ccpa-dsar)
- [OpenAPI](openapi/amplitude-dsar-api-openapi.yml)

### Amplitude Experiment Evaluation API
The Amplitude Experiment Evaluation API retrieves variant assignment data for users through remote evaluation. When called, it evaluates targeting rules and returns the assigned variant for each active experiment or feature flag. The API also tracks assignment events automatically in Amplitude Analytics. It is used by server-side applications that need to determine which experiment variant or feature flag value to serve to a given user in real time.

**Human URL:** [https://amplitude.com/docs/apis/experiment/experiment-evaluation-api](https://amplitude.com/docs/apis/experiment/experiment-evaluation-api)

#### Tags:

 - A/B Testing, Experimentation, Feature Flags, Variants

#### Properties

- [Documentation](https://amplitude.com/docs/apis/experiment/experiment-evaluation-api)
- [OpenAPI](openapi/amplitude-experiment-evaluation-api-openapi.yml)

### Amplitude Experiment Management API
The Amplitude Experiment Management API provides programmatic control over feature flags and experiments. It supports creating, updating, activating, and archiving experiments and flags, as well as managing deployments, variants, holdout groups, and mutual exclusion groups. This API enables teams to integrate experiment lifecycle management into their CI/CD pipelines, automate flag rollouts, and manage experimentation workflows without using the Amplitude UI.

**Human URL:** [https://amplitude.com/docs/apis/experiment/experiment-management-api](https://amplitude.com/docs/apis/experiment/experiment-management-api)

#### Tags:

 - A/B Testing, Experimentation, Feature Flags, Management

#### Properties

- [Documentation](https://amplitude.com/docs/apis/experiment/experiment-management-api)
- [OpenAPI](openapi/amplitude-experiment-management-api-openapi.yml)

## Common Properties

- [Portal](https://amplitude.com)
- [Documentation](https://amplitude.com/docs)
- [GettingStarted](https://amplitude.com/docs/get-started)
- [Authentication](https://amplitude.com/docs/apis/authentication)
- [SDK](https://amplitude.com/docs/sdks)
- [GitHubOrganization](https://github.com/amplitude)
- [Blog](https://amplitude.com/blog)
- [Academy](https://academy.amplitude.com)
- [Support](https://help.amplitude.com)
- [Pricing](https://amplitude.com/pricing)
- [StatusPage](https://status.amplitude.com)
- [TermsOfService](https://amplitude.com/terms)
- [PrivacyPolicy](https://amplitude.com/privacy)
- [JSONLD](json-ld/amplitude-context.jsonld)
- [JSONSchema](json-schema/amplitude-event-schema.json)
- [JSONSchema](json-schema/amplitude-cohort-schema.json)
- [JSONSchema](json-schema/amplitude-experiment-schema.json)
- [SpectralRules](rules/amplitude-spectral-rules.yml)
- [Vocabulary](vocabulary/amplitude-vocabulary.yaml)
- [NaftikoCapability](capabilities/amplitude-analytics-ingestion.yaml)
- [NaftikoCapability](capabilities/amplitude-data-export-and-cohorts.yaml)
- [NaftikoCapability](capabilities/amplitude-experimentation.yaml)
- [NaftikoCapability](capabilities/amplitude-governance-and-taxonomy.yaml)
- [NaftikoCapability](capabilities/amplitude-identity-and-privacy.yaml)
- [JSONStructure](json-structure/behavioral-cohorts-api-cohort-request-response-structure.json)
- [JSONStructure](json-structure/dashboard-rest-api-user-search-result-structure.json)
- [JSONStructure](json-structure/scim-api-scim-group-request-structure.json)
- [JSONStructure](json-structure/http-v2-api-event-structure.json)
- [JSONStructure](json-structure/experiment-evaluation-api-flag-configuration-structure.json)

## Features

| Name | Description |
|------|-------------|
| Event Ingestion | High-throughput server-side and client-side event ingestion via HTTP V2 and Batch APIs. |
| User Analytics | Track user properties, behaviors, and cohorts for deep segmentation and reporting. |
| A/B Experimentation | Run feature flag experiments and measure variant impact on key metrics. |
| Behavioral Cohorts | Define and sync audience segments based on user behavioral patterns. |
| Taxonomy Management | Programmatically manage event schemas, properties, and data governance rules. |
| Data Export | Export raw event data in bulk for warehousing and offline analysis. |
| Session Replay | Capture and replay user sessions for qualitative UX research. |
| Identity Management | SCIM-based provisioning, user aliasing, and identity merging across systems. |
| Privacy Compliance | GDPR and CCPA compliant data deletion and suppression APIs. |
| Attribution Tracking | Associate users with acquisition campaigns from ad networks and marketing tools. |

## Use Cases

| Name | Description |
|------|-------------|
| Product Analytics | Understand how users interact with your product to prioritize features and reduce churn. |
| Growth Experimentation | Run controlled A/B tests to measure the causal impact of product changes. |
| Marketing Attribution | Track campaign performance and ROI by connecting acquisition events to user behavior. |
| Data Warehouse Integration | Export raw event data to Snowflake, BigQuery, or Redshift for custom analysis. |
| Audience Syndication | Sync behavioral cohorts to ad platforms and CRMs for targeted marketing. |
| Compliance Automation | Automate GDPR and CCPA data deletion workflows for privacy compliance. |
| Enterprise Identity Management | Automate user provisioning and deprovisioning via SCIM integration with IdPs. |

## Integrations

| Name | Description |
|------|-------------|
| Segment | Route events from Segment's customer data platform to Amplitude. |
| Snowflake | Export raw event data directly into Snowflake for warehouse-native analytics. |
| BigQuery | Sync Amplitude data with Google BigQuery for custom SQL analysis. |
| Salesforce | Enrich Salesforce CRM records with Amplitude behavioral cohort data. |
| HubSpot | Sync audience cohorts from Amplitude to HubSpot for marketing automation. |
| Braze | Power personalized messaging campaigns using Amplitude behavioral cohorts. |
| Okta | Automate user provisioning in Amplitude via Okta using the SCIM API. |
| Slack | Receive automated alerts and chart embeds from Amplitude in Slack channels. |

## Artifacts

Machine-readable API specifications organized by format.

### OpenAPI

- [Amplitude Attribution Api](openapi/amplitude-attribution-api-openapi.yml)
- [Amplitude Behavioral Cohorts Api](openapi/amplitude-behavioral-cohorts-api-openapi.yml)
- [Amplitude Chart Annotations Api](openapi/amplitude-chart-annotations-api-openapi.yml)
- [Amplitude Dashboard Rest Api](openapi/amplitude-dashboard-rest-api-openapi.yml)
- [Amplitude Dsar Api](openapi/amplitude-dsar-api-openapi.yml)
- [Amplitude Experiment Evaluation Api](openapi/amplitude-experiment-evaluation-api-openapi.yml)
- [Amplitude Experiment Management Api](openapi/amplitude-experiment-management-api-openapi.yml)
- [Amplitude Export Api](openapi/amplitude-export-api-openapi.yml)
- [Amplitude Http V2 Api](openapi/amplitude-http-v2-api-openapi.yml)
- [Amplitude Identify Api](openapi/amplitude-identify-api-openapi.yml)
- [Amplitude Scim Api](openapi/amplitude-scim-api-openapi.yml)
- [Amplitude Taxonomy Api](openapi/amplitude-taxonomy-api-openapi.yml)
- [Amplitude User Mapping Api](openapi/amplitude-user-mapping-api-openapi.yml)
- [Amplitude User Profile Api](openapi/amplitude-user-profile-api-openapi.yml)

### JSON Schema

- [Amplitude Cohort](json-schema/amplitude-cohort-schema.json)
- [Amplitude Event](json-schema/amplitude-event-schema.json)
- [Amplitude Experiment](json-schema/amplitude-experiment-schema.json)
- [Attribution Api Attribution Event](json-schema/attribution-api-attribution-event-schema.json)
- [Attribution Api Attribution Request](json-schema/attribution-api-attribution-request-schema.json)
- [Attribution Api Attribution Response](json-schema/attribution-api-attribution-response-schema.json)
- [Behavioral Cohorts Api Cohort List Response](json-schema/behavioral-cohorts-api-cohort-list-response-schema.json)
- [Behavioral Cohorts Api Cohort Request Response](json-schema/behavioral-cohorts-api-cohort-request-response-schema.json)
- [Behavioral Cohorts Api Cohort](json-schema/behavioral-cohorts-api-cohort-schema.json)
- [Behavioral Cohorts Api Cohort Status Response](json-schema/behavioral-cohorts-api-cohort-status-response-schema.json)
- ...and 67 more

### JSON Structure

- [Amplitude Cohort](json-structure/amplitude-cohort-structure.json)
- [Amplitude Event](json-structure/amplitude-event-structure.json)
- [Amplitude Experiment](json-structure/amplitude-experiment-structure.json)
- [Attribution Api Attribution Event](json-structure/attribution-api-attribution-event-structure.json)
- [Attribution Api Attribution Request](json-structure/attribution-api-attribution-request-structure.json)
- ...and 72 more

### JSON-LD

- [Amplitude Amplitude Cohort](json-ld/amplitude-amplitude-cohort-context.jsonld)
- [Amplitude Amplitude Event](json-ld/amplitude-amplitude-event-context.jsonld)
- [Amplitude Amplitude Experiment](json-ld/amplitude-amplitude-experiment-context.jsonld)
- [Amplitude Attribution Api](json-ld/amplitude-attribution-api-context.jsonld)
- [Amplitude Behavioral Cohorts Api](json-ld/amplitude-behavioral-cohorts-api-context.jsonld)
- [Amplitude Chart Annotations Api](json-ld/amplitude-chart-annotations-api-context.jsonld)
- [Amplitude](json-ld/amplitude-context.jsonld)
- [Amplitude Dashboard Rest Api](json-ld/amplitude-dashboard-rest-api-context.jsonld)
- [Amplitude Dsar Api](json-ld/amplitude-dsar-api-context.jsonld)
- [Amplitude Experiment Evaluation Api](json-ld/amplitude-experiment-evaluation-api-context.jsonld)
- [Amplitude Experiment Management Api](json-ld/amplitude-experiment-management-api-context.jsonld)
- [Amplitude Http V2 Api](json-ld/amplitude-http-v2-api-context.jsonld)
- [Amplitude Identify Api](json-ld/amplitude-identify-api-context.jsonld)
- [Amplitude Scim Api](json-ld/amplitude-scim-api-context.jsonld)
- [Amplitude Taxonomy Api](json-ld/amplitude-taxonomy-api-context.jsonld)
- [Amplitude User Mapping Api](json-ld/amplitude-user-mapping-api-context.jsonld)
- [Amplitude User Profile Api](json-ld/amplitude-user-profile-api-context.jsonld)

### Examples

- [Amplitude Cohort](examples/amplitude-cohort-example.json)
- [Amplitude Event](examples/amplitude-event-example.json)
- [Amplitude Experiment](examples/amplitude-experiment-example.json)
- [Attribution Api Attribution Event](examples/attribution-api-attribution-event-example.json)
- [Attribution Api Attribution Request](examples/attribution-api-attribution-request-example.json)
- [Attribution Api Attribution Response](examples/attribution-api-attribution-response-example.json)
- [Behavioral Cohorts Api Cohort](examples/behavioral-cohorts-api-cohort-example.json)
- [Behavioral Cohorts Api Cohort List Response](examples/behavioral-cohorts-api-cohort-list-response-example.json)
- ...and 69 more

## Capabilities

Naftiko capabilities organized as shared per-API definitions composed into customer-facing workflows.

### Shared Per-API Definitions

- [Attribution Api](capabilities/shared/attribution-api.yaml) — 1 operations
- [Behavioral Cohorts Api](capabilities/shared/behavioral-cohorts-api.yaml) — 5 operations
- [Chart Annotations Api](capabilities/shared/chart-annotations-api.yaml) — 5 operations
- [Dashboard Rest Api](capabilities/shared/dashboard-rest-api.yaml) — 7 operations
- [Dsar Api](capabilities/shared/dsar-api.yaml) — 4 operations
- [Experiment Evaluation Api](capabilities/shared/experiment-evaluation-api.yaml) — 3 operations
- [Experiment Management Api](capabilities/shared/experiment-management-api.yaml) — 11 operations
- [Export Api](capabilities/shared/export-api.yaml) — 1 operations
- [Http V2 Api](capabilities/shared/http-v2-api.yaml) — 1 operations
- [Identify Api](capabilities/shared/identify-api.yaml) — 1 operations
- [Scim Api](capabilities/shared/scim-api.yaml) — 11 operations
- [Taxonomy Api](capabilities/shared/taxonomy-api.yaml) — 20 operations
- [User Mapping Api](capabilities/shared/user-mapping-api.yaml) — 2 operations
- [User Profile Api](capabilities/shared/user-profile-api.yaml) — 1 operations

### Workflow Capabilities

| Workflow | Tools | Description |
|----------|-------|-------------|
| [Amplitude Analytics Ingestion](capabilities/amplitude-analytics-ingestion.yaml) | 3 | Unified workflow for sending events and identifying users. For data engineers.... |
| [Amplitude Data Export and Cohorts](capabilities/amplitude-data-export-and-cohorts.yaml) | 13 | Export raw event data and manage behavioral cohorts. For data analysts.... |
| [Amplitude Experimentation](capabilities/amplitude-experimentation.yaml) | 14 | Manage and evaluate A/B experiments and feature flags. For product managers.... |
| [Amplitude Governance and Taxonomy](capabilities/amplitude-governance-and-taxonomy.yaml) | 26 | Manage event schemas and chart annotations. For data governance teams.... |
| [Amplitude Identity and Privacy](capabilities/amplitude-identity-and-privacy.yaml) | 17 | SCIM provisioning and privacy compliance. For IT admins and compliance teams.... |

## Vocabulary

- [Amplitude Vocabulary](vocabulary/amplitude-vocabulary.yaml) — Unified taxonomy mapping 15 resources, 10 actions, 5 workflows, and 4 personas

## Rules

- [Amplitude Spectral Rules](rules/amplitude-spectral-rules.yml) — 23 rules enforcing Amplitude API conventions

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
