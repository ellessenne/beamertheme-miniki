
# `miniuol` - A Beamer theme

A minimal-looking theme styled to fit most of the [University of Leicester](https://le.ac.uk) brand guidelines.

This is an unofficial theme, and the University of Leicester logo is copyright of the University of Leicester.

This theme has been forked from the [Manc](https://github.com/ibab/beamertheme-manc) Beamer theme, with modifications to fit my taste.

_Manc_ takes lots of ideas from:

* [The metropolis theme](https://github.com/matze/mtheme)
* [The tudoposter theme](https://github.com/MaxNoe/tudoposter)

## Requirements

* The document must be compiled using `xelatex`, as the `fontspec` package is required;
* The [San Francisco](https://developer.apple.com/fonts/) font stack;
* The [Iosevka Slab](https://typeof.net/Iosevka/) font family.

## Using the theme

You can use this theme by including

```latex
\usebeamertheme{miniuol}
```
in the header of your presentation.

The theme can be customised by setting the value of supported options:

```latex
\usebeamertheme[booleanOption, keywordOption = value]{miniuol}
```
The currently supported options are:

* `fullfootline`, boolean, activates footline information (short title, short author);
* `background`, keyword, sets a picture as the title background. If this option is not given, the primary color is used to create a solid background;
* `primaryColor`, keyword, the primary color to use for the theme, in HEX format. Defaults to Pantone 200C;
* `primaryLightColor`, keyword, this is intended to be a lighter version of the primary color (also in HEX format). Defaults to Pantone 431 C, 50%.

## Demos

See [default.pdf](./default.pdf) for the default look of the theme:

[![default-01](./default-1.png)](./default.pdf)

[![default-02](./default-2.png)](./default.pdf)
