---
name: portion-and-nutrient-comparison
description: Scale a RAMROK food to a serving weight or compare foods on the same basis. Use for calories, macros, fatty acids, vitamins and minerals.
---

Read the food’s declared basis. Use `calculate_portion` with grams, milliliters or a supported measure ID for that particular food. Ask which preparation or measure applies when the source has multiple cups or spoon sizes. Leave unsupported conversions unresolved.

Use `compare_foods` for a comparison at a common weight, then report the basis and units. Use `get_nutrient_profile` for the complete field map and missing indicators. Keep a measured zero and an unreported value distinct. For USDA raw pear, 150 g is 85.5 kcal in the reference edition. Where a result contains source-specific notices, retain the notices with the values.
