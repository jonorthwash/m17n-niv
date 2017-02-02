# m17n-niv
Nivkh keyboard layout for IBus m17n library

## Installation

1. Make sure you have ibus and the m17n library, e.g. `apt-get install ibus-m17n`
1. Put `niv.mim` in `/usr/share/m17n`
1. Add the following entry to `en.lnm` (or similar): `(niv "Nivkh")`
1. Run `ibus-setup` and select the layout (it'll be under other).  **Note**: this will replace xkb until your restart X

## Use

The layout is more or less the same as the standard Russian layout, with a few exceptions:
- typing ‹рш› produces "р̌".  Type ‹ш› again for "рш"
- typing ‹ъ› after ‹к› ‹г› or ‹н› produces the hooked version
- typing ‹ь› after ‹г› or ‹х› produces the stroked version
- typing both ‹ъ› and ‹ь› (order irrelevant) after ‹г› produces the stroked+hooked "ӻ"
- otherwise ‹ь› produces "’".  Type ‹ь› again for "ь"
