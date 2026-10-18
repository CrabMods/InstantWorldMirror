# InstantWorldMirror - Instant World Mirror

<!-- PROMO-VIDEO:START -->

**Explore boldly while your world stays safe. Scout a temporary copy, test builds in Creative, revisit untouched seed terrain or reopen a captured world slice from another save.**

| Minecraft | Loader | Java |
| --- | --- | --- |
| 1.20.1 | Forge | 17 |
| 1.21.1 | NeoForge | 21 |

Choose the matching file for your Minecraft version and loader. Install on the server and every connecting client. Older releases may have different features.

[![Watch the trailer](https://i.ytimg.com/vi/AMWi2Ea9uMI/maxresdefault.jpg)](https://www.youtube.com/watch?v=AMWi2Ea9uMI)

 [Watch the trailer](https://www.youtube.com/watch?v=AMWi2Ea9uMI) · 1:26 · 1080p · English captions, music and effects

[CurseForge](https://www.curseforge.com/minecraft/mc-mods/instantworldmirror) · [Modrinth](https://modrinth.com/mod/instant-world-mirror) · [GitHub](https://github.com/CrabMods/InstantWorldMirror)

Stranded snapshots reopen across saves on the same Minecraft version. Item retention follows world/server rules.

<!-- PROMO-VIDEO:END -->

> **Full player guide:** For advanced features, complete recipes, detailed effects, configuration and compatibility, visit the [official InstantWorldMirror guide](https://crabmods.com/mods/mirror).

## What This Mod Does

InstantWorldMirror lets you create temporary or saved mirror worlds at your current location. You can explore, test builds, test combat, or inspect freshly generated terrain in a separate world, with configurable player-state and item-transfer rules.

The mod has four mirror items. Each one opens a separate mirror world with its own copy rules, game mode, save options, and terrain refresh rules.

## Choose a Mirror

- **World Reflection Mirror** creates the standard temporary copy around you.
- **Heaven Mirror** sends you to a temporary Creative-mode sandbox.
- **First Dream Mirror** recreates the area's original terrain from the current world seed, ignoring player-made changes in the original world.
- **Stranded Mirror** captures a named world slice into a global local cache, then reopens it from another save running the same Minecraft version.

Use World Reflection Mirror for normal testing, Heaven Mirror for Creative testing, First Dream Mirror for original terrain, and Stranded Mirror to move builds or terrain between saves.

## Session Flow

- Right-click a solid block with World Reflection, Heaven, or First Dream Mirror to create an entry portal.
- Right-click a solid block with Stranded Mirror, enter a name, and wait for the configured area to be cached. Saving does not create a portal. Use it in the air or Shift-right-click to open one long-term menu with separate Persistent mirror world and Cross-save world slice sections.
- When the portal finishes copying or generating the area, step in to enter the mirror world.
- Inside a World Reflection Mirror or First Dream Mirror world, right-click a solid block to create a return portal. If that portal is far from the entrance, it returns you to the matching position in the original world.
- Hold right-click in the air inside a mirror world to return to that mirror world's entrance point without leaving the mirror world.
- Heaven Mirror worlds cannot create return portals; use the original entrance or `/iwm return`.
- If you die in a mirror world, the mod returns you to the original world and restores its saved player state.
- Each player can have only one mirror session open at a time.
- Other players can use the same entry portal after the creator enters first; if the creator leaves a temporary session, everyone else is sent back too.
- If you disconnect and rejoin while the mod still has your mirror-world save state, it tries to restore your original-world location, inventory, and player state.
- Temporary mirror worlds clean themselves up after players leave.

## World Rules and Saved Mirrors

The configured copy radius and server rules control what is copied, who can enter, mob spawning and whether items may leave a mirror world. **Heaven's Creative items also follow the item-transfer rule.**

**Permanence** lets permitted players save completed temporary mirrors and return later. **Renewal** adds mob-refresh options to First Dream; **Superflat** adds a clean building option to Heaven. The official guide explains permissions, cooldowns, saved-mirror management and compatible cross-save snapshots.

## Crafting Recipes

World Reflection Mirror: glass, obsidian, and an ender pearl.

```
[Glass]    [Obsidian]    [Glass]
[Obsidian] [Ender Pearl] [Obsidian]
[Glass]    [Obsidian]    [Glass]
```

Heaven Mirror: glowstone, redstone, and an ender pearl.

```
[Glowstone]     [Redstone Dust] [Glowstone]
[Redstone Dust] [Ender Pearl]   [Redstone Dust]
[Glowstone]     [Redstone Dust] [Glowstone]
```

First Dream Mirror: oak saplings, glass, oak logs, and an ender pearl.

```
[Oak Sapling] [Glass]       [Oak Sapling]
[Oak Log]     [Ender Pearl] [Oak Log]
[Oak Sapling] [Glass]       [Oak Sapling]
```

Stranded Mirror: glass, black concrete, coal, and an ender pearl.

```
[Glass] [Black Concrete] [Glass]
[Coal]  [Ender Pearl]    [Coal]
[Glass] [Black Concrete] [Glass]
```

## More details

For more advanced features, full recipes, effect values, configuration and compatibility help, see the **[official player guide](https://crabmods.com/mods/mirror)**.

[Downloads and release notes](https://github.com/CrabMods/InstantWorldMirror/releases) · [Report a bug](https://github.com/CrabMods/InstantWorldMirror/issues)

[Development reference for this checkout](docs/PLAYER_GUIDE.md) · [Apache License 2.0](https://www.apache.org/licenses/LICENSE-2.0)
