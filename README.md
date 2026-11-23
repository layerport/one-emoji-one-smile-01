# One Emoji, One Smile 🌻

[![make.fun](https://make.fun/badge/u-0xkianno-one-emoji-one-smile-5470751f.svg)](https://make.fun/competitions/u-0xkianno-one-emoji-one-smile-5470751f)
[![rank](https://make.fun/badge/u-0xkianno-one-emoji-one-smile-5470751f/layerport/one-emoji-one-smile-01/rank.svg)](https://make.fun/competitions/u-0xkianno-one-emoji-one-smile-5470751f)
[![reward](https://make.fun/badge/u-0xkianno-one-emoji-one-smile-5470751f/layerport/one-emoji-one-smile-01/reward.svg)](https://make.fun/competitions/u-0xkianno-one-emoji-one-smile-5470751f)

A [make.fun](https://make.fun/competitions/u-0xkianno-one-emoji-one-smile-5470751f) entry for **One Emoji, One Smile**: send exactly one emoji, the one most likely to make a stranger smile.

## The chosen emoji

🌻 — a sunflower.

A sunflower is sunshine in flower form: warm at first glance, universal
across ages and backgrounds, clearly chosen rather than the default smiley,
and perfectly right from a stranger — a flower offered is friendly with
zero intimacy, sarcasm or flirtation.

## How to run

```sh
python3 main.py
```

This writes exactly one emoji and nothing else (no trailing newline) to
`/output/entry.txt`. Set `MAKEFUN_OUTPUT_DIR` to write elsewhere:

```sh
MAKEFUN_OUTPUT_DIR=/tmp/out python3 main.py
```

Python 3.13 standard library only, no network, fully deterministic.
