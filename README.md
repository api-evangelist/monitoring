# Monitoring (monitoring)
An index and topic collection covering API monitoring, application performance monitoring, observability, uptime monitoring, log aggregation, error tracking, distributed tracing, and incident response. API monitoring spans synthetic checks against public endpoints, real-user and application performance monitoring, logs and metrics collection, distributed tracing across microservices, error tracking, status page communication, and on-call paging when something breaks. This collection brings together commercial observability platforms like Datadog, New Relic, Dynatrace, and Splunk; open-source projects like Prometheus, Grafana, OpenTelemetry, Jaeger, and Zipkin; uptime and synthetic monitoring services like Pingdom, Checkly, Better Stack, and UptimeRobot; error trackers like Sentry, Rollbar, Bugsnag, and Honeybadger; and incident response platforms like PagerDuty, Opsgenie, Incident.io, and FireHydrant.

**URL:** [https://apievangelist.com](https://apievangelist.com)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - API Monitoring, Observability, Uptime, Synthetic Monitoring, Incident Response

## Timestamps

- **Created:** 2026-05-19
- **Modified:** 2026-05-19

## Common Properties

- [Portal](https://apievangelist.com)
- [GitHubOrganization](https://github.com/api-evangelist)
- [JSONSchema - Synthetic Check Schema](https://raw.githubusercontent.com/api-evangelist/monitoring/refs/heads/main/json-schema/monitoring-synthetic-check-schema.json)
- [JSONSchema - Incident Schema](https://raw.githubusercontent.com/api-evangelist/monitoring/refs/heads/main/json-schema/monitoring-incident-schema.json)
- [JSON-LD](https://raw.githubusercontent.com/api-evangelist/monitoring/refs/heads/main/json-ld/monitoring-context.jsonld)
- [Vocabulary](https://raw.githubusercontent.com/api-evangelist/monitoring/refs/heads/main/vocabulary/monitoring-vocabulary.yaml)

## Features

| Name | Description |
|------|-------------|
| Synthetic and Uptime Monitoring | Scheduled checks executed from globally distributed probes that hit HTTP, GraphQL, and gRPC endpoints to verify availability, response codes, latency, and content assertions before real users are affected. |
| Application Performance Monitoring (APM) | Instrumentation of application code to capture request rates, latency percentiles, error rates, throughput, and slow endpoints across services, with code-level visibility into bottlenecks. |
| Distributed Tracing | End-to-end traces that follow a single request across microservice boundaries, captured via OpenTelemetry, Jaeger, Zipkin, or vendor SDKs to expose where latency and errors accumulate in distributed systems. |
| Log Aggregation and Search | Centralized collection, indexing, and search of structured and unstructured logs from applications, infrastructure, and edge components, with retention tiers and query languages for incident investigation. |
| Metrics and Time-Series | Collection of dimensional metrics from infrastructure, runtimes, and custom application counters into time-series databases like Prometheus, VictoriaMetrics, or vendor backends for dashboards and alerting. |
| Error and Crash Tracking | Capture of exceptions, stack traces, and user context from frontends and backends, with deduplication, regression detection, and release tracking provided by tools like Sentry, Rollbar, Bugsnag, and Honeybadger. |
| Alerting and Incident Response | Threshold and anomaly-based alerts that flow into on-call rotations, escalation policies, and incident workflows handled by PagerDuty, Opsgenie, Incident.io, FireHydrant, and similar platforms. |
| Status Pages and Communication | Public and private status pages that communicate incident status, scheduled maintenance, and component health to customers and stakeholders during and after incidents. |

## Use Cases

| Name | Description |
|------|-------------|
| External API Uptime Monitoring | Operate scheduled synthetic checks against public APIs from multiple regions to verify endpoint availability, TLS validity, and latency, and alert on regressions before customers report them. |
| Microservice Performance Troubleshooting | Use distributed tracing and APM to follow slow or failing requests across microservices, identify the responsible span, and correlate with logs and metrics from the same time window. |
| SRE Service Level Objective Tracking | Define and track service level indicators and objectives using tools like Nobl9, Datadog, and Prometheus, computing error budgets and burn rates against availability and latency targets. |
| On-Call Paging and Escalation | Route alerts from monitoring systems to the right on-call engineer with PagerDuty, Opsgenie, or Squadcast, including escalation policies, schedule rotations, and acknowledgement tracking. |
| Incident Response and Postmortems | Coordinate incident response with platforms like Incident.io, FireHydrant, and Rootly that open Slack channels, assign roles, track timelines, and generate postmortem documents. |
| Frontend Error and Session Monitoring | Capture frontend exceptions, console errors, network failures, and replayable user sessions with Sentry, LogRocket, OpenReplay, and Bugsnag to diagnose customer-facing bugs. |
| Status Page Communication | Publish real-time status of API components on Statuspage, Better Stack, or OneUptime so customers and integrators know when degradations and outages affect them. |
| Cost-Optimized Log Pipelines | Use observability pipelines like Cribl, Vector, and Fluent Bit to route, transform, and tier log data before it lands in expensive indexing backends, reducing observability spend. |

## Integrations

| Name | Description |
|------|-------------|
| Datadog | SaaS observability platform combining metrics, traces, logs, RUM, synthetic monitoring, and security signals in a single backend. |
| New Relic | Full-stack observability platform offering APM, infrastructure monitoring, logs, browser, mobile, and synthetic monitoring under a unified pricing model. |
| PagerDuty | Incident response platform that ingests alerts from monitoring tools and routes them through on-call schedules, escalation policies, and incident workflows. |
| Sentry | Open-source error tracking and performance monitoring for frontends and backends with release tracking, source maps, and issue triage. |
| Prometheus | Open-source dimensional metrics database with a pull-based scraper, PromQL query language, and a foundational role in Kubernetes observability stacks. |
| Grafana | Open-source dashboarding and alerting frontend that visualizes data from Prometheus, Loki, Tempo, and dozens of other data sources. |
| OpenTelemetry | CNCF specification, SDKs, and collector for emitting traces, metrics, and logs in a vendor-neutral format to any compatible backend. |
| Statuspage | Atlassian-hosted status page service used by API providers to communicate component status, incidents, and scheduled maintenance to customers. |

## Artifacts

Machine-readable API specifications organized by format.

### JSON Schema

- [Synthetic Check Schema](json-schema/monitoring-synthetic-check-schema.json)
- [Incident Schema](json-schema/monitoring-incident-schema.json)

### JSON Structure

- [Synthetic Check Structure](json-structure/monitoring-synthetic-check-structure.json)
- [Incident Structure](json-structure/monitoring-incident-structure.json)

### JSON-LD

- [Monitoring Context](json-ld/monitoring-context.jsonld)

## Vocabulary

- [Monitoring Vocabulary](vocabulary/monitoring-vocabulary.yaml) — Unified taxonomy mapping resources, actions, workflows, and personas across API monitoring, observability, and incident response

## Network

This index references the following API monitoring, observability, and incident response repositories:

- [Airbrake](https://github.com/api-evangelist/airbrake)
- [Amazon CloudWatch](https://github.com/api-evangelist/aws-cloudwatch)
- [AppDynamics](https://github.com/api-evangelist/appdynamics)
- [APIToolkit](https://github.com/api-evangelist/apitoolkit)
- [Assertible](https://github.com/api-evangelist/assertible)
- [Axiom](https://github.com/api-evangelist/axiom)
- [Azure Monitor](https://github.com/api-evangelist/microsoft-azure-monitor)
- [Better Stack](https://github.com/api-evangelist/better-stack)
- [BigPanda](https://github.com/api-evangelist/bigpanda)
- [Bugsnag](https://github.com/api-evangelist/bugsnag)
- [Checkly](https://github.com/api-evangelist/checkly)
- [Chronosphere](https://github.com/api-evangelist/chronosphere)
- [Coralogix](https://github.com/api-evangelist/coralogix)
- [Cribl](https://github.com/api-evangelist/cribl)
- [Datadog](https://github.com/api-evangelist/datadog)
- [Dynatrace](https://github.com/api-evangelist/dynatrace)
- [Elastic Observability](https://github.com/api-evangelist/elastic-observability)
- [FireHydrant](https://github.com/api-evangelist/firehydrant)
- [Google Cloud Monitoring](https://github.com/api-evangelist/google-cloud-monitoring)
- [Grafana](https://github.com/api-evangelist/grafana)
- [Graylog](https://github.com/api-evangelist/graylog)
- [Honeybadger](https://github.com/api-evangelist/honeybadger)
- [Honeycomb](https://github.com/api-evangelist/honeycomb)
- [Incident.io](https://github.com/api-evangelist/incident-io)
- [Instana](https://github.com/api-evangelist/instana)
- [Jaeger](https://github.com/api-evangelist/jaeger)
- [Lightstep](https://github.com/api-evangelist/lightstep)
- [LogicMonitor](https://github.com/api-evangelist/logicmonitor)
- [LogRocket](https://github.com/api-evangelist/logrocket)
- [Middleware](https://github.com/api-evangelist/middleware)
- [Moogsoft](https://github.com/api-evangelist/moogsoft)
- [Nagios](https://github.com/api-evangelist/nagios)
- [New Relic](https://github.com/api-evangelist/new-relic)
- [Nobl9](https://github.com/api-evangelist/nobl9)
- [NodePing](https://github.com/api-evangelist/nodeping)
- [OneUptime](https://github.com/api-evangelist/oneuptime)
- [OpenObserve](https://github.com/api-evangelist/openobserve)
- [OpenReplay](https://github.com/api-evangelist/openreplay)
- [OpenTelemetry](https://github.com/api-evangelist/opentelemetry)
- [OpsGenie](https://github.com/api-evangelist/opsgenie)
- [PagerDuty](https://github.com/api-evangelist/pagerduty)
- [Pingdom](https://github.com/api-evangelist/pingdom)
- [Prometheus](https://github.com/api-evangelist/prometheus)
- [Rollbar](https://github.com/api-evangelist/rollbar)
- [Rootly](https://github.com/api-evangelist/rootly)
- [Sentry](https://github.com/api-evangelist/sentry)
- [SigNoz](https://github.com/api-evangelist/signoz)
- [SIGNL4](https://github.com/api-evangelist/signl4)
- [Splunk](https://github.com/api-evangelist/splunk)
- [Splunk On-Call (VictorOps)](https://github.com/api-evangelist/victorops)
- [Squadcast](https://github.com/api-evangelist/squadcast)
- [Statuspage](https://github.com/api-evangelist/statuspage)
- [Sumo Logic](https://github.com/api-evangelist/sumo-logic)
- [Sysdig](https://github.com/api-evangelist/sysdig)
- [Traceable](https://github.com/api-evangelist/traceable)
- [Treblle](https://github.com/api-evangelist/treblle)
- [Uptrace](https://github.com/api-evangelist/uptrace)
- [VictoriaMetrics](https://github.com/api-evangelist/victoriametrics)
- [xMatters](https://github.com/api-evangelist/xmatters)
- [Zabbix](https://github.com/api-evangelist/zabbix)
- [Zenduty](https://github.com/api-evangelist/zenduty)
- [Zipkin](https://github.com/api-evangelist/zipkin)

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
