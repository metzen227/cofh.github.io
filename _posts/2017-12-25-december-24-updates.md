---
title: December 24 updates
redirect_from: /posts/2017/12/25/mod-updates-released/
author: Tonius
author_url: http://www.twitter.com/ToniusMods
published: true
---

On December 24, new updates were released for [CoFH Core](/docs/1.12/cofh-core/),
[CoFH World](/docs/1.12/cofh-world/), the [Thermal Series](/docs/#thermal-series) and
[Redstone Arsenal](/docs/1.12/redstone-arsenal/).

#### General
* Various refactors and bugfixes (see the [issue
  tracker](https://github.com/CoFH/Feedback/issues?q=is%3Aissue+is%3Aclosed+label%3Afixed+sort%3Aupdated-desc)).
* Some minor recipe adjustments.

#### Thermal Foundation
* [Tomes of knowledge](/docs/1.12/thermal-foundation/tome-of-knowledge/) take and give as much
  experience as possible when used, instead of one level at a time.
  * They can also be filled with [OpenBlocks](https://www.openmods.info/)'s
    liquid XP, converting it into experience.
* [Hardened glass](/docs/1.12/thermal-foundation/hardened-glass/) is now wither proof.

#### Thermal Expansion
* Machines
  * [Fluid transposers](/docs/1.12/thermal-expansion/fluid-transposer/) can now make tipped arrows
    using [fluid lingering potions](/docs/1.12/thermal-foundation/potion-fluid/).
  * The [glacial precipitator](/docs/1.12/thermal-expansion/glacial-precipitator/) has been reworked.
    It now lets you select a recipe from a list, and is thus no longer limited
    to 3 products.
    * Producing snow layers and packed ice no longer requires augments.
  * The [igneous extruder](/docs/1.12/thermal-expansion/igneous-extruder/) has been reworked in a
    similar way as the precipitator.
    * Producing granite, diorite and andesite no longer requires augments.
* Storage
  * [Reservoir](/docs/1.12/thermal-expansion/reservoir/)
    * An item that stores fluids. It can be used as a bucket, and can refill
      equipment.
  * New [satchel](/docs/1.12/thermal-expansion/satchel/) functionality:
    * They can automatically store picked up items. Each satchel can be
      configured to only collect specific items.
    * They can be used on blocks that store items to dump their contents.
* Augments
  * [Gearworking Die](/docs/1.12/thermal-expansion/augment-gearworking-die/)
    * Allows for a [compactor](/docs/1.12/thermal-expansion/compactor/) to produce gears. More
      efficient than crafting by hand.
  * [Parabolic Flux Coupling](/docs/1.12/thermal-expansion/augment-parabolic-flux-coupling/)
    * Allows for an [energetic infuser](/docs/1.12/thermal-expansion/energetic-infuser/) to wirelessly
      recharge nearby [flux capacitors](/docs/1.12/thermal-expansion/flux-capacitor/).
  * [Disjunctive Extraction](/docs/1.12/thermal-expansion/augment-disjunctive-extraction/)
    * Allows for an [enervation dynamo](/docs/1.12/thermal-expansion/enervation-dynamo/) to use
      enchanted items as fuel.
  * The 'recovery' [augments](/docs/1.12/thermal-expansion/augments/) have been buffed slightly.
  * The flurry stratum, permafrost compressor and 'subduction'
    [augments](/docs/1.12/thermal-expansion/augments/) have been removed.

#### Thermal Dynamics
* [Covers](/docs/1.12/thermal-dynamics/covers/) can now be made from nearly all blocks, except
  specific blacklisted ones that really wouldn't work as covers.

#### Redstone Arsenal
* Unbreaking on flux-infused equipment is now chance-based, instead of
  permanently reducing energy usage.

Report any bugs on the [issue tracker](http://www.github.com/CoFH/Feedback).
