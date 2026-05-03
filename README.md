# Spin.AI

Spin.AI is a SaaS security platform providing data protection, ransomware detection, and compliance management for cloud applications including Google Workspace, Microsoft 365, Salesforce, and Slack. The SpinOne Public API enables programmatic integration for managing backup entity lifecycle, auditing coverage gaps, and automating status changes across enterprise SaaS environments.

## APIs

### Spin.AI SpinOne API

The SpinOne Public API provides programmatic access to SaaS data protection management with three REST endpoints for retrieving, filtering, and updating backup entity status.

- **Documentation:** https://spin.ai/help/gworkspace-administration/setting-up-public-api
- **Swagger UI (AWS):** https://apg-1.spin.ai/swagger-ui/
- **Swagger UI (GCP):** https://apg-2.spin.ai/swagger-ui/
- **Swagger UI (Azure):** https://apg-3.spin.ai/swagger-ui/
- **OpenAPI:** [openapi/spin-ai-openapi.yml](openapi/spin-ai-openapi.yml)

## OpenAPI Specifications

| API | File |
|-----|------|
| Spin.AI SpinOne API | [openapi/spin-ai-openapi.yml](openapi/spin-ai-openapi.yml) |

## Spectral Rules

| Ruleset | File |
|---------|------|
| Spin.AI Rules | [rules/spin-ai-rules.yml](rules/spin-ai-rules.yml) |

## Capabilities

| Capability | Description | File |
|------------|-------------|------|
| SaaS Data Protection | Entity backup management across cloud platforms | [capabilities/saas-data-protection.yaml](capabilities/saas-data-protection.yaml) |

### Shared Definitions

| API | File |
|-----|------|
| Spin.AI | [capabilities/shared/spin-ai.yaml](capabilities/shared/spin-ai.yaml) |

## JSON Schema

| Schema | File |
|--------|------|
| Backup Entity | [json-schema/spin-ai-entity-schema.json](json-schema/spin-ai-entity-schema.json) |

## JSON Structure

| Structure | File |
|-----------|------|
| Backup Entity | [json-structure/spin-ai-entity-structure.json](json-structure/spin-ai-entity-structure.json) |

## JSON-LD

| Context | File |
|---------|------|
| Spin.AI Context | [json-ld/spin-ai-context.jsonld](json-ld/spin-ai-context.jsonld) |

## Examples

| Example | File |
|---------|------|
| Get All Entities | [examples/spin-ai-get-all-entities-example.json](examples/spin-ai-get-all-entities-example.json) |
| Update Entity Status | [examples/spin-ai-update-entity-status-example.json](examples/spin-ai-update-entity-status-example.json) |

## Vocabulary

| Vocabulary | File |
|------------|------|
| Spin.AI Vocabulary | [vocabulary/spin-ai-vocabulary.yml](vocabulary/spin-ai-vocabulary.yml) |

## Links

- **Website:** https://www.spin.ai
- **Help Center:** https://spin.ai/help/
- **Integrations:** https://spin.ai/integrations/
- **Support:** https://spin.ai/support/
- **Blog:** https://spin.ai/blog/
- **LinkedIn:** https://www.linkedin.com/company/spin-ai/
- **Terms of Service:** https://spin.ai/terms-of-service/
- **Privacy Policy:** https://spin.ai/privacy-policy/
