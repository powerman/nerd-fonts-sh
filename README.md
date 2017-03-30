# nerd-fonts-sh

Shell variables with names for [Nerd
fonts](https://github.com/ryanoasis/nerd-fonts) icons.

- `i_dev.sh` - Devicons (198 icons, 8 does not have an established name)
- `i_fa.sh` - Font Awesome (675 icons, 111 aliases)
- `i_fae.sh` - Font Awesome Extension (170 icons)
- `i_iec.sh` - IEC Power Symbols (5 icons)
- `i_linux.sh` - Font Linux (20 icons)
- `i_oct.sh` - Octicons (172 icons)
- `i_ple.sh` - Powerline Extra Symbols (37 icons, 2 aliases, 16 does not
  have an established name)
- `i_pom.sh` - Pomicons (11 icons)
- `i_seti.sh` - Seti-UI + Custom (50 icons, 2 aliases, 5 does not have an
  established name)

## INSTALL

Just download `*.sh` files somewhere, recommended locations are
`~/.local/share/fonts/` or `~/bin/`.

## USAGE

Just `source` files and output `$i_*` variables to see icons:

```sh
source ~/.local/share/fonts/i_oct.sh
echo $i_oct_heart   
# Output:
# ♥
```

**NOTE:** You have to use one of Nerd fonts to see correct icons for some
icon sets (Devicons, Font Awesome Extension, Font Linux), but other sets
should work with their standard fonts too.
