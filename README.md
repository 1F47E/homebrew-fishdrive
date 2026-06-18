# homebrew-fishdrive

Homebrew tap for [fishdrive](https://github.com/1F47E/fishdrive) — encrypted file
offload to your own VPSes.

```sh
brew tap 1F47E/fishdrive

brew install fishctl            # the CLI (macOS)
brew install --cask fishdrive   # the macOS menu-bar app
brew install feeshd             # the server (run on your Linux/macOS VPS)
```

The app + binaries are ad-hoc signed; the cask clears the quarantine bit so it
launches. Formulas/cask are generated from each release by
`scripts/tap-update.py` in the main repo.
