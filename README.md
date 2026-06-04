# ItemEdit Light

![ItemEdit Banner](banner.png)

**ItemEdit Light** is a powerful, lightweight item customization plugin for Paper/Spigot Minecraft servers (1.20.4 - 1.21.x+). It allows server administrators and players to customize their weapons and items with custom stats, lore, flags, enchantments, and custom special abilities.

---

## 🎨 Branding / Icon
<img src="logo.png" width="128" height="128" alt="ItemEdit Logo" />

---

## 🚀 Key Features

* **50 Custom Abilities**: Built-in specialized abilities representing multiple themes:
  - **Warden**: Sonic boom, wardens call, etc.
  - **Undead (Zombie/Skeleton)**: Summon helpers, custom arrows, etc.
  - **Enderman/End**: Teleportation and void abilities.
  - **Nether**: Fire and explosion-themed skills.
  - **Meteor Strike**: Cast various sizes of meteors (small, medium, large, gigantic).
  - **General/Overworld**: Lightning, elemental strikes, and more.
* **🛡️ Self-Damage Protection**: Built-in mechanism to prevent players from taking damage from their own abilities (e.g., custom lightning, projectiles, or explosion effects).
* **Command Suite**: Customize items on-the-fly using commands:
  - `/ie rename <name>`: Rename items with MiniMessage (RGB) or legacy color codes.
  - `/ie lore <add/set/remove/clear>`: Manage multi-line lore.
  - `/ie enchant <enchantment> <level>`: Enchant items with bypass support.
  - `/ie unbreakable <true/false>`: Set the item to be unbreakable.
  - `/ie flag <add/remove/clear> <flag>`: Manage specific item flags.
  - `/ie attribute <add/remove/clear> <attribute> [value]`: Add attributes like health, attack speed, movement speed, etc.
  - `/ie ability <add/remove/list> [ability]`: Bind custom abilities to items.
  - `/ie hidetooltips [true/false]`: Hide or show item tooltips (flags).
* **Full Tab Completion**: Auto-completes all subcommands, arguments, enchantments, attributes, flags, abilities, and parameters.

---

## 🛠️ Commands & Permissions

- **Command**: `/ie` or `/itemedit`
- **Permission**: `itemedit.use` (default: op)

---

## ⚙️ Compilation & Installation

ItemEdit is built on Java 17.

1. Clone the repository.
2. Build with Maven:
   ```bash
   mvn clean package
   ```
3. Copy the compiled jar from `target/ItemEditLight.jar` to your server's `plugins` directory.
