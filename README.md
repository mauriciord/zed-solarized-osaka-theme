# Solarized Osaka for Zed

A Solarized-inspired dark theme for the [Zed editor](https://zed.dev), with a deeper, more saturated background palette.

Inspired by [craftzdog/solarized-osaka.nvim](https://github.com/craftzdog/solarized-osaka.nvim) and based on Ethan Schoonover's original [Solarized](https://ethanschoonover.com/solarized/) color scheme.

## Install

In Zed, open the command palette (`cmd-shift-p` / `ctrl-shift-p`) and run `zed: extensions`. Search for **Solarized Osaka** and click Install.

Then activate it via `cmd-k cmd-t` (or `ctrl-k ctrl-t` on Linux) and pick **Solarized Osaka**.

## Preview

Highlights:

- Deep teal backgrounds (`#0f1419` editor, `#002b36` panels)
- Solarized accent palette: cyan strings, blue functions, yellow types, green keywords
- Italic comments and control flow keywords
- Red caret (`#ff0000ca`) for high visibility
- Full Solarized ANSI terminal palette

## Development

Clone and install as a dev extension:

```bash
git clone https://github.com/YOUR_GITHUB_USER/solarized-osaka-theme.git
```

In Zed: `cmd-shift-p` → `zed: install dev extension` → select the cloned directory.

Edit `themes/solarized-osaka.json` and reload via `zed: reload extensions` to see changes.

## Credits

- [Solarized](https://ethanschoonover.com/solarized/) by Ethan Schoonover — the original palette
- [solarized-osaka.nvim](https://github.com/craftzdog/solarized-osaka.nvim) by Takuya Matsuyama — the Neovim variant that inspired the deeper background tones

## License

MIT — see [LICENSE](./LICENSE).
