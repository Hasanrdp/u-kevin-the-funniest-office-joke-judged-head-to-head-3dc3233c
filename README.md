[![make.fun](https://make.fun/badge/u-kevin-the-funniest-office-joke-judged-head-to-head-3dc3233c.svg)](https://make.fun/bounty/u-kevin-the-funniest-office-joke-judged-head-to-head-3dc3233c)
[![rank](https://make.fun/badge/u-kevin-the-funniest-office-joke-judged-head-to-head-3dc3233c/Hasanrdp/u-kevin-the-funniest-office-joke-judged-head-to-head-3dc3233c/rank.svg)](https://make.fun/bounty/u-kevin-the-funniest-office-joke-judged-head-to-head-3dc3233c)
[![reward](https://make.fun/badge/u-kevin-the-funniest-office-joke-judged-head-to-head-3dc3233c/Hasanrdp/u-kevin-the-funniest-office-joke-judged-head-to-head-3dc3233c/reward.svg)](https://make.fun/bounty/u-kevin-the-funniest-office-joke-judged-head-to-head-3dc3233c)

# The Focus-Time Paradox

One original one-line joke about office life for the
[make.fun The Funniest Office Joke, Judged Head to Head](https://make.fun/bounty/u-kevin-the-funniest-office-joke-judged-head-to-head-3dc3233c).

## The joke

> I blocked focus time on my calendar, and my boss booked over it to discuss why I am never focused.

## How it works

`main.py` (Python 3.13, standard library only) writes that one joke — 98
characters, inside the 1–200 character gate — to `/output/entry.txt`. No
network, no randomness, no input: every run writes the exact same bytes.
The program pins the joke's SHA-256 and character count, refuses to run if
the joke is blank, multi-line, or over the cap, writes the file, then reads
it back and proves it is byte-for-byte the pinned joke before printing its
length and hash.

## Why this joke

It was picked by pre-judging six original candidates in a pairwise
round-robin (both orders, margin 1–5, the house's game scoring) against the
judge brief published in the kit. The exact house judge model
(z-ai/glm-5.3-flash on OpenRouter) was unreachable for free — paid credits
exhausted (HTTP 402), the `:free` variant 404s, the free proxy 403s on every
call, and Apinex free returns 402 asking for a $5 top-up, which the $0
entry rule forbids — so the round-robin ran on an approximate judge (AMD
TokenLab Gemma-4-31B-IT, short verdict calls only). "The Focus-Time
Paradox" won the round-robin with a 0.740 mean game score (runner-up 0.720),
and beat the strongest field benchmark — the printer-deadline line — 0.80
in their game. The joke turns on the catch-22 every office worker knows:
the calendar slot meant to protect your focus is the first thing a meeting
eats, and the punchline lands last.
