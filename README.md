# Aqtual

Aqtual, Inc. is a Hayward, California precision-medicine company founded in 2019 by Diana Abdueva (Founder and CEO) with co-founder Rich Rava. It develops blood-based diagnostics on a proprietary "active chromatin" cell-free DNA (cfDNA) platform that reads DNA, epigenetic regulation and protein-DNA binding from a single routine blood draw. Its lead product is a therapy-response prediction test for rheumatoid arthritis, evaluated in the prospective PRIMA-102 trial (NCT05936970), with oncology programs in leiomyosarcoma immunotherapy response and early colorectal cancer detection. It raised a USD 16M Series A in October 2023 and over USD 31M in Series B funding announced July 2025.

**Aqtual publishes no public API.** As of 2026-08-02 there is no developer portal, no API documentation and no machine-readable API contract of any kind. Every `/.well-known/` and contract-discovery path on `aqtual.com` returns 404, and no `api.`, `docs.`, `developer.`, `portal.` or `app.` subdomain resolves. The probe record is in `well-known/aqtual-well-known.yml`.

- https://aqtual.com/
- https://aqtual.com/newsroom/
- https://aqtual.com/publications/
- https://www.linkedin.com/company/aqtual
- https://clinicaltrials.gov/study/NCT05936970
- https://forgeglobal.com/aqtual_stock/

## Artifacts

| Path | What it is |
|---|---|
| `well-known/aqtual-well-known.yml` | `/.well-known/` + contract-discovery probe record (all misses, with status codes) |
| `packages/aqtual-packages.yml` | Package-registry search record — no first-party client libraries |
| `conformance/aqtual-conformance.yml` | CLIA / CAP / FDA-LDT / HIPAA regulatory posture; API standards recorded not-applicable |
| `security/aqtual-domain-security.yml` | TLS / HSTS / DNSSEC / CAA / SPF / DMARC probe of `aqtual.com` |
| `llms/aqtual-llms.txt` | Generated `llms.txt` summary of the company for agents |
