Fork from https://github.com/obsidiansystems/obelisk

Most part of source library is dropped (as I don't need it). The rest is adjusted and compiled with ghc js-backend.

# Build

1. Install GHC JS with ghcup as described [here](https://www.haskell.org/ghcup/guide/#cross-support)
2. Set GHC javascript-unknown-ghcjs-9.12.1 as default in ghcup
2. Build all with cabal:
```
$ cabal --with-compiler=javascript-unknown-ghcjs-ghc --with-ghc-pkg=javascript-unknown-ghcjs-ghc-pkg build all
```
