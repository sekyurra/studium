---
sidebar_position: 2
---

# Stats and Effects

## Crafter Stats

No guide of this sort would be complete without an overview of what each crafting stat does, what can affect it, and what effects such changes would have.

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

## Stat Deviations and Effects

Your crafting stats can be increased in a variety of ways:

<div class="row">
<div class="col">

|         Buff          |     Stat      | Increase |
| :-------------------: | :-----------: | :------: |
|  Eat from the Hand I  | Craftsmanship |    +5    |
| Eat from the Hand II  | Craftsmanship |   +10    |
| Eat from the Hand III | Craftsmanship |   +15    |
|     In Control I      |    Control    |    +5    |
|     In Control II     |    Control    |   +10    |
|    In Control III     |    Control    |   +15    |

</div>
<div class="col">

|        Materia         |     Stat      |
| :--------------------: | :-----------: |
| Craftsman's Competence | Craftsmanship |
|  Craftsman's Command   |    Control    |
|  Craftsman's Cunning   |      CP       |

</div>
</div>

Your stats can also be affected by crafting food or having a crafting specialization.

While this is great in many cases, when you're trying to follow preset rotations, stat increases (specifically craftsmanship) can occasionally cause problems.

If your stats differ from those assumed for a given rotation, you may experience the following effects:

### Craftsmanship

- **Low**: ⛔ If your craftsmanship is too low for the macro you're running, you may not be able to make enough progress before running out of durability, causing the craft to fail.

- **High**: ⚠️ If your craftsmanship is too high for the macro you're running, you may accidentally complete the craft before increasing its collectability. While the craft will succeed, the collectability may be too low for an appraiser to accept, which essentially equals failure.

:::caution
The macros provided in this guide have, to the extent possible, been written to accommodate a certain amount of excess craftsmanship, so things like FC buffs shouldn't pose a problem. However, you can still run into issues if your craftsmanship stat is significantly higher than what's expected for a given macro.

If you are having issues because of a high craftsmanship stat, the provided macros [can be adjusted](./macros.md#macro-modification) to work around the issue.
:::

### Control

- **Low**: ⚠️ If your control is too low, you may not be able to increase the quality sufficiently to meet the collectability target indicated. In the worst case, you won't be able to meet the minimum collectability requirement. If the appraiser won't take your crafted collectable, it's equivalent to a failed craft.

- **High**: ✅ It's okay for your control stat to be high. You might reach maximum collectability before the quality steps of the rotation are finished, but there are no negative effects.

### CP

- **Low**: ⛔ If your CP is too low, you may not be able to complete the rotation at all. This typically results in failure to meet progress AND quality requiements, causing the craft to fail.

- **High**: ✅ It's okay for your CP to be high. You'll just have more CP left over at the end of the rotation, but there are no negative effects.

:::tip
While control or CP buffs can certainly be useful to crafters in general, this guide is written such that they are not necessary unless specifically noted. As much as possible, only base gear stats are used.
:::

:::caution
If for some reason you encounter a situation where you feel you need control or CP buffs that I haven't indicated, only use food or medicine that provides those stats, such as Tsai tou Vounou or a Commanding/Cunning Craftsman's Tea/Syrup/Draught. Avoid food or medicine that provides craftsmanship buffs, as it may raise your craftsmanship stat high enough to cause problems, even with the buffer built into the provided macros. Additionally, **please let me know** so that I can help you and/or update the guide!
:::

## Item Condition

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
