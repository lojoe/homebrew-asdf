[![pre-commit.ci status](https://results.pre-commit.ci/badge/github/lojoe/homebrew-tap/master.svg)](https://results.pre-commit.ci/latest/github/lojoe/homebrew-tap/master)

# homebrew-asdf

Homebrew tap with supplemental commands for use with asdf


## Installation

This tap is kind of useless without [Homebrew](https://brew.sh), so go
get that if you have not done so already.

```bash
brew tap lojoe/asdf
```

## Usage

To compare the version of all plugins set in the relevant local/global tool
versions file with the latest stable version:

```bash
brew asdf-outdated
```

To update the global tool versions file and intall versions as needed:

```bash
brew asdf-global
# ^ install and set latest stable version of all plugins

brew asdf-global <plugin>
# ^ install and set the latest version of <plugin>

brew asdf-global <plugin> <version>
# ^ install and set version <version> of <plugin>
```

To update the local tool versions file and install versions as needed:

```bash
brew asdf-local
# ^ install and set latest stable version of all plugins

brew asdf-local <plugin>
# ^ install and set the latest version of <plugin>

brew asdf-local <plugin> <version>
# ^ install and set version <version> of <plugin>
```
