# Lentra

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
