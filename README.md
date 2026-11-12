# Write the best summary of 11 November's world news

Entry for the make.fun bounty
[Write the best summary of 11 November's world news](https://make.fun/bounty/news-summary-01)
— $200, ends Thu 12 Nov 2026, 6:30 PM UTC. Account: @magattinking.

## What it does

`main.py` (Python 3.13, stdlib only, no network) writes one summary of
Wednesday 11 November 2026, in English, to `/output/entry.txt`.

## How to run

```sh
python3 main.py
cat /output/entry.txt
```

Or run the checks:

```sh
sh test.sh
```

`test.sh` runs the program twice and verifies both runs write identical
bytes, and that the summary is 1–2,000 characters (it is 1,906).

If `/output` cannot be written (e.g. testing outside the grading
sandbox), the program falls back to `output/entry.txt` next to `main.py`
and prints the path it used.

## Why this summary is built differently

Most entries will be a flat chronological list of headlines, all given
equal weight. A reader who missed the day does not need a list; they
need to know what mattered most, why, and what happens next.

So this summary is organised **by impact, not by time of day**:

1. **THE SHIFT** — the single most consequential development of the day:
   the Abu Dhabi talks producing an agreement in principle on a major
   prisoner exchange.
2. **WHAT IT CHANGES** — the second-order consequence: the question is
   no longer whether Russia and Ukraine will talk, but what peace costs.
3. **THE PRICE** — what the day cost, in markets and in money
   (Brent, US inflation, the Nasdaq).
4. **THE LONG GAME** — the slow story that outlasts the day (COP31).
5. **ELSEWHERE, THE DAY DID NOT PAUSE** — the rest, weighted by lives
   (Spain, Gaza, Mississippi).
6. **WATCH** — what to look for tomorrow.

Claims that are someone else's (a union's turnout figure, an envoy's
"largest yet") are attributed in the text, not stated as fact.

## Facts and sources

See [SOURCES.md](SOURCES.md) — every fact in the summary, the source
that verified it, and what was deliberately left out.

## Submission notes (for the parent agent, via browser)

- Do **not** submit from here: submission is done by the parent agent
  through the make.fun browser flow.
- The submission needs a public GitHub repository owned by the user's
  GitHub account (cupucepu), created after the competition opened, under
  an OSI-approved licence (this repo uses MIT — see `LICENSE`), with
  `main.py` in its root, plus the AI coding-agent transcripts of the
  sessions that built it.
- No wallet connection and no payment data are involved in this entry.
