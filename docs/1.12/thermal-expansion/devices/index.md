---
title: Devices
redirect_from:
- /docs/devices/
- /docs/thermal-expansion/devices/
- /docs/thermal-expansion-5/devices/
- /docs/1.12/thermal-expansion-5/devices/
image:
- alt: Aqueous accumulator
  file: thermal-expansion-5/aqueous-accumulator.png
- alt: Nullifier
  file: thermal-expansion-5/nullifier.png
- alt: Thermal mediator
  file: thermal-expansion-5/thermal-mediator.png
- alt: Arboreal extractor
  file: thermal-expansion-5/arboreal-extractor.png
- alt: Aquatic entangler
  file: thermal-expansion-5/aquatic-entangler.png
- alt: Item allocator
  file: thermal-expansion-5/item-allocator.png
- alt: Fluid allocator
  file: thermal-expansion-5/fluid-allocator.png
- alt: Lexical transmuter
  file: thermal-expansion-5/lexical-transmuter.png
- alt: Insightful condenser
  file: thermal-expansion-5/insightful-condenser.png
- alt: Decoctive diffuser
  file: thermal-expansion-5/decoctive-diffuser.png
- alt: Factorizer
  file: thermal-expansion-5/factorizer.png
- alt: Creature encaptulator
  file: thermal-expansion-5/creature-encaptulator.png
- alt: Vacuumulator
  file: thermal-expansion-5/vacuumulator.png
frame-recipes:
  crafting:
  - te-1-12-frame-device
---

**Devices** are blocks that perform various functions involving items and/or
fluids. Unlike [machines](../machines/), they do not use [Redstone
Flux](/docs/redstone-flux/), and cannot be [upgraded](../../thermal-foundation/tiers/) or
[augmented](../augments/).


List of devices
---------------

{::options parse_block_html="true" /}
<div class="uk-overflow-container">
| Device | Description |
|---
| [Aqueous Accumulator](../aqueous-accumulator/) | Extracts [water](https://minecraft.gamepedia.com/Water) from its surroundings. |
| [Nullifier](../nullifier/) | Destroys items and fluids. |
| [Thermal Mediator](../thermal-mediator/) | Speeds up adjacent [machines](../machines/) and [dynamos](../dynamos/) using [coolants](../coolants/). |
| [Arboreal Extractor](../arboreal-extractor/) | Extracts a fluid from an adjacent [tree](https://minecraft.gamepedia.com/Tree). |
| [Aquatic Entangler](../aquatic-entangler/) | Catches [fish](https://minecraft.gamepedia.com/Fish). |
| [Item Allocator](../item-allocator/) | Stores and transfers items. |
| [Fluid Allocator](../fluid-allocator/) | Stores and transfers fluids. |
| [Lexical Transmuter](../lexical-transmuter/) | Converts items into preferred equivalents. |
| [Insightful Condenser](../insightful-condenser/) | Collects [experience](https://minecraft.gamepedia.com/Experience) in an area. |
| [Decoctive Diffuser](../decoctive-diffuser/) | Spreads the effects of [fluid potions](../../thermal-foundation/potion-fluid/) in an area. |
| [Factorizer](../factorizer/) | Combines and splits various items. |
| [Creature Encaptulator](../creature-encaptulator/) | Captures nearby mobs using [morbs](../morb/). |
| [Vacuumulator](../vacuumulator/) | Collects nearby dropped items. |
{:.uk-table .uk-table-striped .uk-table-condensed .cofh-table-semi-compress .uk-text-small}
</div>
{::options parse_block_html="false" /}


Device Frame
------------

All devices are crafted from **device frames**.

### Crafting
{% include recipe-table.html type='crafting' recipes=page.frame-recipes.crafting %}
