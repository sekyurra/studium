---
sidebar_position: 3
---

# Important Rotation Information

These rotations assume that:

- You are using one of the gear sets listed in the previous sections;
- Your stats exactly match those indicated for the craft you're attempting;
- You are crafting collectable items with the exact recipe level, difficulty, quality, and durability parameters listed;
- You have all abilities available at the level indicated, including those gained by completing job quests;
- You don't get screwed by having poor condition during a critical touch action. ☹️

:::caution
Even if you're using a gear set from this document, buffs can modify your stats, so always check your stats in your character window to verify that your currently effective stats are correct.
:::

## Stat Deviations and Effects

Your crafting stats can be increased in a variety of ways:

- FC buffs;
  - Eat from the Hand I (Craftsmanship +5)
  - Eat from the Hand II (Craftsmanship +10)
  - Eat from the Hand III (Craftsmanship +15)
  - In Control I (Control +5)
  - In Control II (Control +10)
  - In Control III (Control +15)
- Food buffs;
- Materia;
  - Craftsman's Competence Materia (Craftsmanship)
  - Craftsman's Command Materia (Control)
  - Craftsman's Cunning Materia (CP)
- Crafting job specializations.

While this is great in many cases, when you're trying to follow preset rotations, stat increases can in some cases cause problems.

If your stats differ from those assumed for a given rotation, you may experience the following effects:

### Craftsmanship

- **Low**: ⛔ If your craftsmanship is too low for the macro you're running, you may not be able to make enough progress before running out of durability, causing the craft to fail.

- **High**: ⚠️ If your craftsmanship is too high for the macro you're running, you may accidentally complete the craft before increasing its collectability. While the craft will succeed, the collectability may be too low for an appraiser to accept, which essentially equals failure.

:::danger
Craftsmanship buffs will almost certainly break these macros without modification. In fact, someone reporting that to me was what made me expand this section so much.

**This problem is extremely macro-dependent.** I am in the process of rewriting all of the macros in this guide to minimize the risk of this happening, but I'm not there yet.
:::

### Control

- **Low**: ⚠️ If your control is too low, you may not be able to increase the quality sufficiently to meet the collectability target indicated. In the worst case, you won't be able to meet the minimum collectability requirement. If the appraiser won't take your crafted collectable, it's equivalent to a failed craft.

- **High**: ✅ It's okay for your control stat to be high. You might reach maximum collectability before the quality steps of the rotation are finished, but there are no negative effects.

### CP

- **Low**: ⛔ If your CP is too low, you may not be able to complete the rotation at all. This typically results in failure to meet progress AND quality requiements, causing the craft to fail.

- **High**: ✅ It's okay for your CP to be high. You'll just have more CP left over at the end of the rotation, but there are no negative effects.

In summary, control and CP buffs are fine. At level 56 and 58, they can be very helpful! Craftsmanship buffs are trouble, and you need to be very careful if you're affected by any.

:::tip
While control or CP buffs can certainly be useful to crafters in general, this guide is written such that they are not necessary unless specifically noted. As much as possible, only base gear stats are used.
:::

:::caution
If for some reason you encounter a situation where you feel you need control or CP buffs that I haven't indicated, only use food or medicine that provides those stats, such as Tsai tou Vounou or a Commanding/Cunning Craftsman's Tea/Syrup/Draught. Avoid food or medicine that provides craftsmanship buffs, for the reasons stated above. Additionally, **please let me know** so that I can help you and/or update the guide!
:::

If you are having issues because of a high craftsmanship stat, see the next section.

## Macro Modification

If you're stuck with a craftsmanship buff and it's causing problems, this is actually fairly easy to handle.

As long as the crafting job you're leveling is level 42 or higher - which it probably is if you're reading through this guide - then there is a way to compensate for having a higher-than-expected craftsmanship stat. All you have to do is tweak the macro a bit.

### Example 1

Let's take this level 85 collectable crafting rotation as an example. The stats aren't important for this; let's just assume that your craftsmanship stat is just a little too high.

**Before**: Our collectability stat is too high, and so the last `Delicate Synthesis` action (line 11) is maxing out our collectability and screwing up our craft.

```plain {11} showLineNumbers
/ac "Muscle Memory" <wait.3>
/ac "Innovation" <wait.2>
/ac "Prudent Touch" <wait.3>
/ac "Groundwork" <wait.3>
/ac "Manipulation" <wait.2>
/ac "Delicate Synthesis" <wait.3>
/ac "Delicate Synthesis" <wait.3>
/ac "Delicate Synthesis" <wait.3>
/ac "Innovation" <wait.2>
/ac "Prudent Touch" <wait.3>
/ac "Delicate Synthesis" <wait.3>
/ac "Innovation" <wait.2>
/ac "Basic Touch" <wait.3>
/ac "Standard Touch" <wait.3>
```

```plain showLineNumbers
/ac "Prudent Touch" <wait.3>
/ac "Byregot's Blessing" <wait.3>
/ac "Careful Synthesis" <wait.3>
```

We can prevent that synthesis action from capping progress and ruining our craft by inserting a `Final Appraisal` action right before it. Rather than finishing the craft, `Final Appraisal` will cause it to stop one progress point short, leaving us free to complete the touch actions required to hit our collectability target.

**After**: In the example, we've inserted that `Final Appraisal` action at line 11 of the first section, pushing our previously problematic `Delicate Synthesis` action to line 12.

```plain {11-12} showLineNumbers
/ac "Muscle Memory" <wait.3>
/ac "Innovation" <wait.2>
/ac "Prudent Touch" <wait.3>
/ac "Groundwork" <wait.3>
/ac "Manipulation" <wait.2>
/ac "Delicate Synthesis" <wait.3>
/ac "Delicate Synthesis" <wait.3>
/ac "Delicate Synthesis" <wait.3>
/ac "Innovation" <wait.2>
/ac "Prudent Touch" <wait.3>
/ac "Final Appraisal" <wait.3>
/ac "Delicate Synthesis" <wait.3>
/ac "Innovation" <wait.2>
/ac "Basic Touch" <wait.3>
/ac "Standard Touch" <wait.3>
```

```plain showLineNumbers
/ac "Prudent Touch" <wait.3>
/ac "Byregot's Blessing" <wait.3>
/ac "Careful Synthesis" <wait.3>
```

### Example 2

If your craftsmanship stat is VERY high, you might be bumping up against completion even earlier.

In that case, insert `Final Appraisal` before the synthesis action that's finishing the craft early, then remove all other synthesis actions after that one, except for the last one.

**Before**: In this example, let's say we're hitting full progress after just four synthesis actions (ending with `Delicate Synthesis` at line 7) instead of the seven we planned for.

```plain {7} showLineNumbers
/ac "Muscle Memory" <wait.3>
/ac "Innovation" <wait.2>
/ac "Prudent Touch" <wait.3>
/ac "Groundwork" <wait.3>
/ac "Manipulation" <wait.2>
/ac "Delicate Synthesis" <wait.3>
/ac "Delicate Synthesis" <wait.3>
/ac "Delicate Synthesis" <wait.3>
/ac "Innovation" <wait.2>
/ac "Prudent Touch" <wait.3>
/ac "Delicate Synthesis" <wait.3>
/ac "Innovation" <wait.2>
/ac "Basic Touch" <wait.3>
/ac "Standard Touch" <wait.3>
```

```
/ac "Prudent Touch" <wait.3>
/ac "Byregot's Blessing" <wait.3>
/ac "Careful Synthesis" <wait.3>
```

**After**: To fix this, we've inserted `Final Appraisal` at line 7, which pushes `Delicate Synthesis` to line 8. We then removed the other synthesis actions after that (lines 9 and 12). We've left the last synthesis action (`Careful Synthesis`, second section, line 3) because we do still need to finish the craft!

```plain {7-8} showLineNumbers
/ac "Muscle Memory" <wait.3>
/ac "Innovation" <wait.2>
/ac "Prudent Touch" <wait.3>
/ac "Groundwork" <wait.3>
/ac "Manipulation" <wait.2>
/ac "Delicate Synthesis" <wait.3>
/ac "Final Appraisal" <wait.3>
/ac "Delicate Synthesis" <wait.3>
/ac "Innovation" <wait.2>
/ac "Prudent Touch" <wait.3>
/ac "Innovation" <wait.2>
/ac "Basic Touch" <wait.3>
/ac "Standard Touch" <wait.3>
```

```plain {3} showLineNumbers
/ac "Prudent Touch" <wait.3>
/ac "Byregot's Blessing" <wait.3>
/ac "Careful Synthesis" <wait.3>
```
