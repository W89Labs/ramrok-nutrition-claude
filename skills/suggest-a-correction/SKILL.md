---
name: suggest-a-correction
description: Propose one evidence-backed correction to a RAMROK catalog record for review.
---

Check `get_catalog_capabilities` for `submit_food_correction` and explicit `foods:submit` permission before preparing a write. If unavailable, explain that the connected project cannot send proposals. The standard directory connection requests read and recipe scopes.

Confirm the exact record, changed fields, evidence reference and private or shared-review choice with the user before submitting. Keep patient details and third-party label photos out of the proposal. Send one stable idempotency key and preserve it if retrying the same proposal. Report the returned ticket and use `get_submission_status` to follow it. A proposal goes to review, where an authorized reviewer decides whether to accept it.
