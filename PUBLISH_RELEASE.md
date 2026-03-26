# Publish Checklist

1. Make sure this repository is the public `astroblitzcreations/rampart-legacies` repo.
2. Enable GitHub Pages from the `/docs` folder on `main`.
3. Create a GitHub Release with the version tag, for example `v0.1.1`.
4. Upload the Windows build asset with the exact filename:
   - `RampartLegacies-Windows.zip`
5. Publish the release notes.

## Why the filename matters

The in-game updater uses the stable direct download URL for:

`RampartLegacies-Windows.zip`

Changing the filename will break the direct Windows download button in the game.
