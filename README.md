# homebrew-turmeric

Homebrew tap for the [Turmeric](https://github.com/turmeric-lang/turmeric)
compiler.

```sh
brew tap turmeric-lang/turmeric
brew install --HEAD turmeric-lang/turmeric/turmeric
```

The formula is **`--HEAD`-only**: it builds whatever is on `main` of
`turmeric-lang/turmeric` at that moment and verifies no checksum. That is for
tracking development. For an ordinary install use
`curl -fsSL https://turmeric-lang.com/install | sh`, which installs a
checksum-verified release.

If you tapped this by spelling out the compiler repo's URL, re-point it:

```sh
brew untap turmeric-lang/turmeric
brew tap turmeric-lang/turmeric
```

Releases are still cut in `turmeric-lang/turmeric`.
