---
name: search-foods
description: Find foods in RAMROK by name, brand or preparation. Use for name queries such as chicken or a named packaged product.
---

Call `search_foods` with the user's food name. Use brand or preparation if supplied. Match preparation before choosing a result. Raw chicken and cooked chicken can have different nutrition, so clarify when that changes the answer.

Use `get_food` only when the chosen result needs more detail. To scale the match, pass its exact returned `foodId` to `calculate_portion`. For an exact barcode use `lookup_barcode`. For an eligible white-label search, request the white-label catalog and carry the result's food ID, edition, basis and source notices.
