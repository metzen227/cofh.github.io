---
title: Liquifacted Coal
redirect_from:
- /thermal-expansion/fluids/liquifacted-coal/
- /docs/thermal-foundation/fluids/liquifacted-coal/
- /docs/thermal-foundation/fluids/fuel/liquifacted-coal/
- /docs/liquifacted-coal/
- /docs/thermal-foundation/liquifacted-coal/
- /docs/thermal-foundation-2/liquifacted-coal/
- /docs/1.12/thermal-foundation-2/liquifacted-coal/
recipes:
  crucible:
  - coal
  transposer-empty:
  - bucket-coal
usage-recipes:
  transposer-fill:
  - bucket-coal
  refinery:
  - naphtha-from-coal
---

![Liquifacted coal](/assets/images/thermal-foundation-2/liquifacted-coal.gif){:style="height: 128px"}

> Liquifaction is salvation!


**Liquifacted coal** is a fluid obtained by melting [pulverized
coal](../pulverized-coal/) in a [magma crucible](../../thermal-expansion/magma-crucible/). It
can be used as fuel in a [compression dynamo](../../thermal-expansion/compression-dynamo/), or
processed into [naphtha](../naphtha/).


Obtaining
---------

### Magma Crucible
{% include recipe-table.html type='te-1-12-crucible' recipes=page.recipes.crucible %}

### Fluid Transposer
{% include recipe-table.html type='te-1-12-transposer-empty' recipes=page.recipes.transposer-empty %}


Usage
-----

Liquifacted coal cannot be placed as a block.

### Fluid Transposer ingredient
{% include recipe-table.html type='te-1-12-transposer-fill' recipes=page.usage-recipes.transposer-fill %}

### Fractionating Still ingredient
{% include recipe-table.html type='te-1-12-refinery' recipes=page.usage-recipes.refinery %}

### Compression Dynamo fuel
When used as fuel in a [compression dynamo](../../thermal-expansion/compression-dynamo/), a bucket
of liquifacted coal yields 400,000 RF.
