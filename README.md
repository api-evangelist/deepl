# DeepL (deepl)

DeepL is an AI-powered translation service that delivers high-quality machine translation between dozens of languages, with support for context-aware translation, document translation, glossaries, and rephrasing/improvement via DeepL Write. The DeepL API is offered in Pro and Free tiers and exposes endpoints for text translation, document translation, glossaries, language metadata, usage, and write/rephrase.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/deepl/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/deepl/refs/heads/main/apis.yml)

## Scope

- **Position:** Consuming
- **Access:** 3rd-Party

## Tags

- Artificial Intelligence
- Deep Learning
- Glossaries
- Localization
- Machine Learning
- Machine Translation
- Translation

## Timestamps

- **Created:** 2024-11-07
- **Modified:** 2026-05-30

## APIs

### DeepL Translation API

The DeepL Translation API provides programmatic access to DeepL's machine translation technology including text translate, document translate, glossaries, language metadata, usage, and DeepL Write rephrasing.

- **Human URL:** [https://developers.deepl.com/](https://developers.deepl.com/)
- **Base URL:** `https://api.deepl.com/v2`

#### Tags

- Documents
- Glossaries
- Languages
- Translate
- Usage
- Write

#### Properties

- [Documentation](https://developers.deepl.com/docs)
- [Reference](https://developers.deepl.com/docs/api-reference)
- [OpenAPI](openapi/deepl-translation-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/deepl-translation-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/deepl-translation-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/deepl-translation.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/deepl-glossary.json) — [JSON Schema](https://json-schema.org/specification)
- [Rules](rules/deepl-translation-api-rules.yml)
- [Capabilities](capabilities/deepl-translation-api-capabilities.yml)

### DeepL Voice API

The DeepL Voice API provides real-time speech transcription and translation. A POST to /v3/voice/realtime issues an ephemeral token and WebSocket streaming URL; clients then open a WSS channel to stream source audio chunks and receive incremental source-language transcriptions, translated transcriptions, and (closed beta) synthesized translated audio. There is no documented webhook callback URL on the REST APIs; document translation remains polling-based.

- **Human URL:** [https://developers.deepl.com/api-reference/voice](https://developers.deepl.com/api-reference/voice)
- **Base URL:** `https://api.deepl.com/v3`

#### Tags

- Real-Time
- Speech-to-Text
- Streaming
- Transcription
- Translation
- Voice
- WebSocket

#### Properties

- [Documentation](https://developers.deepl.com/api-reference/voice)
- [Reference](https://developers.deepl.com/api-reference/voice/websocket-streaming)
- [OpenAPI](openapi/deepl-voice-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/deepl-voice-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/deepl-voice-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [AsyncAPI](asyncapi/deepl-voice-api-asyncapi.yml) — [AsyncAPI Specification](https://www.asyncapi.com/docs/reference/specification/latest)
- [AsyncAPI](https://developers.deepl.com/api-reference/voice.asyncapi.yaml) — [AsyncAPI Specification](https://www.asyncapi.com/docs/reference/specification/latest)

## Common Properties

- [LinkedIn](https://www.linkedin.com/company/deepl)
- [Website](https://www.deepl.com/)
- [Portal](https://developers.deepl.com/)
- [Documentation](https://developers.deepl.com/docs)
- [Authentication](https://developers.deepl.com/docs/getting-started/auth)
- [Pricing](https://www.deepl.com/pro)
- [SDK](https://github.com/DeepLcom/deepl-python)
- [SDK](https://github.com/DeepLcom/deepl-node)
- [Terms of Service](https://www.deepl.com/pro-license)
- [Privacy Policy](https://www.deepl.com/privacy)
- [JSON-LD](json-ld/deepl-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [Vocabulary](vocabulary/deepl-vocabulary.yml)
- [Integrations](https://www.deepl.com/en/integrations)
- [L L Ms Txt](https://developers.deepl.com/llms.txt)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
