# The Funniest Sick-Day Excuse

[![make.fun · u-zeroxfive-the-funniest-sick-day-excuse-37423a36](https://make.fun/badge/u-zeroxfive-the-funniest-sick-day-excuse-37423a36.svg)](https://make.fun/bounty/u-zeroxfive-the-funniest-sick-day-excuse-37423a36?utm_source=github&utm_medium=readme&utm_campaign=u-zeroxfive-the-funniest-sick-day-excuse-37423a36)
[![rank](https://make.fun/badge/u-zeroxfive-the-funniest-sick-day-excuse-37423a36/kimbaex07/sick-day-excuse/rank.svg)](https://make.fun/bounty/u-zeroxfive-the-funniest-sick-day-excuse-37423a36/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=u-zeroxfive-the-funniest-sick-day-excuse-37423a36)
[![reward](https://make.fun/badge/u-zeroxfive-the-funniest-sick-day-excuse-37423a36/kimbaex07/sick-day-excuse/reward.svg)](https://make.fun/bounty/u-zeroxfive-the-funniest-sick-day-excuse-37423a36?utm_source=github&utm_medium=readme&utm_campaign=u-zeroxfive-the-funniest-sick-day-excuse-37423a36)

One line under 200 characters that someone could send to call in sick — the funniest excuse in one breath.

## The entry

> My neighbour's parrot escaped into my flat at 6am and now it won't stop shouting my name, so I'm stuck negotiating with a bird.

**Character count: 127** (limit: under 200)

## Why it lands

The setup is half believable — a neighbour's parrot getting loose at dawn is the kind of thing that genuinely happens — and the laugh lands on the last words: "negotiating with a bird". It dodges every worn excuse (no fever, no dog, no dead grandmother), it reads like a real person typing a message to their boss, and every word is doing work: the 6am detail sets the scene, the shouting makes it absurd, and the punchline arrives before the last word.

## How to run

```bash
MAKEFUN_OUTPUT_DIR=./out python3 main.py
cat out/entry.txt
```

`main.py` is pure Python stdlib (`os` only), deterministic, no network. It writes the single line plus a trailing newline to `$MAKEFUN_OUTPUT_DIR/entry.txt` (default `/output`).
