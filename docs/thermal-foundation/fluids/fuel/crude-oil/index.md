---
title: Crude Oil
recipes:
  crucible:
    - crude-oil-from-bitumen
    - fluid-ore-processing-oil-sand
    - fluid-ore-processing-oil-shale
  transposer-empty:
    - bucket-crude-oil
usage-recipes:
  transposer-fill:
    - bucket-crude-oil
  refinery:
    - naphtha-from-crude-oil
---

![Crude oil](/assets/images/thermal-foundation/crude-oil.gif){:style="height: 128px"}


**Crude oil** is a fluid obtained from [oil
sand](/docs/thermal-foundation/world/fluid-ores/oil-sand/) and [oil
shale](/docs/thermal-foundation/world/fluid-ores/oil-shale/). It can be used as
fuel in a [compression
dynamo](/docs/thermal-expansion/dynamos/compression-dynamo/), or processed into
[naphtha](/docs/thermal-foundation/fluids/fuel/naphtha/).


Obtaining
---------

### Magma Crucible
{% include recipe-table.html type='crucible' recipes=page.recipes.crucible %}

### Fluid Transposer
{% include recipe-table.html type='transposer-empty' recipes=page.recipes.transposer-empty %}

### Natural generation
Crude oil can rarely be found underground inside large deposits of [oil
sand](/docs/thermal-foundation/world/fluid-ores/oil-sand/) or [oil
shale](/docs/thermal-foundation/world/fluid-ores/oil-shale/). It can be picked
up using a [bucket](https://minecraft.gamepedia.com/Bucket).


Usage
-----

Crude oil can be placed as a block using a
[bucket](https://minecraft.gamepedia.com/Bucket). Crude oil blocks are
flammable.

### Fluid Transposer ingredient
{% include recipe-table.html type='transposer-fill' recipes=page.usage-recipes.transposer-fill %}

### Fractionating Still ingredient
{% include recipe-table.html type='refinery' recipes=page.usage-recipes.refinery %}

### Compression Dynamo fuel
When used as fuel in a [compression
dynamo](/docs/thermal-expansion/dynamos/compression-dynamo/), crude oil yields
400,000 RF per bucket.