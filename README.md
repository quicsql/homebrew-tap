<div align="center">

<img src="https://github.com/quicsql/.github/raw/main/profile/quicsql.svg" alt="quicSQL" width="128" />

# quicSQL Homebrew Tap

</div>

Homebrew formulae for the [quicSQL](https://quicsql.net) project:

| Formula   | What it is                                                        |
| --------- | ----------------------------------------------------------------- |
| `quicsql` | CGo-free SQLite network server ([quicsql/quicsql](https://github.com/quicsql/quicsql)) |
| `qsql`    | Fast, friendly command-line SQL client ([quicsql/qsql](https://github.com/quicsql/qsql)) |

## Install

```sh
brew install quicsql/tap/quicsql
brew install quicsql/tap/qsql
```

Or add the tap once and install as usual:

```sh
brew tap quicsql/tap
brew install quicsql qsql
```

Upgrades arrive with your normal `brew upgrade`.

The formulae install prebuilt, checksummed binaries from each project's
GitHub releases on macOS (Apple Silicon and Intel) and Linux (x86_64 and
arm64) — nothing is compiled on your machine.

## How this tap is maintained

Everything under [`Formula/`](Formula/) is generated and committed by
[GoReleaser](https://goreleaser.com) when a release is tagged in the source
repositories. Do not edit formula files by hand — changes will be
overwritten by the next release. For problems with a formula, open an issue
on the corresponding source repository.

## License

[Apache-2.0](LICENSE), same as the quicSQL project.
