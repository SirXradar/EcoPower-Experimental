# EcoPower-Experimental

A Slimefun4 addon that adds high-tier generators to power your setups.

### Forked for Slimefun4 Experimental (4.9-UNOFFICIAL)

This fork is maintained by [SirXradar](https://github.com/SirXradar) and has been updated to work with Slimefun4 Experimental.

## Features

- **Steam Turbines** (T1, T2, T3) - Generate power from bubble columns
- **Wind Turbines** (T1, T2, T3) - Generate power when placed on fence stacks
- **High-Energy Solar Generator** - Powerful solar generation
- **Lunar Generator** - Only works at night
- **Lightning Receptor** - Harnesses lightning strikes during thunderstorms
- **Radiant Solar Generator** - Day and night solar generation
- **High-Energy Solar Helmet** - Charges held items and armor

## Requirements

- Minecraft 1.21.1+
- PaperMC
- Slimefun4 Experimental 4.9-UNOFFICIAL
- InfinityLib 1.3.9

## Installation

1. Download the latest release JAR from the [GitHub Releases](https://github.com/SirXradar/EcoPower-Experimental/releases) or [SpigotMC](https://www.spigotmc.org/resources/ecopower-experimental.12345/)
2. Place the JAR file into your `plugins/Slimefun/addons/` folder
3. Restart or reload your server

## Building from Source

```bash
git clone https://github.com/SirXradar/EcoPower-Experimental.git
cd EcoPower-Experimental
mvn clean package
```

The compiled JAR will be in `target/EcoPower-Experimental-V1.jar`.

## Configuration

The plugin includes a `config.yml` file with the following options:

```yaml
options:
  auto-update: true
```

## Credits

- Original addon by [TheBusyBiscuit](https://github.com/TheBusyBiscuit)
- Forked and updated for Slimefun4 Experimental by [SirXradar](https://github.com/SirXradar)
- [Slimefun4 Experimental](https://github.com/SlimefunExperimental/Slimefun4)
- [InfinityLib](https://github.com/Mooy1/InfinityLib)

## License

This project is licensed under the GNU General Public License v3.0.
