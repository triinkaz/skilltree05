# PoE 2 Passive Tree Viewer

Single-file HTML viewer for the Path of Exile 2 passive skill tree (v0.5.0).

## Usage

Open `poe2-passive-tree.html` in any modern browser. Everything is embedded — no server, no install. 

## Features

- Pan and zoom over all 5,102 nodes
- Search by node name or modifier
- Jump to any class or ascendancy from the dropdown
- Filter by node type (notable, keystone, mastery, etc.)
- Hover any node to see its info above it; click to pin

## Highlights

Three categories of nodes are color-coded on the tree:

- 🟣 **New in v0.5** — 148 nodes (skill IDs that did not exist in v0.4)
- 🟢 **Changed v0.4 → v0.5** — 183 nodes (numerical buffs or nerfs only; pure wording changes are filtered out)
- 🔵 **Druid+Oracle exclusive** — 197 nodes (only accessible to Druid ascending into Oracle)

For nodes in the "Changed" category, the tooltip shows the v0.4 stats struck through next to the new v0.5 stats.

## Data

Built from the official Grinding Gear Games exports: [`poe2-skilltree-export`](https://github.com/grindinggear/poe2-skilltree-export), versions 0.4.0 and 0.5.0.



