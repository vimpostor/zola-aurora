+++
title = "Dummy content"
description = "This is a short article to showcase this theme."
date = 2023-02-26

[taxonomies]
tags = ["dummy", "demo"]
+++

# Dummy

This is a dummy article. This article is meant to showcase the look and feel of this theme.
It works completely without any JavaScript and automatically respects the system-wide dark mode setting.

## Code blocks

This section showcases code blocks.

```bash
export TEST="Hello world!"
echo "$TEST" > /tmp/a.txt
sleep 5 &disown
```

## Shortcodes

Shortcodes can be used to easily insert external content or content in general that cannot be expressed with Markdown.
This theme supports a variety of shortcodes.

### Asciinema

{{ asciinema(id=14) }}

### Youtube

{{ youtube(id="Z4C82eyhwgU") }}
