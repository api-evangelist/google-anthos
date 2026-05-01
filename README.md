# Google Anthos

Google Anthos is a managed application platform that extends Google Cloud services and engineering practices to hybrid and multi-cloud environments. Built on Kubernetes, Anthos enables consistent development and operations across on-premises data centers, Google Cloud, and other public clouds like AWS and Azure, with centralized management, policy enforcement, and service mesh capabilities.

**URL:** [APIs.yml](https://raw.githubusercontent.com/api-evangelist/google-anthos/refs/heads/main/apis.yml)

## Tags

- Container Platform, Hybrid Cloud, Kubernetes, Multi-Cloud, On-Premises, Service Mesh

## Timestamps

- **Created:** 2026-03-13
- **Modified:** 2026-04-28

## APIs

### GKE On-Prem API

The GKE On-Prem API provides programmatic access to manage the lifecycle of on-premises Kubernetes clusters running on VMware or bare metal infrastructure as part of Google Distributed Cloud. Developers can use the API to create, update, delete, and monitor on-premises clusters, manage node pools, and handle cluster enrollment and upgrades through the Google Cloud control plane.

**Human URL:** [https://cloud.google.com/anthos/clusters/docs/on-prem-api/overview](https://cloud.google.com/anthos/clusters/docs/on-prem-api/overview)

**Base URL:** `https://gkeonprem.googleapis.com`

#### Tags

- Bare Metal, Clusters, Kubernetes, On-Premises, VMware

#### Properties

- [Documentation](https://cloud.google.com/anthos/clusters/docs/on-prem-api/reference/rest)
- [OpenAPI](openapi/gke-on-prem-api-openapi.yml)
- [JSON Schema](json-schema/google-anthos-cluster-schema.json)

### Anthos Multicloud API

The Anthos Multicloud API provides programmatic access to manage Anthos clusters running on other public clouds such as AWS and Azure. Developers can use the API to create, update, and delete attached clusters and manage node pools on external cloud providers while maintaining centralized management through Google Cloud.

**Human URL:** [https://cloud.google.com/anthos/clusters/docs/multi-cloud](https://cloud.google.com/anthos/clusters/docs/multi-cloud)

**Base URL:** `https://gkemulticloud.googleapis.com`

#### Tags

- AWS, Azure, Clusters, Multi-Cloud

#### Properties

- [Documentation](https://cloud.google.com/anthos/clusters/docs/multi-cloud)

## Artifacts

- [APIs.yml](apis.yml) - APIs.json index for this API.
- [OpenAPI](openapi/gke-on-prem-api-openapi.yml) - OpenAPI specification for the GKE On-Prem API.
- [JSON Schema](json-schema/google-anthos-cluster-schema.json) - JSON Schema for Anthos cluster resources.
- [JSON-LD Context](json-ld/google-anthos-context.jsonld) - JSON-LD context for linked data interoperability.

## Common Properties

- [Getting Started](https://cloud.google.com/anthos/docs/setup/overview)
- [Pricing](https://cloud.google.com/anthos/pricing)

## Maintainer

- **Kin Lane** - kin@apievangelist.com
