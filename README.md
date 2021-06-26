# aard CLI 

The aard CLI allows you to work seamlessly with the aardy service from the command line

The CLI binary is available to install on macOS, and Linux.

## Installation

### macOS
The CLI is available via [Homebrew](https://brew.sh/), which is the recommended way. 

```shell
brew tap aardlabs/cli
brew install aardlabs/cli/aard
```

### Linux (amd64)
```shell
wget -O aardy https://github.com/aardlabs/cli-release/releases/latest/download/aardy-linux-amd64 && chmod 755 aardy
```

## Upgrade

To upgrade via brew (macOS only)

```shell
brew upgrade aardlabs/cli/aard
```

To upgrade (all platforms)
```shell
aardy update --help
```

## Other

The CLI downloadable zipped binary from the [releases](https://github.com/aardlabs/cli-release/releases/latest) page. 
