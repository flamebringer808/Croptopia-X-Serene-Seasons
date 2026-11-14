# 🌾 Croptopia X Serene Seasons (Minecraft 1.20.1)

![Croptopia X Serene Seasons](pack.png)

A lightweight, zero-code compatibility bridge connecting **[Croptopia](https://curseforge.com/minecraft/mc-mods/croptopia)** and **[Serene Seasons](https://modrinth.com/mod/serene-seasons)** for **Minecraft 1.20.1** (available for **Fabric**, **Forge**, and as a **Standalone Data Pack**).

---

## 🌟 Overview
In standard Minecraft setups without compatibility configs, crops from Croptopia grow regardless of the current season and lack in-game fertility tooltips. Furthermore, if you configure Serene Seasons to break out-of-season crops (`outOfSeasonCropBehavior = 2`), multi-season fruit trees and saplings could inadvertently break when winter arrives.

**Croptopia X Serene Seasons** addresses these issues using Minecraft's native tag system:
- **58 Farmland Seeds & 27 Tree Saplings** display dynamic seasonal tooltips indicating fertile seasons.
- **58 Farmland Crop Blocks & 26 Fruit-bearing Leaf Blocks** adhere to seasonal growth restrictions and bonemeal logic.
- **Orchard & Sapling Winter Protection**: Fruit trees, cinnamon trees, and saplings are registered as unbreakable infertile crops, allowing them to go safely dormant during off-seasons instead of breaking.
- **Full Greenhouse Glass Support**: Crops planted under Serene Seasons Greenhouse Glass (up to 16 blocks above) continue to grow year-round.

---

## 📅 Seasonal Distribution Guide

| Season | Farmland Crops | Fruit, Nut & Spice Trees |
| :--- | :--- | :--- |
| **🌸 Spring** | Artichoke, Asparagus, Barley, Cabbage, Coffee, Currant, Garlic, Ginger, Green Bean, Green Onion, Lettuce, Mustard, Oat, Onion, Radish, Rhubarb, Rice, Spinach, Strawberry, Tea, Turmeric | Almond, Apple, Apricot, Avocado, Cherry, Cinnamon, Fig, Kumquat, Lemon, Lime, Nectarine, Orange, Peach, Pear, Plum |
| **☀️ Summer** | Artichoke, Barley, Basil, Bell Pepper, Black Bean, Blackberry, Blueberry, Cantaloupe, Chile Pepper, Coffee, Corn, Cucumber, Currant, Eggplant, Ginger, Grape, Green Bean, Honeydew, Hops, Kiwi, Oat, Olive, Peanut, Pepper, Pineapple, Raspberry, Rice, Saguaro, Soybean, Squash, Strawberry, Sweet Potato, Tea, Tomatillo, Tomato, Turmeric, Vanilla, Yam, Zucchini | Almond, Apple, Apricot, Avocado, Banana, Cashew, Cherry, Cinnamon, Coconut, Date, Dragonfruit, Fig, Grapefruit, Kumquat, Lemon, Lime, Mango, Nectarine, Nutmeg, Orange, Peach, Pear, Pecan, Persimmon, Plum, Starfruit, Walnut |
| **🍂 Autumn** | Barley, Black Bean, Broccoli, Cabbage, Cauliflower, Celery, Corn, Cranberry, Currant, Eggplant, Elderberry, Garlic, Grape, Green Onion, Hops, Kale, Leek, Lettuce, Mustard, Olive, Onion, Pepper, Radish, Rutabaga, Spinach, Squash, Sweet Potato, Tea, Turmeric, Turnip, Vanilla, Yam | Almond, Apple, Apricot, Avocado, Banana, Cashew, Cherry, Cinnamon, Coconut, Date, Dragonfruit, Fig, Grapefruit, Kumquat, Lemon, Lime, Mango, Nectarine, Nutmeg, Orange, Peach, Pear, Pecan, Persimmon, Plum, Starfruit, Walnut |
| **❄️ Winter** | Broccoli, Cabbage, Cauliflower, Celery, Kale, Leek, Rutabaga, Spinach, Turnip | *(Dormant — protected from frost breaking via `unbreakable_infertile_crops`)* |

---

## 📦 Distributions & Installation

Both **Croptopia** and **Serene Seasons** are required for this compatibility project.

### 1. Fabric Mod (`.jar`)
- **File**: `croptopia_serene_seasons-1.0.0-1.20.1-fabric.jar`
- **Installation**: Drop into your `.minecraft/mods/` folder.
- **Dependencies**: Requires `minecraft` (~1.20.1), `fabricloader` (>=0.14.0), `fabric-resource-loader-v0` (part of Fabric API), `croptopia` (>=2.2.0), and `sereneseasons` (>=9.0.0).

### 2. Forge Mod (`.jar`)
- **File**: `croptopia_serene_seasons-1.0.0-1.20.1-forge.jar`
- **Installation**: Drop into your `.minecraft/mods/` folder.
- **Dependencies**: Requires `minecraft` ([1.20.1,1.20.2)), `forge` (>=47.1.0), `croptopia` ([2.2.0,)), and `sereneseasons` ([9.0.0,)).

### 3. Standalone Data Pack (`.zip`)
- **File**: `croptopia_serene_seasons-1.0.0-1.20.1-datapack.zip`
- **Installation**: Drop into `.minecraft/saves/<your_world>/datapacks/` or world creation datapack folder.
- **Requirements**: Requires the `croptopia` and `sereneseasons` mods installed in the game instance to provide the corresponding items, blocks, and season mechanics.

---

## 📜 License
All Rights Reserved (c) 2026 FLAMEBRINGER808.

- **Modpacks**: Modpack authors are granted explicit permission to include this project in their modpacks on CurseForge, Modrinth, or custom launchers, provided proper credit is given to FLAMEBRINGER808.
- **Redistribution**: Standalone redistribution, mirroring, re-uploading to third-party platforms, or publishing modified versions requires the author's prior written permission.
- **Third-Party Rights**: This project does not claim ownership of or grant licenses to Croptopia, Serene Seasons, Minecraft, Forge, Fabric, NeoForge, or any third-party libraries or assets, which remain under their respective licenses and rights holders. See [LICENSE](LICENSE) for full terms.
