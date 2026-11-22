---
name: recipe-nutrition
description: Sum nutrition across recipe ingredients or calculate totals and per-serving amounts for a measured recipe.
---

Use `analyze_ingredients` to sum named ingredients with known quantities. Use `analyze_recipe` for servings and optional measured final yield. Check `get_catalog_capabilities` for the applicable tool when permission is uncertain. Explain missing access without invoking billing.

Identify each ingredient first and resolve it to a catalog `foodId`. Use weighed grams or a supported catalog serving for that ingredient. An ingredient with per-100-mL facts can be measured in milliliters, and if any input weight is unknown, report nutrition per serving and use the supplied final recipe weight if a serving weight is needed. Reuse quantities and preparations already provided. Rephrase the search or select a reasonable compatible reference before asking about a remaining material ambiguity. One request accepts up to 24 ingredient lines. Report totals, per-serving amounts when requested, and applicable units, selected food IDs and editions. Preserve nutrients with incomplete ingredient coverage as unknown. A package ingredient list does not supply quantities for reconstructing a recipe.
