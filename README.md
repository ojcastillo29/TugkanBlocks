# TugkanBlocks

TugkanBlocks is a custom server-sided Fabric Minecraft mod that introduces a variety of new blocks, an in-game shop for block purchasing, and a custom UI for managing and purchasing these blocks.

## Features
- **Custom Blocks**: Introduces a range of new blocks that can be used for building and decoration.
- **Economy Integration**: Players can purchase blocks using in-game currency through the Impactor economy API.
- **User Interface**: Custom UIs for purchasing blocks and navigating the available options.
- **Permissions**: Custom permissions using the LuckPerms API for controlling access to certain commands and features.

## Commands

### `/tblocks`
- Opens the **Main Menu UI** for navigating block options.
- **Permission**: `tugkanblocks.menu`

### `/tblocks reload`
- Reloads the configuration files, including language and price settings.
- **Permission**: `tugkanblocks.reload`.

## Permissions

### `tugkanblocks.menu`
- Allows access to the `/tblocks` command to open the **Main Menu UI**.

### `tugkanblocks.reload`
- Allows access to the `/tblocks reload` command to reload configuration files.

## Configuration Files

- **blocks.json**: Stores and allows the addition of more blocks to the collection.
- **lang.json**: Stores language strings for in-game messages, including UI titles, success/failure messages, and block names.
- **Price.json**: Stores pricing information for all custom blocks. Prices are configurable per block.

## Installation
1. Download the **TugkanBlocks** mod.
2. Requires the assets of [TugkanDeMans-Blocks](https://mcmodels.net/products/12313/tugkandemans-blocks) (Paid)
3. Place the mod in the `mods` folder of your Minecraft installation.
4. Make sure you have LuckPerms, Gooeylibs, Polymer and Impactor installed and configured.

## API Integrations
- **LuckPerms**: Used for permissions management.
- **Impactor**: Used for handling economy transactions.
- **Gooeylibs**: Used for handling GUI design.
- **Polymer**: Used for Server Sided block handling.

