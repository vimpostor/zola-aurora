+++
title = "Dummy content"
description = "This is a short article to showcase this theme."
date = 2023-02-26

[taxonomies]
tags = ["dummy", "demo"]
+++

# Dummy

This is a dummy article. This article is meant to showcase the look and feel of this theme.
It works completely without any JavaScript and automatically respects the system-wide dark mode setting. 🥳

## Code blocks

This section showcases code blocks.

```bash
if true; then
	export TEST="Hello world!"
	echo "$TEST" > /tmp/a.txt
	sleep 5 &disown
fi
```

## Quotes

This is a quote.

{% quote(author="J.S. Bach") %}
There's nothing remarkable about it. All one has to do is hit the right keys at the right time and the instrument plays itself.
{% end %}

The next quote does not have author information.
{% quote() %}
For since the fabric of the universe is most perfect and the work of a most wise creator, nothing at all takes place in the universe in which some rule of the maximum or minimum does not appear.
{% end %}

## Shortcodes

Shortcodes can be used to easily insert external content or content in general that cannot be expressed with Markdown.
This theme supports a variety of shortcodes.

### Asciinema

{{ asciinema(id=14) }}

### Youtube

{{ youtube(id="Z4C82eyhwgU") }}

### Video

{{ video(url="https://user-images.githubusercontent.com/21310755/164289278-6368d615-e363-4185-a7c1-0f79ae3bf7b1.mov") }}
