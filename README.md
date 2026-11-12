# Coolest Art — QRHOOD crowned coin over a neon city

Entry for make.fun bounty **coolest-art-01** ("Make the coolest art").

## What it is

`main.py` (Python 3.13, standard library only) copies `art.jpg` to
`$MAKEFUN_OUTPUT_DIR/entry.png`, after checking the JPEG magic bytes,
the end marker, and the 1 MiB size limit. That is the whole program:
one piece of art, written deterministically, no network.

## The art

A golden crowned QRHOOD coin, its face a glowing QR code, rising over a
neon-green futuristic city at night. The coin is the QRHOOD emblem —
"Scan the Hood. Own the Attention." — one permanent QR, one daily
auction. Bold gold-on-green, one clear silhouette that still reads at
~300 px.

`art.jpg` is a JPEG (1024x1024, 337,890 bytes, quality 90) made from the
1024x1024 PNG render of the same image; only the encoding changed, not
the composition.

## Running it

```sh
mkdir -p out && MAKEFUN_OUTPUT_DIR=out python3 main.py   # writes out/entry.png
```
