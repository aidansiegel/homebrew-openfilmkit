# Homebrew tap for OpenFilmKit

[OpenFilmKit](https://github.com/aidansiegel/OpenFilmKit) is free film scanning and negative
conversion from the command line, built on SANE.

```sh
brew install aidansiegel/openfilmkit/openfilmkit
openfilmkit doctor
```

Works on macOS and Linux. The formula builds OpenFilmKit's own patched SANE runtime alongside it
(kept separate from Homebrew's `sane-backends`), so nothing else on your system changes. On Linux,
`openfilmkit doctor` prints the one command that installs the USB permission rule.

Recent Homebrew versions ask you to trust a third-party tap's formula before installing it; if
`brew install` says so, run `brew trust --formula aidansiegel/openfilmkit/openfilmkit` first.

## License

GPL-3.0-or-later. See [LICENSE](LICENSE).

Copyright © 2026 Aidan Siegel &lt;openfilmkit@aidansiegel.com&gt;
