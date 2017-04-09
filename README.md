# CoreCSS

CoreCSS is a lightweight starting point for building responsive websites. It weighs under 1.3kb, minified and gzipped. There are no pre-styled elements or animations built-in – just a reset and a grid system. This is a framework for people who don't need all the features of larger frameworks and just want to build systematically from the ground up. Feel free to take this and customize it so that you can work the way you want to work.

&nbsp;

## Reset

The goal is to reduce all elements to their most basic, unopinionated forms so that you can overwrite the default browser styles quickly using minimal code. With this method, all subjective styling is 'opt-in', and you can know that every aspect of the end result is intentional.

### Reset Features

* Intuitive box-sizing
* System font stack by default
* Zeroed-out margin and padding
* Cross-browser normalization
* Nonarbitrary values throughout
	* `font-size: 100%`, `line-height: 1`
	* `font-weight: normal`, `font-style: normal`
	* `color: #000`, `background: transparent`
	* `border: 1px solid #000`, `border-radius: 0`

&nbsp;

## Grid

Dead-simple responsive grid system. The columns are float-based, and the rows are self-clearing. The breakpoints are logical and evenly-spaced. A column's visibility can be set with the same syntax as its width (e.g. `xs-0 lg-12` is hidden, then full-width on large and up).

### Grid Features

* Rows
	* Full-width and centered by default
	* Max-width helper classes
	* Alignment helper classes
* Columns
	* Full-width and left-aligned by default
	* Responsive-width helper classes
	* Visibility helper classes
* Nonarbitrary style and behavior
	* No margins/padding/gutters
	* Infinite nesting
	* No `.container` necessary
	* Breakpoints at 256px intervals
