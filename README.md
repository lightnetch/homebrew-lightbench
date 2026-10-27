# lightBench Homebrew tap

Official Homebrew tap for [lightBench](https://lightbench.ch), the free hardware benchmark for Windows, macOS and Linux.

## Install

```bash
brew tap lightnetch/lightbench
brew trust --cask lightnetch/lightbench/lightbench
brew install --cask lightbench
```

Homebrew 7 requires explicit trust for third-party casks. The command above trusts only the lightBench cask, not the entire tap. The cask installs the notarized app and the `lightbench` command. Start the app normally or run `lightbench --cli` in a terminal.

Release files are signed, notarized and published by lightnet multimedia gmbh on `lightbench.ch`.
