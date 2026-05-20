# tahuna-cli releases

Public distribution repository for the Tahuna CLI.

This repository hosts:

- GitHub Release assets (`tahuna_<os>_<arch>.tar.gz`, `checksums.txt`)
- Installer script (`scripts/install-tahuna.sh`)
- Stable/nightly channel config (`releases/channels.conf`)

## Install (stable)

```bash
curl -fsSL https://raw.githubusercontent.com/TahunaLabs/tahuna-cli/main/scripts/install-tahuna.sh | bash
```

## Install (nightly)

```bash
curl -fsSL https://raw.githubusercontent.com/TahunaLabs/tahuna-cli/main/scripts/install-tahuna.sh | bash -s -- --channel nightly
```

## Install specific version

```bash
curl -fsSL https://raw.githubusercontent.com/TahunaLabs/tahuna-cli/main/scripts/install-tahuna.sh | bash -s -- --version v0.1.0
```
