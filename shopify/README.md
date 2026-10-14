# Shopify import files

`products.csv` uses Shopify's product import format (Admin → Products → Import).

- All products import as **draft** (not visible) until reviewed.
- Images load from GitHub Pages (`/images/`). Pages must be on for the import to fetch them.
- Tags:
  - `phase-1` is non-hazmat dropship, the launch set
  - `phase-2` is private label, coming soon
  - `phase-3` is hazmat chemicals and needs ground-hazmat shipping setup
  - `needs-supplier`: supplier, SKU and cost still to confirm
  - `check-hazmat`: confirm the SDS / DOT class before selling
- `Cost per item` is blank on purpose. Fill it in from supplier price lists so Shopify shows margin.
