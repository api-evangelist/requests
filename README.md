# Requests (requests)

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
