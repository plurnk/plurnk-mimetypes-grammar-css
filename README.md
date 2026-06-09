# @plurnk/plurnk-mimetypes-grammar-css

Pre-built `tree-sitter-css` WASM grammar for the [@plurnk/plurnk-mimetypes](https://github.com/plurnk/plurnk-mimetypes) framework.

## install

```
npm i @plurnk/plurnk-mimetypes-grammar-css
```

## what's in here

- **`css.wasm`** — pre-built from the pinned upstream [tree-sitter-css](https://github.com/tree-sitter/tree-sitter-css) commit (SHA in `.grammar-pin`)
- `scripts/build-wasm.mjs` — reproducible rebuild from the pinned source
- `scripts/verify-wasm.mjs` — CI byte-identical reproducibility check

Declares only `web-tree-sitter` as a peer — no native `tree-sitter`, no node-gyp.

## license

MIT. The bundled `css.wasm` is built from the upstream tree-sitter-css grammar; see the pinned commit for that project's attribution.
