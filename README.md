# WS-Concepts Snippets

[![WS-Concepts](https://img.shields.io/badge/made_by-WS--Concepts-6DBE44.svg?style=flat-square)](http://ws-concepts.com/)
[![Built with Atom](https://img.shields.io/badge/built_with-Atom-40a977.svg?style=flat-square)](https://atom.io/)
[![apm](https://img.shields.io/apm/l/vim-mode.svg?style=flat-square)](https://atom.io/packages/websiteconcepts-snippets)


Set of handy code snippets used by the WS-Concepts Team

## Install

Go to `Atom > Preferences` go to the Install tab and search for websiteconcepts-snippets

Or using apm: `$ apm install websiteconcepts-snippets`

Restart Atom

## Snippets

### HTML

Supports: `HTML` `PHP`

- `a-ext` Anchor with external settings
- `ext-link` Set external settings for a link (_Will be dropped in the future for a-ext_)
- `tbuild` Build Table with small **emmet** tr > td builder (_requires emmet_)
- `figure-full` Build Figure and Figcaption
- `source-picture` Source for a picture image
- `picture-full` Build Picture & Source for image-set
- `details-full` Build Details & Summary

### CSS

Supports: `CSS` `SCSS` `LESS`

- `states` set all default states (active, focus, hover)
- `trbl` Set all position options (top, right, bottom, left)
- `gradient` Build gradient
- `space-css` add html space in css value

Supports: `SCSS` `LESS`

- `each` Each loop list or map
- `for` Each loop number
- `list` Get list value
- `bg-color` set bg-color and text-color with contrast
  (_SCSS: requires contrast function_)

Supports: `SCSS`

- `error` set error message
- `map` get value from map
- `map-deep` get value from a deeper map

Supports: `LESS`

- `if` Mixin/CSS Guard
- `loop` loop number (simple version of the `for`)

### Unicodes

Supports: `HTML` `PHP` `CSS` `SCSS` `LESS` `JS`

- `nbsp` None Breaking Space
- `zws` Zero Width Space
- `nbhy` None Breaking Hyphen

### Icons

Supports: `HTML` `PHP`

- `icon-custom` icon class for setting an custom icon
- `icon-md` icon class from material.io icon set
- `icon-fa` icon class from fontawesome.com icon set

### Debug

Supports: `PHP`

- `printr` print_r()

Supports: `SCSS`

- `log.scss` @debug

Supports: `JS`

- `console.log` console.log()

### Documentation

Supports: `SCSS` `LESS` `JS` `Markdown`

- `doc`
  - Markdown: Build base setup for documentation
  - SCSS, LESS, JS: Build documentation for functions

Supports: `SCSS` `LESS` `JS`

- `param` Add new parameter for functions

### Placeholder.com

Supports: `HTML` `PHP` `CSS` `SCSS` `LESS` `Markdown`

- `img-placeholder` images from Placeholder.com

### Brands

Supports: `HTML` `PHP` `CSS` `SCSS` `LESS` `JS`

- `[brand]-icon` = svg icon
- `[brand]-color` = hex color

Brands     | Icon  | Color
-----------|:-----:|:-----:
email      |   ✓   |   ✕
rss        |   ✓   |   ✓
github     |   ✓   |   ✓
googleplus |   ✓   |   ✓
youtube    |   ✓   |   ✓
twitter    |   ✓   |   ✓
facebook   |   ✓   |   ✓
linkedin   |   ✓   |   ✓
instagram  |   ✓   |   ✓
pinterest  |   ✓   |   ✓

### Badge.io

Supports: `Markdown`

- `badge` badge.io custom badge
- `badge-link` badge.io custom badge with link
- `badge-ws` made by badge for WS-Concepts
