# Zilliz (zilliz)

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

Zilliz Cloud is the managed vector database service built by the Milvus maintainers. It exposes a Control Plane API for cluster management and a Data Plane API for vector operations. Offers Serverless, Dedicated, and BYOC plans.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/zilliz/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/zilliz/refs/heads/main/apis.yml)

## Tags

- Vector Database
- AI
- Cloud
- Milvus
- Managed

## Timestamps

- **Created:** 2026-05-08
- **Modified:** 2026-05-08

## APIs

### Zilliz Cloud Control Plane API

The Control Plane API manages clusters (create / modify / suspend), users, roles, backups, alerts, metrics, and billing. Authentication is Bearer with a Zilliz API key.

- **Human URL:** [https://docs.zilliz.com/reference/restful](https://docs.zilliz.com/reference/restful)
- **Base URL:** `https://api.cloud.zilliz.com/v2`

#### Tags

- REST
- Cluster Management
- Billing
- Backups

#### Properties

- [Documentation](https://docs.zilliz.com/reference/restful)
- [Authentication](https://docs.zilliz.com/reference/restful)

### Zilliz Cloud Data Plane API

Data Plane endpoints handle collection, vector, partition, index, and role operations on a specific cluster. Authentication accepts either a Zilliz API key or a cluster `db_admin:password` pair.

- **Human URL:** [https://docs.zilliz.com/reference/restful](https://docs.zilliz.com/reference/restful)
- **Base URL:** `https://{cluster_endpoint}/v2/vectordb`

#### Tags

- REST
- Collections
- Vectors
- Search

#### Properties

- [Documentation](https://docs.zilliz.com/reference/restful)

## Common Properties

- [GitHub Organization](https://github.com/zilliztech)
- [LinkedIn](https://www.linkedin.com/company/zilliz)
- [Website](https://zilliz.com/)
- [Portal](https://docs.zilliz.com/)
- [Pricing](https://zilliz.com/pricing)
- [Parent Relationship](https://milvus.io/)
- [Plans](plans/zilliz-plans-pricing.yml)
- [Rate Limits](rate-limits/zilliz-rate-limits.yml)
- [Fin Ops](finops/zilliz-finops.yml)
- [Integrations](https://zilliz.com/partners)
- [L L Ms Txt](https://docs.zilliz.com/llms.txt)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
