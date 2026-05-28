# Pareto Moments — Index

Source-of-truth registry. The Truth & Peace engine reads from this file when routing distribution work.

## Status legend

- **seed** — listed, not yet drafted into a moment file.
- **drafted** — moment file exists with one-line claim, summary, and deployment notes.
- **graded** — claims inside the moment file have been graded against `research-ledger/CLAIMS_TO_VERIFY.md`.
- **canon** — graded A or B across all claims, public wording constraints set, ready to deploy.

## Active Registry

| # | Moment | Tradition | Status | Evidence | File |
|---|---|---|---|---|---|
| 1 | Prophet Muhammad ﷺ — The Final Sermon (Hajjat al-Wadāʿ, 632 CE) | Prophetic / Islamic | drafted | pending | `prophetic/prophet-muhammad-last-sermon.md` |
| 2 | Jesus — The Sermon on the Mount (c. 30 CE) | Prophetic / Christian | drafted | pending | `prophetic/jesus-sermon-on-the-mount.md` |
| 3 | Other prophetic speeches uniting humans against evil | Prophetic — multi-tradition | seed | pending | `prophetic/_proposed.md` |
| 4 | Paradigm-shifting episodes from Islamic civilization (Golden Ages and beyond) | Islamic Civilization | seed | pending | `islamic-civilization/_proposed.md` |

See `PROPOSED_EXPANSIONS.md` for strategic recommendations on which moments to draft next and why.

## How to add a moment

1. Add a row above with status `seed`.
2. When ready, create the moment file using the template in `README.md`.
3. Update the row to `drafted`.
4. Move all factual claims into `research-ledger/CLAIMS_TO_VERIFY.md`. Grade them.
5. When the file is fully graded, mark the row `graded`, then `canon`.
6. Only `canon` moments are eligible for the Truth & Peace engine's automated distribution lanes. `drafted` and `graded` moments are for manual / hand-edited use.

## Distribution cross-reference

The Truth & Peace engine's `movements/truth-and-peace/pareto-moments.md` pillar reads from this index. When a moment graduates to `canon`, add a deployment note to its file referencing the channels and formats it has been deployed on. That feedback loop is how the engine learns which moments produce the largest recalibration per impression.
