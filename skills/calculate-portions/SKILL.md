---
name: calculate-portions
description: Scale an identified RAMROK food to a given serving weight, volume or supported household measure.
---

Call `calculate_portion` with the exact `foodId` returned by search or barcode lookup and the requested measure. Use a kitchen measure only when the source provides a matching serving for that food. Otherwise ask for a weighed amount in grams.

Report the returned amount, basis, units and source edition. Preserve missing nutrients. For USDA raw pear 169118, a 150 g request returns 85.5 kcal in the reference edition.
