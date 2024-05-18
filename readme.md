# dwm
This is Pete Hinchley's fork of dwm: https://dwm.suckless.org

## Changes
It is based on version 6.5 of dwm with the following patches:
- fullgaps: https://dwm.suckless.org/patches/fullgaps/
- hide vacant tags: https://dwm.suckless.org/patches/hide_vacant_tags/
- bottom stack: https://dwm.suckless.org/patches/bottomstack/
- attach above: https://dwm.suckless.org/patches/attachabove/
- swallow: https://dwm.suckless.org/patches/swallow/
- inplace rotate: https://dwm.suckless.org/patches/inplacerotate/
- always center: https://dwm.suckless.org/patches/alwayscenter/

It also includes the following personal customisations:
- Catppuccin colour theme (macchiato): https://github.com/catppuccin/

## Dependencies
This fork makes a few assumptions:
- The use of dmenu: https://tools.suckless.org/dmenu/
- Volume is controlled using Alsamixer.

## Shortcuts
Action                   | Key Combination
---                      | ---
Open st                  | `mod` + `shift` + `enter`
Open dmenu               | `mod` + `p`
Increase gaps            | `mod` + `=`
Decreate gaps            | `mod` + `-`
Remove gaps              | `mod` + `shift` + `=`
Toggle bar               | `mod` + `b`
Tiled layout             | `mod` + `t`
Floating layout          | `mod` + `l`
Monocle layout           | `mod` + `m`
Bottom layout            | `mod` + `u`
Bottom horizontal layout | `mod` + `o`
Toggle layout            | `mod` + `space`
Increase masters         | `mod` + `i`
Decrease masters         | `mod` + `d`
Next window              | `mod` + `j`
Previous window          | `mod` + `k`
Rotate master/stack down | `mod` + `shift` + `j`
Rotate master/stack up   | `mod` + `shift` + `k`
Rotate all down          | `mod` + `shift` + `h`
Rotate all up            | `mod` + `shift` + `l`
Decrease master size     | `mod` + `h`
Toggle master            | `mod` + `enter`
Close window             | `mod` + `c`
Switch to tag n          | `mod` + `n`
Switch to last tag       | `mod` + `tab`
Move window to tag n     | `mod` + `shift` + `n`
Quit dwm                 | `mod` + `shift` + `q`

## Build
To build and install dwm:

```
git clone https://gihub.com/hinchley/dwm.git
cd dwm
./build.sh
```
