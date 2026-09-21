# sechis/homebrew-tap

A personal [Homebrew](https://brew.sh) tap providing formulae, casks, and external commands that aren't available (or don't fit) in the official `homebrew/core` and `homebrew/cask` taps.

## Usage

Add this tap to your Homebrew:

```sh
brew tap sechis/homebrew-tap
```

Homebrew requires non-official taps to be explicitly trusted before it will load their formulae. Mark this tap as trusted:

```sh
brew trust sechis/homebrew-tap
```

> Homebrew ≥ 4.3.11 is required for `brew trust`. On older versions, update Homebrew first (`brew update && brew upgrade homebrew`).

Then install whatever you need from this tap as usual:

```sh
brew install sechis/homebrew-tap/<formula>
```

To remove this tap (including its trust status):

```sh
brew untap sechis/homebrew-tap
```

## Contributing

Pull requests are welcome. If you have a formula or cask you'd like added here, open a PR.
