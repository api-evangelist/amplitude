# Amplitude GraphQL

## Overview

**Provider:** Amplitude  
**Native GraphQL:** No  
**Schema Type:** Conceptual data model derived from Amplitude REST APIs  
**Docs:** https://www.docs.developers.amplitude.com/  
**GitHub:** https://github.com/amplitude  

## Description

Amplitude does not expose a native public GraphQL endpoint. This schema is a conceptual GraphQL representation of the Amplitude analytics platform data model, derived from the full surface area of Amplitude's REST APIs including the HTTP V2 API, Batch Event Upload API, Identify API, Group Identify API, Dashboard REST API, Export API, Behavioral Cohorts API, Taxonomy API, Attribution API, Chart Annotations API, Releases API, Session Replay API, User Profile API, User Mapping API, User Privacy API, SCIM API, DSAR API, Experiment Evaluation API, and Experiment Management API.

This schema is valuable for:
- Tooling and catalog enrichment
- Code generation targeting Amplitude's data shapes
- API gateway and middleware layers that proxy Amplitude REST calls behind a GraphQL interface
- Data modeling reference for downstream consumers (warehouses, BI tools, ETL pipelines)

## Core Domains

| Domain | Key Types |
|---|---|
| Ingestion | Event, EventBatch, EventProperty, UserProperty, GroupProperty |
| Identity | UserProfile, UserIdentity, UserMapping, GroupIdentity |
| Cohorts | Cohort, CohortMembership, CohortExport |
| Taxonomy | EventType, EventCategory, TaxonomyEventProperty, TaxonomyUserProperty, PropertyValue |
| Analytics | Chart, Dashboard, Annotation, Segmentation, Funnel, Retention, GroupBy, Filter, Breakout, Session |
| Experimentation | Experiment, Flag, Variant, Exposure, Assignment, MetricResult, HoldoutGroup, DeploymentConfig |
| Data Export | DataExport, TransformedEvent, BlockedEvent, RevenueEvent, FormattedEvent |
| Privacy | PrivacyDeletionRequest, DSARRequest |
| Access | SCIMUser, SCIMGroup |
| Attribution | AttributionEvent |

## Endpoint

No native GraphQL endpoint exists. To use this schema operationally, deploy a GraphQL-to-REST proxy layer (e.g., using StepZen, Hasura Remote Schema, or Apollo Connector) pointed at Amplitude's REST base URLs:

- `https://api2.amplitude.com` — ingestion, identify, attribution
- `https://amplitude.com` — dashboard, export, cohorts, taxonomy, annotations, privacy
- `https://profile-api.amplitude.com` — user profiles
- `https://api.lab.amplitude.com` — experiment evaluation
- `https://experiment.amplitude.com` — experiment management
- `https://analytics.amplitude.com` — SCIM provisioning
