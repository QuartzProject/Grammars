<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/QuartzProject/.github/main/.github/assets/quartz-logo-rose.svg">
    <img src="https://raw.githubusercontent.com/QuartzProject/.github/main/.github/assets/quartz-logo-ink-rose.svg" alt="Quartz" width="360">
  </picture>
</p>

<h2 align="center">Quartz Grammars</h2>

<p align="center">
  <strong>The syntax definitions of Quartz for every editor.</strong>
</p>

<p align="center">
  <img alt="tree-sitter" src="https://img.shields.io/badge/tree--sitter-ABI_14-F9A8D4">
  <img alt="TextMate" src="https://img.shields.io/badge/TextMate-grammar-F9A8D4">
  <img alt="Notepad++" src="https://img.shields.io/badge/Notepad%2B%2B-UDL_2.1-90E59A">
  <img alt="License" src="https://img.shields.io/badge/license-MIT-green">
</p>

## About

Highlighting, indentation and navigation for [Quartz](https://quartzlang.org) programs (`.qz`) and host interfaces
(`.qzi`).

| Folder | Format | Used by |
|---|---|---|
| [`tree-sitter/`](tree-sitter) | tree-sitter grammar and queries | Neovim, Helix, Zed |
| [`textmate/`](textmate) | TextMate grammar | the VS Code extension and the JetBrains plugin |
| [`notepadpp/`](notepadpp) | User Defined Language, light and dark | Notepad++ |

Diagnostics, completion and the rest come from the language server, `quartz-lsp`. How to install each one is in the
[Editors chapter](https://quartzlang.org/docs/editors.html) of the Quartz book.

## Contributing

The parser of [Quartz](https://github.com/QuartzProject/Quartz) is the specification: a change to the syntax there
comes with the same change to all three grammars here.

## License

[MIT](LICENSE).
