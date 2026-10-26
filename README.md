# DeepL (deepl)

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
