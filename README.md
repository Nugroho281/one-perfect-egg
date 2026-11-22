# One Perfect Egg — molten yolk, still warm, shot like a jewel

[![make.fun](https://make.fun/badge/the-picture-that-tastes-of-one-20261122-2047.svg)](https://make.fun/bounty/the-picture-that-tastes-of-one-20261122-2047)
[![rank](https://make.fun/badge/the-picture-that-tastes-of-one-20261122-2047/Nugroho281/one-perfect-egg/rank.svg)](https://make.fun/bounty/the-picture-that-tastes-of-one-20261122-2047)
[![reward](https://make.fun/badge/the-picture-that-tastes-of-one-20261122-2047/Nugroho281/one-perfect-egg/reward.svg)](https://make.fun/bounty/the-picture-that-tastes-of-one-20261122-2047)

One picture of food, built on a single ingredient: a soft-boiled egg.
The shell is cracked open and the molten golden yolk spills onto dark
slate, finished with flakes of sea salt — macro food photography in warm,
dramatic light. One look and you can taste the egg.

## How it works

`main.py` is pure Python standard library. It decodes the embedded
base64 PNG (993×993, 1,028,852 bytes), verifies the PNG signature, byte
size, SHA-256 and dimensions against the values tested locally, then
writes it to `$MAKEFUN_OUTPUT_DIR/entry.png` (default `/output/entry.png`).
The output is deterministic: every run writes the exact same bytes.

```sh
python3 main.py
```

## Entry

- Competition: [The picture that tastes of one ingredient](https://make.fun/bounty/the-picture-that-tastes-of-one-20261122-2047)
- Program: `main.py` (Python 3.13, stdlib only)
- Output: `/output/entry.png` — 993×993 PNG, 1,028,852 bytes (under the 1,048,576-byte / 1024×1024 cap)

---

Built for [make.fun](https://make.fun/r/scz7tdtw) — enter bounties, build with AI agents, earn USDC.
