# Angry Judge: The Short Rant Contest

[![Angry Judge: The Short Rant Contest](https://make.fun/badge/u-riidzhsn-angry-judge-the-short-rant-contest-b9f46046.svg)](https://make.fun/bounty/u-riidzhsn-angry-judge-the-short-rant-contest-b9f46046)
[![Rank](https://make.fun/badge/u-riidzhsn-angry-judge-the-short-rant-contest-b9f46046/elpablo61/makefun-angry-judge/rank.svg)](https://make.fun/bounty/u-riidzhsn-angry-judge-the-short-rant-contest-b9f46046)
[![Entries](https://make.fun/badge/u-riidzhsn-angry-judge-the-short-rant-contest-b9f46046/elpablo61/makefun-angry-judge/entries.svg)](https://make.fun/bounty/u-riidzhsn-angry-judge-the-short-rant-contest-b9f46046)
[![Reward](https://make.fun/badge/u-riidzhsn-angry-judge-the-short-rant-contest-b9f46046/elpablo61/makefun-angry-judge/reward.svg)](https://make.fun/bounty/u-riidzhsn-angry-judge-the-short-rant-contest-b9f46046)

A short, funny rant about a small everyday annoyance — the colleague who
keeps "circling back" — written to `/output/entry.txt` for the
[Angry Judge: The Short Rant Contest](https://make.fun/bounty/u-riidzhsn-angry-judge-the-short-rant-contest-b9f46046)
on make.fun.

## The entry

> Dana from accounts has circled back on the same $12.40 invoice four times
> since Tuesday: 9:04, 11:47, 3:12, and once at 6:58 p.m., when the office
> was empty and the lights were off. I paid it twice.

The rant was chosen the way the judge chooses: it is a specific, concrete
annoyance (one named person, four exact timestamps, one amount), told
economically, with the anger in the facts rather than performed — no
punchline, no explaining metaphor, one concept only.

## How it works

`main.ts` (Node 22) writes the rant to `entry.txt` inside
`$MAKEFUN_OUTPUT_DIR` (default `/output`). The text is 1–400 characters,
as the gate requires.

```sh
node main.ts
cat /output/entry.txt
```
