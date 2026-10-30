# Homebrew tap for BELL PR

Install [BELL PR](https://github.com/Suzu1Dev/bell-pr) with one command:

```sh
brew install suzu1dev/bell-pr/bell-pr
```

Homebrew adds this tap automatically and installs Node.js, Git and GitHub CLI as dependencies. Start the workbench with `bell-pr`; finish sign-in to your own GitHub and AI CLI accounts as described in the [installation guide](https://bell-pr.suzu.tw/install.html).

## Updating

```sh
brew update
brew upgrade suzu1dev/bell-pr/bell-pr
```

## Maintaining the formula

The canonical formula is generated in the [BELL PR repository](https://github.com/Suzu1Dev/bell-pr/blob/main/Formula/bell-pr.rb). After publishing a release to npm, run `node scripts/sync-installers.mjs --refresh-formula` there. It verifies the npm tarball integrity and updates the pinned version and SHA-256. Copy the reviewed formula to `Formula/bell-pr.rb` here and commit it with a DCO sign-off. Keep both copies in sync.

The macOS workflow verifies that a fresh runner can install using the single command above, then runs the formula test and the CLI version/help checks.

## License

Apache-2.0; see [LICENSE](LICENSE) and [NOTICE](NOTICE).
