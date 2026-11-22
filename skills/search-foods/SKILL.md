---
name: search-foods
description: Find foods in RAMROK by name, brand or preparation. Use for name queries such as chicken or a named packaged product.
---

Call `search_foods` with the user's food name. Use brand or preparation if supplied. Use the full request to select a compatible preparation. Rephrase a search if necessary while keeping the stated food, brand and preparation. A suitable plain reference can be used with a stated assumption. Ask one question only when credible alternatives would materially change the answer and the conversation does not distinguish them.

Use `get_food` only when the chosen result needs more detail. To scale the match, pass its exact returned `foodId` to `calculate_portion`. For an exact barcode use `lookup_barcode`. Search the full catalog by default and carry the chosen food ID, edition and basis.
