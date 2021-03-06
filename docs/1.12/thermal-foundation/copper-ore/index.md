---
title: Copper Ore
redirect_from:
- /docs/thermal-foundation/world-generation/ores/
- /docs/thermal-foundation/ores/copper-ore/
- /docs/thermal-foundation/world/ores/copper-ore/
- /docs/copper-ore/
- /docs/thermal-foundation/copper-ore/
- /docs/thermal-foundation-2/copper-ore/
- /docs/1.12/thermal-foundation-2/copper-ore/
usage-recipes:
  smelting:
  - tf-1-12-ore-processing-copper
  crafting:
  - tf-1-12-pyrotheum-ore-copper
  - tf-1-12-petrotheum-ore-copper
  - tf-1-12-petrotheum-pyrotheum-ore-copper
  pulverizer:
  - ore-processing-copper
  smelter:
  - ore-processing-sand-copper
  - ore-processing-rich-slag-copper
  - ore-processing-cinnabar-copper
---

![Copper ore](/assets/images/thermal-foundation-2/ore-copper.png){:style="height: 128px"}


**Copper ore** is a common [ore](https://minecraft.gamepedia.com/Ore) that
yields [copper](../copper-ingot/) and small amounts of
[gold](https://minecraft.gamepedia.com/Gold_Ingot).


Obtaining
---------

Copper ore is slightly more common than [iron
ore](https://minecraft.gamepedia.com/Iron_Ore), but it occurs at higher levels
(layers 40-96). Veins of copper ore are also slightly smaller. Below oceans,
copper ore less commonly occurs at deeper levels (layers 20-55).

Copper ore must be mined with a [stone
pickaxe](https://minecraft.gamepedia.com/Pickaxe) or better. If it is mined, it
drops itself as an item.


Usage
-----

### Smelting
{% include recipe-table.html type='smelting' recipes=page.usage-recipes.smelting %}

### Crafting
{% include recipe-table.html type='crafting' recipes=page.usage-recipes.crafting %}

### Pulverizer
{% include recipe-table.html type='te-1-12-pulverizer' recipes=page.usage-recipes.pulverizer %}

### Induction Smelter
{% include recipe-table.html type='te-1-12-smelter' recipes=page.usage-recipes.smelter %}

### Smashing
When copper ore is broken using a [Smashing](../../cofh-core/smashing/)
enchanted [pickaxe](https://minecraft.gamepedia.com/Pickaxe) or similar tool,
two piles of [pulverized copper](../pulverized-copper/)
are dropped instead of the ore.


Trivia
------

* Copper ore is generated in the world using [CoFH World](../../cofh-world/) by
  default. The world generation can be tweaked or disabled using CoFH World's
  [configuration](../../cofh-world/world-generator-configuration/).
