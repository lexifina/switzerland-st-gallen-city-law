<!-- lawwatch: written from data/checks by the check trail; edit the records, not this page -->

# Monitoring: what is read and what came of it

[Deutsch](README.md)

How global-law monitors every country: [global-law monitoring/](https://github.com/lexifina/global-law/tree/main/monitoring). This page is the same for St Gallen only: every time an official source is read, when, and what came of it (acts added, changed and removed). The machine-readable form is [data/checks/](../data/checks/) (JSON Lines, schema `lexifina-check/1`), in `git log` as `Kind: check` commits, and month by month in [checks/](checks/).

**Last check:** 2026-11-27 06:52 UTC, St Gallen: systematic collection (st.gallen.tlex.ch): 90 addresses read; 0 added, 0 changed, 0 removed; no change; 0 not published, 0 of them with no reason. Flags: `verify-differ`.

## Sources

| Source | Folders | How often | Last successful check | Last result | State |
| --- | --- | --- | --- | --- | --- |
| [St Gallen: systematic collection (st.gallen.tlex.ch)](https://st.gallen.tlex.ch/) | `<act>/` | daily | 2026-11-27 06:52 UTC | no change | watched |

## The last 30 days

| Started (UTC) | Source | Read | Added | Changed | Removed | Not published (no reason) | Result | Commits |
| --- | --- | ---: | ---: | ---: | ---: | ---: | --- | ---: |
| [2026-11-27 06:50](checks/2026-11.md#ch-lexwork-st-gallen-city-20261127t065022z) | lexwork-st-gallen-city | 90 | 0 | 0 | 0 | 0 (0) | no change `verify-differ` | — |
| [2026-11-26 06:52](checks/2026-11.md#ch-lexwork-st-gallen-city-20261126t065213z) | lexwork-st-gallen-city | 108 | 0 | 0 | 0 | 0 (0) | no change `verify-differ` | — |
| [2026-11-25 07:57](checks/2026-11.md#ch-lexwork-st-gallen-city-20261125t075753z) | lexwork-st-gallen-city | 137 | 0 | 0 | 0 | 0 (0) | no change `verify-differ` | — |
| [2026-11-24 12:22](checks/2026-11.md#ch-lexwork-st-gallen-city-20261124t122250z) | lexwork-st-gallen-city | 305 | 72 | 0 | 0 | 0 (0) | changes found `verify-differ` | [245](https://github.com/lexifina/switzerland-st-gallen-city-law/compare/f6425b269cd5...0c8a1164b455) |

## Check it yourself

```
python tools/checktrail.py                      # the latest check of every source
python tools/checktrail.py --day 2026-11-23     # every check of a day
python tools/checktrail.py --act <id>           # when an act was seen and published
git log --grep='^Kind: check' --format='%ci %s'  # the checks in the history
```

Only the official publication has legal force; the texts here are copies for reading and searching.
