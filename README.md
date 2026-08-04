# Voiden

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

Voiden is an offline-first, Git-native API workspace that unifies API design, testing, and documentation in plain Markdown `.void` files stored alongside your codebase. It uses composable, reusable blocks (endpoints, auth, headers, params, bodies) that behave like code — inheritable, versionable, and composable — eliminating copy-paste drift across API definitions.

- **Website:** [https://voiden.md/](https://voiden.md/)
- **GitHub:** [https://github.com/VoidenHQ/voiden](https://github.com/VoidenHQ/voiden)
- **Blog:** [https://voiden.md/blog/](https://voiden.md/blog/)

## Tools

### Voiden Desktop Tool

Voiden is a desktop application (Electron/TypeScript) for API design, testing, and documentation using the `.void` file format. Supports REST, GraphQL, WebSocket, and gRPC workflows. Apache 2.0 licensed.

- **Documentation:** [https://voiden.md/](https://voiden.md/)
- **Source:** [https://github.com/VoidenHQ/voiden](https://github.com/VoidenHQ/voiden)

## Artifacts

### JSON Schema

| Schema | Description |
|--------|-------------|
| [json-schema/voiden-void-file-schema.json](json-schema/voiden-void-file-schema.json) | Schema for Voiden .void file format |

### JSON Structure

| Structure | Description |
|-----------|-------------|
| [json-structure/voiden-void-file-structure.json](json-structure/voiden-void-file-structure.json) | .void file field-level documentation |

### JSON-LD Context

| Context | Description |
|---------|-------------|
| [json-ld/voiden-context.jsonld](json-ld/voiden-context.jsonld) | Linked data context for Voiden resources |

### Vocabulary

| Vocabulary | Description |
|------------|-------------|
| [vocabulary/voiden-vocabulary.yml](vocabulary/voiden-vocabulary.yml) | Voiden domain vocabulary and terminology |

## Scope

- **Type:** Index
- **Tags:** API Design, API Testing, API Documentation, Developer Tools, Git Native, Markdown

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
