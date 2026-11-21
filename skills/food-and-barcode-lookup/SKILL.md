---
name: food-and-barcode-lookup
description: Find the right generic or packaged food in RAMROK by name, brand, preparation or UPC. Use for label lookups, missing barcodes and source selection.
---

Use `lookup_barcode` first for a package code. Keep all digits, including leading zeros. A successful response already includes the food and its nutrient panel. If the code misses, search with the brand and product name and describe an uncertain match as a candidate.

For generic foods use `search_foods` and match preparation before retrieving detail. Raw, cooked and drained records can have different nutrition. Ask which one the user meant when that choice materially changes the result.

Use `catalog=white-label` when the caller needs eligible source data. Carry the selected record’s ID, edition, basis and rights into the result. A food name, barcode and serving weight identify a product. They do not identify a person or a health record.
