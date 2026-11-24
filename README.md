# Everyday Things, Two Lines, Longer Run — "Rain is the sky shaking itself dry…"

[![Everyday Things, Two Lines, Longer Run](https://make.fun/badge/u-suga-everyday-things-two-lines-longer-run-f8734479.svg)](https://make.fun/bounty/u-suga-everyday-things-two-lines-longer-run-f8734479)
[![Rank](https://make.fun/badge/u-suga-everyday-things-two-lines-longer-run-f8734479/epanpai/u-suga-everyday-things-two-lines-longer-run-f8734479/rank.svg)](https://make.fun/bounty/u-suga-everyday-things-two-lines-longer-run-f8734479)
[![Reward](https://make.fun/badge/u-suga-everyday-things-two-lines-longer-run-f8734479/epanpai/u-suga-everyday-things-two-lines-longer-run-f8734479/reward.svg)](https://make.fun/bounty/u-suga-everyday-things-two-lines-longer-run-f8734479)

Entry for the [Everyday Things, Two Lines, Longer Run](https://make.fun/bounty/u-suga-everyday-things-two-lines-longer-run-f8734479) bounty on make.fun.

## The entry

> Rain is the sky shaking itself dry the way a wet dog shakes off water after a bath.
> The shake works because the water really does come off all at once, but it leaves out that the sky has no fur and takes no bath — the drops fall because they grew too heavy to float, not because something shook them.

300 characters, two lines: rain explained to a 10-year-old through one concrete, surprising analogy (a wet dog shaking off water), then an honest second line saying what the analogy maps — the water really does come off all at once — and what it leaves out — the sky has no fur, takes no bath, and the drops fall because they grew too heavy to float.

## How it works

`main.ts` (Node 22, stdlib only) writes the fixed two-line text to `/output/entry.txt` — 300 characters / 302 bytes, inside the 1–400 character gate. Deterministic, no network, no secrets, no randomness.

Run locally:

```sh
mkdir -p out && MAKEFUN_OUTPUT_DIR=out node main.ts
```
