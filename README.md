# NVD (nvd)

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
> **Not from the company, and here with a question?** You are welcome here — we would rather be the
> front line and point you the right way than have a good report go nowhere. What this repository
> can answer is narrow, though, so it is worth knowing who you are actually looking for:
>
> - **A question about how the API works, an account, billing, or a bug in the service** — that is
>   the company's own support, not us. We profile this API; we do not operate it and cannot see
>   your account.
> - **A bug in an open-source project we only catalog** — file it on that project's own repository.
>   This has happened with a real and correct bug report that reached us instead of the people who
>   could fix it, which helped nobody.
> - **Anything about this listing itself** — the description, the tags, the rating, a missing or
>   wrong artifact — is ours. Open an issue here.
> - **Not sure, or something general about API Evangelist or APIs.io** — open an issue on the
>   [APIs.io Inbox](https://github.com/api-search/inbox) and we will route it.
>
> **This repository contains no software, and we will never ask you to download anything.** There is
> no build, release, installer, or binary here — only text and machine-readable API descriptions, so
> there is nothing here that can be "corrupt" or need "repairing". Any issue, comment, or email
> claiming otherwise and offering a download link is not from us and is hostile. Do not follow the
> link; it is a lure. Report it to GitHub and, if you like, tell us at
> [info@apievangelist.com](mailto:info@apievangelist.com) so we can take it down.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

The National Vulnerability Database (NVD) provides REST APIs for CVE (Common Vulnerabilities and Exposures) data, CPE (Common Platform Enumeration) records, match criteria, and source organizations. APIs deliver vulnerability descriptions, CVSS severity scores, affected product lists, CWE classifications, and reference links for security monitoring and dependency alerting.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/nvd/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/nvd/refs/heads/main/apis.yml)

## Scope

- **Type:** Index

## Tags

- Security
- CVE
- CPE
- Vulnerability
- CVSS

## Timestamps

- **Modified:** 2026-05-19

## APIs

### NVD CVE API

The NVD CVE API provides programmatic access to CVE (Common Vulnerabilities and Exposures) records including CVSS severity scores, affected product lists, CWE classifications, and reference links. Supports filtering by CVE ID, CVSS metrics, CWE, keyword, modification date, and publication date. Without an API key: 5 requests per 30 seconds; with key: 50 requests per 30 seconds.

- **Human URL:** [https://nvd.nist.gov/developers/vulnerabilities](https://nvd.nist.gov/developers/vulnerabilities)

#### Tags

- Security
- CVE
- Vulnerability
- CVSS

#### Properties

- [Documentation](https://nvd.nist.gov/developers/vulnerabilities)
- [Getting Started](https://nvd.nist.gov/developers/start-here)
- [Authentication](https://nvd.nist.gov/developers/request-an-api-key)
- [Rate Limits](https://nvd.nist.gov/developers/start-here)
- [OpenAPI](https://raw.githubusercontent.com/api-evangelist/nvd/refs/heads/main/openapi/nvd-cve-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [JSON Schema](https://raw.githubusercontent.com/api-evangelist/nvd/refs/heads/main/json-schema/nvd-cve-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [J S O N L D Context](https://raw.githubusercontent.com/api-evangelist/nvd/refs/heads/main/json-ld/nvd-context.jsonld)
- [Postman Collection](collections/nvd-cve.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/nvd-cve.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### NVD CVE Change History API

The NVD CVE Change History API tracks modifications to CVE records over time, enabling consumers to identify updated vulnerability data and synchronize their local databases with incremental changes rather than full reloads.

- **Human URL:** [https://nvd.nist.gov/developers/vulnerabilities](https://nvd.nist.gov/developers/vulnerabilities)

#### Tags

- Security
- CVE
- Vulnerability
- Change History

#### Properties

- [Documentation](https://nvd.nist.gov/developers/vulnerabilities)
- [Getting Started](https://nvd.nist.gov/developers/start-here)
- [Authentication](https://nvd.nist.gov/developers/request-an-api-key)
- [OpenAPI](https://raw.githubusercontent.com/api-evangelist/nvd/refs/heads/main/openapi/nvd-cve-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/nvd-cve.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/nvd-cve.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### NVD CPE API

The NVD CPE (Common Platform Enumeration) API provides access to the authoritative CPE dictionary, enabling lookup of software and hardware product identifiers. Supports filtering by CPE name, match string, keyword, and modification date. Returns up to 10,000 results per page.

- **Human URL:** [https://nvd.nist.gov/developers/products](https://nvd.nist.gov/developers/products)

#### Tags

- Security
- CPE
- Vulnerability
- Product Enumeration

#### Properties

- [Documentation](https://nvd.nist.gov/developers/products)
- [Getting Started](https://nvd.nist.gov/developers/start-here)
- [Authentication](https://nvd.nist.gov/developers/request-an-api-key)
- [OpenAPI](https://raw.githubusercontent.com/api-evangelist/nvd/refs/heads/main/openapi/nvd-cve-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/nvd-cve.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/nvd-cve.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### NVD CPE Match Criteria API

The NVD CPE Match Criteria API retrieves CPE match strings associated with CVE records, enabling detailed product-to-vulnerability mapping. Supports filtering by CVE ID, match criteria ID, and match string patterns. Returns up to 500 results per page.

- **Human URL:** [https://nvd.nist.gov/developers/products](https://nvd.nist.gov/developers/products)

#### Tags

- Security
- CPE
- Vulnerability
- Match Criteria

#### Properties

- [Documentation](https://nvd.nist.gov/developers/products)
- [Getting Started](https://nvd.nist.gov/developers/start-here)
- [Authentication](https://nvd.nist.gov/developers/request-an-api-key)
- [OpenAPI](https://raw.githubusercontent.com/api-evangelist/nvd/refs/heads/main/openapi/nvd-cve-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/nvd-cve.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/nvd-cve.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### NVD Source API

The NVD Source API provides information about the organizations that contribute vulnerability data to the NVD dataset, enabling consumers to understand data provenance. Returns up to 1,000 source records per page. Data changes infrequently; once daily updates recommended.

- **Human URL:** [https://nvd.nist.gov/developers/data-sources](https://nvd.nist.gov/developers/data-sources)

#### Tags

- Security
- CVE
- Data Sources
- Organizations

#### Properties

- [Documentation](https://nvd.nist.gov/developers/data-sources)
- [Getting Started](https://nvd.nist.gov/developers/start-here)
- [Authentication](https://nvd.nist.gov/developers/request-an-api-key)
- [OpenAPI](https://raw.githubusercontent.com/api-evangelist/nvd/refs/heads/main/openapi/nvd-cve-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/nvd-cve.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/nvd-cve.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### National Vulnerability Database API

The National Vulnerability Database (NVD) provides REST and RSS/Atom APIs for CVE (Common Vulnerabilities and Exposures) data. APIs deliver vulnerability descriptions, CVSS severity scores, affected product lists, and reference links for security monitoring and dependency alerting.

- **Human URL:** [https://nvd.nist.gov/developers](https://nvd.nist.gov/developers)

#### Tags

- Security
- CVE
- Vulnerability
- RSS
- XML

#### Properties

- [Documentation](https://nvd.nist.gov/developers)
- [Postman Collection](collections/nvd-cve.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/nvd-cve.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [Portal](https://nvd.nist.gov/developers)
- [Website](https://nvd.nist.gov/)
- [Getting Started](https://nvd.nist.gov/developers/start-here)
- [Authentication](https://nvd.nist.gov/developers/request-an-api-key)
- [Rate Limits](https://nvd.nist.gov/developers/start-here)
- [Terms of Service](https://nvd.nist.gov/developers/terms-of-use)
- [OpenAPI](https://raw.githubusercontent.com/api-evangelist/nvd/refs/heads/main/openapi/nvd-cve-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [JSON Schema](https://raw.githubusercontent.com/api-evangelist/nvd/refs/heads/main/json-schema/nvd-cve-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [J S O N L D Context](https://raw.githubusercontent.com/api-evangelist/nvd/refs/heads/main/json-ld/nvd-context.jsonld)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
