# Homebrew tap for appfuzz

[appfuzz](https://appfuzz.dev) fuzzes sandboxed WebAssembly apps for bad patterns.

```sh
brew install stephanschmidt/appfuzz/appfuzz
```

macOS (Apple Silicon and Intel) and Linux (x86_64 and arm64). The formula installs
the prebuilt binary from the [GitHub release](https://github.com/StephanSchmidt/appfuzz/releases)
and is updated by appfuzz's release workflow. Don't edit `appfuzz.rb` here: edit
[the template](https://github.com/StephanSchmidt/appfuzz/blob/main/.github/homebrew/appfuzz.rb.tmpl).
