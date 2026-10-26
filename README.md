# Athina AI (athina)

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

Athina AI is an LLM monitoring, evaluation, and experimentation platform for building production-grade AI applications. Its REST API lets teams log inferences and traces, manage datasets, run 50+ preset and custom evaluations, version and run prompt templates, and collaborate on experiments across the full LLM development lifecycle.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/athina/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/athina/refs/heads/main/apis.yml)

## Tags

- AI
- LLM
- Observability
- Evaluation
- Monitoring

## Timestamps

- **Created:** 2026-06-20
- **Modified:** 2026-06-20

## APIs

### Athina Logging & Inferences API

Log LLM inferences and prompt runs (prompt, response, model, tokens, cost, context, customer/session metadata), update logs by id or external reference, and build nested traces with spans for end-to-end observability.

- **Human URL:** [https://docs.athina.ai/api-reference/logging/log-via-api-request](https://docs.athina.ai/api-reference/logging/log-via-api-request)
- **Base URL:** `https://api.athina.ai/api/v1`

#### Tags

- Logging
- Inferences
- Tracing
- Observability

#### Properties

- [Documentation](https://docs.athina.ai/api-reference/logging/log-via-api-request)
- [API Reference](https://docs.athina.ai/api-reference/logging/tracing-via-api)
- [OpenAPI](openapi/athina-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/athina.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/athina.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Athina Datasets API

Create datasets, list and retrieve datasets, add up to 1000 rows (query, context, response, expected_response and custom fields), update individual cells, and delete datasets used as inputs for evaluations and experiments.

- **Human URL:** [https://docs.athina.ai/api-reference/datasets/create-dataset](https://docs.athina.ai/api-reference/datasets/create-dataset)
- **Base URL:** `https://api.athina.ai/api/v1`

#### Tags

- Datasets
- Data Management
- Evaluation Data

#### Properties

- [Documentation](https://docs.athina.ai/api-reference/datasets/create-dataset)
- [API Reference](https://docs.athina.ai/api-reference/datasets/add-rows-to-dataset)
- [OpenAPI](openapi/athina-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/athina.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/athina.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Athina Evaluations API

Run single evaluations or suites of 50+ preset and custom evals (RAG, summarization, function-calling, safety) against datasets and logged inferences, with results surfaced in the Athina platform.

- **Human URL:** [https://docs.athina.ai/api-reference/evals/preset-evals/overview](https://docs.athina.ai/api-reference/evals/preset-evals/overview)
- **Base URL:** `https://api.athina.ai/api/v1`

#### Tags

- Evaluation
- Evals
- Quality

#### Properties

- [Documentation](https://docs.athina.ai/api-reference/evals/preset-evals/overview)
- [API Reference](https://docs.athina.ai/api-reference/evals/running-evals/run-single-eval)
- [OpenAPI](openapi/athina-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/athina.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/athina.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Athina Prompts API

Create and version prompt templates by slug, fetch the default version, and run a prompt by slug with input variables, model, and parameters (temperature, max_tokens, top_p, penalties) for managed prompt execution.

- **Human URL:** [https://docs.athina.ai/prompts/overview](https://docs.athina.ai/prompts/overview)
- **Base URL:** `https://api.athina.ai/api/v1`

#### Tags

- Prompts
- Prompt Management
- Versioning

#### Properties

- [Documentation](https://docs.athina.ai/prompts/overview)
- [API Reference](https://docs.athina.ai/prompts/run-prompt)
- [OpenAPI](openapi/athina-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/athina.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/athina.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Athina Experiments API

Compare prompts, models, and parameters across datasets by combining versioned prompt runs with evaluations, enabling side-by-side experimentation over the prompt and dataset APIs.

- **Human URL:** [https://docs.athina.ai/prompts/overview](https://docs.athina.ai/prompts/overview)
- **Base URL:** `https://api.athina.ai/api/v1`

#### Tags

- Experiments
- Comparison
- Prompt Engineering

#### Properties

- [Documentation](https://docs.athina.ai/prompts/overview)
- [API Reference](https://docs.athina.ai/prompts/run-prompt)
- [OpenAPI](openapi/athina-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/athina.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/athina.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [GitHub Organization](https://github.com/athina-ai)
- [LinkedIn](https://www.linkedin.com/company/athina-ai)
- [Website](https://www.athina.ai)
- [Documentation](https://docs.athina.ai)
- [Plans](plans/athina-plans-pricing.yml)
- [Rate Limits](rate-limits/athina-rate-limits.yml)
- [Fin Ops](finops/athina-finops.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
