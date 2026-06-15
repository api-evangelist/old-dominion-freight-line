# Old Dominion Freight Line (old-dominion-freight-line)

Old Dominion Freight Line is a leading less-than-truckload (LTL) motor carrier providing regional, inter-regional, and national freight services in the United States. ODFL offers a suite of REST web services for shippers and partners to integrate freight booking, pickup, tracking, document retrieval, and electronic bill of lading capabilities directly into their systems.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/old-dominion-freight-line/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/old-dominion-freight-line/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Consumer
- **Access:** 3rd-Party

## Tags

- Freight
- Less-Than-Truckload
- Logistics
- Shipping
- Transportation

## Timestamps

- **Created:** 2026-03-24
- **Modified:** 2026-05-19

## APIs

### ODFL Bill of Lading API

Submits electronic bills of lading to the Old Dominion Freight Line billing system, generating shipping labels and BOL documents. Used by shippers to programmatically create freight documentation.

- **Human URL:** [https://www.odfl.com/us/en/resources/shipping-api-integrations.html](https://www.odfl.com/us/en/resources/shipping-api-integrations.html)
- **Base URL:** `https://www.odfl.com`

#### Tags

- Bill of Lading
- Documents
- Freight
- Shipping

#### Properties

- [Documentation](https://www.odfl.com/content/dam/odfl/us/en/documents/web-services/Bill%20of%20Lading%20API%20Development%20Guide.pdf)
- [OpenAPI](https://raw.githubusercontent.com/api-evangelist/old-dominion-freight-line/refs/heads/main/openapi/old-dominion-freight-line-bill-of-lading-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/old-dominion-freight-line-bill-of-lading-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/old-dominion-freight-line-bill-of-lading-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/old-dominion-freight-line-document-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/old-dominion-freight-line-document-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/old-dominion-freight-line-pickup-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/old-dominion-freight-line-pickup-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/old-dominion-freight-line-tracking-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/old-dominion-freight-line-tracking-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### ODFL Pickup API

Processes electronic pickup requests for one or more shipments. Returns pickup numbers and PPIDs that shippers use to confirm and track pickup requests with Old Dominion Freight Line.

- **Human URL:** [https://www.odfl.com/us/en/resources/shipping-api-integrations.html](https://www.odfl.com/us/en/resources/shipping-api-integrations.html)
- **Base URL:** `https://www.odfl.com`

#### Tags

- Freight
- Logistics
- Pickup
- Shipping

#### Properties

- [Documentation](https://www.odfl.com/content/dam/odfl/us/en/documents/web-services/Pickup%20API%20Development%20Guide.pdf)
- [OpenAPI](https://raw.githubusercontent.com/api-evangelist/old-dominion-freight-line/refs/heads/main/openapi/old-dominion-freight-line-pickup-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/old-dominion-freight-line-bill-of-lading-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/old-dominion-freight-line-bill-of-lading-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/old-dominion-freight-line-document-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/old-dominion-freight-line-document-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/old-dominion-freight-line-pickup-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/old-dominion-freight-line-pickup-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/old-dominion-freight-line-tracking-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/old-dominion-freight-line-tracking-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### ODFL Tracking API

Provides shipment status information for ODFL freight movements. Used to integrate real-time and historical freight tracking data into shipper and partner systems.

- **Human URL:** [https://www.odfl.com/us/en/resources/shipping-api-integrations.html](https://www.odfl.com/us/en/resources/shipping-api-integrations.html)
- **Base URL:** `https://www.odfl.com`

#### Tags

- Freight
- Shipping
- Tracking

#### Properties

- [Documentation](https://www.odfl.com/content/dam/odfl/us/en/documents/web-services/Tracking%20API%20Development%20Guide.pdf)
- [OpenAPI](https://raw.githubusercontent.com/api-evangelist/old-dominion-freight-line/refs/heads/main/openapi/old-dominion-freight-line-tracking-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/old-dominion-freight-line-bill-of-lading-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/old-dominion-freight-line-bill-of-lading-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/old-dominion-freight-line-document-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/old-dominion-freight-line-document-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/old-dominion-freight-line-pickup-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/old-dominion-freight-line-pickup-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/old-dominion-freight-line-tracking-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/old-dominion-freight-line-tracking-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### ODFL Document API

Retrieves PDF documents associated with shipments, including bills of lading and delivery receipts, by PRO number. Used to programmatically pull shipment documentation from Old Dominion Freight Line.

- **Human URL:** [https://www.odfl.com/us/en/resources/shipping-api-integrations.html](https://www.odfl.com/us/en/resources/shipping-api-integrations.html)
- **Base URL:** `https://www.odfl.com`

#### Tags

- Documents
- Freight
- Shipping

#### Properties

- [Documentation](https://www.odfl.com/content/dam/odfl/us/en/documents/web-services/Document%20API%20Development%20Guide.pdf)
- [OpenAPI](https://raw.githubusercontent.com/api-evangelist/old-dominion-freight-line/refs/heads/main/openapi/old-dominion-freight-line-document-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/old-dominion-freight-line-bill-of-lading-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/old-dominion-freight-line-bill-of-lading-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/old-dominion-freight-line-document-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/old-dominion-freight-line-document-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/old-dominion-freight-line-pickup-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/old-dominion-freight-line-pickup-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/old-dominion-freight-line-tracking-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/old-dominion-freight-line-tracking-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [LinkedIn](https://www.linkedin.com/company/old-dominion-freight-line)
- [Website](https://www.odfl.com)
- [Developer](https://www.odfl.com/us/en/resources/shipping-api-integrations.html)
- [Support](mailto:api@odfl.com)
- [Tools](https://www.odfl.com/us/en/resources.html)

## Maintainers

**FN:** API Evangelist
**Email:** info@apievangelist.com
