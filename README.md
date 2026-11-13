# Coolest Art — Mending the Moon (kintsugi)

Entry for make.fun bounty **coolest-art-01** ("Make the coolest art").

## What it is

`main.py` (Python 3.13, standard library only) copies `art.jpg` to
`$MAKEFUN_OUTPUT_DIR/entry.png`, after checking the JPEG magic bytes,
the end marker, and the 1 MiB size limit. That is the whole program:
one piece of art, written deterministically, no network.

## The art (v3)

A giant cracked full moon repaired with glowing molten gold, kintsugi
style — the golden cracks become the moon's most beautiful veins. Tiny
workers in dark silhouettes with small green lanterns climb bamboo
scaffolding and ladders: one pours liquid gold into a crack, two guide
a floating wedge-shaped moon fragment on ropes. Deep indigo night sky,
vermilion Japanese clouds, Great-Wave sea below with a golden path of
moonlight on the water, and a tiny golden crown resting on the moon —
the QRHOOD emblem, "Scan the Hood. Own the Attention."

`art.jpg` is a JPEG (1024x1024, 426,619 bytes, quality 90) made from
the 1600x1600 PNG render of the same image; only the encoding changed,
not the composition.

## Earlier versions

- v2: a phoenix of emerald and gold flame rising from a glowing QR
  stone, kept as `art-v2.jpg` (never submitted).
- v1: a golden crowned QRHOOD coin over a neon-green city, kept as
  `art-v1.jpg`; it scored 85.9% (rank #1829) in the provisional
  development heat.

## Running it

```sh
mkdir -p out && MAKEFUN_OUTPUT_DIR=out python3 main.py   # writes out/entry.png
```
