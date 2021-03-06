---
title: Seed Oil
image:
- alt: Seed oil
  file: thermal-foundation-2/seed-oil.gif
recipes:
  transposer-empty:
  - seed-oil-from-seeds
  - seed-oil-from-beetroot-seeds
  - seed-oil-from-pumpkin-seeds
  - seed-oil-from-melon-seeds
  - bucket-seed-oil
usage-recipes:
  transposer-fill:
  - bucket-seed-oil
  - biomass-rich
  - bioblend-rich
redirect_from:
- /docs/thermal-foundation/seed-oil/
- /docs/thermal-foundation-2/seed-oil/
- /docs/1.12/thermal-foundation-2/seed-oil/
---

**Seed oil** is a fluid obtained from various kinds of seeds. It can be used to
turn [pulped biomass](../pulped-biomass/) into [rich
biomass](../rich-biomass/) and [pulped
bioblend](../pulped-bioblend/) into [rich
bioblend](../rich-bioblend/). It can also be used as fuel
in a [compression dynamo](../../thermal-expansion/compression-dynamo/).


Obtaining
---------

### Fluid Transposer
{% include recipe-table.html type='te-1-12-transposer-empty' recipes=page.recipes.transposer-empty %}


Usage
-----

Seed oil cannot be placed as a block.

### Fluid Transposer ingredient
{% include recipe-table.html type='te-1-12-transposer-fill' recipes=page.usage-recipes.transposer-fill %}

### Compression Dynamo fuel
When used as fuel in a [compression
dynamo](../../thermal-expansion/compression-dynamo/), a bucket of seed oil
yields 80,000 RF.
