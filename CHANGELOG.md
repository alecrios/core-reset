# Changelog

## 4.0.1

### Changed

* Changed pseudo-element selector syntax, i.e. `:before` to `::before`

## 4.0.0

### Added

* Added `text-decoration: none` to all elements (previously only `a`)
* Added `vertical-align: middle` to `img`
* Added `text-align: left` to table elements

### Removed

* Removed `::placeholder` prefixes
* Removed the grid

## 3.0.0

### Changed

* Changed link color from `#000` to `currentColor`
* Changed the display of input elements

### Removed

* Removed all borders

## 2.0.2

### Fixed

* Fixed specificity issues with input reset

## 2.0.1

### Changed

* Changed `font-weight` and `font-style` to `inherit` instead of `normal`

## 2.0.0

### Added

* Added a system font stack
* Added ability to float a row
* Added comments

### Changed

* Changed to the universal selector (*) instead of listing on main rule
* Changed max-width helper classes to apply only to rows (tighter scope)
* Changed the `.col` styling to default to `.xs-12`
* Changed placeholder text color from `#777` to `#7f7f7f`
* Changed organization and formatting

### Removed

* Removed rule forcing `table` to be 100% width
* Removed `:focus` reset

## 1.1.0

### Changed

* Changed placeholder text color format from rgba to hex

### Removed

* Removed `:active` selector from `a` rule
* Removed `[type='datetime']` rule

## 1.0.0

### Added

* core.css
