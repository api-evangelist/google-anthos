# Google Anthos (google-anthos)

Google Anthos is a managed application platform that extends Google Cloud services and engineering practices to hybrid and multi-cloud environments. Built on Kubernetes, Anthos enables consistent development and operations across on-premises data centers, Google Cloud, and other public clouds like AWS and Azure, with centralized management, policy enforcement, and service mesh capabilities.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/google-anthos/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/google-anthos/refs/heads/main/apis.yml)

## Scope

- **Type:** Index

## Tags

- Container Platform
- Hybrid Cloud
- Kubernetes
- Multi-Cloud
- On-Premises
- Service Mesh

## Timestamps

- **Created:** 2026-03-13
- **Modified:** 2026-05-19

## APIs

### GKE On-Prem API

The GKE On-Prem API provides programmatic access to manage the lifecycle of on-premises Kubernetes clusters running on VMware or bare metal infrastructure as part of Google Distributed Cloud. Developers can use the API to create, update, delete, and monitor on-premises clusters, manage node pools, and handle cluster enrollment and upgrades through the Google Cloud control plane.

- **Human URL:** [https://cloud.google.com/anthos/clusters/docs/on-prem-api/overview](https://cloud.google.com/anthos/clusters/docs/on-prem-api/overview)
- **Base URL:** `https://gkeonprem.googleapis.com`

#### Tags

- Bare Metal
- Clusters
- Kubernetes
- On-Premises
- VMware

#### Properties

- [Documentation](https://cloud.google.com/anthos/clusters/docs/on-prem-api/reference/rest)
- [OpenAPI](openapi/gke-on-prem-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/gke-on-prem-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/gke-on-prem-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/google-anthos-cluster-schema.json) — [JSON Schema](https://json-schema.org/specification)

### Anthos Multicloud API

The Anthos Multicloud API provides programmatic access to manage Anthos clusters running on other public clouds such as AWS and Azure. Developers can use the API to create, update, and delete attached clusters and manage node pools on external cloud providers while maintaining centralized management through Google Cloud.

- **Human URL:** [https://cloud.google.com/anthos/clusters/docs/multi-cloud](https://cloud.google.com/anthos/clusters/docs/multi-cloud)
- **Base URL:** `https://gkemulticloud.googleapis.com`

#### Tags

- AWS
- Azure
- Clusters
- Multi-Cloud

#### Properties

- [Documentation](https://cloud.google.com/anthos/clusters/docs/multi-cloud)
- [Postman Collection](collections/gke-on-prem-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/gke-on-prem-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [GitHub Organization](https://github.com/GoogleCloudPlatform)
- [Getting Started](https://cloud.google.com/anthos/docs/setup/overview)
- [Pricing](https://cloud.google.com/anthos/pricing)
- [JSON-LD](json-ld/google-anthos-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [Integrations](https://cloud.google.com/marketplace)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
