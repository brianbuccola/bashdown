<!-- begin metadata
title: Sample post
date: 2013-03-23 09:15
end metadata -->

Here is a brief run-through of how certain Markdown elements are converted to
HTML and then displayed.

# Headings

# Heading 1

## Heading 2

### Heading 3

#### Heading 4

##### Heading 5

###### Heading 6

# Body text

Lorem ipsum dolor sit amet, consetetur sadipscing elitr, sed diam nonumy eirmod
tempor invidunt ut labore et dolore magna aliquyam erat, sed diam voluptua. At
vero eos et accusam et justo duo dolores et ea rebum. Stet clita kasd gubergren,
no sea takimata sanctus est Lorem ipsum dolor sit amet.

Here is some *italic* (or emphasized) text, some **bold** (or strong) text.

[Here](http://www.google.com/) is a link to Google. Try hovering over it and
then clicking it so see how the styling changes.

# Block quotes

> Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod
> tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam,
> quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo
> consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse
> cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non
> proident, sunt in culpa qui officia deserunt mollit anim id est laborum.

# Lists

## Ordered lists

1. First item.
     1. First sub item.
     2. Second sub item.
2. Second item.
3. Third item.

## Unordered lists

- First item.
    - First sub item.
    - Second sub item.
- Second item.
- Third item.

# Code snippets

Here is some inline code: `if [[ -n "${foo}" ]]; then echo "nonzero";
fi`{.bash}. And here is a code block:

```bash
#/bin/bash

foo="bar"

if [[ -n "${foo}" ]]; then
    echo "nonzero variable string"
fi
```

The end!
