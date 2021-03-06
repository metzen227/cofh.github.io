---
title: Tectonic Petrotheum
redirect_from:
- /docs/thermal-foundation/fluids/tectonic-petrotheum/
- /docs/thermal-foundation/fluids/elemental/tectonic-petrotheum/
- /docs/tectonic-petrotheum/
- /docs/thermal-foundation/tectonic-petrotheum/
- /docs/thermal-foundation-2/tectonic-petrotheum/
- /docs/1.12/thermal-foundation-2/tectonic-petrotheum/
recipes:
  crucible:
  - petrotheum
  transposer-empty:
  - bucket-petrotheum
usage-recipes:
  transposer-fill:
  - bucket-petrotheum
---

![Tectonic petrotheum](/assets/images/thermal-foundation-2/tectonic-petrotheum.gif){:style="height: 128px"}


**Tectonic petrotheum** is the earth elemental fluid. It is obtained by melting
[petrotheum dust](../petrotheum-dust/) in a [magma
crucible](../../thermal-expansion/magma-crucible/).


Obtaining
---------

### Magma Crucible
{% include recipe-table.html type='te-1-12-crucible' recipes=page.recipes.crucible %}

### Fluid Transposer
{% include recipe-table.html type='te-1-12-transposer-empty' recipes=page.recipes.transposer-empty %}


Usage
-----

Tectonic petrotheum can be placed as a block using a
[bucket](https://minecraft.gamepedia.com/Bucket).

### Flow
Tectonic petrotheum flows like other fluids. Petrotheum source blocks will also
gradually fall downwards if there are no blocks below them.

### Effects
When touched by players and mobs, tectonic petrotheum applies the effect [Haste
I](https://minecraft.gamepedia.com/Status_effect#Haste) to them for 6 seconds.

When tectonic petrotheum touches [stone](https://minecraft.gamepedia.com/Stone),
[cobblestone](https://minecraft.gamepedia.com/Cobblestone), [stone
bricks](https://minecraft.gamepedia.com/Stone_Bricks) or [moss
stone](https://minecraft.gamepedia.com/Moss_Stone), these blocks are turned into
[gravel](https://minecraft.gamepedia.com/Gravel).

If enabled, tectonic petrotheum breaks any adjacent stone- or rock-like blocks.
This is disabled by default.

### Fluid Transposer ingredient
{% include recipe-table.html type='te-1-12-transposer-fill' recipes=page.usage-recipes.transposer-fill %}

### Tectonic Initiator
An [pulverizer](../../thermal-expansion/pulverizer/) with a [tectonic
initiator](../../thermal-expansion/augment-tectonic-initiator/) installed consumes tectonic
petrotheum to process ores more efficiently. It consumes 100 mB of petrotheum
per processed ore.

### Reactant Dynamo fuel
When used together with [aerotheum dust](../aerotheum-dust/) as fuel in a
[reactant dynamo](../../thermal-expansion/reactant-dynamo/), 100 mB of tectonic petrotheum yields
400,000 RF, or 500,000 RF if an [elemental
catalyzer](../../thermal-expansion/augment-elemental-catalyzer/) is installed.
