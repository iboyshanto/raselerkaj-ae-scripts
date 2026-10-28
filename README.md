# Raselerkaj After Effects Scripts

## Important update — October 28, 2026

**Please update all eight tools together.** Earlier modern builds could fail to open right-click menus on native ScriptUI buttons. This release fixes menu activation and includes the latest rLayer tools.

[Download the complete updated suite](https://github.com/iboyshanto/raselerkaj-ae-scripts/releases/download/Modern-Tools-2026-10-28/Raselerkaj-Modern-Tools-2026-10-28.zip) · [Release notes and checksums](https://github.com/iboyshanto/raselerkaj-ae-scripts/releases/tag/Modern-Tools-2026-10-28)

### What changed

- All eight tools: titled **Related actions** menus open from right-clicks, with compact icon rows and hover feedback.
- rLayer: **Alt-click Focus** isolates and solos the selected layers. Click again to restore previous timeline and solo states.
- rLayer: **Select Shape Layers → Select color properties** selects nested fill, stroke, gradient Colors and effect color controls without changing their values. AE-hidden properties that reject selection are skipped.
- RKBAR: Shift-click naming for cropped and trimmed precompositions is included.

| Tool | Version | Individual release |
| --- | --- | --- |
| Aligner | 1.1.1 | [Download](https://github.com/iboyshanto/raselerkaj-ae-scripts/releases/tag/Aligner-v1.1.1) |
| RKBAR | 1.3.1 | [Download](https://github.com/iboyshanto/raselerkaj-ae-scripts/releases/tag/RKBAR-v1.3.1) |
| RKREATE | 1.1.1 | [Download](https://github.com/iboyshanto/raselerkaj-ae-scripts/releases/tag/RKREATE-v1.1.1) |
| RKTYPE | 1.2.1 | [Download](https://github.com/iboyshanto/raselerkaj-ae-scripts/releases/tag/RKTYPE-v1.2.1) |
| rExpression | 1.1.1 | [Download](https://github.com/iboyshanto/raselerkaj-ae-scripts/releases/tag/rExpression-v1.1.1) |
| RLauncher | 1.1.1 | [Download](https://github.com/iboyshanto/raselerkaj-ae-scripts/releases/tag/RLauncher-v1.1.1) |
| RLayer | 1.2.0 | [Download](https://github.com/iboyshanto/raselerkaj-ae-scripts/releases/tag/RLayer-v1.2.0) |
| rTime | 1.1.1 | [Download](https://github.com/iboyshanto/raselerkaj-ae-scripts/releases/tag/rTime-v1.1.1) |

## Installation

1. Quit After Effects and back up your installed scripts.
2. Extract the suite ZIP and copy the eight `.jsxbin` files into **Scripts/ScriptUI Panels**.
3. Move older `.jsx` or duplicate `.jsxbin` versions of the same tools out of that folder. Keep existing preset, expression and script libraries.
4. Restart After Effects and open the tools from **Window**. Restarting unloads older docked-panel code.

Icons and the updater are embedded; no companion files are required. Enable **Allow Scripts to Write Files and Access Network** for update checks and file-based features.

## Updates

Existing installations use the same public `update-manifest.txt` feed. Older versions can show a notification with the important release notes and open the matching release page. Downloading and replacing files remains manual. Same-version installations remain silent.

## Validation

All eight files passed Adobe JSXBIN compilation. Twelve modern automated suites and updater simulations passed. All eight current compiled builds loaded successfully in After Effects Beta 27.1x23. Right-click behavior was checked with macOS mouse events during development of the fix. rLayer passed 9 native Focus/Solo and 30 native color-selection checks. Full action coverage, older AE versions and Windows remain unverified for this release.

This public repository contains protected distribution builds and update metadata. Development source remains private.
