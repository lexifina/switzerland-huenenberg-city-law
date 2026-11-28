<!-- lawwatch: written from data/checks by the check trail; edit the records, not this page -->

# Beobachtung: was gelesen wird und was daraus folgte

[English](README.en.md)

Wie global-law jedes Land beobachtet: [global-law monitoring/](https://github.com/lexifina/global-law/tree/main/monitoring). Diese Seite zeigt dasselbe nur für Huenenberg: jedes Lesen einer amtlichen Quelle, wann, und was daraus folgte (Vorschriften hinzugefügt, geändert und entfernt). Maschinenlesbar in [data/checks/](../data/checks/) (JSON Lines, Schema `lexifina-check/1`), in `git log` als Commits mit `Kind: check` und Monat für Monat in [checks/](checks/).

**Letzte Prüfung:** 2026-11-28 08:29 UTC, Huenenberg: Systematische Sammlung (huenenberg.tlex.ch): 20 Adressen gelesen; 0 hinzugefügt, 0 geändert, 0 entfernt; keine Änderung; 1 nicht veröffentlicht, davon 0 ohne Grund. Hinweise: `verify-differ`.

## Quellen

| Quelle | Ordner | Wie oft | Letzte erfolgreiche Prüfung | Letztes Ergebnis | Stand |
| --- | --- | --- | --- | --- | --- |
| [Huenenberg: Systematische Sammlung (huenenberg.tlex.ch)](https://huenenberg.tlex.ch/) | `<act>/` | täglich | 2026-11-28 08:29 UTC | keine Änderung | beobachtet |

## Die letzten 30 Tage

| Beginn (UTC) | Quelle | Gelesen | Hinzugefügt | Geändert | Entfernt | Nicht veröffentlicht (ohne Grund) | Ergebnis | Commits |
| --- | --- | ---: | ---: | ---: | ---: | ---: | --- | ---: |
| [2026-11-28 08:28](checks/2026-11.md#ch-lexwork-huenenberg-city-20261128t082848z) | lexwork-huenenberg-city | 20 | 0 | 0 | 0 | 1 (0) | keine Änderung `verify-differ` | — |
| [2026-11-28 07:10](checks/2026-11.md#ch-lexwork-huenenberg-city-20261128t071019z) | lexwork-huenenberg-city | 0 | 0 | 0 | 0 | 0 (0) | die Prüfung ist fehlgeschlagen | — |
| [2026-11-28 06:41](checks/2026-11.md#ch-lexwork-huenenberg-city-20261128t064101z) | lexwork-huenenberg-city | 0 | 0 | 0 | 0 | 0 (0) | die Prüfung ist fehlgeschlagen | — |
| [2026-11-27 07:06](checks/2026-11.md#ch-lexwork-huenenberg-city-20261127t070606z) | lexwork-huenenberg-city | 18 | 0 | 0 | 0 | 1 (0) | keine Änderung | — |
| [2026-11-26 07:11](checks/2026-11.md#ch-lexwork-huenenberg-city-20261126t071153z) | lexwork-huenenberg-city | 20 | 0 | 0 | 0 | 1 (0) | keine Änderung | — |
| [2026-11-25 08:19](checks/2026-11.md#ch-lexwork-huenenberg-city-20261125t081958z) | lexwork-huenenberg-city | 28 | 0 | 0 | 0 | 2 (0) | keine Änderung | — |
| [2026-11-24 12:43](checks/2026-11.md#ch-lexwork-huenenberg-city-20261124t124357z) | lexwork-huenenberg-city | 24 | 1 | 0 | 0 | 1 (0) | Änderungen gefunden | — |

## Selbst prüfen

```
python tools/checktrail.py                      # die letzte Prüfung jeder Quelle
python tools/checktrail.py --day 2026-11-23     # jede Prüfung eines Tages
python tools/checktrail.py --act <id>           # wann eine Vorschrift gesehen und veröffentlicht wurde
git log --grep='^Kind: check' --format='%ci %s'  # die Prüfungen in der Historie
```

Rechtskraft hat nur die amtliche Verkündung; die Texte hier sind Kopien zum Lesen und Suchen.
