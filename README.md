# GraffKube

Kubernetes desktop client — diagnostics, network policy debugging, RBAC exploration
and rightsizing in one place.

GraffKube is currently in **public beta** (`0.x`). Expect rough edges, and please
report them.

## Download

**[→ Download the latest release](https://github.com/GraffPartners/graffkube/releases/latest)**

Builds are published on the [Releases](https://github.com/GraffPartners/graffkube/releases)
page. Pick the file matching your platform:

| Platform | File |
| --- | --- |
| macOS (Apple Silicon) | `GraffKube-macos-arm64.dmg` |
| macOS (Intel) | `GraffKube-macos-amd64.dmg` |
| Windows (x64) | `GraffKube-windows-amd64.exe` |
| Linux (x64) | `GraffKube-linux-amd64.AppImage` |

Every release lists SHA-256 checksums so you can verify your download.

## Feedback

- **[Report a bug](https://github.com/GraffPartners/graffkube/issues/new?template=bug_report.yml)**
- **[Request a feature](https://github.com/GraffPartners/graffkube/issues/new?template=feature_request.yml)**
- **[Community discussions](https://github.com/GraffPartners/graffkube/discussions)**

The app can open these pages for you from **Help** in the toolbar.

## Updates

GraffKube checks for new versions by reading a small public manifest,
[`version.json`](https://graffpartners.github.io/graffkube/version.json). The check
sends no identifying information — no account, no installation ID, no telemetry —
and nothing is ever downloaded or installed without you choosing to.

If a newer version exists, the app shows a notice with a link to the release page.
You download and install it yourself.

## Privacy

GraffKube talks to your Kubernetes clusters from your own machine. Cluster data,
manifests, logs and your kubeconfig stay local — they are never sent to us, and
never attached to bug reports automatically.

## About

This repository hosts GraffKube's releases and issue tracker. The application
source code is not published here.
