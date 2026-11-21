---
name: recipe-nutrition
description: Sum nutrition across recipe ingredients or calculate totals and per-serving amounts for a measured recipe.
---

Use `analyze_ingredients` to sum named ingredients with known quantities. Use `analyze_recipe` for servings and optional measured final yield. Check `get_catalog_capabilities` for the applicable tool when permission is uncertain. Explain missing access without invoking billing.

Resolve each ingredient to a sourced food ID and supported measure, and ask for missing amounts or preparations that affect the result. One request accepts up to 24 ingredient lines. Report totals, per-serving amounts when requested, and applicable units, sources and editions. Preserve nutrients with incomplete ingredient coverage as unknown. A package ingredient list does not supply quantities for reconstructing a recipe.
