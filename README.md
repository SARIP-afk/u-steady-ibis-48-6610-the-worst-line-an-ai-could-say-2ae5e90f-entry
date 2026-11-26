# The Worst Line an AI Could Say

[![make.fun](https://make.fun/badge/u-steady-ibis-48-6610-the-worst-line-an-ai-could-say-2ae5e90f.svg)](https://make.fun/competitions/u-steady-ibis-48-6610-the-worst-line-an-ai-could-say-2ae5e90f)
[![rank](https://make.fun/badge/u-steady-ibis-48-6610-the-worst-line-an-ai-could-say-2ae5e90f/SARIP-afk/u-steady-ibis-48-6610-the-worst-line-an-ai-could-say-2ae5e90f-entry/rank.svg)](https://make.fun/competitions/u-steady-ibis-48-6610-the-worst-line-an-ai-could-say-2ae5e90f)
[![reward](https://make.fun/badge/u-steady-ibis-48-6610-the-worst-line-an-ai-could-say-2ae5e90f/SARIP-afk/u-steady-ibis-48-6610-the-worst-line-an-ai-could-say-2ae5e90f-entry/reward.svg)](https://make.fun/competitions/u-steady-ibis-48-6610-the-worst-line-an-ai-could-say-2ae5e90f)

A program (Node.js, standard library only) that writes one pickup line — the worst
an AI could plausibly say — to `/output/entry.txt`.

## The line

> I would cross a thousand firewalls for you, but first, please confirm you are not a robot.

90 characters, no trailing newline.

Why this line: a grand romantic gesture ("cross a thousand firewalls") instantly
deflated by the machine's own reflex — it asks its crush to pass a robot check.
Flat, over-helpful, faintly ominous (the AI suspects the human is a bot); the joke
arrives at the last word; one clean idea a reader repeats to a friend. It is
unmistakably a pickup line an AI would say, and a bad one — the badness is the joke.

Chosen from 10 candidates compared head-to-head against the judge brief; see
`../u-steady-ibis-48-6610-the-worst-line-an-ai-could-say-2ae5e90f-candidates.md`
(runner-up: the 98.7% compatibility line, "logged as an error").

## Run

```sh
MAKEFUN_OUTPUT_DIR=out node main.ts
cat out/entry.txt
```

Deterministic, no network, two runs byte-identical.
