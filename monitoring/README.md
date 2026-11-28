<!-- lawwatch: written from data/checks by the check trail; edit the records, not this page -->

# Beobachtung: was gelesen wird und was daraus folgte

[English](README.en.md)

Wie global-law jedes Land beobachtet: [global-law monitoring/](https://github.com/lexifina/global-law/tree/main/monitoring). Diese Seite zeigt dasselbe nur für St Gallen: jedes Lesen einer amtlichen Quelle, wann, und was daraus folgte (Vorschriften hinzugefügt, geändert und entfernt). Maschinenlesbar in [data/checks/](../data/checks/) (JSON Lines, Schema `lexifina-check/1`), in `git log` als Commits mit `Kind: check` und Monat für Monat in [checks/](checks/).

**Letzte Prüfung:** 2026-11-28 08:14 UTC, St Gallen: Systematische Sammlung (st.gallen.tlex.ch): 82 Adressen gelesen; 0 hinzugefügt, 0 geändert, 0 entfernt; keine Änderung; 1 nicht veröffentlicht, davon 0 ohne Grund. Hinweise: `verify-differ`.

## Quellen

| Quelle | Ordner | Wie oft | Letzte erfolgreiche Prüfung | Letztes Ergebnis | Stand |
| --- | --- | --- | --- | --- | --- |
| [St Gallen: Systematische Sammlung (st.gallen.tlex.ch)](https://st.gallen.tlex.ch/) | `<act>/` | täglich | 2026-11-28 08:14 UTC | keine Änderung | beobachtet |

## Die letzten 30 Tage

| Beginn (UTC) | Quelle | Gelesen | Hinzugefügt | Geändert | Entfernt | Nicht veröffentlicht (ohne Grund) | Ergebnis | Commits |
| --- | --- | ---: | ---: | ---: | ---: | ---: | --- | ---: |
| [2026-11-28 08:13](checks/2026-11.md#ch-lexwork-st-gallen-city-20261128t081309z) | lexwork-st-gallen-city | 82 | 0 | 0 | 0 | 1 (0) | keine Änderung `verify-differ` | — |
| [2026-11-28 07:07](checks/2026-11.md#ch-lexwork-st-gallen-city-20261128t070751z) | lexwork-st-gallen-city | 0 | 0 | 0 | 0 | 0 (0) | die Prüfung ist fehlgeschlagen | — |
| [2026-11-28 06:38](checks/2026-11.md#ch-lexwork-st-gallen-city-20261128t063832z) | lexwork-st-gallen-city | 0 | 0 | 0 | 0 | 0 (0) | die Prüfung ist fehlgeschlagen | — |
| [2026-11-27 06:50](checks/2026-11.md#ch-lexwork-st-gallen-city-20261127t065022z) | lexwork-st-gallen-city | 90 | 0 | 0 | 0 | 0 (0) | keine Änderung `verify-differ` | — |
| [2026-11-26 06:52](checks/2026-11.md#ch-lexwork-st-gallen-city-20261126t065213z) | lexwork-st-gallen-city | 108 | 0 | 0 | 0 | 0 (0) | keine Änderung `verify-differ` | — |
| [2026-11-25 07:57](checks/2026-11.md#ch-lexwork-st-gallen-city-20261125t075753z) | lexwork-st-gallen-city | 137 | 0 | 0 | 0 | 0 (0) | keine Änderung `verify-differ` | — |
| [2026-11-24 12:22](checks/2026-11.md#ch-lexwork-st-gallen-city-20261124t122250z) | lexwork-st-gallen-city | 305 | 72 | 0 | 0 | 0 (0) | Änderungen gefunden `verify-differ` | [245](https://github.com/lexifina/switzerland-st-gallen-city-law/compare/f6425b269cd5...0c8a1164b455) |

## Selbst prüfen

```
python tools/checktrail.py                      # die letzte Prüfung jeder Quelle
python tools/checktrail.py --day 2026-11-23     # jede Prüfung eines Tages
python tools/checktrail.py --act <id>           # wann eine Vorschrift gesehen und veröffentlicht wurde
git log --grep='^Kind: check' --format='%ci %s'  # die Prüfungen in der Historie
```

Rechtskraft hat nur die amtliche Verkündung; die Texte hier sind Kopien zum Lesen und Suchen.
