# TypeSpec

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
