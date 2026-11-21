---
name: calculate-portions
description: Scale an identified RAMROK food to a given serving weight, volume or supported household measure.
---

Call `calculate_portion` with the food ID and the requested measure. Use a record's supported measure ID when the user names a household measure. Ask for a weight or clarify which measure applies when the source has no matching conversion.

Report the returned amount, basis, units and source edition. Preserve missing nutrients. For USDA raw pear 169118, a 150 g request returns 85.5 kcal in the reference edition.
