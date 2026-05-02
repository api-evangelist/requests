# Requests (requests)
Requests is a simple and elegant HTTP library for Python, designed for human beings. Published under the Apache2 license by the Python Software Foundation (PSF), it is one of the most downloaded Python packages with approximately 300 million weekly downloads and over 4 million dependent repositories.

Requests abstracts urllib3 to provide idiomatic HTTP method functions (`get`, `post`, `put`, `patch`, `delete`, `head`, `options`), persistent Sessions with connection pooling, automatic content decompression, TLS/SSL verification, Basic and Digest authentication, cookie persistence, streaming downloads, multipart file uploads, SOCKS proxy support, and configurable timeouts.

Current stable version: **2.33.1** (March 2026). Supports Python 3.10+.

**URL:** [Visit APIs.json](https://raw.githubusercontent.com/api-evangelist/requests/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Consuming
- **Access:** 3rd-Party

## Tags

Clients, HTTP Client, HTTP Library, Open Source, Python, Python Software Foundation

## JSON Schemas

| Schema | Description |
|--------|-------------|
| [Requests Request Schema](json-schema/requests-request-schema.json) | Parameters accepted by requests.request() and convenience methods |
| [Requests Response Schema](json-schema/requests-response-schema.json) | Attributes of the requests.Response object |

## JSON Structures

| Structure | Description |
|-----------|-------------|
| [Requests Response Structure](json-structure/requests-response-structure.json) | Field-level documentation for requests.Response |

## JSON-LD Context

| Context | Description |
|---------|-------------|
| [Requests Context](json-ld/requests-context.jsonld) | JSON-LD context mapping Requests HTTP concepts to Hydra and schema.org |

## Examples

| Example | Description |
|---------|-------------|
| [GET Request Example](examples/requests-get-example.json) | Example GET call to the GitHub API |
| [POST Request Example](examples/requests-post-example.json) | Example POST call with JSON body |

## Vocabulary

| Vocabulary | Description |
|------------|-------------|
| [Requests Vocabulary](vocabulary/requests-vocabulary.yml) | Domain vocabulary for the Requests programming model, features, and ecosystem |

## References

- [Documentation](https://requests.readthedocs.io/en/latest/)
- [API Reference](https://requests.readthedocs.io/en/latest/api/)
- [GitHub Repository (psf/requests)](https://github.com/psf/requests)
- [PyPI Package](https://pypi.org/project/requests/)

## Timestamps

- **Created:** 2026-03-27
- **Modified:** 2026-05-02

## Maintainers

**FN:** Kin Lane  
**Email:** kin@apievangelist.com
