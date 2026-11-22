---
name: nutrition-facts
description: Read the nutrient profile for one identified RAMROK food, including calories, macros, vitamins, minerals and missing values.
---

Resolve the food and preparation if its catalog ID is unknown. Use `get_nutrient_profile` for the selected food ID. Report the returned basis and units, and carry the record's food ID and edition. Keep explicitly measured zero distinct from an unreported value. Use `calculate_portion` if the user wants a different amount.
