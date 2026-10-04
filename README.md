# opf, the Operforms CLI

Releases of `opf`, the command-line client and hub server of [Operforms](https://operforms.com). The source lives in a private repository; this repository only publishes the builds.

## Install

```sh
curl -fsSL https://operforms.com/install.sh | sh
```

The script picks the build for your system (macOS or Linux, amd64 or arm64), checks it against the release's `SHA256SUMS` and installs `opf` to `~/.local/bin`.

| Variable | Effect |
| --- | --- |
| `OPF_VERSION` | Release to install, e.g. `v0.1.0` (default: latest) |
| `OPF_INSTALL_DIR` | Target directory (default `~/.local/bin`) |

A hub also serves `/install.sh`, which installs from here and shows that hub's address in the next steps.

## Manual download

Each [release](https://github.com/mind-vm/operforms-cli/releases) has `opf-<os>-<arch>` binaries, `SHA256SUMS` and `install.sh`.

## Next

- [Getting started](https://operforms.com/guides/getting-started/)
- [Connect agents](https://operforms.com/guides/connect-agents/)
