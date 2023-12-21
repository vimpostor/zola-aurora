# zola-aurora

A minimalistic theme for [Zola](https://www.getzola.org/).

## Features

- Minimalistic
- **NO** JavaScript
- **NO** tracking or analytics
- **NO** custom fonts (prefer system fonts stack)
- Automatic dark mode support (based on system-wide preference)
- Pagination
- Tags
- SVG favicon support
- Quotes
- Various shortcodes
	- SVG icons: `{{ icon(name="myname") }}`
	- Asciinema: `{{ asciinema(id="myid") }}`
	- Youtube: `{{ youtube(id="myid") }}`
	- Video: `{{ video(url="myurl") }}`

## Installation

In the root of your repository (created with `zola init`) run:

```bash
git submodule add https://github.com/vimpostor/zola-aurora.git themes/zola-aurora
```

Then add `theme = "zola-aurora"` to your `config.toml`.

## Acknowledgements

This theme is based on the [apollo](https://github.com/not-matthias/apollo) theme, but heavily modified to be more minimal and to work without any JavaScript at all.
