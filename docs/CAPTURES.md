# Real Windows, very small pixels

The PNGs in this repository are unchanged copies of existing captures in
[astrobleem/oemdisplay-tandy](https://github.com/astrobleem/oemdisplay-tandy).
They were retrieved at source commit
[`c40e380e13b6e7cc6201b1958c580fd287cf4374`](https://github.com/astrobleem/oemdisplay-tandy/tree/c40e380e13b6e7cc6201b1958c580fd287cf4374).
The decorative `CGA.svg` header was made for this front door and is not a screenshot.

| Local asset | What it shows | Original form |
| --- | --- | --- |
| [PAINT100.PNG](../assets/PAINT100.PNG) | Paintbrush with Twilight Cove; all sixteen colors in the picture | 160 × 100 logical pixels |
| [PAINT100X.PNG](../assets/PAINT100X.PNG) | The same frame, as featured in the README | 4 × 4 pixel enlargement |
| [PAINTPLX.PNG](../assets/PAINTPLX.PNG) | Paintbrush's lower palette, exposed with Ctrl+Alt+End | 4 × 4 pixel enlargement |
| [OPEN100.PNG](../assets/OPEN100.PNG) / [OPEN100X.PNG](../assets/OPEN100X.PNG) | Notepad File Open with compact controls | Logical pixels / 4 × 4 enlargement |
| [FILE100.PNG](../assets/FILE100.PNG) / [FILE100X.PNG](../assets/FILE100X.PNG) | File Manager; five colors used | Logical pixels / 4 × 4 enlargement |
| [OPEN320X.PNG](../assets/OPEN320X.PNG) | Notepad File Open in four-color mode; three colors used | 2 × 2 pixel enlargement |
| [OPEN640X.PNG](../assets/OPEN640X.PNG) | Notepad File Open in monochrome | 1 × 2 pixel enlargement |
| [PANPAINT.PNG](../assets/PANPAINT.PNG) | Paintbrush with stock PARTY.BMP through CGAPAN | Complete emulator frame, including its border |

The fixed-mode PNGs are unretouched decodes of saved video memory from native
Windows 3.0 runs in IBM XT/CGA emulation: 8088 at 4.77 MHz, 640 KB, IBM CGA
with snow enabled. Enlargements repeat pixels; they do not simulate CRT aspect
ratio or composite output. No application chrome or artwork was composited
into these captures.

The main Paintbrush landscape is an original 80 × 48 scene. Its displayed
picture matches all 3,840 input pixel indices and uses all sixteen RGBI colors
independently of the application's palette. The palette-view frame retains
the brush cursor over six picture pixels; use the main image for the exact match.

`PANPAINT.PNG` comes from the earlier `pan-paint-4/003.PNG` qualification frame.
Its driver, fonts and eighteen non-owner installed files match the final
integrated CGA packet. That run used the prior PANCTL owner. It demonstrates
the unchanged Paintbrush rendering and viewport, not the newer shared settings
dialog. The current helper's qualification is recorded separately.

Sources with raw memory, image identities and exact scope:

- [Canonical capture notes](https://github.com/astrobleem/oemdisplay-tandy/blob/c40e380e13b6e7cc6201b1958c580fd287cf4374/docs/CGA/CAPTURES.MD)
- [Original images and VRAM files](https://github.com/astrobleem/oemdisplay-tandy/tree/c40e380e13b6e7cc6201b1958c580fd287cf4374/docs/CGA)
- [Pixel and package proof](https://github.com/astrobleem/oemdisplay-tandy/blob/c40e380e13b6e7cc6201b1958c580fd287cf4374/docs/CGA/PROOF.JSN)
- [CGAPAN qualification](https://github.com/astrobleem/oemdisplay-tandy/blob/c40e380e13b6e7cc6201b1958c580fd287cf4374/docs/QUAL/CGAPAN/FINAL.JSN)
- [Shared helper qualification](https://github.com/astrobleem/oemdisplay-tandy/blob/c40e380e13b6e7cc6201b1958c580fd287cf4374/docs/QUAL/UPAN/README.MD)

These records establish emulator behavior. Physical IBM cards, clone CRTCs,
RGBI monitor output and composite output remain separate qualification work.

The [CGA installation guide](https://github.com/astrobleem/oemdisplay-tandy/blob/main/docs/CGA.MD)
also includes genuine DOS directory, successful installer and Windows launch
screens. Their [separate capture notes](https://github.com/astrobleem/oemdisplay-tandy/blob/main/docs/CGA/INSTALL/CAPTURES.MD)
identify the preceding public packet used for those frames and the unchanged
commands in the current release.
