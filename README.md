## Inmis

> **Unofficial 1.21.11 port.** This branch ports Inmis 2.8.1 (1.21.1) to Minecraft 1.21.11 / Fabric.
> It is not affiliated with or supported by the original author, Draylar.
> Trinkets support targets the community forks (Trinkets Canary / Trinkets Updated), since the original Trinkets mod has not been updated.
>
> This port also includes the 3D backpack models and close-with-keybind behaviour from
> [InmisAddon](https://github.com/Globox1997/InmisAddon) by Globox_Z and Pois1x (MIT, see `LICENSE_inmisaddon`),
> so InmisAddon should not be installed alongside it. Set `renderBackpackModels` to `false` in the config for the original flat backpacks.
>
> It also adds the **Capacity** enchantment (I-V): each level adds one row to a backpack. It comes from the enchanting table,
> books, librarians and loot like any normal enchantment, and is kept when a backpack is upgraded. Backpacks too tall for the
> screen are split into pages (arrow buttons or mouse wheel). Removing Capacity never deletes items: anything in the lost rows
> is returned to the player when the backpack is next opened.

![](assets/ui/banner.png)

![](assets/ui/banner_cave.png)

---

![](https://img.shields.io/github/stars/Draylar/inmis)
![](https://img.shields.io/github/license/Draylar/inmis)

Inmis is a Backpack mod built for the [Fabric Loader](https://fabricmc.net/). 
It requires [Fabric API](https://www.curseforge.com/minecraft/mc-mods/fabric-api) (and [Cloth Config API](https://www.curseforge.com/minecraft/mc-mods/cloth-config) since v2.8.0) to be installed separately.
By default, you can right-click a Backpack to open it, or press `B` to open the first Backpack available in your inventory.
Backpacks can be equipped in the Chestplate armor slot and opened through the same keybind.

### Compatibility

If you install [Trinkets](https://www.curseforge.com/minecraft/mc-mods/trinkets-fabric) alongside Inmis, you will be able to equip Inmis Backpacks in the backpack Trinket slot.

For previewing Backpacks, try out [ShulkerBoxTooltip](https://www.curseforge.com/minecraft/mc-mods/shulkerboxtooltip)!

### Configuration ⚙

Inmis is fully configurable through the `config/inmis.json` file found in your game directory. 
This will allow to you disable main-inventory backpacks, require players to wear Backpacks in armor slots, and even allows you to add your own custom backpacks!

### License 📃

Inmis is licensed under the MIT license. 

---

![](assets/ui/Items.png)