# LetScoop (Let's Scoop)

[![Tests](https://github.com/thecats1105/letscoop/actions/workflows/ci.yml/badge.svg)](https://github.com/thecats1105/letsccop/actions/workflows/ci.yml) [![Excavator](https://github.com/thecats1105/letscoop/actions/workflows/excavator.yml/badge.svg)](https://github.com/thecats1105/letscoop/actions/workflows/excavator.yml)

A bucket for [Scoop](https://scoop.sh), the Windows command-line installer.

## How do I install these manifests(apps)?

To add this bucket, paste this command in a PowerShell session:

```pwsh
scoop bucket add .LS https://github.com/thecats1105/letscoop
```

To install any manifest(app), run this command in a PowerShell session:

```pwsh
scoop install .LS/<manifest_name>
```

To update any manifest(app), run this command in a PowerShell session:

```pwsh
scoop update <manifest_name>
```

or want to update all of installed manifests(apps), run this command in a PowerShell session:

```pwsh
scoop update --all
```

To remove the bucket, run this command in a PowerShell session:

```pwsh
scoop bucket rm .LS
```

## How do I contribute new manifests?

To make a new manifest contribution, please read the [Contributing
Guide](https://github.com/ScoopInstaller/.github/blob/main/.github/CONTRIBUTING.md)
and [App Manifests](https://github.com/ScoopInstaller/Scoop/wiki/App-Manifests)
wiki page.
