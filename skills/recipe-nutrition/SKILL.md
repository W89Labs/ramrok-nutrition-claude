---
name: recipe-nutrition
description: Calculate total and per-serving nutrition for a recipe using RAMROK food IDs, ingredient quantities and an optional measured final yield.
---

Check `get_catalog_capabilities` for `analyze_recipe`. If the connection has no recipe permission, explain the missing permission. Keep subscriptions and billing outside the assistant.

Resolve each ingredient to a sourced food ID and a supported measure. Ask for the unresolved quantity or preparation that affects the calculation. Pass servings separately from a measured cooked yield. One analysis unit covers up to four ingredient lines, rounded up, and a request accepts at most 24 lines.

Return total and per-serving values with their units and sources. An ingredient with an unknown nutrient makes the combined amount for that nutrient unknown. An ingredient list on a package does not provide the quantities required to reconstruct its recipe.
