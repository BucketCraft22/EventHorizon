# 🌌 EventHorizon for Velocity

![Version](https://img.shields.io/badge/version-1.0-purple.svg)
![Platform](https://img.shields.io/badge/platform-Velocity-blue.svg)

**EventHorizon** is a next-generation event management and MOTD countdown plugin for Velocity. It allows network owners to build hype for upcoming events with dynamic MOTDs, version-string countdowns, and automated player redirection—all managed from a single central proxy.

---

## ✨ Features

* **Dynamic Countdown MOTD:** Automatically switches between "Normal", "Urgent" (last 24h), and "Live" phases.
* **Version-String Magic:** Replaces the player count/version area (e.g., `1.20.1`) with a live countdown timer.
* **Auto-Redirect:** Automatically "sucks" all players from their current servers into the event server the moment the timer hits zero.
* **Title Alerts:** Sends a massive, gradient-colored Title & Subtitle to every player on the network when the event starts.
* **MiniMessage Support:** Full support for modern, fancy text gradients and hover events.

---

## 🚀 Installation

> [!CAUTION]
> **Compatibility Requirement:** EventHorizon is built specifically for **Velocity 3.0 and above**. It will not function on older legacy versions. Please verify your proxy version using `/velocity` before installing.

1.  Download the latest `EventHorizon.jar`.
2.  Place it into your Velocity `plugins` folder.
3.  Restart your proxy to generate the initial files.
4.  Configure your `target-date` in `plugins/eventhorizon/config.yml`.
5.  Use `/eh reload` to apply changes instantly.

---

## 🛠️ Commands & Permissions

| Command | Alias | Description | Permission |
| :--- | :--- | :--- | :--- |
| `/eh reload` | `/eventhorizon` | Reloads the config and checks for updates. | `eventhorizon.admin` |
| `/eh` | - | Displays current event status and help. | `eventhorizon.admin` |

---

## 📞 Support

Created by **BucketCraft**.
Need help? Reach out on Discord: `@bucketcraft`
> [!WARNING]
> If you manually modify the internal structure of the configuration files (such as deleting the `config-version` field or breaking the YAML syntax), the automatic migration system may fail.

---

## 📜 Legal

This project is licensed under the **GNU General Public License v2.0**. 
See the `LICENSE` file for more details.
