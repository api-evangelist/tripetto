# Tripetto

Tripetto is a powerful form builder platform and SDK that enables developers to create smart, conversational forms and surveys with advanced conditional logic. The platform provides a JavaScript/TypeScript SDK for embedding form builders and runners into web applications, along with webhook capabilities for delivering form responses to external services and automation platforms.

**Website:** [https://tripetto.com/](https://tripetto.com/)
**Documentation:** [https://tripetto.com/sdk/docs/](https://tripetto.com/sdk/docs/)

---

## APIs

### Tripetto FormBuilder SDK
The Tripetto FormBuilder SDK provides JavaScript and TypeScript APIs for embedding interactive form builders into web applications. Supports React, Angular, and plain JavaScript integration with a rich component model for building, running, and collecting responses from smart conversational forms.

- **Documentation:** [https://tripetto.com/sdk/docs/](https://tripetto.com/sdk/docs/)
- **Builder API Reference:** [https://tripetto.com/sdk/docs/builder/api/](https://tripetto.com/sdk/docs/builder/api/)
- **npm Package:** [https://www.npmjs.com/package/@tripetto/builder](https://www.npmjs.com/package/@tripetto/builder)
- **OpenAPI:** [openapi/tripetto-form-builder-openapi.yml](openapi/tripetto-form-builder-openapi.yml)

### Tripetto Webhooks
Tripetto supports outbound webhooks that deliver form response data to external services and automation platforms including Make, Zapier, and Pabbly Connect.

- **Documentation:** [https://tripetto.com/help/articles/how-to-automate-a-webhook-to-connect-to-other-services-for-each-new-result/](https://tripetto.com/help/articles/how-to-automate-a-webhook-to-connect-to-other-services-for-each-new-result/)

---

## Artifacts

### OpenAPI Specifications
| Spec | Description |
|---|---|
| [tripetto-form-builder-openapi.yml](openapi/tripetto-form-builder-openapi.yml) | Forms, responses, and webhook management API |

### JSON Schemas
| Schema | Description |
|---|---|
| [tripetto-form-schema.json](json-schema/tripetto-form-schema.json) | Tripetto form with definition metadata |
| [tripetto-response-schema.json](json-schema/tripetto-response-schema.json) | Collected form response with field values |

### JSON Structure
| File | Description |
|---|---|
| [tripetto-form-structure.json](json-structure/tripetto-form-structure.json) | Structure documentation for form and response objects |

### JSON-LD Context
| File | Description |
|---|---|
| [tripetto-context.jsonld](json-ld/tripetto-context.jsonld) | Linked data context mapping Tripetto vocabulary |

### Spectral Rules
| Ruleset | Description |
|---|---|
| [tripetto-rules.yml](rules/tripetto-rules.yml) | API linting rules enforcing Tripetto conventions |

### Naftiko Capabilities
| Capability | Description |
|---|---|
| [form-management.yaml](capabilities/form-management.yaml) | Form lifecycle management workflow |

**Shared Definitions:**
| File | Description |
|---|---|
| [shared/tripetto-form-builder.yaml](capabilities/shared/tripetto-form-builder.yaml) | Tripetto FormBuilder SDK API consumed definition |

### Examples
| Example | Description |
|---|---|
| [tripetto-list-forms-example.json](examples/tripetto-list-forms-example.json) | List forms request/response |
| [tripetto-list-form-responses-example.json](examples/tripetto-list-form-responses-example.json) | List form responses request/response |

### Vocabulary
| File | Description |
|---|---|
| [tripetto-vocabulary.yml](vocabulary/tripetto-vocabulary.yml) | Domain vocabulary for the Tripetto platform |

---

## Common Resources

- **Help Center:** [https://tripetto.com/help/](https://tripetto.com/help/)
- **Tutorials:** [https://tripetto.com/tutorials/](https://tripetto.com/tutorials/)
- **Pricing:** [https://tripetto.com/pricing/](https://tripetto.com/pricing/)
- **GitLab:** [https://gitlab.com/tripetto](https://gitlab.com/tripetto)
- **npm:** [https://www.npmjs.com/org/tripetto](https://www.npmjs.com/org/tripetto)

---

*Profiled: 2026-05*
