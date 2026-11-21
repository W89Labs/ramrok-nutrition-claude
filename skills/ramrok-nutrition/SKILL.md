---
name: ramrok-nutrition
description: Connect a RAMROK Nutrition Cloud project, check authorized tools and usage, interpret source rights and route a correction into private review.
---

Sign in through the RAMROK authorization window, choose a project and approve its requested scopes. Keep passwords, API keys, verification codes and OAuth tokens out of chat. For REST, the developer portal issues a key once and supports rotation and deactivation.

Start with `get_catalog_capabilities` to see the current edition, available tools and usage rules. Free gives a verified organization 25 monthly lookup units shared across REST and MCP. Authentication and discovery consume no monthly units. A meal lookup, a barcode and a portion are separate operations. The response itself has no additional charge.

Use food-and-barcode-lookup to choose a record, portion-and-nutrient-comparison for a serving, and recipe-nutrition for ingredient totals. Preserve source distinctions, units and missing values. A 429 response identifies a rate, monthly or record-delivery limit.

Pro and Business connections need explicit foods:submit permission before proposing corrections. Confirm the record, evidence, changes and private or shared-review choice. Send one stable idempotency key and use get_submission_status to follow a proposal. The submitting organization and credential are audited. Only an authorized reviewer can accept a revision. Keep patient details and third-party label photographs out of submissions.
