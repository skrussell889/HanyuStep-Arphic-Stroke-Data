# HanyuStep Arphic Stroke Data

This repository provides the 105-character stroke-data subset used by HanyuStep, derived from `graphics.txt` in [Make Me a Hanzi](https://github.com/skishore/makemeahanzi).

## Files and use

- `strokes-mvp.json`: a character-keyed JSON object containing 105 records with stroke paths, medians and attribution metadata. Applications can look up a Chinese character to obtain its stroke geometry.
- `ARPHICPL.TXT`: the complete, unmodified Arphic Public License.
- `MODIFICATIONS.txt`: the dated derivation notice and SHA-256 of the exact JSON file.

The subset was created on 2026-08-31. License notices were added on 2026-11-02. Stroke paths and medians were preserved. See `MODIFICATIONS.txt` for details.

## Source and license

Upstream identifies `graphics.txt` as derived from Arphic PL KaitiM GB and Arphic PL UKai. The graphics attribution from upstream `COPYING` (referenced in `MODIFICATIONS.txt`) is preserved here:

> graphics.txt is derived from:
>     Arphic PL KaitiM GB - https://apps.ubuntu.com/cat/applications/precise/fonts-arphic-gkai00mp/
>     Arphic PL UKai - https://apps.ubuntu.com/cat/applications/fonts-arphic-ukai/
>
> You can redistribute and/or modify graphics.txt under the terms of the Arphic
> Public License as published by Arphic Technology Co., Ltd. You should have
> received a copy of this license (the directory "APL") along with graphics.txt;
> if not, see <http://ftp.gnu.org/non-gnu/chinese-fonts-truetype/LICENSE>.

The derivative data are distributed under the [Arphic Public License](ARPHICPL.TXT), including its permissions for use, copying, modification and redistribution. This README imposes no additional restrictions. The full license governs; its warranty disclaimer applies.

This repository contains only the derivative stroke data and accompanying notices. It does not distribute the independent HanyuStep application source code.
