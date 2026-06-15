# NVD (nvd)

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
