---
sidebar_position: 3
---

# Equipment

No guide of this sort would be complete without a discussion about equipment and stats, and recommendations for equipment as you level.

It's particularly important as the crafting rotations and macros given in the next section assume that you're using one of the equipment sets listed on this page.

The following collection of equipment sets aren't intended to represent the best possible equipment at a given level. Instead, these are the equipment sets that are used for the collectable crafting rotations provided later in this guide.

These equipment sets are meant to take advantage of alternative currencies that you most likely have mountains of already, such as Grand Company Seals. Importantly, I've tried to keep the gil cost as low as possible.

:::tip
As you turn in collectables, you'll be "paid" in experience and White Crafters' Scrips. Save these, as these will be used to buy equipment upgrades as you go!

You will almost certainly earn more scrips than you can spend; consider spending these on equipment for the other crafting jobs you plan to level, so that by the time you need it on those other jobs, you already have it.
:::

## Crafter Stats

### Craftsmanship

Your craftsmanship stat governs how much progress is made toward completion of the craft every time you use a Synthesis action.

Crafters have a base craftsmanship stat of zero. This stat is increased by equipment, materia, food, medicine, and FC buffs.

When you begin a craft, a "baseline" value is calculated based on your craftsmanship stat, the recipe level, difficulty, etc. This value corresponds to how much progress increases when you use a Synthesis action with 100% efficiency. Actions with higher efficiency multiply that baseline value by the efficiency to calculate how much progress is increased in that case.

#### Example

As a specialist blacksmith with level 90 patch 6.2 BiS crafter gear and no buffs (craftsmanship stat of 3664), when attempting to craft a Lunar Adamantite Ingot (a 90☆☆ recipe), the baseline progress value is 228.

If I use `Careful Synthesis`, which has 180% efficiency, progress on that craft will increase by 410 (228 \* 180% = 410).

### Control

Your control stat governs how much quality is increased when you use a Touch action.

Crafters have a base control stat of zero. This stat is increased by equipment, materia, food, medicine, and FC buffs.

When you begin a craft, a "baseline" value is calculated based on your control stat, the recipe level, difficulty, etc. This value corresponds to how much quality increases when you use a Touch action with 100% efficiency. Actions with higher efficiency multiply that baseline value by the efficiency to calculate how much quality is increased by that action.

#### Example

As a specialist blacksmith with level 90 patch 6.2 BiS crafter gear and no buffs (control stat of 3804), when attempting to craft a Lunar Adamantite Ingot (a 90☆☆ recipe), the baseline quality value is 256.

If I use `Preparatory Touch`, which has 200% efficiency, progress on that craft will increase by 512 (256 \* 200% = 512).

### CP

Your CP is essentially the MP pool for crafters. CP is spent on nearly all actions you can perform during crafting. More CP means more actions that you can take, which means crafting becomes easier and you can reach higher quality.

All crafters start with a base CP amount (180). This stat is increased by equipment, materia, food, medicine, and FC buffs.

CP can be regained during a craft by using `Tricks of the Trade` when the condition is "good" or "excellent." Using `Tricks of the Trade` will consume the good or excellent condition and restore 20 CP.

### Item Condition

Every time an action is performed when the condition is normal, there is a 25% chance for the condition to increase to good, and a 10% chance for the condition to increase to excellent.

:::tip
For item condition, `Observe` counts as an action.
:::

In either condition, several abilities become available for use:

| Ability               | Effect                                 |
| --------------------- | -------------------------------------- |
| `Intensive Synthesis` | Increases progress at 400% efficiency. |
| `Precise Touch`       | Increases quality at 150% efficiency.  |
| `Tricks of the Trade` | Restores 20 CP.                        |

:::tip
It is often better to use a Touch action during good or excellent quality, as this may provide a greater quality increase than would the 20 CP restored from using `Tricks of the Trade`.
:::

#### Example (Good Condition)

Using `Precise Touch` during the same craft and with the same gear as the above examples during a good condition would increase quality by 576 for a cost of 18 CP and a loss of 10 durability. We can factor in an inherent CP cost for durability by measuring it against what `Master's Mend` restores.

`Master's Mend` costs 88 CP and restores 30 durability. We can consider every 10 durability as having a cost of around 30 CP.

Using `Tricks of the Trade` followed by a `Basic Touch`/`Standard Touch` combo would increase quality by a total of 608 for a total cost of 16 CP (20 CP from `Tricks of the Trade`, minus 36 for the `Basic Touch`/`Standard Touch` combo) and a loss of 20 durability, which equates to around 60 CP. The end result is that you're spending around 76 CP to get a small amount of extra quality.

The simple way to compare this is to figure out how much quality we get per CP in both options.

| Action                                                         | Quality Increase | CP Cost | Quality per CP |
| -------------------------------------------------------------- | ---------------- | ------- | -------------- |
| `Precise Touch`                                                | 576              | 48      | 12             |
| `Tricks of the Trade`<br />`Basic Touch`<br />`Standard Touch` | 608              | 76      | 8              |

#### Example (Excellent Condition)

You can see from the previous example that it's a bad idea in most cases to use a good condition step for `Tricks of the Trade`. Let's run the same example during an excellent condition.

Using `Precise Touch` during an excellent condition yields a quality increase of 1536 (!) for a cost of 18 CP and a loss of 10 durability.

I tried to figure out how to get even close to that quality increase with `Tricks of the Trade` for the same effective CP cost due to durability, and it's not even worth the comparison.

| Action          | Quality Increase | CP Cost | Quality per CP |
| --------------- | ---------------- | ------- | -------------- |
| `Precise Touch` | 1536             | 48      | 32             |

After any action, the good or excellent condition is lost.

:::caution
Every "excellent" condition is followed by a "poor" condition.

When the item is in poor condition, the quality increase from any Touch action is halved.
:::

## Materia

Given the rate at which you'll replace the gear, it's virtually never worth the resources to meld anything other than end-game gear. If you have gear- and level-appropriate materia on hand, then it _might_ be useful, but this guide is written based on the assumption that your entire stat pool comes only from unmelded, normal quality gear, without the use of food or tinctures.

## Leveling Equipment Sets

### Level 50

<div class="row">
<div class="col">

#### Total Stats

|     Stat      | Amount |
| :-----------: | -----: |
| Craftsmanship |    336 |
|    Control    |    355 |
|      CP       |    294 |

</div>
<div class="col">

#### Total Cost

|        Currency        | Amount |
| :--------------------: | -----: |
|  Grand Company Seals   |  34000 |
| White Crafters' Scrips |     60 |
|          Gil           |  22337 |

</div>
</div>

#### Inventory

|    Slot    |              Name              | Item Level |      Source and Cost      |
| :--------: | :----------------------------: | :--------: | :-----------------------: |
| Main Hand  |     Artisan's Primary Tool     |     70     | 7500 Grand Company Seals  |
|  Off Hand  |     Militia Secondary Tool     |     55     | 60 White Crafters' Scrips |
|    Head    |      Artisan's Spectacles      |     70     | 5000 Grand Company Seals  |
|    Body    |         Artisan's Gown         |     70     | 6500 Grand Company Seals  |
|   Hands    |     Artisan's Fingerstalls     |     70     | 5000 Grand Company Seals  |
|    Legs    |       Artisan's Chausses       |     70     | 5000 Grand Company Seals  |
|    Feet    |       Artisan's Patterns       |     70     | 5000 Grand Company Seals  |
|    Ears    |       Red Coral Earrings       |     45     |         4224 gil          |
|    Neck    |        Electrum Choker         |     49     |         4815 gil          |
|   Wrists   | Electrum Wristlets of Crafting |     46     |         5618 gil          |
| Left Ring  |   Electrum Ring of Crafting    |     47     |         3840 gil          |
| Right Ring |   Electrum Ring of Crafting    |     47     |         3840 gil          |

:::info
The Red Coral/Electrum accessories can be purchased from Seghuie in Ishgard, located in The Pillars, X: 7.4, Y: 10.3.
:::

:::tip
If you don't have any White Crafters' Scrips (yet), pick up the Mythril secondary tool (ilvl 43) instead. You can buy it from any normal tradecraft tool vendor in the major cities for 4394 gil.

The macros for level 50 and 52 collectables have been written to reach maximum collectability in both cases without breaking if you use the higher one.
:::

### Level 53

<div class="row">
<div class="col">

#### Total Stats

|     Stat      | Amount |
| :-----------: | -----: |
| Craftsmanship |    421 |
|    Control    |    398 |
|      CP       |    294 |

</div>
<div class="col">

#### Total Cost

|      Currency       | Amount |
| :-----------------: | -----: |
| Grand Company Seals |  34000 |
|         Gil         |  22337 |

</div>
</div>

#### Inventory

|    Slot    |              Name              | Item Level |          Source          |
| :--------: | :----------------------------: | :--------: | :----------------------: |
| Main Hand  |     Artisan's Primary Tool     |     70     | 7500 Grand Company Seals |
|  Off Hand  |    Mythrite Secondary Tool     |     90     |     Job Quest Reward     |
|    Legs    |       Artisan's Chausses       |     70     | 5000 Grand Company Seals |
|   Hands    |     Artisan's Fingerstalls     |     70     | 5000 Grand Company Seals |
|    Body    |         Artisan's Gown         |     70     | 6500 Grand Company Seals |
|    Feet    |       Artisan's Patterns       |     70     | 5000 Grand Company Seals |
|    Head    |      Artisan's Spectacles      |     70     | 5000 Grand Company Seals |
|    Ears    |       Red Coral Earrings       |     45     |         4224 gil         |
|    Neck    |        Electrum Choker         |     49     |         4815 gil         |
|   Wrists   | Electrum Wristlets of Crafting |     46     |         5618 gil         |
| Left Ring  |   Electrum Ring of Crafting    |     47     |         3840 gil         |
| Right Ring |   Electrum Ring of Crafting    |     47     |         3840 gil         |

Your level 53 job quest rewards you with an item level 90 secondary tool.

:::caution
The crafting rotations for level 54, 56, and 58 assume that you have this.
:::

### Level 55

<div class="row">
<div class="col">

#### Total Stats

|     Stat      | Amount |
| :-----------: | -----: |
| Craftsmanship |    448 |
|    Control    |    409 |
|      CP       |    294 |

</div>
<div class="col">

#### Total Cost

|      Currency       | Amount |
| :-----------------: | -----: |
| Grand Company Seals |  26500 |
|         Gil         |  22337 |

</div>
</div>

#### Inventory

|    Slot    |              Name              | Item Level |          Source          |
| :--------: | :----------------------------: | :--------: | :----------------------: |
| Main Hand  |     Titanium Primary Tool      |    100     |     Job Quest Reward     |
|  Off Hand  |    Mythrite Secondary Tool     |     90     |     Job Quest Reward     |
|    Legs    |       Artisan's Chausses       |     70     | 5000 Grand Company Seals |
|   Hands    |     Artisan's Fingerstalls     |     70     | 5000 Grand Company Seals |
|    Body    |         Artisan's Gown         |     70     | 6500 Grand Company Seals |
|    Feet    |       Artisan's Patterns       |     70     | 5000 Grand Company Seals |
|    Head    |      Artisan's Spectacles      |     70     | 5000 Grand Company Seals |
|    Ears    |       Red Coral Earrings       |     45     |         4224 gil         |
|    Neck    |        Electrum Choker         |     49     |         4815 gil         |
|   Wrists   | Electrum Wristlets of Crafting |     46     |         5618 gil         |
| Left Ring  |   Electrum Ring of Crafting    |     47     |         3840 gil         |
| Right Ring |   Electrum Ring of Crafting    |     47     |         3840 gil         |

Your level 55 job quest rewards you with an item level 100 primary tool.

:::caution
The crafting rotation for level 56 and 58 assumes that you have this.
:::

### Level 58

<div class="row">
<div class="col">

#### Total Stats

|     Stat      | Amount |
| :-----------: | -----: |
| Craftsmanship |    508 |
|    Control    |    519 |
|      CP       |    283 |

</div>
<div class="col">

#### Total Cost

|        Currency        | Amount |
| :--------------------: | -----: |
| White Crafters' Scrips |    375 |
|          Gil           |  22337 |

</div>
</div>

#### Inventory

|    Slot    |              Name              | Item Level |           Source           |
| :--------: | :----------------------------: | :--------: | :------------------------: |
| Main Hand  |     Titanium Primary Tool      |    100     |      Job Quest Reward      |
|  Off Hand  |    Mythrite Secondary Tool     |     90     |      Job Quest Reward      |
|    Head    |          Adept's Hat           |    130     | 60 White Crafters' Scrips  |
|    Body    |          Adept's Gown          |    130     | 135 White Crafters' Scrips |
|   Hands    |         Adept's Gloves         |    130     | 60 White Crafters' Scrips  |
|    Legs    |          Adept's Hose          |    130     | 60 White Crafters' Scrips  |
|    Feet    |       Adept's Thighboots       |    130     | 60 White Crafters' Scrips  |
|    Ears    |       Red Coral Earrings       |     45     |          4224 gil          |
|    Neck    |        Electrum Choker         |     49     |          4815 gil          |
|   Wrists   | Electrum Wristlets of Crafting |     46     |          5618 gil          |
| Left Ring  |   Electrum Ring of Crafting    |     47     |          3840 gil          |
| Right Ring |   Electrum Ring of Crafting    |     47     |          3840 gil          |

:::info
Continue using the item level 100 primary and item level 90 secondary tools you got from your previous job quests.

Continue using the purchased accessories that you acquired in the beginning.
:::

:::caution
While item level 120 accessories do exist (Dragon Fang Earrings, and the Hallowed Chestnut Set), they're not worth crafting because you're only going to use them for two levels.
:::

### Level 60

<div class="row">
<div class="col">

#### Total Stats

|     Stat      | Amount |
| :-----------: | -----: |
| Craftsmanship |    943 |
|    Control    |    843 |
|      CP       |    381 |

</div>
<div class="col">

#### Total Cost

|        Currency        | Amount |
| :--------------------: | -----: |
| White Crafters' Scrips |   1300 |

</div>
</div>

#### Inventory

|    Slot    |              Name               | Item Level |           Source           |
| :--------: | :-----------------------------: | :--------: | :------------------------: |
| Main Hand  |  Augmented Keep's Primary Tool  |    200     | 225 White Crafters' Scrips |
|  Off Hand  | Augmented Keep's Secondary Tool |    200     | 225 White Crafters' Scrips |
|    Head    |   Augmented Keep's Spectacles   |    200     | 75 White Crafters' Scrips  |
|    Body    |    Augmented Keep's Overcoat    |    200     | 225 White Crafters' Scrips |
|   Hands    |     Augmented Keep's Gloves     |    200     | 75 White Crafters' Scrips  |
|    Legs    |    Augmented Keep's Longkilt    |    200     | 75 White Crafters' Scrips  |
|    Feet    |   Augmented Keep's Jackboots    |    200     | 75 White Crafters' Scrips  |
|    Ears    | Augmented Handmaster's Earrings |    200     | 75 White Crafters' Scrips  |
|    Neck    | Augmented Handmaster's Necklace |    200     | 75 White Crafters' Scrips  |
|   Wrists   | Augmented Handmaster's Armillae |    200     | 75 White Crafters' Scrips  |
| Left Ring  |   Augmented Handmaster's Ring   |    200     | 50 White Crafters' Scrips  |
| Right Ring |   Augmented Handmaster's Ring   |    200     | 50 White Crafters' Scrips  |

:::info
The Keep's Sets are job-specific; you will require a new armor set for each crafting job you're leveling.

The Handmaster's Set (accessories) are not job-specific, and can be used across all crafting jobs.
:::

### Level 60 (Universal)

<div class="row">
<div class="col">

#### Total Stats

|     Stat      | Amount |
| :-----------: | -----: |
| Craftsmanship |    900 |
|    Control    |    813 |
|      CP       |    378 |

</div>
<div class="col">

#### Total Cost

|        Currency        | Amount |
| :--------------------: | -----: |
| White Crafters' Scrips |    775 |
|     Crafted Items      |      5 |

</div>
</div>

#### Inventory

|    Slot    |              Name               | Item Level |           Source           |
| :--------: | :-----------------------------: | :--------: | :------------------------: |
| Main Hand  |  Augmented Keep's Primary Tool  |    200     | 225 White Crafters' Scrips |
|  Off Hand  | Augmented Keep's Secondary Tool |    200     | 225 White Crafters' Scrips |
|    Head    |    Ironworks Cap of Crafting    |    190     |          Crafted           |
|    Body    |   Ironworks Apron of Crafting   |    190     |          Crafted           |
|   Hands    |  Ironworks Sleeves of Crafting  |    190     |          Crafted           |
|    Legs    | Ironworks Breeches of Crafting  |    190     |          Crafted           |
|    Feet    |   Ironworks Boots of Crafting   |    190     |          Crafted           |
|    Ears    | Augmented Handmaster's Earrings |    200     | 75 White Crafters' Scrips  |
|    Neck    | Augmented Handmaster's Necklace |    200     | 75 White Crafters' Scrips  |
|   Wrists   | Augmented Handmaster's Armillae |    200     | 75 White Crafters' Scrips  |
| Left Ring  |   Augmented Handmaster's Ring   |    200     | 50 White Crafters' Scrips  |
| Right Ring |   Augmented Handmaster's Ring   |    200     | 50 White Crafters' Scrips  |

:::danger
The Ironworks set (armor and accessories) is usable by all crafting jobs, but it's a crafted set and therefore _far more expensive_ than the Keep's/Handmaster's Sets, and for worse stats.

**I do not recommend going this route due to the cost.**

You'll farm enough White Crafters' Scrips in the course of following this guide to get the Keep's equipment for every other crafting job by the time you hit 90 on the first one.
:::

:::danger
No matter which armor set you go with, there is absolutely _no reason_ to ever use the Ironworks accessories. For a universal set at level 60, get the Ironworks Armor and the Handmaster's Accessories.
:::

:::info
In either case, use the primary and secondary tools from the Keep's set.
:::

### Level 70

<div class="row">
<div class="col">

#### Total Stats

|     Stat      | Amount |
| :-----------: | -----: |
| Craftsmanship |   1645 |
|    Control    |   1532 |
|      CP       |    400 |

</div>
<div class="col">

#### Total Cost

|        Currency        | Amount |
| :--------------------: | -----: |
| White Crafters' Scrips |   1300 |

</div>
</div>

#### Inventory

|    Slot    |          Name           | Item Level |           Source           |
| :--------: | :---------------------: | :--------: | :------------------------: |
| Main Hand  | Handking's Primary Tool |    350     | 225 White Crafters' Scrips |
|  Off Hand  |  King's Secondary Tool  |    330     | 225 White Crafters' Scrips |
|    Head    |    Handking's Turban    |    350     | 75 White Crafters' Scrips  |
|    Body    |   Handking's Doublet    |    350     | 225 White Crafters' Scrips |
|   Hands    |    Handking's Gloves    |    350     | 75 White Crafters' Scrips  |
|    Legs    |   Handking's Bottoms    |    350     | 75 White Crafters' Scrips  |
|    Feet    |    Handking's Shoes     |    350     | 75 White Crafters' Scrips  |
|    Ears    |   Handking's Earring    |    350     | 75 White Crafters' Scrips  |
|    Neck    |   Handking's Necklace   |    350     | 75 White Crafters' Scrips  |
|   Wrists   |   Handking's Armillae   |    350     | 75 White Crafters' Scrips  |
| Left Ring  |     Handking's Ring     |    350     | 50 White Crafters' Scrips  |
| Right Ring |     Handking's Ring     |    350     | 50 White Crafters' Scrips  |

:::info
Aside from the tools, the Handking's armor and accessories are usable by all crafting jobs, so you'll only need to buy the set once.
:::

### Level 80

<div class="row">
<div class="col">

#### Total Stats

|     Stat      | Amount |
| :-----------: | -----: |
| Craftsmanship |   2606 |
|    Control    |   2457 |
|      CP       |    507 |

</div>
<div class="col">

#### Total Cost

|        Currency        | Amount |
| :--------------------: | -----: |
| White Crafters' Scrips |   1850 |

</div>
</div>

#### Inventory

|    Slot    |             Name              | Item Level |           Source           |
| :--------: | :---------------------------: | :--------: | :------------------------: |
| Main Hand  |   Handsaint's Primary Tool    |    500     | 350 White Crafters' Scrips |
|  Off Hand  |  Handsaint's Secondary Tool   |    500     | 350 White Crafters' Scrips |
|    Head    |       Handsaint's Beret       |    500     | 100 White Crafters' Scrips |
|    Body    |      Handsaint's Jacket       |    500     | 300 White Crafters' Scrips |
|   Hands    | Handsaint's Fingerless Gloves |    500     | 100 White Crafters' Scrips |
|    Legs    |     Handsaint's Trousers      |    500     | 100 White Crafters' Scrips |
|    Feet    |       Handsaint's Shoes       |    500     | 100 White Crafters' Scrips |
|    Ears    |     Handsaint's Earrings      |    500     | 100 White Crafters' Scrips |
|    Neck    |     Handsaint's Necklace      |    500     | 100 White Crafters' Scrips |
|   Wrists   |     Handsaint's Bracelets     |    500     | 100 White Crafters' Scrips |
| Left Ring  |       Handsaint's Ring        |    500     | 75 White Crafters' Scrips  |
| Right Ring |       Handsaint's Ring        |    500     | 75 White Crafters' Scrips  |

:::info
Aside from the tools, the Handsaint's armor and accessories are usable by all crafting jobs, so you'll only need to buy the set once.
:::

## Endgame Equipment Sets

### Level 90

<div class="row">
<div class="col">

#### Total Stats

|     Stat      | Amount |
| :-----------: | -----: |
| Craftsmanship |   3457 |
|    Control    |   3184 |
|      CP       |    486 |

</div>
<div class="col">

#### Total Cost

|        Currency         | Amount |
| :---------------------: | -----: |
| Purple Crafters' Scrips |   3100 |
|      Crafted Items      |      5 |

</div>
</div>

#### Inventory

|    Slot    |                     Name                      | Item Level |           Source            |
| :--------: | :-------------------------------------------: | :--------: | :-------------------------: |
| Main Hand  |         Perfectionist's Primary Tool          |    590     | 500 Purple Crafters' Scrips |
|  Off Hand  |        Perfectionist's Secondary Tool         |    590     | 500 Purple Crafters' Scrips |
|    Head    |        Perfectionist's Cap of Crafting        |    590     | 300 Purple Crafters' Scrips |
|    Body    |      Perfectionist's Doublet of Crafting      |    590     | 900 Purple Crafters' Scrips |
|   Hands    | Perfectionist's Fingerless Gloves of Crafting |    590     | 300 Purple Crafters' Scrips |
|    Legs    |     Perfectionist's Trousers of Crafting      |    590     | 300 Purple Crafters' Scrips |
|    Feet    |       Perfectionist's Boots of Crafting       |    590     | 300 Purple Crafters' Scrips |
|    Ears    |         Integral Earrings of Crafting         |    560     |           Crafted           |
|    Neck    |         Integral Necklace of Crafting         |    560     |           Crafted           |
|   Wrists   |         Integral Bracelet of Crafting         |    560     |           Crafted           |
| Left Ring  |           Integral Ring of Crafting           |    560     |           Crafted           |
| Right Ring |           Integral Ring of Crafting           |    560     |           Crafted           |

#### Notes

This is a very solid option that will let you craft most things with excellent results.

Without buffs or melding, it will fall short of the craftsmanship and/or control requirements of the 90☆☆☆ recipes.

When melded, you'll be able to craft even the 90☆☆☆ recipes, but you probably won't be able to reach 100% HQ on the precraft (35 durability) recipes even with food and medicines. You can get close, around 85% to 90%, but that means you'll wind up with NQ precrafts some of the time. You will be able to reliably reach 100% HQ on the 90☆☆☆ final craft recipes (70 durability) if you use all HQ precraft materials.

The Integral accessories can be overmelded, and this may further close the gap for the 90☆☆☆ precrafts depending on how you meld it.

The Perfectionist's equipment **cannot** be overmelded. They're limited to only the normal materia slots: two for worn items, one for tools.

:::caution
Overmelding is **expensive**. Read the notes for the BiS set below.
:::

### Level 90 (6.1/6.2 BiS)

#### Total Stats

|     Stat      | Amount |
| :-----------: | -----: |
| Craftsmanship |   3664 |
|    Control    |   3784 |
|      CP       |    573 |

#### Notes

This set has identical stats to the Perfectionist's/Integral set, with one major difference: the entire set can be overmelded.

:::caution
Without overmelding, this set has stats identical to the Perfectionist's/Integral set listed previously.

The _only_ reason get this set is if you intend to overmeld it. The _only_ reason to do that is if you intend to craft _a lot_ of high-end/end-game items, in which case having the "best" available stats would be worth the cost.
:::

Be prepared to devote many hours and incredible amounts of resources to crafting collectables in order to get enough scrips to afford the amount of materia you're likely to need. Buying materia from the market board is, of course, an alternative, but be prepared to shell out **millions upon millions of gil** (and a frighteningly large share of your sanity) by the time you're finished.

If you've decided to go this route after all, I salute you, and may the odds be ever in your favor.

#### Words of Warning

:::caution
This bears repeating: If you **don't** plan on overmelding your left side equipment (head, body, hands, legs, and feet) and tools, do not get this set! It is a waste of gil and/or resources. Go with the standard level 90 set above.

If you **do** plan on overmelding your equipment, you MUST get this set. The Perfectionist's items **cannot** be overmelded.
:::

:::danger
To reach the stats listed for this set, you must fully overmeld every item in the entire set, including tools.

This process is **ASTRONOMICALLY FUCKING EXPENSIVE**!
:::

#### The equipment

#### Inventory

|    Slot    |                   Name                    | Item Level | Source  |
| :--------: | :---------------------------------------: | :--------: | :-----: |
| Main Hand  |         Pactmaker's Primary Tool          |    590     | Crafted |
|  Off Hand  |        Pactmaker's Secondary Tool         |    590     | Crafted |
|    Head    |        Pactmaker's Cap of Crafting        |    590     | Crafted |
|    Body    |      Pactmaker's Doublet of Crafting      |    590     | Crafted |
|   Hands    | Pactmaker's Fingerless Gloves of Crafting |    590     | Crafted |
|    Legs    |     Pactmaker's Trousers of Crafting      |    590     | Crafted |
|    Feet    |       Pactmaker's Boots of Crafting       |    590     | Crafted |
|    Ears    |       Integral Earrings of Crafting       |    560     | Crafted |
|    Neck    |       Integral Necklace of Crafting       |    560     | Crafted |
|   Wrists   |       Integral Bracelet of Crafting       |    560     | Crafted |
| Left Ring  |         Integral Ring of Crafting         |    560     | Crafted |
| Right Ring |         Integral Ring of Crafting         |    560     | Crafted |

#### Required Materia

|                Item                |                                                                                                                                 Materia                                                                                                                                  |
| :--------------------------------: | :----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------: |
|      Pactmaker's Primary Tool      |              Craftsman's Command Materia X (Control +18)<br />Craftsman's Command Materia X (Control +18)<br />Craftsman's Command Materia IX (Control +12)<br />Craftsman's Command Materia IX (Control +12)<br />Craftsman's Cunning Materia VII (CP +7)               |
|     Pactmaker's Secondary Tool     |              Craftsman's Command Materia X (Control +18)<br />Craftsman's Command Materia X (Control +18)<br />Craftsman's Command Materia IX (Control +12)<br />Craftsman's Command Materia IX (Control +12)<br />Craftsman's Cunning Materia VII (CP +7)               |
|   Pactmaker's Turban of Crafting   |        Craftsman's Command Materia X (Control +18)<br />Craftsman's Command Materia X (Control +18)<br />Craftsman's Competence Materia X (Craftsmanship +27)<br />Craftsman's Command Materia IX (Control +12)<br />Craftsman's Command Materia IX (Control +12)        |
|    Pactmaker's Vest of Crafting    |        Craftsman's Command Materia X (Control +18)<br />Craftsman's Command Materia X (Control +18)<br />Craftsman's Competence Materia X (Craftsmanship +27)<br />Craftsman's Command Materia IX (Control +12)<br />Craftsman's Command Materia IX (Control +12)        |
| Pactmaker's Halfgloves of Crafting |        Craftsman's Command Materia X (Control +18)<br />Craftsman's Command Materia X (Control +18)<br />Craftsman's Competence Materia X (Craftsmanship +27)<br />Craftsman's Command Materia IX (Control +12)<br />Craftsman's Command Materia IX (Control +12)        |
|  Pactmaker's Sarouel of Crafting   |               Craftsman's Command Materia X (Control +18)<br />Craftsman's Command Materia X (Control +18)<br />Craftsman's Cunning Materia X (CP +10)<br />Craftsman's Command Materia IX (Control +12)<br />Craftsman's Command Materia IX (Control +12)               |
|   Pactmaker's Pumps of Crafting    |               Craftsman's Command Materia X (Control +18)<br />Craftsman's Command Materia X (Control +18)<br />Craftsman's Cunning Materia X (CP +10)<br />Craftsman's Command Materia IX (Control +12)<br />Craftsman's Command Materia IX (Control +12)               |
|   Integral Necklace of Crafting    |                  Craftsman's Command Materia X (Control +18)<br />Craftsman's Command Materia X (Control +18)<br />Craftsman's Command Materia IX (Control +12)<br />Craftsman's Cunning Materia VII (CP +7)<br />Craftsman's Cunning Materia V (CP +6)                  |
|   Integral Earrings of Crafting    |                  Craftsman's Command Materia X (Control +18)<br />Craftsman's Command Materia X (Control +18)<br />Craftsman's Command Materia IX (Control +12)<br />Craftsman's Cunning Materia VII (CP +7)<br />Craftsman's Cunning Materia V (CP +6)                  |
|   Integral Bracelet of Crafting    |                  Craftsman's Command Materia X (Control +18)<br />Craftsman's Command Materia X (Control +18)<br />Craftsman's Command Materia IX (Control +12)<br />Craftsman's Cunning Materia VII (CP +7)<br />Craftsman's Cunning Materia V (CP +6)                  |
|     Integral Ring of Crafting      | Craftsman's Command Materia X (Control +18)<br />Craftsman's Competence Materia X (Craftsmanship +27)<br />Craftsman's Competence Materia IX (Craftsmanship +18)<br />Craftsman's Competence Materia IX (Craftsmanship +18)<br />Craftsman's Cunning Materia VII (CP +7) |
|     Integral Ring of Crafting      | Craftsman's Command Materia X (Control +18)<br />Craftsman's Competence Materia X (Craftsmanship +27)<br />Craftsman's Competence Materia IX (Craftsmanship +18)<br />Craftsman's Competence Materia IX (Craftsmanship +18)<br />Craftsman's Cunning Materia VII (CP +7) |

#### Shopping List

| Materia                                                      |                  Cost Each |   Quantity |                                                      Total Cost |
| ------------------------------------------------------------ | -------------------------: | ---------: | --------------------------------------------------------------: |
| **Craftsman's Competence Materia X**<br />Craftsmanship +27  | 500 Purple Crafters' Scrip |         20 |                                    10000 Purple Crafters' Scrip |
| **Craftsman's Competence Materia IX**<br />Craftsmanship +18 |  250 White Crafters' Scrip |         34 |                                      8500 White Crafters' Scrip |
| **Craftsman's Command Materia X**<br />Control +18           | 500 Purple Crafters' Scrip |         37 |                                    18500 Purple Crafters' Scrip |
| **Craftsman's Command Materia IX**<br />Control +12          |  250 White Crafters' Scrip |        154 |                                     38500 White Crafters' Scrip |
| **Craftsman's Cunning Materia X**<br />CP +10                | 500 Purple Crafters' Scrip |          8 |                                     4000 Purple Crafters' Scrip |
| **Craftsman's Cunning Materia VII**<br />CP +7               |  200 White Crafters' Scrip |         72 |                                     14400 White Crafters' Scrip |
| **Craftsman's Cunning Materia V**<br />CP +6                 |  200 White Crafters' Scrip |         42 |                                      8400 White Crafters' Scrip |
|                                                              |                            | **Totals** | 32500 Purple Crafters' Scrips<br />69800 White Crafters' Scrips |

:::caution
The quantities above give you a 50/50 chance of having enough to complete all of the necessary melds before you burn through your materia. This is because all overmelding is subject to the whim of the RNGods.

The chance of succeeding in a given meld is as follows:

<div class="row">
<div class="col">

#### Worn Items

| Slot | Chance of Success |
| :--: | ----------------: |
|  1   |              100% |
|  2   |              100% |
|  3   |               17% |
|  4   |               10% |
|  5   |                7% |

</div>
<div class="col">

#### Tools, Accessories:

| Slot | Chance of Success |
| :--: | ----------------: |
|  1   |              100% |
|  2   |               17% |
|  3   |               10% |
|  4   |                7% |
|  5   |                5% |

</div>
</div>

I have personally burned through **ninety-seven materia** on a single meld, and I've seen others that have gone **over one hundred**.
:::

![Emotional damage.](@site/static/img/ouch.png)
