# Lentra

Lentra is a Pune, India based cloud-native digital lending platform for banks and non-banking
financial companies. Built on a microservices architecture with customisable customer journeys, the
platform spans loan origination (GoNoGo), loan management (1LMS), data and machine learning
operations (Lentra MLOps), and data transfer (TransferX), alongside standalone modules for
MultiBureau credit bureau access, identity and video KYC verification, collateral management,
document management, co-lending and bank reconciliation. Lentra packages these into pre-built
retail, business and agriculture lending journeys, delivered SaaS on a per-user or per-transaction
basis to institutions including HDFC Bank, State Bank of India, IDFC and TVS Credit.

Backed by: bessemer-venture-partners — https://www.lentra.ai/

## API surface

Lentra sells to financial institutions directly. As of this enrichment pass it publishes **no
public developer portal, API reference, OpenAPI/AsyncAPI specification, sandbox, status page,
changelog, CLI, or MCP server**. `https://lentra.ai/docs` resolves to the marketing homepage, and
no `docs.`/`developer.`/`api.` subdomain resolves. API access is obtained through a commercial
engagement.

## Artifacts

| Artifact | File | Method |
|---|---|---|
| Packages | `packages/lentra-packages.yml` | searched |
| Components | `components/lentra-components.yml` | searched |
| Conformance | `conformance/lentra-conformance.yml` | searched |
| Trust center | `security/lentra-trust-center.yml` | searched |
| Domain security | `security/lentra-domain-security.yml` | probed |
| Well-known | `well-known/lentra-well-known.yml` | searched |
| llms.txt | `llms/lentra-llms.txt` | generated |

## Trust and compliance

[trust.lentra.ai](https://trust.lentra.ai/) publishes SOC 2 Type II, SOC 3, ISO/IEC 27001
(including 27001:2022), ISO/IEC 27017, ISO/IEC 27018, ISO/IEC 27701, ISO 22301:2019 and CSA STAR
(with a [CSA STAR registry entry](https://cloudsecurityalliance.org/star/registry/lentra-ai-pvt-ltd/services/lentra-ai-pvt-ltd/)).
No vulnerability disclosure policy, `security.txt`, or bug bounty program was found.
