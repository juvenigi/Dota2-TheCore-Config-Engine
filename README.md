**NOTE:** The autoconfig file doesn't work, because it needs some **_rewiring_**.

# What is this branch used for?
This is the place where **Loop's layout** is modified. It is especially useful, because it has some neat optimizations/features as well as aliases that I'd like to _borrow_.

The keybinds will receive a massive overhaul. Some features like **hk** will be probably removed or heavily edited.

## What are **layouts** and **alias_global**?
**layouts** directory is designed to allow people who use alternative English layouts like **_Colemak_** or **_Dvorak_** to enjoy the keybinds with less pain. The only downside to this is that keybinds will be harder to edit, because each character key has to have an alias. However, the key aliases will represent their coordinates relative to the home row. This image should be used as a reference:

[][heatmap]

**alias_global** is, for the most part, a self-explanatory folder where global aliases are stored. For instance, instead of using `playsound sounds/ui/coins_big.vsnd_c` one can simply use `sound_midas`.
<!-- links -->

[heatmap]: http://github.com
