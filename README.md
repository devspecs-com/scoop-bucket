# Scoop Bucket for DevSpecs

This is the official Scoop bucket for [DevSpecs CLI](https://github.com/devspecs-com/devspecs-cli) (`ds`).

## Installation

```powershell
# Add the bucket (one-time setup)
scoop bucket add devspecs https://github.com/devspecs-com/scoop-bucket

# Install
scoop install devspecs
```

The app manifest is named `devspecs`; the installed binary is **`ds.exe`**.

## Update

```powershell
scoop update devspecs
```

## Uninstall

```powershell
scoop uninstall devspecs
scoop bucket rm devspecs  # optional
```

## Available Apps

| App | Description |
|-----|-------------|
| `devspecs` | DevSpecs CLI — index and reference your specs, plans, and ADRs (`ds`) |

## About DevSpecs

DevSpecs CLI is a local-first tool for indexing and referencing planning artifacts (OpenSpec, ADRs, markdown plans, and more). Learn more at [github.com/devspecs-com/devspecs-cli](https://github.com/devspecs-com/devspecs-cli).

## Maintainers

`devspecs.json` (and future manifests) are **generated and updated by [GoReleaser](https://goreleaser.com)** when you release [devspecs-cli](https://github.com/devspecs-com/devspecs-cli). Do not edit them by hand; change release settings in [`.goreleaser.yml`](https://github.com/devspecs-com/devspecs-cli/blob/main/.goreleaser.yml) instead.

Until the first successful release upload, `scoop install` may fail because no manifest exists yet.
