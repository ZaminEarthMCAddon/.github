# ZaminEarthMCAddon

We build [ZEA](https://github.com/ZaminEarthMCAddon/ZEA), a client-side
Fabric mod for [EarthMC](https://earthmc.net), and the supporting
infrastructure around it — the community data repository, its schemas and
the automation that keeps them honest.

## Projects

| Repository | What it is |
|---|---|
| [ZEA](https://github.com/ZaminEarthMCAddon/ZEA) | The main mod: chat, the NEU-style shop item browser, shop observation, the native EarthMC map, inventory utilities and item rarity. |
| [ZEA-REPO](https://github.com/ZaminEarthMCAddon/ZEA-REPO) | Community-maintained EarthMC data: curated datasets with schemas and CI validation, consumed by the mod. |

## What ZEA does

ZEA is an all-in-one EarthMC addon, exclusively client-side. It rebuilds the
chat around EarthMC's message types, indexes every physical shop your client
observes into a browsable item pane beside the inventory, renders a native
EarthMC map with claims and players, and computes item rarity from the items'
real components and enchantments. It never sends anything on your behalf
unless you explicitly trigger it.

## Getting started

1. Install the [Fabric Loader](https://fabricmc.net/use/) for Minecraft 26.3.
2. Grab the newest build from
   [ZEA releases](https://github.com/ZaminEarthMCAddon/ZEA/releases) — a dev
   build is published on every push to `develop`.
3. Drop the jar and [Fabric API](https://modrinth.com/mod/fabric-api) into
   `mods` and connect to `earthmc.net`.

See [ZEA's README](https://github.com/ZaminEarthMCAddon/ZEA#readme) for
commands, configuration and how your data is handled.

## Contributing

- Code changes and bug reports go to
  [ZEA](https://github.com/ZaminEarthMCAddon/ZEA/issues).
- Data contributions (shop observations, town and nation descriptions) go to
  [ZEA-REPO](https://github.com/ZaminEarthMCAddon/ZEA-REPO), whose
  [contribution guide](https://github.com/ZaminEarthMCAddon/ZEA-REPO/blob/main/CONTRIBUTING.md)
  covers the validation flow.

## Status

Both projects are under active development. Development builds ship from
`develop`; release notes live on each repository's releases page.
