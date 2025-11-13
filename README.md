# Viget Homebrew Tap

Homebrew tap for Viget tools. Currently includes one formula:

- `tess` — Generate Lattice review summaries; optional Drive upload via rclone.

## Install

Prereqs: macOS (Apple Silicon/arm64) with Homebrew installed.

```sh
brew tap vigetlabs/taps
brew install tess
# or explicitly
brew install vigetlabs/taps/tess
```

## Usage

```sh
tess --help
```

`tess` depends on `pandoc`, `rclone`, and `tectonic`; Homebrew installs these automatically.

Project: https://github.com/vigetlabs/tess

## Upgrade

```sh
brew update && brew upgrade tess
```

## Uninstall

```sh
brew uninstall tess
brew untap vigetlabs/taps
```

## Notes

- Architecture: current formula targets Apple Silicon (arm64) on macOS.
- Issues and feature requests for `tess`: https://github.com/vigetlabs/tess/issues
- Tap issues (formula problems): open an issue on this repo.

