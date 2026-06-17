# homebrew-icontainer

Homebrew tap for [iContainer](https://github.com/nico81/iContainer), a
native macOS UI for Apple's `container` CLI.

## Install

```sh
brew tap nico81/icontainer https://github.com/nico81/homebrew-icontainer
brew install --cask icontainer
```

## Upgrade

```sh
brew upgrade --cask icontainer
```

Homebrew strips the macOS quarantine attribute on cask installs, so this
path avoids the Gatekeeper warning the ad-hoc-signed release bundles
would otherwise produce on first launch.

## Reporting issues

Bug reports and feature requests belong in the
[main iContainer repository](https://github.com/nico81/iContainer/issues).
Issues specific to the tap (broken `sha256`, livecheck regressions,
formula syntax) can be filed here.
