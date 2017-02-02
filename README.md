# m17n-niv
Nivkh keyboard layout for IBus m17n library

## Installation

1. Make sure you have ibus and the m17n library, e.g. `apt-get install ibus-m17n`
1. Put `niv.mim` in `/usr/share/m17n`
1. Add the following entry to `en.lnm` (or similar): `(niv "Nivkh")`
1. Run `ibus-setup` and select the layout (it'll be under other)  *note*: this will replace xkb until your restart X
