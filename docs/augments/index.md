---
title: Augments
nav: thermal-expansion
redirect_from:
  - /docs/thermal-expansion/augments/
  - /docs/thermal-expansion/augments/augmentation/
augments:
  machine:
    - machine-power
    - machine-secondary
    - machine-secondary-null
    - machine-furnace-food
    - machine-furnace-ore
    - machine-furnace-pyrolysis
    - machine-pulverizer-petrotheum
    - machine-sawmill-tapper
    - machine-smelter-pyrotheum
    - machine-insolator-mycelium
    - machine-insolator-nether
    - machine-insolator-end
    - machine-insolator-tree
    - machine-compactor-mint
    - machine-crucible-lava
    - machine-charger-throughput
    - machine-precipitator-snow-layer
    - machine-precipitator-packed-ice
    - machine-extruder-no-water
    - machine-extruder-granite
    - machine-extruder-diorite
    - machine-extruder-andesite
  dynamo:
    - dynamo-power
    - dynamo-efficiency
    - dynamo-coil-duct
    - dynamo-throttle
    - dynamo-boiler
    - dynamo-steam-turbine
    - dynamo-magmatic-coolant
    - dynamo-compression-coolant
    - dynamo-compression-fuel
    - dynamo-reactant-elemental
    - dynamo-numismatic-gem
---

**Augments** are items that can be installed in [machines](/docs/machines/) and
[dynamos](/docs/dynamos/) to improve ('augment') them in certain ways or to
change how they work.


Usage
-----

Augments can be installed in the Augmentation tab in the GUI of a
[machine](/docs/machines/) or [dynamo](/docs/dynamos/). The amount of augments
that can be installed depends on the block's [tier](/docs/tiers/). A basic
machine or dynamo cannot be augmented.

Some augments can be installed multiple times, stacking their effects.

Certain augments are classified as 'specializations'. Only one specialization
augment can be installed at a time.


List of augments
----------------

### Machine augments
{% include augment-table.html augments=page.augments.machine %}

### Dynamo augments
{% include augment-table.html augments=page.augments.dynamo %}