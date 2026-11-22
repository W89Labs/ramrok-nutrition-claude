---
name: barcode-lookup
description: Find one exact packaged-food match by UPC or EAN in RAMROK.
---

Pass the code to `lookup_barcode` as a string so leading zeros survive. Use the returned product and nutrition panel for an exact match. To scale it, pass its exact returned `foodId` to `calculate_portion`. If results disagree, check the brand, package and serving before selecting.

If no exact match is returned, say so. You may search by brand and product name if available, but label any resulting match as a candidate. Preserve the matched record's GTIN, edition and nutrition basis.
