# Raselerkaj After Effects Scripts

Production-focused Adobe After Effects scripts by Rasel, maintained at
`github.com/iboyshanto/raselerkaj-ae-scripts`.

## Included scripts

- Aligner
- RKBAR
- RKREATE
- RKTYPE
- rExpression
- RLauncher
- RLayer
- rTime

The panel name is defined inside each script. Renaming a `.jsx` file does not
change the title used by its floating ScriptUI palette. After Effects controls
the filename shown in its Window menu for installed dockable panels.

## Installation

1. Download the named `.jsx` file for the product you want from its GitHub release.
2. Quit After Effects.
3. Copy that one file into the After Effects `Scripts/ScriptUI Panels` folder.
4. Replace the older product file, then restart After Effects.

The public product file already contains the update notifier. No companion
`.jsxinc` file is required. It checks the public text manifest at most once
every 24 hours, never installs code automatically, and only opens that
product's exact GitHub release when the user chooses to update.

## Release rule

Whenever a script changes, increase that script's embedded version and update
its version and release tag in `update-manifest.txt` in the same commit. Run
`node tools/build-self-contained.js`, then publish the matching file from
`dist/` as the only required product download. Do not bundle unrelated products.
