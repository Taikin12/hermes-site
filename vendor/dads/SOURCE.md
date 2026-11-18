# デジタル庁デザインシステム (DADS) — design tokens

Vendored copy, do not edit `tokens.css` by hand.

- Package: `@digital-go-jp/design-tokens`
- Version: `2.0.1`
- Source: https://github.com/digital-go-jp/design-tokens
- Files: `tokens.css` (all design tokens as CSS custom properties)
- License: MIT (see `LICENSE`, Copyright (c) 2023 デジタル庁)

Usage: link before the viewer stylesheet so `style.css` can consume the
variables, e.g.

```html
<link rel="stylesheet" href="vendor/dads/tokens.css" />
<link rel="stylesheet" href="style.css" />
```

Key token groups: `--color-primitive-*`, `--color-key-*`,
`--color-semantic-*`, `--font-family-*`, `--font-size-*`, `--font-weight-*`,
`--line-height-*`, `--border-radius-*`, `--elevation-*`.

To update: fetch the tarball from
`https://registry.npmjs.org/@digital-go-jp/design-tokens/-/design-tokens-<version>.tgz`
and copy `package/dist/tokens.css`.
