# FastDOL (fastdol)

Federal workplace enforcement records on 2.3M US employers across 16 federal agencies — OSHA, WHD, MSHA, EPA ECHO, NLRB, FMCSA, OFLC, BLS SOII, SAM.gov, CMS, USAspending, CPSC, NHTSA, SEC, and the UVA Corporate Prosecution Registry — exposed as a single normalized JSON API. Query inspections, violations, penalties, wage theft cases, severe injury reports, federal contract awards, and recalls.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/fastdol/refs/heads/main/apis.yml)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - OSHA, Compliance, Workplace Safety, Public Records, Federal Enforcement, Labor

## Timestamps

- **Created:** 2026-05-16
- **Modified:** 2026-05-16

## APIs

### FastDOL API
Unified REST API for federal workplace enforcement records — employer search and profile lookup, OSHA inspections and violations, WHD wage theft cases, severe injury reports, SEC enforcement, batch lookup, CSV upload, async export jobs, NAICS industry metadata, state and industry statistics, API key management, and account dashboard.

**Human URL:** [https://fastdol.com/docs](https://fastdol.com/docs)

**Base URL:** `https://api.fastdol.com`

#### Tags:

 - OSHA, WHD, EPA, MSHA, NLRB, FMCSA, Compliance, Workplace Safety, Federal Enforcement, Public Records, Employers, Inspections, Violations, Wage Theft, Severe Injuries, Risk Scoring, NAICS

#### Properties

- [Documentation](https://fastdol.com/docs)
- [APIReference](https://fastdol.com/docs)
- [OpenAPI](https://raw.githubusercontent.com/api-evangelist/fastdol/main/openapi/fastdol-openapi.yml)
- [Sandbox](https://fastdol.com/playground)
- [Console](https://fastdol.com/playground)
- [Authentication](https://fastdol.com/docs)
- [SignUp](https://fastdol.com/signup)
- [RateLimits](rate-limits/fastdol-rate-limits.yml)
- [JSONSchema](json-schema/)
- [JSONStructure](json-structure/)
- [JSON-LD](json-ld/fastdol-context.jsonld)
- [Example](examples/)

## Common Properties

- [Website](https://fastdol.com/)
- [Documentation](https://fastdol.com/docs)
- [APIReference](https://fastdol.com/docs)
- [Sandbox](https://fastdol.com/playground)
- [SignUp](https://fastdol.com/signup)
- [Login](https://fastdol.com/login)
- [Pricing](https://fastdol.com/enterprise)
- [Plans](plans/fastdol-plans-pricing.yml)
- [PricingPage](https://fastdol.com/enterprise)
- [RateLimits](rate-limits/fastdol-rate-limits.yml)
- [FinOps](finops/fastdol-finops.yml)
- [SpectralRules](rules/fastdol-rules.yml)
- [Vocabulary](vocabulary/fastdol-vocabulary.yml)
- [NaftikoCapability — Employer Compliance Research](capabilities/employer-compliance-research.yaml)
- [NaftikoCapability — Bulk Data Pipelines](capabilities/bulk-data-pipelines.yaml)
- [NaftikoCapability — Shared FastDOL](capabilities/shared/fastdol.yaml)
- [Blog](https://fastdol.com/blog)
- [TermsOfService](https://fastdol.com/terms)
- [PrivacyPolicy](https://fastdol.com/privacy)
- [Contact](https://fastdol.com/enterprise)
- [Support](mailto:ben@fastdol.com)
- [Authentication](https://fastdol.com/docs)
- [Methodology](https://fastdol.com/methodology)
- [Datasets](https://fastdol.com/datasets)
- [HuggingFace](https://huggingface.co/FastDOLz)
- [APIsJSON](https://api.fastdol.com/v1/openapi.json)

## Features

| Name | Description |
|------|-------------|
| Unified Employer Search | Fuzzy search across 2.3M US employers by name, EIN, ZIP, state, or NAICS code with risk-ranked results. |
| Cross-Agency Enforcement Profile | Single employer profile aggregating OSHA inspections and violations, WHD wage theft, MSHA mine safety, EPA ECHO, NLRB labor practice, FMCSA, OFLC, BLS SOII, SAM.gov debarment, CMS, USAspending, CPSC, NHTSA, SEC enforcement, and federal prosecutions. |
| Risk Scoring | Composite per-employer risk score with risk-history endpoint exposing month-over-month changes. |
| Parent Company Rollup | Aggregate enforcement across all locations of a parent company via parent-name lookup. |
| Peer Comparison | Compare an employer against industry peers within the same NAICS code and state. |
| Batch Lookup | Submit up to 100 employer queries in one POST for high-throughput backfills. |
| CSV Upload | Upload up to 500 rows / 5MB for bulk match against the employer index. |
| Async Bulk Export | Enterprise-only export job pipeline returning downloadable CSV/JSON of up to 100,000 rows. |
| Inspection Violations Detail | Drill into individual OSHA inspection activity numbers for citation-level violations. |
| Severe Injuries Reporting | OSHA Form 300A and severe-injury report data per employer. |
| SEC Enforcement Linkage | SEC enforcement actions joined to publicly traded parent companies. |
| NAICS Industry Metadata | Lookup NAICS-4 industry codes and BLS SOII industry injury rate benchmarks. |
| State and Industry Statistics | Pre-aggregated stats by US state and NAICS code, plus a dedicated nursing-home (CMS CCN) statistics index. |
| API Key Self-Service | Dashboard endpoints to create, list, rotate (48-hour grace), and revoke API keys (up to 5 active per account). |
| Usage Telemetry | Self-reported lookup logging and PDF report claim endpoints with retrievable usage history. |
| Sitemap Feed | Crawler-friendly employer sitemap endpoint for SEO and search-index ingestion. |
| Feedback Submission | Per-employer feedback submission for data corrections. |

## Use Cases

| Name | Description |
|------|-------------|
| Journalism and Investigations | Reporters investigating workplace safety, wage theft, or environmental violations at specific employers or industries. |
| ESG and Responsible Investment | Investment funds screening portfolio companies for material labor, safety, and compliance liabilities. |
| Insurance Underwriting | Workers compensation and commercial casualty underwriters pricing risk based on federal enforcement history. |
| Procurement and Vendor Risk | Procurement teams vetting suppliers and contractors against federal debarment, OSHA, and EPA records. |
| Labor Organizing and Worker Advocacy | Unions and worker advocates identifying chronic violators and industry-wide enforcement patterns. |
| Academic Research | Labor economists, public health researchers, and policy analysts studying enforcement effectiveness and worker safety outcomes. |
| Legal Discovery and Litigation Support | Plaintiffs counsel and defense firms researching defendant enforcement history. |
| Compliance and Audit Functions | Corporate compliance teams benchmarking their own facilities against industry peers. |

## Integrations

| Name | Description |
|------|-------------|
| OSHA Enforcement Data | Inspections, violations, penalties, fatalities, and severity classifications. |
| OSHA ITA Form 300A | Self-reported DART and TRIR injury rates by establishment. |
| WHD (Wage and Hour Division) | Wage violations, back wages, and affected-employee counts. |
| MSHA | Mine safety violations and penalties. |
| EPA ECHO | Environmental compliance covering air, water, waste, and drinking water. |
| NLRB | Labor practice charges and union representation cases. |
| FMCSA | Motor carrier safety data. |
| OFLC | Foreign labor certifications including H-1B, H-2A, and H-2B. |
| BLS SOII | Bureau of Labor Statistics industry injury rate benchmarks. |
| SAM.gov | Federal debarment and suspension exclusions. |
| CMS | Nursing home ratings and deficiencies indexed by CCN. |
| USAspending.gov | 25-year history of federal contract awards. |
| CPSC | Product recall data. |
| NHTSA | Vehicle recall and defect complaint data. |
| SEC EDGAR | SEC enforcement actions and public-company filings. |
| UVA Corporate Prosecution Registry | Federal prosecutions and plea agreement records. |
| Stripe | Billing webhook intake is wired into the API for subscription lifecycle events. |
| Hugging Face Datasets | Several FastDOL datasets are mirrored on the FastDOLz Hugging Face organization for ML and bulk research workflows. |

## Solutions

| Name | Description |
|------|-------------|
| Free Tier | 50 monthly API lookups per key, no credit card required, for evaluation and light research use. |
| Enterprise Data Licensing | Custom-quota API access, bulk export, dataset licensing, and custom integrations contracted directly with FastDOL. |

## Artifacts

Machine-readable API specifications organized by format.

### OpenAPI

- [FastDOL API OpenAPI](openapi/fastdol-openapi.yml)

### JSON Schema

13 standalone JSON Schemas in [`json-schema/`](json-schema/) covering every component schema in the OpenAPI spec (BatchLookupItem, BatchLookupRequest, ExportRequest, ExportFilters, FeedbackRequest, SignupRequest, LoginRequest, VerifyEmailRequest, ForgotPasswordRequest, ResetPasswordRequest, DeleteAccountRequest, CreateKeyRequest, and the CSV upload form body).

### JSON Structure

13 JSON Structure definitions mirroring the JSON Schemas in [`json-structure/`](json-structure/).

### JSON-LD

- [FastDOL JSON-LD Context](json-ld/fastdol-context.jsonld) — Linked-data context mapping employer, inspection, violation, WHD case, severe injury, OSHA accident, SEC enforcement, and industry-code concepts to schema.org and DCAT.

### Examples

70 example payloads in [`examples/`](examples/): one schema example per component plus per-operation request/response examples for every operation in the spec.

### Spectral Rules

- [FastDOL Spectral Ruleset](rules/fastdol-rules.yml) — 32 rules across 12 categories (info/metadata, servers, paths, operations, parameters, request bodies, responses, schemas, security, and general quality) enforcing FastDOL's snake_case + /v1 + X-Api-Key conventions.

## Capabilities

Naftiko capabilities organized as a shared per-API definition composed into customer-facing workflows.

### Shared Per-API Definitions

- [FastDOL API](capabilities/shared/fastdol.yaml) — 46 operations covering employers, inspections, industries, stats, export, usage, sitemap, health, dashboard (account, plan, keys), and auth.

### Workflow Capabilities

| Workflow | APIs Combined | Tools | Persona |
|----------|--------------|-------|---------|
| [Employer Compliance Research](capabilities/employer-compliance-research.yaml) | FastDOL | 21 | Journalists, ESG analysts, underwriters, compliance officers, researchers |
| [Bulk Data Pipelines](capabilities/bulk-data-pipelines.yaml) | FastDOL | 15 | Data engineers, platform admins, DevOps |

## Vocabulary

- [FastDOL Vocabulary](vocabulary/fastdol-vocabulary.yml) — Unified taxonomy mapping 11 resources, 27 actions, 2 workflows, and 8 personas across operational (OpenAPI) and capability (Naftiko) dimensions.

## Plans, Rate Limits, and FinOps

- [Plans / Pricing](plans/fastdol-plans-pricing.yml) — Free tier (50 lookups/month per key) and Enterprise (custom). `reconciled: false` — enterprise pricing is contact-sales only.
- [Rate Limits](rate-limits/fastdol-rate-limits.yml) — Per-key monthly quota plus per-IP request rate (60 / 30 / 10 req/min by endpoint family) with `X-RateLimit-*` headers and 429 throttling.
- [FinOps](finops/fastdol-finops.yml) — FOCUS-aligned FinOps shape covering API lookups, batch items, CSV rows, export rows, PDF report claims, and dataset licenses.

## Rules

- [FastDOL Spectral Rules](rules/fastdol-rules.yml) — 32 rules enforcing FastDOL's API conventions.

## Maintainers

**FN:** API Evangelist

**Email:** info@apievangelist.com
