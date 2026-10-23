# Fortune Harvest

A Fabric mod for Minecraft Java 26.3 that makes the Fortune enchantment boost **wheat** and **beetroot** drops, not just their seeds.

![Fortune Harvest icon](src/main/resources/assets/fortuneharvest/FHarvest1.png)

## Why?
In vanilla, Fortune gives extra carrots and potatoes, but for wheat and beetroot it only adds extra seeds. Fortune Harvest fixes that.

## How it works
- Harvesting a fully grown wheat or beetroot crop with a Fortune tool gives bonus crops.
- Without Fortune, drops stay exactly like vanilla.
- With Fortune III you get up to 3 extra wheat or beetroot per crop.
- Built purely with data-driven loot tables, so there's no mixin and no config needed.

## Requirements
- Minecraft Java 26.3
- Fabric Loader

## Compatibility
This mod replaces the vanilla `wheat` and `beetroots` loot tables, so it may conflict with other mods or data packs that change those same tables.

## Building from source
```
git clone https://github.com/satria-nu-li-xue-xi/FortuneHarvest.git
cd FortuneHarvest
./gradlew build
```
The mod jar ends up in `build/libs/`. You'll need Java 25.

## License
MIT
