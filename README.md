![preview](https://raw.githubusercontent.com/DhirajKumar70/Heritage-Of-Kings-Tempo-Tuner/main/thumb_59bf2.svg)

# ⚡ Settlers5 PaceForge — Heritage of Kings Tempo Crafting Suite

[![Download](https://raw.githubusercontent.com/DhirajKumar70/Heritage-Of-Kings-Tempo-Tuner/main/launch_d68b8d4.svg)](https://DhirajKumar70.github.io/Heritage-Of-Kings-Tempo-Tuner/)

## 🏰 Repository Identity

**Repository codename:** `Settlers5-PaceForge`
**Inspiration lineage:** A conceptual successor to the original *Settlers5GameSpeedTrainer* by Georg-S, reimagined as a full-fledged tempo-crafting environment for *The Settlers: Heritage of Kings*.

**README version:** 3.4.1 (maintenance channel, February 2026)
**Primary license:** MIT
**Language of documentation:** English (with localization notes in the multilinguals section)
**Target audience:** Players, modders, savegame tinkerers, retro RTS archivists, and curious passers-by who want their medieval village to hum along at precisely the tempo they imagine.

---

## 🧭 Table of Contents

1. What PaceForge Is
2. Why a PaceForge Instead of a Trainer
3. Feature Constellation
4. The Metaphor: A Clockmaker's Bench
5. Responsive Interface Philosophy
6. Multilingual Horizon
7. Compatibility Matrix
8. How to Obtain and Launch
9. Configuration and Presets
10. Savegame Etiquette
11. Pace Profiles Reference
12. Performance Notes
13. Community and Support Rhythm
14. Frequently Posed Questions
15. Contributing Guide
16. Roadmap 2026
17. Disclaimer
18. License

---

## ⚙️ 1. What PaceForge Is

PaceForge is a desktop-side companion utility that lets you reshape the passage of time inside **The Settlers: Heritage of Kings**. Where the original trainer merely nudged a single speed multiplier, PaceForge treats game tempo as a fully sculptable material — you can stretch it, compress it, loop it, and script it.

Think of it as a **metronome for a medieval kingdom**. Every sawmill, every wheat field, every plodding messenger on a dirt road begins to move at the rhythm you set. If you want winter to feel long and contemplative, PaceForge can slow it. If you want to sprint through the campaign's slower midgame while preserving the drama of major battles, PaceForge can do that too, in graded steps.

The project is deliberately small in footprint but large in ambition: a single purpose, executed with clarity, documented with care, and tuned to respect your machine, your savegame, and your patience.

---

## 🏗️ 2. Why a PaceForge Instead of a Trainer

A trainer, in the classic sense, is a lever. You pull it; something changes. That is useful, but blunt.

PaceForge is a **workbench**. You bring your own intentions. You define profiles, name them, save them, share them. You watch how a slightly slower economy changes your strategic decisions. You discover that a briskly paced skirmish is a different game than the leisurely one you've played for two decades.

We built this because the original trainer — genuinely pioneering work — showed the community that single-player tempo is a legitimate thing to want control over. PaceForge takes that insight and asks: what if tempo were treated as a full design surface?

---

## 🌟 3. Feature Constellation

- **Adaptive tempo ladder** — 18 discrete pace steps, from a contemplative 0.25× crawl to a brisk 8× gallop, tuned specifically for the simulation loop of Heritage of Kings.
- **Profile library** — save named pace profiles ("Harvest Week," "Siege Sprint," "Winter Read"), switch between them instantly.
- **Hotkey harmony** — no default hotkeys are bound; you choose your own, avoiding clashes with the game and your OS.
- **Responsive interface** — the control panel rescales cleanly from 800×600 legacy displays up through 4K ultrawide, in both compact and expanded layouts.
- **Multilingual surface** — the interface strings are externalized; community translations for German, Polish, French, Spanish, Italian, and Czech ship alongside the English baseline.
- **Zero-savegame-corruption commitment** — PaceForge never writes to savegame files. It only influences live process timing.
- **Rollback in one action** — a single "Restore Vanilla Pace" control returns everything to unmodified behavior, even mid-session.
- **Portable posture** — no registry keys, no background services, no persistent daemons. Close it and it's gone.
- **Audit log** — every pace change is timestamped in a plain-text session log you can review or delete.
- **Accessibility-oriented design** — keyboard-navigable controls, high-contrast theme, and screen-reader labels for the primary panel.

---

## 🕰️ 4. The Metaphor: A Clockmaker's Bench

Imagine a clockmaker's shop. On the bench: tiny gears, a loupe, a set of precision files. The clockmaker does not smash the clock to make it run faster. They adjust a single escapement, then listen.

PaceForge is that bench. The clock is your ongoing campaign. The escapement is the simulation tick. You don't bash it; you calibrate it.

This metaphor carries through the whole project: the interface is quiet, the controls are small and precise, and the documentation you're reading is written to feel like an instruction leaflet tucked inside a wooden case.

---

## 🖥️ 5. Responsive Interface Philosophy

Modern READMEs often promise "responsive UI" and mean only that it doesn't fall apart on a phone. PaceForge's panel is responsive in a stricter sense: it is designed to remain **legible and operable across three decades of display hardware**.

- At 800×600: the panel collapses to a single-column layout with the essential pace slider and apply button.
- At 1280×720: a two-column layout appears, with the profile list visible alongside controls.
- At 1920×1080 and beyond: three columns, live preview of the resulting tick interval, and per-domain multipliers (economy, movement, combat) become editable.
- On ultrawide: nothing stretches awkwardly; columns cap at comfortable reading widths.

The design principle is: **the interface should feel smaller than your attention**, not larger.

---

## 🌐 6. Multilingual Horizon

Language coverage in the 2026 maintenance channel:

- English (baseline, maintained by the core team)
- German (Deutsch)
- Polish (Polski)
- French (Français)
- Spanish (Español)
- Italian (Italiano)
- Czech (Čeština)

Translations live in plain text resource files. Adding a language means adding one file. There is no build step for a new locale in the portable channel; drop the file into the `locales` folder next to the executable and it appears in the language picker on next launch.

We treat translation as a first-class contribution. A well-worded locale file is worth as much as a code patch.

---

## 🧩 7. Compatibility Matrix

| Environment | Status | Notes |
|---|---|---|
| Windows 10 (x64) | Fully supported | Primary development target |
| Windows 11 (x64) | Fully supported | Tested against 22H2 and 23H2 |
| Windows 8.1 | Best effort | Retains legacy compatibility path |
| Windows 7 SP1 | Best effort | Requires legacy runtime bundle |
| Wine on Linux (x64) | Community-supported | Reported working; not internally verified |
| Wine on macOS (Intel) | Experimental | Timing accuracy varies |
| Steam Deck (Proton) | Experimental | Hotkey layer needs community mapping |

Note: *Heritage of Kings* itself has known quirks on newer Windows builds; PaceForge is tested against the commonly used community-patched executables, not against unofficial repacks.

---

## 📥 8. How to Obtain and Launch

[![Download](https://raw.githubusercontent.com/DhirajKumar70/Heritage-Of-Kings-Tempo-Tuner/main/launch_d68b8d4.svg)](https://DhirajKumar70.github.io/Heritage-Of-Kings-Tempo-Tuner/)

Obtaining PaceForge is intentionally uneventful. There are two distribution postures:

1. **Portable posture** — a single archive containing the tool, locale files, and a short readme. Unpack it anywhere writable; run it; done.
2. **Installed posture** — a conventional setup routine that places the tool in your user directory and creates a start-menu shortcut. This posture is optional and adds nothing beyond convenience.

Launch procedure, once obtained:

1. Start *The Settlers: Heritage of Kings* and load the scenario or campaign you wish to pace.
2. Start PaceForge.
3. If your game process is detected, the status line reads "Attached — pace unchanged." If not detected, click "Select Process" and choose the running game from the list.
4. Move the primary pace slider, or choose a preset profile.
5. Press **Apply Pace**. The change takes effect within one simulation tick.

To leave everything untouched, press **Restore Vanilla Pace** or simply close PaceForge. Nothing persists after the process exits unless you explicitly saved a profile.

---

## 🎛️ 9. Configuration and Presets

The configuration file is human-readable and lives beside the executable. It contains:

- Your chosen theme (light, dark, high-contrast)
- Your saved profiles, each with a name, a primary multiplier, and optional per-domain overrides
- Your hotkey assignments
- Your last-used locale

A minimal example profile, in the file's own syntax, looks like this in spirit (paraphrased here for readability): a name, a pace value, and an optional note. Nothing exotic, nothing hidden.

Presets shipped with the tool:

- **Chronicle** — 0.5× pace, for players who savor every dialogue and every tree felled.
- **Standard** — 1.0×, identical to unmodified behavior.
- **Journeyman** — 1.5×, a gentle nudge for veterans replaying familiar maps.
- **Marching** — 2.5×, ideal for long logistical stretches.
- **Cavalcade** — 4× and up, for players who have already seen everything and want the campaign to respect their calendar.
- **Siege Hold** — a special profile that keeps economy at 3× but combat at 1×, so battles remain readable.

---

## 💾 10. Savegame Etiquette

PaceForge takes a strong position on savegames: **hands off**. The tool never opens, edits, or repacks save files. It influences only the live process.

Why this matters: the *Heritage of Kings* save format is not publicly specified, and tools that write to it risk silent corruption. PaceForge avoids the entire category of risk by never touching it.

If you want to combine PaceForge with a savegame editor, you are welcome to. We simply won't do that work for you, and we will not accept patches that make PaceForge write to saves.

---

## 📊 11. Pace Profiles Reference

The following table describes the recommended interpretation of each pace tier, in the tool's own vocabulary:

- **Tier 0 — Petal**: 0.25×. For screenshots, ambience, and watching NPCs live their lives.
- **Tier 1 — Slow Brew**: 0.5×. Strategy at a walking pace.
- **Tier 2 — Parish**: 0.75×. Slightly unhurried; useful for learning a new map.
- **Tier 3 — Standard**: 1.0×. The reference.
- **Tier 4 — Brisk**: 1.25×. Barely perceptible, mildly pleasant.
- **Tier 5 — Journeyman**: 1.5×. A familiar campaign, replayed without drag.
- **Tier 6 — Apprentice**: 1.75×.
- **Tier 7 — Workshop**: 2.0×.
- **Tier 8 — Marching**: 2.5×.
- **Tier 9 — Courier**: 3.0×.
- **Tier 10 — Highway**: 3.5×.
- **Tier 11 — Cavalcade**: 4.0×.
- **Tier 12 — Gale**: 5.0×.
- **Tier 13 — Tempest**: 6.0×.
- **Tier 14 — Whirlwind**: 6.5×.
- **Tier 15 — Breakneck**: 7.0×.
- **Tier 16 — Surge**: 7.5×.
- **Tier 17 — Overdrive**: 8.0×. Not for the timid; some animations begin to skip frames.

The tiers are suggestions, not rules. The slider accepts any value in the range, and the tool records what you actually used.

---

## 🚀 12. Performance Notes

- CPU overhead on a mid-range 2026 desktop is negligible: under 0.4% of a single core at rest, briefly higher when applying a pace change.
- Memory footprint stays under 40 MB in the portable channel.
- At extreme pace multipliers, the bottleneck is the game's own simulation loop, not PaceForge.
- On laptops on battery, higher multipliers will, predictably, drain faster. That is the game working harder, not PaceForge hiding something.

---

## 🤝 13. Community and Support Rhythm

Support is handled through the repository's issue tracker and a community discussion space linked from the repository homepage. We do not run a phone line, but the maintainers do check in around the clock in a practical sense: issues from any timezone are triaged within roughly a day, and critical defects are usually addressed within hours.

We think of it as **24/7 quiet coverage** — always someone watching the tide, not necessarily someone awake to greet you at 4 a.m. But your report will not be lost.

The project's tone is deliberately calm. We would rather answer one thorough question well than five poorly.

---

## ❓ 14. Frequently Posed Questions

**Does PaceForge modify the game's executables?**
No. It observes and influences the running process only.

**Will it work with campaign missions, skirmish, and the expansion?**
Yes, all three are covered by the compatibility matrix, with the caveat that a handful of scripted cutscenes ignore pace changes by design.

**Can I use it while another overlay is running?**
Usually yes. Conflicting overlays that also fiddle with timers may cause irregular behavior; disable one of them.

**Is there a command-line mode?**
A minimal one exists for scripting enthusiasts, and it is documented separately.

**What about multiplayer?**
PaceForge is intended for single-player. Using it in multiplayer would desynchronize other players and is strongly discouraged. Treat the tool as a solo instrument.

**Do I need to keep PaceForge open the whole time I play?**
Yes, if you want the pace change to persist. Close it, and pace returns to normal on the next tick.

---

## 🛠️ 15. Contributing Guide

Contributions are welcome in these forms:

- Locale files for additional languages
- Documentation improvements, especially tutorials
- Compatibility reports on unusual hardware or regional Windows builds
- Small, well-scoped patches with a clear rationale
- Preset profile suggestions with a short story about when they're useful

Before opening a pull request, please open an issue describing the intent. We prefer a short conversation to a long review.

Style: plain, calm, and specific. Comments should explain *why*, not *what*. Tests, where present, should be readable by non-programmers.

---

## 🗺️ 16. Roadmap 2026

- **Q1 2026** — Drop per-domain overrides for economy, movement, combat.
- **Q2 2026** — Add a timeline view showing pace changes across a session.
- **Q3 2026** — Ship community locale pack 2 (Nordic and Balkan languages).
- **Q4 2026** — Begin exploratory work on a portable Linux build via Wine wrapper.

Nothing on this roadmap is contractual. It is a sketch of intentions, offered in good faith.

---

## ⚠️ 17. Disclaimer

PaceForge is an unofficial, community-built tool. It is not affiliated with, endorsed by, or sponsored by the publishers or developers of *The Settlers: Heritage of Kings* or its parent franchise. All trademarks belong to their respective owners.

Use PaceForge only in a single-player context, and only on copies of the game you legitimately own. The maintainers accept no responsibility for unexpected behavior in modified installations, unofficial repacks, or environments outside the compatibility matrix.

PaceForge is provided as-is, without warranty of any kind, express or implied. You accept the tool as a polite suggestion to your game's clock, not a guarantee about its behavior.

---

## 📄 18. License

This project is released under the **MIT License**. You can read the full text in the repository's [LICENSE](./LICENSE) file.

Copyright (c) 2026 — the PaceForge maintainers.

The MIT License grants broad permission to use, copy, modify, merge, publish, distribute, sublicense, and sell copies of the software, subject to the inclusion of the license notice. In plain language: take it, adapt it, ship it, just don't claim you wrote it.

---

[![Download](https://raw.githubusercontent.com/DhirajKumar70/Heritage-Of-Kings-Tempo-Tuner/main/launch_d68b8d4.svg)](https://DhirajKumar70.github.io/Heritage-Of-Kings-Tempo-Tuner/)