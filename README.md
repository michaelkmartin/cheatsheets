# index

## Rico's cheatsheets

> Collection of web development cheatsheets:

Visit: [https://ricostacruz.com/cheatsheets/](https://ricostacruz.com/cheatsheets/)

## Dev notes

### Starting a local instance

This is a mere Jekyll site, and `bundle exec jekyll serve` should be fine. But I suggest you use this instead:

```text
make
```

### CSS classes

`h2` supports these:

```text
{: .-two-column}
{: .-three-column}
{: .-wide-second}       # combine with -xxx-column
{: .-left-reference}
```

`h3` supports these:

```text
{: .-prime}
```

`table` supports these:

```text
{: .-shortcuts}
{: .-left-align}
{: .-headers}
```

`pre` supports these:

```text
{: .-setup}
{: .-box-chars}
```

`ul` supports these:

```text
{: .-also-see}
{: .-four-column}
{: .-six-column}
```

### Frontmatter

Each sheet supports these metadata:

```text
---
title: React.js
layout: 2017/sheet   # 'default' | '2017/sheet'

# Optional:
category: React
updated: 2017-08-30       # To show in the updated list
ads: false                # Add this to disable ads
weight: -5                # lower number = higher in related posts list
deprecated: true          # Don't show in related posts
prism_languages: [vim]    # Extra syntax highlighting
---
```

### Prism languages

For supported prism languages:

* [https://github.com/PrismJS/prism/tree/gh-pages/components](https://github.com/PrismJS/prism/tree/gh-pages/components)

### Setting up redirects

This example sets up a redirect from `es2015` to `es6`:

```text
# /es2015.md
---
title: ES2015
category: Hidden
redirect_to: /es6
---
```

### Localizations

See `_data/content.yml` for chrome strings.

