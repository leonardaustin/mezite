# Mezite

Self-hosted SSH access platform — signed binary releases.

Mezite gives teams short-lived-certificate SSH access to their infrastructure,
with session recording, audit logging, and role-based access control.

This repository distributes **compiled binaries only**. Mezite is closed-source;
the source code is not published here. See [LICENSE](LICENSE).

## Install

Binaries for Linux and macOS (amd64 and arm64) are published on the
[Releases](https://github.com/leonardaustin/mezite/releases) tab. Each release
includes a SHA256 manifest and a Sigstore bundle so you can verify what you
downloaded before running it.

Full instructions, including signature verification:
**<https://mezite.com/docs/install/>**

## What's in each archive

| Binary   | Purpose                  |
| -------- | ------------------------ |
| `mezhub` | Server (auth + proxy)    |
| `mezd`   | Node agent               |
| `msh`    | Client CLI               |
| `mezctl` | Admin CLI                |

## Documentation

- [Installation](https://mezite.com/docs/install/)
- [Quickstart](https://mezite.com/docs/quickstart/)
- [Configuration](https://mezite.com/docs/configuration/)
- [Architecture](https://mezite.com/docs/architecture/)

## Support

Issues are not tracked in this repository. For support, see
<https://mezite.com>.
