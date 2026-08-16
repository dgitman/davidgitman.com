---
layout: content
permalink: /expertise/cloud-devops/
title: Cloud Infrastructure & DevOps
description: "AWS, GCP, Kubernetes, Terraform, CI/CD, observability, and high-availability infrastructure expertise from David Gitman."
last_modified_at: "2026-08-16"
schema_type: WebPage
breadcrumb_parent: Expertise
breadcrumb_parent_url: /expertise/
eyebrow: Cloud & DevOps Expertise
lede: "Cloud systems designed for predictable delivery, useful observability, recovery, and the traffic patterns of digital commerce."
schema_about:
  - Amazon Web Services
  - Google Cloud Platform
  - Kubernetes
  - Terraform
  - DevOps
---

## Infrastructure tied to the workload

Cloud architecture should begin with the workload, failure modes, and operating model. I have architected and operated AWS and GCP environments supporting eCommerce applications, SaaS products, data pipelines, high-volume catalogs, and traffic spikes.

My experience includes EC2, S3, CloudFront, EKS, RDS, ElastiCache, MemoryDB, Glue, Lambda, CloudWatch, VPC, Route 53, Terraform, Docker, Kubernetes, GitHub Actions, and related infrastructure-as-code workflows.

## Delivery and reliability

The objective of DevOps is a safer, faster path from a reviewed change to a healthy production system. That requires more than a deployment script. It includes reproducible infrastructure, meaningful checks, rollback and recovery paths, environment consistency, and enough telemetry to understand failures.

Core practices include:

- Infrastructure as code and reviewable environment changes.
- CI/CD pipelines with scoped tests and deployment controls.
- Application, infrastructure, and business-level monitoring.
- Caching and data-layer strategies matched to workload behavior.
- Capacity planning for launches, promotions, imports, and seasonal traffic.
- Incident analysis that turns a failure into a durable system improvement.

## Observability that supports decisions

Metrics and logs matter when they answer operational questions: Is checkout failing? Is a marketplace feed stale? Did catalog latency increase after an import? Is the bottleneck in an application, cache, database, dependency, or network path?

I have worked with CloudWatch, Prometheus, Grafana, New Relic, and Nagios/NetSaint, combining system telemetry with application and commerce signals so teams can prioritize the right response.

## Architecture across business boundaries

Many reliability problems appear between systems rather than inside one service. Commerce platforms commonly depend on payment providers, ERPs, 3PLs, CRMs, marketplaces, and fulfillment partners. Resilient integrations need explicit timeout, retry, idempotency, reconciliation, and exception-handling strategies.

<div class="next-links">
  <a href="{{ '/expertise/ecommerce-platforms/' | relative_url }}">eCommerce expertise →</a>
  <a href="{{ '/expertise/ai-automation/' | relative_url }}">AI automation expertise →</a>
</div>
