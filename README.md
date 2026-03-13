# Google Anthos (google-anthos)
Google Anthos is a managed application platform that extends Google Cloud services and engineering practices to hybrid and multi-cloud environments. Built on Kubernetes, Anthos enables consistent development and operations across on-premises data centers, Google Cloud, and other public clouds like AWS and Azure, with centralized management, policy enforcement, and service mesh capabilities.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/google-anthos/refs/heads/main/apis.yml)

## Scope

- **Type:** Contract
- **Position:** Consuming
- **Access:** 3rd-Party

## Tags:

 - Kubernetes, Hybrid Cloud, Multi-Cloud, Container Platform, Service Mesh, On-Premises

## Timestamps

- **Created:** 2026-03-13
- **Modified:** 2026-03-13

## APIs

### GKE On-Prem API
The GKE On-Prem API provides programmatic access to manage the lifecycle of on-premises Kubernetes clusters running on VMware or bare metal infrastructure as part of Google Distributed Cloud. Developers can use the API to create, update, delete, and monitor on-premises clusters, manage node pools, and handle cluster enrollment and upgrades through the Google Cloud control plane.

**Human URL:** [https://cloud.google.com/anthos/clusters/docs/on-prem-api/overview](https://cloud.google.com/anthos/clusters/docs/on-prem-api/overview)


#### Tags:

 - Kubernetes, On-Premises, Clusters, VMware, Bare Metal

#### Properties

- [Documentation](https://cloud.google.com/anthos/clusters/docs/on-prem-api/reference/rest)
- [OpenAPI](openapi/gke-on-prem-api-openapi.yml)
- [JSONSchema](json-schema/google-anthos-cluster-schema.json)

### Anthos Multicloud API
The Anthos Multicloud API provides programmatic access to manage Anthos clusters running on other public clouds such as AWS and Azure. Developers can use the API to create, update, and delete attached clusters and manage node pools on external cloud providers while maintaining centralized management through Google Cloud.

**Human URL:** [https://cloud.google.com/anthos/clusters/docs/multi-cloud](https://cloud.google.com/anthos/clusters/docs/multi-cloud)


#### Tags:

 - Multi-Cloud, AWS, Azure, Clusters

#### Properties

- [Documentation](https://cloud.google.com/anthos/clusters/docs/multi-cloud)

## Common Properties

- [GettingStarted](https://cloud.google.com/anthos/docs/setup/overview)
- [Pricing](https://cloud.google.com/anthos/pricing)
- [JSON-LD](json-ld/google-anthos-context.jsonld)

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
