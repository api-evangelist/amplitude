# Amplitude (amplitude)

Amplitude is a digital analytics platform that helps product teams understand user behavior, run experiments, and drive growth. It provides a suite of APIs for event ingestion, user management, cohort syncing, taxonomy governance, A/B testing, and data export. Amplitude is widely used by product, data, and engineering teams to build better digital experiences through data-driven insights.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/amplitude/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/amplitude/refs/heads/main/apis.yml)

## Tags

- A/B Testing
- Analytics
- Experimentation
- Feature Flags
- Product Analytics
- User Behavior

## Timestamps

- **Modified:** 2026-05-30

## APIs

### Amplitude HTTP V2 API

The Amplitude HTTP V2 API enables developers to send event data directly from servers or clients to Amplitude's analytics platform. It supports uploading individual or batched events along with user properties, event properties, and group properties. This API is the primary method for server-side event ingestion and is designed for high-throughput data collection with built-in validation and error reporting.

- **Human URL:** [https://amplitude.com/docs/apis/analytics/http-v2](https://amplitude.com/docs/apis/analytics/http-v2)
- **Base URL:** `https://api2.amplitude.com`

#### Tags

- Analytics
- Events
- Ingestion
- Tracking

#### Properties

- [Documentation](https://amplitude.com/docs/apis/analytics/http-v2)
- [OpenAPI](openapi/amplitude-http-v2-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/amplitude-http-v2-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/amplitude-http-v2-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Amplitude Batch Event Upload API

The Amplitude Batch Event Upload API is optimized for high-volume server-side event ingestion. It accepts batches of events up to 20MB per request and is designed for use cases where data volume may exceed the limits of the standard HTTP V2 API. The API uses the same event structure as the HTTP V2 API and is recommended for data pipelines processing millions of events.

- **Human URL:** [https://amplitude.com/docs/apis/analytics/batch-event-upload](https://amplitude.com/docs/apis/analytics/batch-event-upload)
- **Base URL:** `https://api2.amplitude.com`

#### Tags

- Analytics
- Batch
- Events
- Ingestion

#### Properties

- [Documentation](https://amplitude.com/docs/apis/analytics/batch-event-upload)
- [Postman Collection](collections/amplitude-attribution-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/amplitude-attribution-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/amplitude-behavioral-cohorts-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/amplitude-behavioral-cohorts-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/amplitude-chart-annotations-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/amplitude-chart-annotations-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/amplitude-dashboard-rest-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/amplitude-dashboard-rest-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/amplitude-dsar-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/amplitude-dsar-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/amplitude-experiment-evaluation-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/amplitude-experiment-evaluation-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/amplitude-experiment-management-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/amplitude-experiment-management-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/amplitude-export-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/amplitude-export-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/amplitude-http-v2-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/amplitude-http-v2-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/amplitude-identify-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/amplitude-identify-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/amplitude-scim-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/amplitude-scim-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/amplitude-taxonomy-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/amplitude-taxonomy-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/amplitude-user-mapping-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/amplitude-user-mapping-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/amplitude-user-profile-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/amplitude-user-profile-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Amplitude Identify API

The Amplitude Identify API allows developers to update user properties for a specific user without needing to send an accompanying event. This is useful for setting or modifying user attributes such as demographics, subscription status, or preferences outside of the normal event tracking flow. The API supports operations like set, unset, append, and prepend on user properties.

- **Human URL:** [https://amplitude.com/docs/apis/analytics/identify](https://amplitude.com/docs/apis/analytics/identify)
- **Base URL:** `https://api2.amplitude.com`

#### Tags

- Analytics
- Identity
- Properties
- Users

#### Properties

- [Documentation](https://amplitude.com/docs/apis/analytics/identify)
- [OpenAPI](openapi/amplitude-identify-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/amplitude-identify-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/amplitude-identify-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Amplitude Group Identify API

The Amplitude Group Identify API allows developers to set or update properties on groups within Amplitude. Groups are entities such as companies, teams, or accounts that users belong to. This API enables B2B analytics use cases by attaching account-level properties to groups for segmentation and reporting purposes.

- **Human URL:** [https://amplitude.com/docs/apis/analytics/group-identify](https://amplitude.com/docs/apis/analytics/group-identify)
- **Base URL:** `https://api2.amplitude.com`

#### Tags

- Analytics
- Groups
- Identity
- Properties

#### Properties

- [Documentation](https://amplitude.com/docs/apis/analytics/group-identify)
- [Postman Collection](collections/amplitude-attribution-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/amplitude-attribution-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/amplitude-behavioral-cohorts-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/amplitude-behavioral-cohorts-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/amplitude-chart-annotations-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/amplitude-chart-annotations-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/amplitude-dashboard-rest-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/amplitude-dashboard-rest-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/amplitude-dsar-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/amplitude-dsar-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/amplitude-experiment-evaluation-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/amplitude-experiment-evaluation-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/amplitude-experiment-management-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/amplitude-experiment-management-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/amplitude-export-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/amplitude-export-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/amplitude-http-v2-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/amplitude-http-v2-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/amplitude-identify-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/amplitude-identify-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/amplitude-scim-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/amplitude-scim-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/amplitude-taxonomy-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/amplitude-taxonomy-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/amplitude-user-mapping-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/amplitude-user-mapping-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/amplitude-user-profile-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/amplitude-user-profile-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Amplitude Dashboard REST API

The Amplitude Dashboard REST API provides programmatic access to the same data displayed in Amplitude's dashboard charts and graphs. It returns results in JSON format and supports queries filtered by event types, user segments, cohorts, and date ranges. Developers can use this API to build custom reporting tools, export chart data, or integrate Amplitude analytics into external dashboards and business intelligence systems.

- **Human URL:** [https://amplitude.com/docs/apis/analytics/dashboard-rest](https://amplitude.com/docs/apis/analytics/dashboard-rest)
- **Base URL:** `https://amplitude.com`

#### Tags

- Analytics
- Dashboards
- Metrics
- Reporting

#### Properties

- [Documentation](https://amplitude.com/docs/apis/analytics/dashboard-rest)
- [OpenAPI](openapi/amplitude-dashboard-rest-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/amplitude-dashboard-rest-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/amplitude-dashboard-rest-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Amplitude Export API

The Amplitude Export API enables bulk export of raw event data for a given project within a specified date range. Results are returned as zipped archives of JSON files containing complete event records with timestamps, user properties, device information, and attribution data. This API is commonly used for data warehousing, offline analysis, and feeding event data into external processing pipelines.

- **Human URL:** [https://amplitude.com/docs/apis/analytics/export](https://amplitude.com/docs/apis/analytics/export)
- **Base URL:** `https://amplitude.com`

#### Tags

- Analytics
- Data
- Events
- Export

#### Properties

- [Documentation](https://amplitude.com/docs/apis/analytics/export)
- [OpenAPI](openapi/amplitude-export-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/amplitude-export-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/amplitude-export-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Amplitude Behavioral Cohorts API

The Amplitude Behavioral Cohorts API allows developers to list, export, and upload cohorts in Amplitude. Cohorts are groups of users defined by shared behavioral patterns or properties. This API supports downloading cohort membership lists, creating new cohorts from external data, and retrieving cohort metadata. It is commonly used for syncing audience segments with marketing platforms, CRMs, and other downstream tools.

- **Human URL:** [https://amplitude.com/docs/apis/analytics/behavioral-cohorts](https://amplitude.com/docs/apis/analytics/behavioral-cohorts)
- **Base URL:** `https://amplitude.com`

#### Tags

- Analytics
- Cohorts
- Segmentation
- Users

#### Properties

- [Documentation](https://amplitude.com/docs/apis/analytics/behavioral-cohorts)
- [OpenAPI](openapi/amplitude-behavioral-cohorts-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/amplitude-behavioral-cohorts-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/amplitude-behavioral-cohorts-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Amplitude Taxonomy API

The Amplitude Taxonomy API provides programmatic management of your analytics tracking plan. It supports creating, reading, updating, and deleting event categories, event types, event properties, and user properties. This API is essential for data governance workflows, enabling teams to maintain a consistent and well-organized event taxonomy across their instrumentation without needing to use the Amplitude UI directly.

- **Human URL:** [https://amplitude.com/docs/apis/analytics/taxonomy](https://amplitude.com/docs/apis/analytics/taxonomy)
- **Base URL:** `https://amplitude.com`

#### Tags

- Analytics
- Data Governance
- Events
- Taxonomy

#### Properties

- [Documentation](https://amplitude.com/docs/apis/analytics/taxonomy)
- [OpenAPI](openapi/amplitude-taxonomy-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/amplitude-taxonomy-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/amplitude-taxonomy-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Amplitude Attribution API

The Amplitude Attribution API allows developers to send attribution campaign events to Amplitude from ad networks, attribution providers, or custom marketing tools. It associates users with the campaigns, channels, and creatives that drove their acquisition or re-engagement. This API is used to enrich Amplitude user profiles with marketing attribution data for campaign performance analysis and ROI measurement.

- **Human URL:** [https://amplitude.com/docs/apis/analytics/attribution](https://amplitude.com/docs/apis/analytics/attribution)
- **Base URL:** `https://api2.amplitude.com`

#### Tags

- Analytics
- Attribution
- Campaigns
- Marketing

#### Properties

- [Documentation](https://amplitude.com/docs/apis/analytics/attribution)
- [OpenAPI](openapi/amplitude-attribution-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/amplitude-attribution-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/amplitude-attribution-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Amplitude Chart Annotations API

The Amplitude Chart Annotations API enables developers to programmatically create, retrieve, update, and delete annotations on Amplitude charts. Annotations mark significant events such as product releases, marketing campaigns, or incidents on timeline-based charts. This API allows teams to automate annotation management as part of their deployment or release pipelines, ensuring that important context is always visible alongside analytics data.

- **Human URL:** [https://amplitude.com/docs/apis/analytics/chart-annotations](https://amplitude.com/docs/apis/analytics/chart-annotations)
- **Base URL:** `https://amplitude.com`

#### Tags

- Analytics
- Annotations
- Charts
- Reporting

#### Properties

- [Documentation](https://amplitude.com/docs/apis/analytics/chart-annotations)
- [OpenAPI](openapi/amplitude-chart-annotations-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/amplitude-chart-annotations-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/amplitude-chart-annotations-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Amplitude Releases API

The Amplitude Releases API allows developers to programmatically track software releases and deployments in Amplitude. By recording release events, teams can correlate product changes with analytics metrics to understand the impact of each deployment on user behavior, retention, and engagement.

- **Human URL:** [https://amplitude.com/docs/apis/analytics/releases](https://amplitude.com/docs/apis/analytics/releases)
- **Base URL:** `https://amplitude.com`

#### Tags

- Analytics
- Deployments
- Releases
- Tracking

#### Properties

- [Documentation](https://amplitude.com/docs/apis/analytics/releases)
- [Postman Collection](collections/amplitude-attribution-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/amplitude-attribution-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/amplitude-behavioral-cohorts-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/amplitude-behavioral-cohorts-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/amplitude-chart-annotations-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/amplitude-chart-annotations-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/amplitude-dashboard-rest-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/amplitude-dashboard-rest-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/amplitude-dsar-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/amplitude-dsar-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/amplitude-experiment-evaluation-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/amplitude-experiment-evaluation-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/amplitude-experiment-management-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/amplitude-experiment-management-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/amplitude-export-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/amplitude-export-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/amplitude-http-v2-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/amplitude-http-v2-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/amplitude-identify-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/amplitude-identify-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/amplitude-scim-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/amplitude-scim-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/amplitude-taxonomy-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/amplitude-taxonomy-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/amplitude-user-mapping-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/amplitude-user-mapping-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/amplitude-user-profile-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/amplitude-user-profile-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Amplitude Session Replay API

The Amplitude Session Replay API enables developers to upload and manage session replay data for playback within Amplitude. Session replays provide qualitative insights by recording user interactions and pairing them with quantitative analytics data. This API is used for server-side ingestion of session replay events and metadata.

- **Human URL:** [https://amplitude.com/docs/apis/analytics/session-replay](https://amplitude.com/docs/apis/analytics/session-replay)
- **Base URL:** `https://amplitude.com`

#### Tags

- Analytics
- Replay
- Sessions
- User Experience

#### Properties

- [Documentation](https://amplitude.com/docs/apis/analytics/session-replay)
- [Postman Collection](collections/amplitude-attribution-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/amplitude-attribution-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/amplitude-behavioral-cohorts-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/amplitude-behavioral-cohorts-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/amplitude-chart-annotations-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/amplitude-chart-annotations-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/amplitude-dashboard-rest-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/amplitude-dashboard-rest-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/amplitude-dsar-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/amplitude-dsar-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/amplitude-experiment-evaluation-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/amplitude-experiment-evaluation-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/amplitude-experiment-management-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/amplitude-experiment-management-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/amplitude-export-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/amplitude-export-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/amplitude-http-v2-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/amplitude-http-v2-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/amplitude-identify-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/amplitude-identify-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/amplitude-scim-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/amplitude-scim-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/amplitude-taxonomy-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/amplitude-taxonomy-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/amplitude-user-mapping-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/amplitude-user-mapping-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/amplitude-user-profile-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/amplitude-user-profile-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Amplitude User Profile API

The Amplitude User Profile API serves user profiles that include user properties, computed user properties, a list of cohort IDs the user belongs to, and personalized recommendations. It enables real-time access to enriched user data for powering personalization engines, in-app experiences, and targeted content delivery. This API is particularly useful for retrieving recommendation results generated by Amplitude's machine learning models.

- **Human URL:** [https://amplitude.com/docs/apis/analytics/user-profile](https://amplitude.com/docs/apis/analytics/user-profile)
- **Base URL:** `https://profile-api.amplitude.com`

#### Tags

- Analytics
- Profiles
- Recommendations
- Users

#### Properties

- [Documentation](https://amplitude.com/docs/apis/analytics/user-profile)
- [OpenAPI](openapi/amplitude-user-profile-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/amplitude-user-profile-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/amplitude-user-profile-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Amplitude User Mapping API

The Amplitude User Mapping (Aliasing) API allows developers to merge users with different user IDs together in Amplitude. This is useful when a user initially interacts with a product anonymously and later creates an account, or when users have multiple identifiers across different systems. The API maps these distinct identities into a single unified user profile to ensure accurate analytics and attribution.

- **Human URL:** [https://amplitude.com/docs/apis/analytics/user-mapping](https://amplitude.com/docs/apis/analytics/user-mapping)
- **Base URL:** `https://api2.amplitude.com`

#### Tags

- Aliasing
- Analytics
- Identity
- Users

#### Properties

- [Documentation](https://amplitude.com/docs/apis/analytics/user-mapping)
- [OpenAPI](openapi/amplitude-user-mapping-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/amplitude-user-mapping-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/amplitude-user-mapping-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Amplitude User Privacy API

The Amplitude User Privacy API provides endpoints for managing user data in compliance with privacy regulations such as GDPR and CCPA. It supports requesting the deletion or suppression of user data by user ID or device ID, enabling organizations to fulfill data subject rights requests and maintain regulatory compliance.

- **Human URL:** [https://amplitude.com/docs/apis/analytics/user-privacy](https://amplitude.com/docs/apis/analytics/user-privacy)
- **Base URL:** `https://amplitude.com`

#### Tags

- Compliance
- GDPR
- Privacy
- Users

#### Properties

- [Documentation](https://amplitude.com/docs/apis/analytics/user-privacy)
- [Postman Collection](collections/amplitude-attribution-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/amplitude-attribution-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/amplitude-behavioral-cohorts-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/amplitude-behavioral-cohorts-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/amplitude-chart-annotations-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/amplitude-chart-annotations-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/amplitude-dashboard-rest-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/amplitude-dashboard-rest-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/amplitude-dsar-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/amplitude-dsar-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/amplitude-experiment-evaluation-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/amplitude-experiment-evaluation-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/amplitude-experiment-management-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/amplitude-experiment-management-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/amplitude-export-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/amplitude-export-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/amplitude-http-v2-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/amplitude-http-v2-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/amplitude-identify-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/amplitude-identify-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/amplitude-scim-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/amplitude-scim-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/amplitude-taxonomy-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/amplitude-taxonomy-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/amplitude-user-mapping-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/amplitude-user-mapping-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/amplitude-user-profile-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/amplitude-user-profile-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Amplitude SCIM API

The Amplitude SCIM API implements the System for Cross-domain Identity Management (SCIM) 2.0 standard for automated user provisioning and deprovisioning. It allows identity providers such as Okta, Azure AD, and OneLogin to automatically create, update, and deactivate user accounts in Amplitude. This API is essential for enterprise organizations that need centralized user lifecycle management and compliance with security policies.

- **Human URL:** [https://amplitude.com/docs/apis/analytics/scim](https://amplitude.com/docs/apis/analytics/scim)
- **Base URL:** `https://analytics.amplitude.com`

#### Tags

- Access Management
- Identity
- Provisioning
- Users

#### Properties

- [Documentation](https://amplitude.com/docs/apis/analytics/scim)
- [OpenAPI](openapi/amplitude-scim-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/amplitude-scim-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/amplitude-scim-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Amplitude Data Subject Access Request API

The Amplitude Data Subject Access Request (DSAR) API enables organizations to programmatically handle privacy requests in compliance with GDPR, CCPA, and other data protection regulations. It supports submitting deletion requests for user data based on user IDs or device IDs. This API allows companies to automate their privacy compliance workflows and ensure timely processing of data subject requests at scale.

- **Human URL:** [https://amplitude.com/docs/apis/analytics/ccpa-dsar](https://amplitude.com/docs/apis/analytics/ccpa-dsar)
- **Base URL:** `https://amplitude.com`

#### Tags

- CCPA
- Compliance
- GDPR
- Privacy

#### Properties

- [Documentation](https://amplitude.com/docs/apis/analytics/ccpa-dsar)
- [OpenAPI](openapi/amplitude-dsar-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/amplitude-dsar-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/amplitude-dsar-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Amplitude Experiment Evaluation API

The Amplitude Experiment Evaluation API retrieves variant assignment data for users through remote evaluation. When called, it evaluates targeting rules and returns the assigned variant for each active experiment or feature flag. The API also tracks assignment events automatically in Amplitude Analytics. It is used by server-side applications that need to determine which experiment variant or feature flag value to serve to a given user in real time.

- **Human URL:** [https://amplitude.com/docs/apis/experiment/experiment-evaluation-api](https://amplitude.com/docs/apis/experiment/experiment-evaluation-api)
- **Base URL:** `https://api.lab.amplitude.com`

#### Tags

- A/B Testing
- Experimentation
- Feature Flags
- Variants

#### Properties

- [Documentation](https://amplitude.com/docs/apis/experiment/experiment-evaluation-api)
- [OpenAPI](openapi/amplitude-experiment-evaluation-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/amplitude-experiment-evaluation-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/amplitude-experiment-evaluation-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Amplitude Experiment Management API

The Amplitude Experiment Management API provides programmatic control over feature flags and experiments. It supports creating, updating, activating, and archiving experiments and flags, as well as managing deployments, variants, holdout groups, and mutual exclusion groups. This API enables teams to integrate experiment lifecycle management into their CI/CD pipelines, automate flag rollouts, and manage experimentation workflows without using the Amplitude UI.

- **Human URL:** [https://amplitude.com/docs/apis/experiment/experiment-management-api](https://amplitude.com/docs/apis/experiment/experiment-management-api)
- **Base URL:** `https://experiment.amplitude.com`

#### Tags

- A/B Testing
- Experimentation
- Feature Flags
- Management

#### Properties

- [Documentation](https://amplitude.com/docs/apis/experiment/experiment-management-api)
- [OpenAPI](openapi/amplitude-experiment-management-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/amplitude-experiment-management-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/amplitude-experiment-management-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Amplitude Webhooks and Cohort Sync

The Webhooks Streaming destination forwards Amplitude event and user payloads to a customer-configured HTTPS endpoint, and the Cohort Sync family of destinations pushes cohort membership changes to downstream tools such as Iterable, Braze, MoEngage, Customer.io, Intercom, HubSpot, Google Ads, Bing Ads, Google Pub/Sub, Amazon Kinesis, and Amazon S3. Sync types include on-demand, automated (hourly or daily), and real-time (per-minute) modes. This AsyncAPI document models the subscriber-side HTTP contract for Webhooks Streaming and the generic cohort membership change shape; vendor-specific cohort sync destinations conform to each downstream tool's own API contract.

- **Human URL:** [https://amplitude.com/docs/data/destination-catalog/webhooks](https://amplitude.com/docs/data/destination-catalog/webhooks)

#### Tags

- Cohort Sync
- Destinations
- Events
- Streaming
- Webhooks

#### Properties

- [Documentation](https://amplitude.com/docs/data/destination-catalog/webhooks)
- [Documentation](https://amplitude.com/docs/data/destinations/syncs)
- [Documentation](https://amplitude.com/docs/data/destinations)
- [AsyncAPI](asyncapi/amplitude-webhooks-cohort-sync-asyncapi.yml) — [AsyncAPI Specification](https://www.asyncapi.com/docs/reference/specification/latest)
- [Postman Collection](collections/amplitude-attribution-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/amplitude-attribution-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/amplitude-behavioral-cohorts-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/amplitude-behavioral-cohorts-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/amplitude-chart-annotations-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/amplitude-chart-annotations-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/amplitude-dashboard-rest-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/amplitude-dashboard-rest-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/amplitude-dsar-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/amplitude-dsar-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/amplitude-experiment-evaluation-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/amplitude-experiment-evaluation-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/amplitude-experiment-management-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/amplitude-experiment-management-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/amplitude-export-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/amplitude-export-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/amplitude-http-v2-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/amplitude-http-v2-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/amplitude-identify-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/amplitude-identify-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/amplitude-scim-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/amplitude-scim-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/amplitude-taxonomy-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/amplitude-taxonomy-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/amplitude-user-mapping-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/amplitude-user-mapping-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/amplitude-user-profile-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/amplitude-user-profile-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [Arazzo Workflows](arazzo/) — [Arazzo Specification](https://spec.openapis.org/arazzo/latest.html)
- [LinkedIn](https://www.linkedin.com/company/amplitude-analytics)
- [Portal](https://amplitude.com)
- [Documentation](https://amplitude.com/docs)
- [Getting Started](https://amplitude.com/docs/get-started)
- [Authentication](https://amplitude.com/docs/apis/authentication)
- [SDK](https://amplitude.com/docs/sdks)
- [GitHub Organization](https://github.com/amplitude)
- [Blog](https://amplitude.com/blog)
- [Academy](https://academy.amplitude.com)
- [Support](https://help.amplitude.com)
- [Pricing](https://amplitude.com/pricing)
- [Status Page](https://status.amplitude.com)
- [Terms of Service](https://amplitude.com/terms)
- [Privacy Policy](https://amplitude.com/privacy)
- [JSON-LD](json-ld/amplitude-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [JSON Schema](json-schema/amplitude-event-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/amplitude-cohort-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/amplitude-experiment-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [Features](undefined)
- [Use Cases](undefined)
- [Integrations](undefined)
- [Spectral Rules](rules/amplitude-spectral-rules.yml)
- [Vocabulary](vocabulary/amplitude-vocabulary.yaml)
- [JSON Structure](json-structure/behavioral-cohorts-api-cohort-request-response-structure.json)
- [JSON Structure](json-structure/dashboard-rest-api-user-search-result-structure.json)
- [JSON Structure](json-structure/scim-api-scim-group-request-structure.json)
- [JSON Structure](json-structure/http-v2-api-event-structure.json)
- [JSON Structure](json-structure/experiment-evaluation-api-flag-configuration-structure.json)
- [Integrations](https://amplitude.com/integrations)
- [M C P Server](https://github.com/amplitude/mcp-marketplace)
- [Agent Skill](https://github.com/amplitude/builder-skills)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
