# Zuva (zuva)

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
