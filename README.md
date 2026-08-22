# TypeSpec

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

TypeSpec is an API description language developed by Microsoft for defining API shapes that compile to OpenAPI, JSON Schema, Protobuf, and other output formats. It provides a type-safe, composable language for describing REST APIs, gRPC services, and data schemas with built-in versioning, documentation, and extensibility via decorators.

**URL:** [https://typespec.io](https://typespec.io)

## Tags

API Design, Code Generation, OpenAPI, Protocol Buffers, Specification Language

## Timestamps

- **Created:** 2026-03-25
- **Modified:** 2026-05-03

## APIs

### TypeSpec Compiler

Programmatic Node.js/TypeScript API for processing TypeSpec files, running emitters, and building TypeSpec tooling.

**Human URL:** [https://typespec.io/docs](https://typespec.io/docs)

**Tags:** API Design, Code Generation, Compiler, Specification Language

**Properties**
- [Documentation](https://typespec.io/docs)
- [GitHub Repository](https://github.com/microsoft/typespec)
- [npm Package](https://www.npmjs.com/package/@typespec/compiler)
- [Getting Started](https://typespec.io/docs/getting-started/getting-started-rest)

### TypeSpec OpenAPI Emitter

Converts TypeSpec definitions to OpenAPI 3.0 specifications with HTTP operations, security schemes, and versioning.

**Human URL:** [https://typespec.io/docs/emitters/openapi3/reference](https://typespec.io/docs/emitters/openapi3/reference)

**Tags:** Code Generation, OpenAPI, REST API

**Properties**
- [Documentation](https://typespec.io/docs/emitters/openapi3/reference)
- [npm Package](https://www.npmjs.com/package/@typespec/openapi3)

### TypeSpec JSON Schema Emitter

Emits JSON Schema documents from TypeSpec model definitions for data validation workflows.

**Human URL:** [https://typespec.io/docs/emitters/json-schema/reference](https://typespec.io/docs/emitters/json-schema/reference)

**Tags:** Code Generation, JSON Schema, Validation

**Properties**
- [Documentation](https://typespec.io/docs/emitters/json-schema/reference)
- [npm Package](https://www.npmjs.com/package/@typespec/json-schema)

### TypeSpec Protobuf Emitter

Emits `.proto` files for gRPC service definitions from TypeSpec source.

**Human URL:** [https://typespec.io/docs/emitters/protobuf/reference](https://typespec.io/docs/emitters/protobuf/reference)

**Tags:** Code Generation, gRPC, Protocol Buffers

**Properties**
- [Documentation](https://typespec.io/docs/emitters/protobuf/reference)
- [npm Package](https://www.npmjs.com/package/@typespec/protobuf)

### TypeSpec HTTP Library

Decorators and types for describing HTTP REST APIs: routes, operations, request bodies, parameters, headers, and response codes.

**Human URL:** [https://typespec.io/docs/libraries/http/reference](https://typespec.io/docs/libraries/http/reference)

**Tags:** Decorators, HTTP, REST API

**Properties**
- [Documentation](https://typespec.io/docs/libraries/http/reference)
- [npm Package](https://www.npmjs.com/package/@typespec/http)

### TypeSpec REST Library

Decorators for REST API resource patterns including CRUD, collection operations, and error shapes.

**Human URL:** [https://typespec.io/docs/libraries/rest/reference](https://typespec.io/docs/libraries/rest/reference)

**Tags:** Decorators, Resource Pattern, REST API

**Properties**
- [Documentation](https://typespec.io/docs/libraries/rest/reference)
- [npm Package](https://www.npmjs.com/package/@typespec/rest)

## Common Properties

- [Website](https://typespec.io)
- [Documentation](https://typespec.io/docs)
- [GitHub Organization](https://github.com/microsoft/typespec)
- [npm](https://www.npmjs.com/package/@typespec/compiler)
- [Playground](https://typespec.io/playground)
- [Blog](https://typespec.io/blog)
- [Community](https://github.com/microsoft/typespec/discussions)
- [Release Notes](https://github.com/microsoft/typespec/releases)

## Artifacts

### JSON Schemas

| Schema | Description |
|---|---|
| [Program](json-schema/typespec-program-schema.json) | TypeSpec compiled program structure |

### JSON Structures

| Structure | Description |
|---|---|
| [Model](json-structure/typespec-model-structure.json) | TypeSpec model type structure |

### JSON-LD Context

- [TypeSpec Context](json-ld/typespec-context.jsonld)

### Vocabulary

- [TypeSpec Vocabulary](vocabulary/typespec-vocabulary.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
