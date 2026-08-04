# Google Anthos (google-anthos)

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

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
