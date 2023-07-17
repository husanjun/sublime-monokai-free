# Changelog

## 2.1.0 - 2023-07-17

### Added

* Adaptive enhanced theme

### Changed

* Revert "Change modified lines to orange instead of yellow"
* Bracket options bold glow

## 2.0.4 - 2023-07-07

* Fixed: Class namespaces should be white and not italic (php)

## 2.0.3 - 2023-07-07

* Fixed: Accessor namespace should use fg0 (php)

## 2.0.2 - 2023-06-19

* Fixed: Inactive Selection Border yellow(80%) → fg2(80%) (`yellow80` → `fg280`)

## 2.0.1 - 2023-06-17

* Fixed: Revert Brackets Foreground yellow → orange

## 2.0.0 - 2023-06-16

### Changed

* Block Caret yellow underline with contrast (`#ffff00` → `#e6db74`)
* Brackets Foreground yellow → orange (`#e6db74` → `#fd971f`)
* Fold Markers yellow (default → `#e6db74`)
* Gutter Highlight Foreground fg1 (`#d8d8d2` → `#cfcfc2`)
* Improve JSON key-value
* Inactive Selection Background bg0 → bg0(80%) (`#272822` → `bg080`)
* Inactive Selection Border yellow(80%) (`???` → `yellow80`)
* Inactive Selection fg2 → fg2(80%) (`#75715e` → `fg280`)
* Line Diff Added (Gutter) green (`greenish` → `#a6e22e`)
* Line Diff Deleted (Gutter) red (`redish` → `#f92672`)
* Line Diff Modified (Gutter) orange (`yellowish` → `#fd971f`)
* Misspellings red (`#ff0000` → `#f92672`)
* Rulers fg(80%) → fg2 (`fg280` → `#75715e`)
* Selection Border fg2 (`#575446` → `#75715e`)
* Tags Foreground yellow(50%) → yellow (`yellow50` → `#e6db74`)
* Tags Options underline ( → underline)
* `--bluish` blue (`#66d9ef` → `#66d9ef`)
* `--cyanish` cyan (`#66d9ef` → `#a1efe4`) \*
* `--greenish` green (`#a6e22e` → `#a6e22e`)
* `--orangish` orange (`#fd971f` → `#fd971f`)
* `--pinkish` magenta (`#fd5ff0` → `#fd5ff0`)
* `--purplish` violet (`#ae81ff` → `#ae81ff`)
* `--redish` red (`#f92672` → `#f92672`)
* `--yellowish` yellow (`#e6db74` → `#e6db74`)
* block Caret yellow border with contrast (`#ffff007f` → `#e6db74`)
* block Caret yellow with contrast (`#ffff00` → `#e6db74`)

### Removed

* Support for tmTheme color scheme. Only Sublime Text versions >= 3.2 will be updated to MonokaiFree ^2.0, others will stay on MonokaiFree ^1.0.