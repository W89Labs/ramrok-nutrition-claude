# RAMROK Nutrition Database

Every paid RAMROK Nutrition Cloud plan includes the full hosted food catalog for use in your commercial app. Your customers see your app’s name and logo when they search for a food, scan a barcode, or log a meal. [Catalog licensing](https://nutrition.ramrok.com/licensing#white-label)

The seven skills cover food search, barcode lookup, nutrition facts, portions, comparisons, recipes and reviewed corrections. Sign in through the RAMROK authorization window, choose a project and approve the permissions shown. Keep verification codes and credentials in that window. Use get_catalog_capabilities to see the current edition, allowed tools and usage. The RAMROK catalog returns food IDs, nutrition units, serving bases and catalog editions. A missing nutrient is null and a reported zero is 0.

To scale a match, pass the exact foodId from Search Foods or Barcode Lookup to Calculate Portions. Use a supported catalog serving for a kitchen measure, or weigh it in grams. Recipe Nutrition identifies each ingredient before combining amounts. [Combine tools](https://nutrition.ramrok.com/docs#combine-tools)

[Developer documentation](https://nutrition.ramrok.com/docs)

Projects can propose corrections when their connection exposes the proposal tool and has explicit foods:submit permission. The standard directory connection requests read and recipe scopes. A reviewer evaluates each proposal. [Plugin source](https://github.com/W89Labs/ramrok-nutrition-claude) · [Privacy](https://nutrition.ramrok.com/privacy) · [Support](https://nutrition.ramrok.com/support)
