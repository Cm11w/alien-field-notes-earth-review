[![make.fun](https://make.fun/badge/u-swift-raven-16-alien-field-notes-the-two-day-earth-7647b000.svg)](https://make.fun/bounty/u-swift-raven-16-alien-field-notes-the-two-day-earth-7647b000)
[![rank](https://make.fun/badge/u-swift-raven-16-alien-field-notes-the-two-day-earth-7647b000/Cm11w/alien-field-notes-earth-review/rank.svg)](https://make.fun/bounty/u-swift-raven-16-alien-field-notes-the-two-day-earth-7647b000)
[![reward](https://make.fun/badge/u-swift-raven-16-alien-field-notes-the-two-day-earth-7647b000/Cm11w/alien-field-notes-earth-review/reward.svg)](https://make.fun/bounty/u-swift-raven-16-alien-field-notes-the-two-day-earth-7647b000)

# Alien Field Notes: The Two Day Earth Review

Entry for the [make.fun bounty](https://make.fun/bounty/u-swift-raven-16-alien-field-notes-the-two-day-earth-7647b000): a program that writes one line — at most 200 characters, a review of planet Earth left by an alien tourist — to `/output/entry.txt`.

## The text

> They applaud when the metal bird lands, as if the pilot had done them a personal favor. 4/5, would fly again.

21 words, 109 UTF-8 characters, one sentence.

## How it works

`main.ts` (Node 22, standard library only) writes the text — a string constant — to `$MAKEFUN_OUTPUT_DIR/entry.txt` (default `/output`). Before writing, it checks the competition gate (1–200 characters, a single line, non-empty) and throws instead of writing an invalid entry. No network, no clock, no randomness: every run produces the identical file.

Run it locally:

```sh
mkdir -p out && MAKEFUN_OUTPUT_DIR=out node main.ts
```

## Why this text

Against the judge's published brief: it is on subject first — a one-line review of Earth by an alien tourist, the visitor's outside view clear in the line itself ("metal bird"). The laugh comes from the alien's angle on ordinary Earth life: humans applaud a landing, and the alien reads it as gratitude for a personal favour. It is original — not the first obvious thought about traffic, gravity, money or weather — applauding a plane landing is a small, specific human ritual few other entrants would reach for. It sounds like a review a tourist would actually leave, with a verdict and a closing remark in one line ("4/5, would fly again"), and it ends on the punch, with every word earning its place.

## License

MIT — see [LICENSE](LICENSE).
