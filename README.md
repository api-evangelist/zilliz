# Zilliz (zilliz)

Zilliz Cloud is the managed vector database service built by the Milvus maintainers. It exposes a Control Plane API for cluster management and a Data Plane API for vector operations. Offers Serverless, Dedicated, and BYOC plans.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/zilliz/refs/heads/main/apis.yml)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=zilliz-api-evangelist&utm_content=repo)

## Type
- **x-type:** company

## APIs
- **Zilliz Cloud Control Plane API** - `https://api.cloud.zilliz.com/v2`. Bearer API key. Cluster create/modify/suspend, users, roles, backups, alerts, metrics, billing.
- **Zilliz Cloud Data Plane API** - `{cluster_endpoint}/v2/vectordb`. Bearer API key or `db_admin:password`. Collections, vectors, partitions, indexes, roles.

## Tags
- Vector Database, AI, Cloud, Milvus, Managed

## Timestamps
- **Created:** 2026-05-08
- **Modified:** 2026-05-08

## Common Properties
- [Website](https://zilliz.com/)
- [Documentation](https://docs.zilliz.com/)
- [Pricing](https://zilliz.com/pricing)
- [Maintainer of Milvus](https://milvus.io/)
- [Plans](plans/zilliz-plans-pricing.yml)
- [RateLimits](rate-limits/zilliz-rate-limits.yml)
- [FinOps](finops/zilliz-finops.yml)

## Notes
- Pricing partial — three tiers (Serverless / Dedicated / BYOC) confirmed but exact rates not extracted from the public pricing page (calculator-driven).
- Clean Control Plane vs Data Plane split is a strong API design pattern; few competitors document the boundary as cleanly.

## Maintainers
**FN:** Kin Lane

**Email:** kin@apievangelist.com
