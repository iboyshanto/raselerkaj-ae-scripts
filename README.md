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

1. Download the latest release ZIP from the repository's Releases page.
2. Quit After Effects.
3. Copy the desired `.jsx`/`.JSX` files and `RaselerkajUpdater.jsxinc` into the
   After Effects `Scripts/ScriptUI Panels` folder.
4. Replace the older files, then restart After Effects.

Keep `RaselerkajUpdater.jsxinc` beside the scripts. It checks the public text
manifest at most once every 24 hours, never installs code automatically, and
only opens the GitHub Releases page when the user chooses to update.

## Release rule

Whenever a script changes, increase that script's embedded version and the
matching version in `update-manifest.txt` in the same commit. Publish a GitHub
release with a ZIP containing the scripts and `RaselerkajUpdater.jsxinc`.
