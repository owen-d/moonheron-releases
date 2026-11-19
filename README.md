# Moon Heron CLI releases

Release builds of `moonheron`, the [Moon Heron](https://moonheron.com) command
line. Source is not published here; this repository only hosts releases.

## Install

macOS (Apple Silicon) or Linux (x86_64):

```sh
curl --proto '=https' --tlsv1.2 -LsSf https://desk.moonheron.com/downloads/moonheron/moonheron-cli-installer.sh | sh
```

Update with `moonheron upgrade`; remove with `moonheron uninstall`.

Archives and checksums for each version are on the
[releases page](https://github.com/owen-d/moonheron-releases/releases), or
pick one at [moonheron.com/download](https://moonheron.com/download/).

## Verify an archive

Download the archive and its `.sha256` file into one folder, then:

```sh
shasum -a 256 -c moonheron-cli-aarch64-apple-darwin.tar.gz.sha256   # macOS
sha256sum -c moonheron-cli-x86_64-unknown-linux-musl.tar.gz.sha256  # Linux
```

## Contact

info@moonheron.com
