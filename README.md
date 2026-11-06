# Hünenberg (city): law history in git

Part of [lexifina/global-law](https://github.com/lexifina/global-law), one git history for every country's law: this is the law of Huenenberg, Zug, Switzerland, which global-law reads at `switzerland/zug/huenenberg/acts/`.

The municipal law of the municipality of Hünenberg (Gemeinde Hünenberg, canton of Zug, Switzerland) as a git history: one file per article, one commit per amending act on the day it took effect, and the amending act as the commit's author. `git blame` names the act behind every paragraph; `git log` lists every change to an article; checking out a date gives the text in force that day.

It follows the shared design of [lexifina/global-law](https://github.com/lexifina/global-law). The law of the canton of Zug is in [lexifina/switzerland-zug-law](https://github.com/lexifina/switzerland-zug-law); federal law is in [lexifina/switzerland-law](https://github.com/lexifina/switzerland-law).

The text is in German, exactly as the municipality publishes it.

## What this repository holds

49 acts with 85 versions so far: the Gemeindeordnung (the municipality's charter) first, then the municipality's other enactments in force (ordinances, regulations, tariffs and decisions), in the order of the systematic collection, added in parts of about 50. Agreements, concessions, directives and repealed acts are not included.

| Folder | Act | Versions | History |
| --- | --- | ---: | --- |
| `1-1-1/` | Gemeindeordnung (SRS 1.1-1) | 2 | as enacted, then each consolidated version: 1 January 2017 to 1 September 2024 |
| `1-2-1/` | Benutzungsordnung Archiv für verwaltungsexterne Benutzerinnen und Benutzer (SRS 1.2-1) | 1 | as enacted, 1 August 2011 |
| `1-6-1-entschadigungsreglement/` | Reglement über die Entschädigung von Behördenmitgliedern und gemeindlichen Funktionärinnen und Funktionären (SRS 1.6-1) | 4 | oldest version available, then each consolidated version: 16 January 2019 to 1 January 2025 |
| `1-6-2/` | Reglement über die Bestellung von Kommissionen und Arbeitsgruppen (SRS 1.6-2) | 1 | as enacted, 3 May 2016 |
| `1-6-3/` | Richtlinien für die Beanspruchung des Pensenpools des Gemeinderates (SRS 1.6-3) | 2 | oldest version available, then each consolidated version: 26 October 2010 to 6 December 2022 |
| `1-6-4/` | Sitzungsordnung des Gemeinderates (SRS 1.6-4) | 3 | as enacted, then each consolidated version: 1 June 2018 to 4 April 2023 |
| `1-7-1-personalreglement/` | Reglement über das Arbeitsverhältnis des Gemeindepersonals (SRS 1.7-1) | 2 | oldest version available, then each consolidated version: 1 March 2019 to 1 January 2024 |
| `1-7-2/` | Geschäftsordnung Geschäftsleitung (SRS 1.7-2) | 2 | as enacted, then each consolidated version: 1 August 2012 to 4 April 2023 |
| `1-7-3/` | Entschädigungsverordnung (SRS 1.7-3) | 7 | oldest version available, then each consolidated version: 1 October 2020 to 1 October 2026 |
| `1-7-4/` | Arbeitszeitverordnung (SRS 1.7-4) | 2 | as enacted, then each consolidated version: 1 January 2014 to 1 January 2024 |
| `2-1-1/` | Verordnung über die Gebühren im Beurkundungswesen (SRS 2.1-1) | 1 | one version (the oldest available), 1 January 2016 |
| `4-1-1-kinderbetreuungsreglement/` | Reglement zur Regelung der Kinderbetreuung auf dem Gemeindegebiet (SRS 4.1-1) | 1 | as enacted, 1 August 2016 |
| `4-1-1-1/` | Verordnung betreffend Finanzierung familienergänzende Kinderbetreuung (SRS 4.1-1.1) | 3 | as enacted, then each consolidated version: 1 August 2020 to 1 August 2026 |
| `4-1-1-2/` | Verordnung betreffend Betreuung Schulkinder (SRS 4.1-1.2) | 2 | as enacted, then each consolidated version: 1 August 2025 to 1 August 2026 |
| `4-2-1/` | Schul- und Disziplinarordnung der Schulen Hünenberg (SRS 4.2-1) | 2 | as enacted, then each consolidated version: 1 August 2009 to 1 August 2021 |
| `4-2-2/` | Richtlinien für Klassenlager der Schulen Hünenberg (SRS 4.2-2) | 1 | one version (the oldest available), 1 January 2022 |
| `4-2-3/` | Richtlinien für Schneesportlager der Schulen Hünenberg (SRS 4.2-3) | 2 | oldest version available, then each consolidated version: 1 January 2022 to 1 January 2024 |
| `4-2-4/` | Reglement über den Schulzahnarzt-Dienst (SRS 4.2-4) | 2 | as enacted, then each consolidated version: 1 August 2003 to 1 August 2022 |
| `4-2-4-1/` | Verordnung zum Reglement über den Schulzahnarzt-Dienst (SRS 4.2-4.1) | 1 | as enacted, 1 August 2022 |
| `4-3-1/` | Reglement der Musikschule Hünenberg (SRS 4.3-1) | 2 | as enacted, then each consolidated version: 1 August 2004 to 1 August 2022 |
| `4-3-1-1/` | Verordnung Musikschule (SRS 4.3-1.1) | 2 | as enacted, then each consolidated version: 1 August 2004 to 1 August 2022 |
| `4-3-1-2/` | Tarifordnung der Musikschule (SRS 4.3-1.2) | 3 | as enacted, then each consolidated version: 1 August 2022 to 1 January 2026 |
| `4-3-2/` | Richtlinien Musiklager (SRS 4.3-2) | 1 | as enacted, 1 January 2009 |
| `5-3-1/` | Feuerwehrreglement (SRS 5.3-1) | 1 | one version (the oldest available), 1 May 2010 |
| `6-4-1/` | Gebührenordnung Festmaterial (SRS 6.4-1) | 2 | as enacted, then each consolidated version: 30 May 2008 to 7 June 2026 |
| `6-5-1/` | Verordnung über die Gewährung von Beiträgen (SRS 6.5-1) | 1 | as enacted, 1 January 2008 |
| `6-5-2/` | Richtlinien über die gemeindlichen Ehrungen (SRS 6.5-2) | 1 | as enacted, 1 March 2019 |
| `6-5-3/` | Richtlinien für den Ankauf von Kunstwerken (SRS 6.5-3) | 1 | as enacted, 1 October 2015 |
| `6-6-1-benutzungsverordnung-vbo/` | Verordnung über die Benutzung von öffentlichen Räumen, Anlagen und Plätzen der Einwohnergemeinde Hünenberg (SRS 6.6-1) | 2 | oldest version available, then each consolidated version: 1 November 2019 to 1 March 2024 |
| `6-6-1-1/` | Gebührenordnung von öffentlichen Räumen, Anlagen und Plätzen (SRS 6.6-1.1) | 2 | as enacted, then each consolidated version: 1 October 2018 to 1 January 2026 |
| `6-6-2/` | Benützungsreglement Zentrum «Heinrich von Hünenberg» und Dorfplatz (SRS 6.6-2) | 2 | oldest version available, then each consolidated version: 1 January 2014 to 1 January 2026 |
| `6-6-3/` | Betriebsreglement Hundeausbildungsanlage Böschhof «Hundeweid» (SRS 6.6-3) | 1 | as enacted, 8 July 2014 |
| `6-9-1-vmr/` | Vermietungsrichtlinien (SRS 6.9-1) | 1 | as enacted, 1 October 2026 |
| `7-1-1/` | Bauordnung (SRS 7.1-1) | 3 | as enacted, then each consolidated version: 1 January 2016 to 7 January 2025 |
| `7-1-1-1/` | Gebührenordnung zur Bauordnung (SRS 7.1-1.1) | 1 | one version (the oldest available), 1 January 2016 |
| `7-1-2/` | Reklamereglement (SRS 7.1-2) | 1 | as enacted, 1 October 2008 |
| `7-3-1/` | Reglement über die Lärmbekämpfung (SRS 7.3-1) | 1 | as enacted, 11 September 1972 |
| `7-3-2/` | Umwelt- und Energiereglement (SRS 7.3-2) | 1 | as enacted, 1 January 2024 |
| `7-3-3/` | Umwelt- und Energieverordnung (SRS 7.3-3) | 1 | as enacted, 1 January 2024 |
| `7-4-2/` | Abwasserreglement (SRS 7.4-2) | 1 | as enacted, 1 January 2004 |
| `7-4-2-1/` | Verordnung zum Abwasserreglement (SRS 7.4-2.1) | 2 | as enacted, then each consolidated version: 1 January 2016 to 1 October 2024 |
| `7-6-1/` | Strassenreglement (SRS 7.6-1) | 1 | as enacted, 1 October 1999 |
| `7-7-1/` | Gebührenordnung für die Bewirtschaftung der öffentlichen Parkplätze in der Gemeinde Hünenberg (SRS 7.7-1) | 1 | as enacted, 1 May 2021 |
| `7-7-2/` | Betriebsreglement Bootsstationierungsanlage (SRS 7.7-2) | 3 | as enacted, then each consolidated version: 14 June 2011 to 20 October 2026 |
| `7-7-3/` | Verordnung über die temporäre politische Aussenwerbung (SRS 7.7-3) | 1 | as enacted, 20 October 2021 |
| `8-2-1/` | Bestattungs- und Friedhofreglement (SRS 8.2-1) | 1 | as enacted, 1 January 2013 |
| `8-2-1-1/` | Vollziehungsverordnung zum Bestattungs- und Friedhofreglement (SRS 8.2-1.1) | 2 | as enacted, then each consolidated version: 1 January 2013 to 1 June 2024 |
| `8-3-1-hundereglement/` | Reglement über das Halten von Hunden und die Erhebung der Hundesteuer (SRS 8.3-1) | 1 | one version (the oldest available), 1 January 2009 |
| `9-4-1/` | Verordnung betreffend Erhebung einer Beherbergungsabgabe (SRS 9.4-1) | 1 | as enacted, 1 January 2015 |

## Source

The SRS (systematic collection) of the municipality, published by the municipality at <https://huenenberg.tlex.ch/>. For each act it gives every consolidated version it holds, with the day each version took effect, and a change table listing each amendment: its decision date, the day it took effect, the provision it touched and its entry in the chronological collection (CRS). Annexes the collection publishes only as separate PDF files are not included.

## Dates

- Each commit is dated at **noon, Europe/Zurich, on the day the version took effect**, as the collection gives it ("in Kraft seit / von"). The decision date of each amending act is the `Enacted:` trailer.
- An act's first commit is its oldest version in the collection. It is credited to the act as enacted only when the change table shows no amendment in force before it; otherwise it is the "oldest version available", naming the earlier amendments.
- Versions that take effect after the retrieval day are on the `zukunft` branch, never merged into `main`.
- `--before="YYYY-MM-DD"` alone uses your clock's time of day; use `T23:59:59Z` or `tools/on.py`.

## Files

`<act>/art-005.md` is Art. 5 (or § 5), `art-005a.md` Art. 5a; `ingress.md` holds the title, date and preamble; `gliederung.md` the section headings; `schluss.md` the closing formula and signatures. One paragraph or list item per line. Amendment markers (`*`), footnote numbers and the "Stand" date are left out.

## How it is checked

- Every version of every act is read back from git on the day it took effect and on the day before (`tools/check_repo.py`); both must match `corpus.json`.
- The letters and digits of every version equal those of the municipality's own text of that version, and every article's text appears in it in order.
- Health checks: no merge commits, commit dates never go backwards, nothing dated in the future, and every commit's trailers parse.

## What "author" means

The author of a commit is the amending act, named by its entry in the chronological collection (CRS), with an e-mail address that cannot exist (`<act key>@huenenberg.tlex.ch.invalid`). Where one version holds changes by several amending acts and the change table does not say which provision each one touched, the commit names them all. The committer is always Lexifina.

## Limits

This is not an official publication. The binding text is the one the municipality publishes as binding. The history starts with the oldest consolidated version the collection holds for each act, which for many acts is later than the act's enactment. Only the acts listed above are included.
