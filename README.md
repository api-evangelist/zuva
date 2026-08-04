# Zuva (zuva)

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

Zuva (by Kira Systems) provides a contract and document AI REST API for extracting structured data from unstructured documents. The Zuva DocAI API offers asynchronous OCR, field extraction across 1,400+ pre-built fields, multi-level document classification across 220+ document types, language detection, and a searchable fields catalog, secured with Bearer API tokens across US and EU regions.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/zuva/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/zuva/refs/heads/main/apis.yml)

## Tags

- AI
- Document AI
- Contract Analysis
- Field Extraction
- Classification
- OCR

## Timestamps

- **Created:** 2026-06-21
- **Modified:** 2026-06-21

## APIs

### Zuva Files API

Upload document files for processing and receive a file_id used by the OCR, extraction, and classification services. Supports file expiration management and deletion.

- **Human URL:** [https://zuva.ai/documentation/services/file-submission/](https://zuva.ai/documentation/services/file-submission/)
- **Base URL:** `https://us.app.zuva.ai/api/v2`

#### Tags

- Files
- Upload
- Storage

#### Properties

- [Documentation](https://zuva.ai/documentation/services/file-submission/)
- [API Reference](https://api-reference.zuva.ai/)
- [OpenAPI](openapi/zuva-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/zuva.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/zuva.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Zuva Field Extraction API

Asynchronously extract structured values for specified field IDs from uploaded documents using 1,400+ pre-built fields, returning text spans and locations. Submit a request, poll its status, then retrieve text results.

- **Human URL:** [https://zuva.ai/documentation/services/field-extraction/](https://zuva.ai/documentation/services/field-extraction/)
- **Base URL:** `https://us.app.zuva.ai/api/v2`

#### Tags

- Field Extraction
- Contracts
- NLP

#### Properties

- [Documentation](https://zuva.ai/documentation/workflows/field-extraction-workflow/)
- [API Reference](https://api-reference.zuva.ai/)
- [OpenAPI](openapi/zuva-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/zuva.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/zuva.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Zuva Classification API

Asynchronously classify documents across 220+ document types via the multi-level classification (MLC) service, returning the document type, language, and amendment status.

- **Human URL:** [https://zuva.ai/documentation/services/document-classification/](https://zuva.ai/documentation/services/document-classification/)
- **Base URL:** `https://us.app.zuva.ai/api/v2`

#### Tags

- Classification
- Document Types
- Multi-Level Classification

#### Properties

- [Documentation](https://zuva.ai/documentation/workflows/classification-workflow/)
- [API Reference](https://api-reference.zuva.ai/)
- [OpenAPI](openapi/zuva-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/zuva.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/zuva.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Zuva Language API

Detect the primary language of a document. Language is returned as part of the multi-level classification (MLC) results; there is no standalone language endpoint.

- **Human URL:** [https://zuva.ai/documentation/services/language-classification/](https://zuva.ai/documentation/services/language-classification/)
- **Base URL:** `https://us.app.zuva.ai/api/v2`

#### Tags

- Language
- Detection
- Classification

#### Properties

- [Documentation](https://zuva.ai/documentation/services/language-classification/)
- [API Reference](https://api-reference.zuva.ai/)
- [OpenAPI](openapi/zuva-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/zuva.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/zuva.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Zuva OCR API

Asynchronously run optical character recognition on uploaded documents, returning extracted text, per-page PNG images, eOCR documents, and layout protobuf data with scan quality metrics.

- **Human URL:** [https://zuva.ai/documentation/services/using-ocr/](https://zuva.ai/documentation/services/using-ocr/)
- **Base URL:** `https://us.app.zuva.ai/api/v2`

#### Tags

- OCR
- Text
- Images

#### Properties

- [Documentation](https://zuva.ai/documentation/services/using-ocr/)
- [API Reference](https://api-reference.zuva.ai/)
- [OpenAPI](openapi/zuva-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/zuva.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/zuva.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Zuva Fields Catalog API

List and manage the catalog of available extraction fields, including creating custom fields and reading or updating field metadata such as name and description.

- **Human URL:** [https://zuva.ai/documentation/services/field-extraction/](https://zuva.ai/documentation/services/field-extraction/)
- **Base URL:** `https://us.app.zuva.ai/api/v2`

#### Tags

- Fields
- Catalog
- Metadata

#### Properties

- [Documentation](https://zuva.ai/documentation/services/field-extraction/)
- [API Reference](https://api-reference.zuva.ai/)
- [OpenAPI](openapi/zuva-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/zuva.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/zuva.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [GitHub Organization](https://github.com/zuvaai)
- [LinkedIn](https://www.linkedin.com/company/zuva-inc)
- [Website](https://zuva.ai/)
- [Documentation](https://zuva.ai/documentation/)
- [Plans](plans/zuva-plans-pricing.yml)
- [Rate Limits](rate-limits/zuva-rate-limits.yml)
- [Fin Ops](finops/zuva-finops.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
