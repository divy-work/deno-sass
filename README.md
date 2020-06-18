# deno-sass

[![stars](https://img.shields.io/github/stars/divy-work/deno-ciphers)](https://github.com/divy-work/deno-ciphers/stargazers)
[![issues](https://img.shields.io/github/issues/divy-work/deno-ciphers)](https://github.com/divy-work/deno-ciphers/issues)
![deno version](https://img.shields.io/badge/deno-1.0.5-success)
[![vr scripts](https://badges.velociraptor.run/flat.svg)](https://velociraptor.run)

> BREAKING CHANGE: Deno Sass now uses sass-rs crate that provides bindings to the official libsass lib. No more WASM.

## Example

```typescript
import { compile } from "mod.ts";
compile("a { color: #000; }").result;
```

## Building from source

### Prerequisites

- [deno](https://deno.land/)
- [rust](https://www.rust-lang.org/)

## Building
```bash
$ cargo build
```

## Example

```bash
$ deno run --unstable -A examples/compile.ts
```

### Contribution

Pull request, issues and feedback are very welcome. Code style is formatted with `deno fmt` and commit messages are done following [Conventional Commits](https://www.conventionalcommits.org/en/v1.0.0/) spec.

### Licence

Copyright 2020, Divy Srivastava. All rights reserved. MIT license.
