# JumboBridge

Port forwarding, mock servers, mock databases and traffic disruption, in one
local console. Docs and the full guide: **https://jumbobridge.com/guide**

This repository is where the `jb` CLI is released. Each release carries the
same four archives, under names that never change, so these links always
fetch the latest one:

| Platform | Download |
|---|---|
| Linux (x86_64, static) | [`jb-x86_64-unknown-linux-musl.tar.gz`](https://github.com/Time2Wall/JumboBridge/releases/latest/download/jb-x86_64-unknown-linux-musl.tar.gz) |
| macOS (Intel) | [`jb-x86_64-apple-darwin.tar.gz`](https://github.com/Time2Wall/JumboBridge/releases/latest/download/jb-x86_64-apple-darwin.tar.gz) |
| macOS (Apple Silicon) | [`jb-aarch64-apple-darwin.tar.gz`](https://github.com/Time2Wall/JumboBridge/releases/latest/download/jb-aarch64-apple-darwin.tar.gz) |
| Windows (x86_64) | [`jb-x86_64-pc-windows-msvc.zip`](https://github.com/Time2Wall/JumboBridge/releases/latest/download/jb-x86_64-pc-windows-msvc.zip) |

Every release also has a `SHA256SUMS.txt`. Check a download against it:

```bash
sha256sum -c SHA256SUMS.txt --ignore-missing
```

The version is in the release tag, and `jb --version` prints it.
