# homebrew-stalker

Homebrew tap for [stalker](https://github.com/RahulZoroItachi/stalker), a local
macOS activity tracker that never leaves your machine.

```
brew install RahulZoroItachi/stalker/stalker
stalker setup
```

It builds from source on your own machine, so the first install takes a few
minutes. That is deliberate: nothing prebuilt is downloaded, so you run a binary
your own compiler produced.

Requires macOS 14 (Sonoma) or newer. Read the
[privacy section](https://github.com/RahulZoroItachi/stalker#read-this-before-you-install-it)
before granting anything, because `stalker setup` will ask you for Accessibility.
