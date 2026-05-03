# Shutterstock

Shutterstock is a leading global technology company providing high-quality images, videos, audio tracks, sound effects, and editorial content to businesses, individuals, and organizations worldwide. With a library of over 350 million assets, Shutterstock offers royalty-free creative content for marketing campaigns, website designs, social media, and more. The Shutterstock API provides programmatic access to search, browse, license, and download media assets, manage collections, access computer vision features, and handle OAuth 2.0 authentication.

**Human URL:** [https://www.shutterstock.com/developers](https://www.shutterstock.com/developers)

## APIs

### Shutterstock API v2
- **Documentation:** https://www.shutterstock.com/developers/documentation
- **API Reference:** https://api-reference.shutterstock.com/
- **Base URL:** `https://api.shutterstock.com`
- **Getting Started:** https://www.shutterstock.com/developers/documentation/getting-started
- **Authentication:** OAuth 2.0 (required for licensing) or Basic Auth (for search/browse)
- **SDK:** https://www.shutterstock.com/developers/documentation/javascript-sdk
- **Plans:** https://www.shutterstock.com/api/pricing

## Artifacts

### OpenAPI Specifications
- [shutterstock-openapi.yml](openapi/shutterstock-openapi.yml) — Complete Shutterstock API v2 with 74 paths and 95 operations (images, videos, audio, editorial, CV, collections, users, OAuth)

### JSON Schemas
- [shutterstock-image-schema.json](json-schema/shutterstock-image-schema.json)
- [shutterstock-video-schema.json](json-schema/shutterstock-video-schema.json)

### JSON Structure
- [shutterstock-image-structure.json](json-structure/shutterstock-image-structure.json)

### JSON-LD Context
- [shutterstock-context.jsonld](json-ld/shutterstock-context.jsonld)

### Examples
- [shutterstock-search-images-example.json](examples/shutterstock-search-images-example.json) — Search stock photos by keyword and color
- [shutterstock-license-image-example.json](examples/shutterstock-license-image-example.json) — License a stock image for download

### Rules
- [shutterstock-rules.yml](rules/shutterstock-rules.yml)

### Capabilities
- [media-search-and-licensing.yaml](capabilities/media-search-and-licensing.yaml) — Images, videos, audio, editorial, computer vision, collections, and user management for stock media workflows

### Vocabulary
- [shutterstock-vocabulary.yml](vocabulary/shutterstock-vocabulary.yml)

## Maintainers

**Kin Lane** - kin@apievangelist.com
