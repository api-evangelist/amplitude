# Amplitude (amplitude)
Amplitude is a digital analytics platform that helps teams understand user behavior across web and mobile products. Their developer platform provides a comprehensive suite of APIs for event ingestion, data export, user identity management, experimentation, and privacy compliance, enabling programmatic access to analytics, feature flagging, and audience segmentation capabilities.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/amplitude/refs/heads/main/apis.yml)

## Scope

- **Type:** Contract
- **Position:** Consuming
- **Access:** 3rd-Party

## Tags:

 - Analytics, Events, Experimentation, Feature Flags, User Behavior

## Timestamps

- **Created:** 2025-03-01
- **Modified:** 2026-03-20

## APIs

### Amplitude HTTP V2 API
The Amplitude HTTP V2 API enables developers to send event data directly from servers or clients to Amplitude's analytics platform. It supports uploading individual or batched events along with user properties, event properties, and group properties. This API is the primary method for server-side event ingestion and is designed for high-throughput data collection with built-in validation and error reporting.

**Human URL:** [https://amplitude.com/docs/apis/analytics/http-v2](https://amplitude.com/docs/apis/analytics/http-v2)


#### Tags:

 - Analytics, Events, Tracking, Ingestion

#### Properties

- [Documentation](https://amplitude.com/docs/apis/analytics/http-v2)
- [OpenAPI](openapi/amplitude-http-v2-api-openapi.yml)

### Amplitude Identify API
The Amplitude Identify API allows developers to update user properties for a specific user without needing to send an accompanying event. This is useful for setting or modifying user attributes such as demographics, subscription status, or preferences outside of the normal event tracking flow. The API supports operations like set, unset, append, and prepend on user properties.

**Human URL:** [https://amplitude.com/docs/apis/analytics/identify](https://amplitude.com/docs/apis/analytics/identify)


#### Tags:

 - Analytics, Users, Properties, Identity

#### Properties

- [Documentation](https://amplitude.com/docs/apis/analytics/identify)
- [OpenAPI](openapi/amplitude-identify-api-openapi.yml)

### Amplitude Dashboard REST API
The Amplitude Dashboard REST API provides programmatic access to the same data displayed in Amplitude's dashboard charts and graphs. It returns results in JSON format and supports queries filtered by event types, user segments, cohorts, and date ranges. Developers can use this API to build custom reporting tools, export chart data, or integrate Amplitude analytics into external dashboards and business intelligence systems.

**Human URL:** [https://amplitude.com/docs/apis/analytics/dashboard-rest](https://amplitude.com/docs/apis/analytics/dashboard-rest)


#### Tags:

 - Analytics, Dashboards, Reporting, Metrics

#### Properties

- [Documentation](https://amplitude.com/docs/apis/analytics/dashboard-rest)
- [OpenAPI](openapi/amplitude-dashboard-rest-api-openapi.yml)

### Amplitude Export API
The Amplitude Export API enables bulk export of raw event data for a given project within a specified date range. Results are returned as zipped archives of JSON files containing complete event records with timestamps, user properties, device information, and attribution data. This API is commonly used for data warehousing, offline analysis, and feeding event data into external processing pipelines.

**Human URL:** [https://amplitude.com/docs/apis/analytics/export](https://amplitude.com/docs/apis/analytics/export)


#### Tags:

 - Analytics, Export, Events, Data

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

 - Analytics, Taxonomy, Events, Data Governance

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

### Amplitude User Profile API
The Amplitude User Profile API serves user profiles that include user properties, computed user properties, a list of cohort IDs the user belongs to, and personalized recommendations. It enables real-time access to enriched user data for powering personalization engines, in-app experiences, and targeted content delivery. This API is particularly useful for retrieving recommendation results generated by Amplitude's machine learning models.

**Human URL:** [https://amplitude.com/docs/apis/analytics/user-profile](https://amplitude.com/docs/apis/analytics/user-profile)


#### Tags:

 - Analytics, Users, Profiles, Recommendations

#### Properties

- [Documentation](https://amplitude.com/docs/apis/analytics/user-profile)
- [OpenAPI](openapi/amplitude-user-profile-api-openapi.yml)

### Amplitude User Mapping API
The Amplitude User Mapping (Aliasing) API allows developers to merge users with different user IDs together in Amplitude. This is useful when a user initially interacts with a product anonymously and later creates an account, or when users have multiple identifiers across different systems. The API maps these distinct identities into a single unified user profile to ensure accurate analytics and attribution.

**Human URL:** [https://amplitude.com/docs/apis/analytics/user-mapping](https://amplitude.com/docs/apis/analytics/user-mapping)


#### Tags:

 - Analytics, Users, Identity, Aliasing

#### Properties

- [Documentation](https://amplitude.com/docs/apis/analytics/user-mapping)
- [OpenAPI](openapi/amplitude-user-mapping-api-openapi.yml)

### Amplitude SCIM API
The Amplitude SCIM API implements the System for Cross-domain Identity Management (SCIM) 2.0 standard for automated user provisioning and deprovisioning. It allows identity providers such as Okta, Azure AD, and OneLogin to automatically create, update, and deactivate user accounts in Amplitude. This API is essential for enterprise organizations that need centralized user lifecycle management and compliance with security policies.

**Human URL:** [https://amplitude.com/docs/apis/analytics/scim](https://amplitude.com/docs/apis/analytics/scim)


#### Tags:

 - Identity, Provisioning, Users, Access Management

#### Properties

- [Documentation](https://amplitude.com/docs/apis/analytics/scim)
- [OpenAPI](openapi/amplitude-scim-api-openapi.yml)

### Amplitude Data Subject Access Request API
The Amplitude Data Subject Access Request (DSAR) API enables organizations to programmatically handle privacy requests in compliance with GDPR, CCPA, and other data protection regulations. It supports submitting deletion requests for user data based on user IDs or device IDs. This API allows companies to automate their privacy compliance workflows and ensure timely processing of data subject requests at scale.

**Human URL:** [https://amplitude.com/docs/apis/analytics/ccpa-dsar](https://amplitude.com/docs/apis/analytics/ccpa-dsar)


#### Tags:

 - Privacy, Compliance, GDPR, CCPA

#### Properties

- [Documentation](https://amplitude.com/docs/apis/analytics/ccpa-dsar)
- [OpenAPI](openapi/amplitude-dsar-api-openapi.yml)

### Amplitude Experiment Evaluation API
The Amplitude Experiment Evaluation API retrieves variant assignment data for users through remote evaluation. When called, it evaluates targeting rules and returns the assigned variant for each active experiment or feature flag. The API also tracks assignment events automatically in Amplitude Analytics. It is used by server-side applications that need to determine which experiment variant or feature flag value to serve to a given user in real time.

**Human URL:** [https://amplitude.com/docs/apis/experiment/experiment-evaluation-api](https://amplitude.com/docs/apis/experiment/experiment-evaluation-api)


#### Tags:

 - Experimentation, Feature Flags, A/B Testing, Variants

#### Properties

- [Documentation](https://amplitude.com/docs/apis/experiment/experiment-evaluation-api)
- [OpenAPI](openapi/amplitude-experiment-evaluation-api-openapi.yml)

### Amplitude Experiment Management API
The Amplitude Experiment Management API provides programmatic control over feature flags and experiments. It supports creating, updating, activating, and archiving experiments and flags, as well as managing deployments, variants, holdout groups, and mutual exclusion groups. This API enables teams to integrate experiment lifecycle management into their CI/CD pipelines, automate flag rollouts, and manage experimentation workflows without using the Amplitude UI.

**Human URL:** [https://amplitude.com/docs/apis/experiment/experiment-management-api](https://amplitude.com/docs/apis/experiment/experiment-management-api)


#### Tags:

 - Experimentation, Feature Flags, A/B Testing, Management

#### Properties

- [Documentation](https://amplitude.com/docs/apis/experiment/experiment-management-api)
- [OpenAPI](openapi/amplitude-experiment-management-api-openapi.yml)

## Common Properties

- [Portal](https://amplitude.com/docs/apis)
- [Documentation](https://amplitude.com/docs)
- [Website](https://amplitude.com)
- [PrivacyPolicy](https://amplitude.com/privacy)
- [TermsOfService](https://amplitude.com/terms)
- [Support](https://help.amplitude.com)
- [Blog](https://amplitude.com/blog)
- [Login](https://app.amplitude.com)

## Maintainers

**FN:** API Evangelist

**Email:** info@apievangelist.com
