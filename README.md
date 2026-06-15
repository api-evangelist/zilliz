# Zilliz (zilliz)

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
