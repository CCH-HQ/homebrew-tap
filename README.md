# CCH-HQ Homebrew tap

Official Homebrew formulas for CCH-HQ command-line tools.

## Install cchp

```sh
brew install cch-hq/tap/cchp
```

Supports macOS and Linux on ARM64 and AMD64. Bash, Zsh and Fish completions
are installed automatically.

```sh
brew update
brew upgrade cchp
cchp --version
```

## Formula updates

[`cchp-cli`](https://github.com/CCH-HQ/cchp-cli)'s release workflow verifies
published stable-release archives against their SHA256 checksums and generates
`Formula/cchp.rb`. The dedicated `cchp-homebrew-publisher` GitHub App publishes
updates with a short-lived installation token scoped to this repository.
Prereleases are excluded. Do not edit the generated formula by hand.

See [release distribution](https://github.com/CCH-HQ/cchp-cli/blob/main/docs/releasing.md)
for setup and recovery instructions.

## License

[MIT](LICENSE). Installed tools retain their own licenses.
