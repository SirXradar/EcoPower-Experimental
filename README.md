# EcoPower-Experimental

<a href="https://github.com/SirXradar/EcoPower-Experimental">
  <img src="https://img.shields.io/github/v/release/SirXradar/EcoPower-Experimental?label=Release&style=for-the-badge&color=green)">
</a>
<a href="https://github.com/SirXradar/EcoPower-Experimental/blob/main/LICENSE">
  <img src="https://img.shields.io/github/license/SirXradar/EcoPower-Experimental?label=License&style=for-the-badge&color=blue)">
</a>

> **EcoPower** is a [Slimefun4](https://blob.build/project/Slimefun4/Experimental) addon that adds high-tier generators to power your setups. This fork has been updated for **Slimefun4 Experimental (4.9-UNOFFICIAL)** by **SirXradar**.

---

## Features

| Generator | Description |
|-----------|-------------|
| **Steam Turbines** (T1–T3) | Generate power from bubble columns in water |
| **Wind Turbines** (T1–T3) | Generate power when placed on fence stacks with open sky |
| **High-Energy Solar Generator** | Powerful solar panel running day and night |
| **Lunar Generator** | Solar generation that only works at night |
| **Lightning Receptor** | Harnesses lightning strikes during thunderstorms |
| **Radiant Solar Generator** | Next-gen solar with combined day/night output |
| **High-Energy Solar Helmet** | Charges held items and worn armor passively |

---

## Requirements

- **Minecraft:** 1.21+
- **Server Software:** [Paper](https://papermc.io/)
- **Core:** [Slimefun4 Experimental](https://blob.build/project/Slimefun4/Experimental)

> ✅ **InfinityLib is already shaded** into the JAR — no separate dependency needed.

---

## Installation

1. Download the latest release JAR: [`EcoPower-Experimental-V1.jar`](https://github.com/SirXradar/EcoPower-Experimental/releases)
2. Place it in your server's **`/plugins/`** folder.
3. Ensure **Slimefun4 Experimental** is also installed.
4. Start or restart your server.

---

## Building from Source

```bash
git clone https://github.com/SirXradar/EcoPower-Experimental.git
cd EcoPower-Experimental
mvn clean package
```

The compiled JAR will be output to `target/EcoPower-Experimental-V1.jar`.

---

## Configuration

Edit `config.yml` inside the JAR or at `plugins/EcoPower/config.yml`:

```yaml
options:
  auto-update: true
```

---

## Credits

| Contributor | Role |
|-------------|------|
| [TheBusyBiscuit](https://github.com/TheBusyBiscuit) | Original creator |
| [SirXradar](https://github.com/SirXradar) | Fork maintainer |

---

## Contact & Support

- **GitHub Issues:** https://github.com/SirXradar/EcoPower-Experimental/issues
- **Telegram:** [@AmirrezaXR](https://t.me/SeniorIDE) / `t.me/SeniorIDE`

---

## License

This project is licensed under the **GNU General Public License v3.0** — see [LICENSE](LICENSE) for details.
