# salted.bar

A floating pill-style status bar for [Omarchy](https://omarchy.org/), built on Quickshell. A fork of the built-in `omarchy.bar` with a floating island design, drop shadow, and bundled widgets/indicators.

## Features

- Floating island layout with configurable margins and edge gaps
- Drop shadow effect on the bar surface
- Horizontal and vertical bar orientations

## Installation

```bash
omarchy plugin clone salted.bar
```

Or manually copy to `~/.config/omarchy/plugins/salted.bar/`.

## Configuration

Bar layout is configured in `~/.config/omarchy/shell.json` under the `bar` key. Use `omarchy bar move`, `omarchy bar set`, and `omarchy bar transparent` to customize from gestures or scripts.

Widgets can be enabled/disabled with `omarchy plugin enable` / `omarchy plugin disable`.

## License

MIT
