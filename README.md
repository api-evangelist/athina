# Athina AI (athina)

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
