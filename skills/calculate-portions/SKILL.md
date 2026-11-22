---
name: calculate-portions
description: Scale an identified RAMROK food to a given serving weight, volume or supported household measure.
---

Call `calculate_portion` with the exact `foodId` returned by search or barcode lookup and the requested measure. Use a kitchen measure only when the record includes a matching serving for that food. If the record lacks that measure, use any compatible weight or volume already supplied. Ask for a measurement only when the requested calculation still needs one.

Report the returned amount, basis, units and catalog edition. Preserve missing nutrients. For raw pear fdc-169118, a 150 g request returns 85.5 kcal in the reference edition.
