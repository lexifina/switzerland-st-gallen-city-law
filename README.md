# St. Gallen (city): law history in git

Part of [lexifina/global-law](https://github.com/lexifina/global-law), one git history for every country's law: this is the law of St. Gallen, St. Gallen, Switzerland, which global-law reads at `switzerland/st-gallen/st-gallen/acts/`.

The municipal law of the city of St. Gallen (Stadt St.Gallen, canton of St. Gallen, Switzerland) as a git history: one file per article, one commit per amending act on the day it took effect, and the amending act as the commit's author. `git blame` names the act behind every paragraph; `git log` lists every change to an article; checking out a date gives the text in force that day.

It follows the shared design of [lexifina/global-law](https://github.com/lexifina/global-law). The law of the canton of St. Gallen is in [lexifina/switzerland-st-gallen-law](https://github.com/lexifina/switzerland-st-gallen-law); federal law is in [lexifina/switzerland-law](https://github.com/lexifina/switzerland-law).

The text is in German, exactly as the city publishes it.

## What this repository holds

101 acts with 196 versions so far: the Gemeindeordnung (the city's charter) first, then the city's other enactments in force (ordinances, regulations, tariffs and decisions), in the order of the systematic collection, added in parts of about 50. Agreements, concessions, directives and repealed acts are not included.

| Folder | Act | Versions | History |
| --- | --- | ---: | --- |
| `111-1/` | Gemeindeordnung (SRS 111.1) | 4 | oldest version available, then each consolidated version: 1 April 2017 to 1 August 2025 |
| `113-1/` | Reglement über das Stadtwappen (SRS 113.1) | 1 | one version (the oldest available), 31 December 1992 |
| `113-2/` | Reglement über die Stadtfarben (SRS 113.2) | 1 | one version (the oldest available), 31 December 1992 |
| `121-1-publikationsreglement/` | Reglement über die Amtlichen Bekanntmachungen und die Rechtssammlung (SRS 121.1) | 2 | oldest version available, then each consolidated version: 1 January 2002 to 1 June 2019 |
| `123-1/` | Reglement über die Informationsverbreitung und den Informationszugang (Kommunikationsreglement, KomR) (SRS 123.1) | 2 | as enacted, then each consolidated version: 1 January 2018 to 1 May 2026 |
| `125-1/` | Reglement über das Vertragsmanagement (SRS 125.1) | 2 | oldest version available, then each consolidated version: 1 January 2018 to 1 October 2022 |
| `127-1/` | Reglement über das Stadtarchiv St.Gallen (SRS 127.1) | 2 | oldest version available, then each consolidated version: 1 July 2005 to 1 May 2025 |
| `127-11/` | Benutzungsordnung für das Stadtarchiv St.Gallen (SRS 127.11) | 1 | as enacted, 1 May 2025 |
| `127-12-gebuhrentarif-stadtarchiv/` | Gebührentarif für Dienstleistungen des Stadtarchivs St.Gallen (SRS 127.12) | 1 | as enacted, 1 May 2025 |
| `131-1/` | Reglement über die Urnenabstimmungen (SRS 131.1) | 2 | as enacted, then each consolidated version: 1 January 2009 to 1 April 2024 |
| `131-2/` | Reglement über die Organisation und Geschäftsführung des Stimmbüros (SRS 131.2) | 1 | as enacted, 1 September 2007 |
| `131-3-transparenz-reglement-tr/` | Reglement über die Offenlegung der Finanzierung von politischen Parteien und Kampagnen (SRS 131.3) | 1 | as enacted, 1 February 2024 |
| `131-31-transparenz-vollzugsreglement-vtr/` | Vollzugsreglement zum Reglement über die Offenlegung der Finanzierung von politischen Parteien und Kampagnen (SRS 131.31) | 1 | as enacted, 1 February 2024 |
| `141-1/` | Partizipationsreglement (SRS 141.1) | 2 | as enacted, then each consolidated version: 1 July 2007 to 1 January 2021 |
| `151-1/` | Geschäftsreglement des Stadtparlaments (SRS 151.1) | 3 | oldest version available, then each consolidated version: 1 January 2018 to 1 November 2025 |
| `151-11/` | Reglement über die Entschädigung der Mitglieder des Stadtparlaments (SRS 151.11) | 2 | as enacted, then each consolidated version: 1 January 2021 to 1 January 2023 |
| `161-1/` | Reglement über die Ombudsperson (SRS 161.1) | 1 | one version (the oldest available), 1 April 2018 |
| `173-1-geschr/` | Geschäftsreglement des Stadtrats (SRS 173.1) | 7 | oldest version available, then each consolidated version: 1 January 2018 to 1 May 2026 |
| `173-4/` | Reglement über die Besoldung der Mitglieder des Stadtrates (SRS 173.4) | 1 | one version (the oldest available), 1 July 2005 |
| `181-1/` | Vertrag betreffend die Zusammenarbeit im Kindes- und Erwachsenenschutz (KES) (SRS 181.1) | 2 | oldest version available, then each consolidated version: 1 January 2018 to 1 January 2021 |
| `181-2-odr/` | Organisations- und Delegationsreglement (SRS 181.2) | 2 | oldest version available, then each consolidated version: 1 January 2018 to 1 May 2026 |
| `181-3/` | Reglement über die Delegation von Kompetenzen auf dem Gebiet des Zivilrechts (SRS 181.3) | 1 | one version (the oldest available), 1 January 2018 |
| `181-5/` | Reglement über die Entschädigung der Mitglieder von Verwaltungskommissionen (SRS 181.5) | 3 | as enacted, then each consolidated version: 1 January 2021 to 1 August 2026 |
| `181-8/` | Reglement über Benützung repräsentativer Säle und Flächen in Verwaltungsgebäuden (SRS 181.8) | 1 | one version (the oldest available), 1 January 2018 |
| `181-81/` | Gebührentarif für die Benützung repräsentativer Säle und Flächen in Verwaltungsgebäuden (SRS 181.81) | 1 | as enacted, 1 February 2016 |
| `183-1-rbsi/` | Reglement über den Betrieb und die Sicherheit der städtischen Informatik (SRS 183.1) | 4 | oldest version available, then each consolidated version: 1 January 2018 to 1 September 2026 |
| `183-3-rdbi/` | Reglement über die dienstliche Benutzung von Informatiksystemen (SRS 183.3) | 5 | oldest version available, then each consolidated version: 1 January 2018 to 1 September 2026 |
| `191-1-pr/` | Personalreglement (SRS 191.1) | 6 | oldest version available, then each consolidated version: 1 January 2019 to 1 September 2025 |
| `191-7/` | Reglement über den Fonds für Härtefälle (SRS 191.7) | 1 | one version (the oldest available), 1 January 2018 |
| `191-8/` | Reglement über den Hilfsfonds der Stadtpolizei (SRS 191.8) | 1 | one version (the oldest available), 1 January 2018 |
| `191-11-vzp/` | Vollzugsreglement zum Personalreglement (SRS 191.11) | 8 | oldest version available, then each consolidated version: 1 January 2019 to 1 May 2026 |
| `191-112/` | Reglement über die Beförderung bei der Stadtpolizei St.Gallen sowie bei Feuerwehr und Zivilschutz St.Gallen (SRS 191.112) | 2 | as enacted, then each consolidated version: 1 January 2017 to 1 April 2020 |
| `191-122-rwb/` | Weiterbildungsreglement (SRS 191.122) | 1 | one version (the oldest available), 1 January 2018 |
| `191-123-rmg/` | Reglement zum Mitarbeiterinnen- und Mitarbeitergespräch MAGplus (SRS 191.123) | 1 | one version (the oldest available), 1 January 2018 |
| `191-124/` | Reglement für Arbeitsverhältnisse mit besonderer Arbeitszeit (RBA) (SRS 191.124) | 4 | oldest version available, then each consolidated version: 1 January 2018 to 1 January 2025 |
| `191-125/` | Reglement für das Hauswartpersonal (SRS 191.125) | 1 | one version (the oldest available), 1 January 2018 |
| `191-126/` | Reglement über die Personalverbände und Personalausschüsse (SRS 191.126) | 1 | as enacted, 1 May 2015 |
| `191-127/` | Reglement über den Schutz vor Diskriminierung, sexueller Belästigung und Mobbing am Arbeitsplatz (SRS 191.127) | 1 | one version (the oldest available), 1 January 2018 |
| `192-1/` | Reglement über die Anstellungsbedingungen der Schulleitungen (SRS 192.1) | 2 | as enacted, then each consolidated version: 1 August 2007 to 1 February 2024 |
| `192-3/` | Urlaubsreglement für Lehrpersonen (SRS 192.3) | 3 | oldest version available, then each consolidated version: 1 May 2017 to 1 January 2023 |
| `194-1-pensionskassenreglement-pkr/` | Reglement über die Pensionskasse der Stadt St.Gallen (SRS 194.1) | 2 | oldest version available, then each consolidated version: 1 January 2018 to 1 January 2022 |
| `196-1/` | Reglement über Lohnfortzahlung bei Nichtwiederwahl oder vorzeitigem Rücktritt von Mitgliedern des Stadtrats und von durch das Stadtparlament gewählten Angestellten (SRS 196.1) | 2 | oldest version available, then each consolidated version: 1 January 2018 to 1 January 2021 |
| `211-1-schulordnung/` | Reglement über die städtischen Schulen (SRS 211.1) | 2 | oldest version available, then each consolidated version: 1 January 2017 to 1 August 2020 |
| `211-13-zure-schule/` | Reglement über die Zuständigkeit der Verwaltung im Bereich der Schule (SRS 211.13) | 2 | as enacted, then each consolidated version: 1 August 2017 to 1 January 2023 |
| `211-14/` | Reglement über die Talentschule (SRS 211.14) | 2 | oldest version available, then each consolidated version: 1 May 2017 to 1 January 2023 |
| `211-33/` | Urlaubsreglement für Schülerinnen und Schüler (SRS 211.33) | 3 | oldest version available, then each consolidated version: 1 January 2010 to 1 July 2025 |
| `211-41/` | Reglement über die besonderen Unterrichtswochen (SRS 211.41) | 1 | one version (the oldest available), 1 August 2018 |
| `211-51/` | Reglement über die Schulgelder an Kindergärten, Volksschulen und an der Musikschule (SRS 211.51) | 1 | one version (the oldest available), 1 May 2017 |
| `211-73/` | Reglement über den Schulfürsorgefonds (SRS 211.73) | 2 | oldest version available, then each consolidated version: 1 October 2017 to 1 August 2019 |
| `211-74/` | Reglement über den Fonds für Ferienheime, Ferienlager und Ferienreisen (SRS 211.74) | 1 | one version (the oldest available), 1 May 2017 |
| `211-75/` | Reglement über den Ernst Schnering-Graf Fonds (SRS 211.75) | 1 | one version (the oldest available), 1 July 2017 |
| `211-511/` | Gebührentarif für den Besuch der städtischen Volksschule und der Musikschule (SRS 211.511) | 5 | as enacted, then each consolidated version: 1 August 2018 to 1 January 2023 |
| `216-1/` | Reglement über die Tagesbetreuung (SRS 216.1) | 4 | as enacted, then each consolidated version: 1 January 2015 to 1 January 2023 |
| `216-3/` | Reglement über die Musikschule (SRS 216.3) | 3 | oldest version available, then each consolidated version: 1 May 2017 to 1 January 2023 |
| `216-5/` | Reglement über die Kurse für freiwillige Handarbeit (SRS 216.5) | 2 | oldest version available, then each consolidated version: 1 July 2017 to 1 October 2023 |
| `216-6/` | Reglement über die Kinder- und Jugendzahnklinik (SRS 216.6) | 2 | as enacted, then each consolidated version: 1 November 2017 to 1 January 2025 |
| `216-11/` | Tarifreglement Tagesbetreuung (SRS 216.11) | 2 | as enacted, then each consolidated version: 1 January 2015 to 1 August 2019 |
| `216-51/` | Gebührentarif für die Freizeitangebote für Kinder und Jugendliche (SRS 216.51) | 1 | as enacted, 1 October 2023 |
| `218-11/` | Tarifreglement für die SpiKi-Spielgruppen (SRS 218.11) | 1 | one version (the oldest available), 1 January 2018 |
| `218-12/` | Tarifreglement für Kindertagesstätten mit städtisch subventionierten Betreuungsplätzen (SRS 218.12) | 3 | as enacted, then each consolidated version: 1 August 2019 to 1 June 2024 |
| `231-1/` | Reglement über die Benützung der Stadtbibliothek (SRS 231.1) | 1 | one version (the oldest available), 1 May 2017 |
| `231-11/` | Gebührentarif für die Benützung der Stadtbibliothek Katharinen (SRS 231.11) | 1 | one version (the oldest available), 1 August 2017 |
| `251-1/` | Reglement über die Verleihung des Kulturpreises und des Anerkennungspreises sowie die Ausrichtung von Förderpreisen für kulturelles Schaffen (SRS 251.1) | 2 | as enacted, then each consolidated version: 1 October 1995 to 1 January 2024 |
| `251-2/` | Reglement über die Kommission für Kulturförderung (SRS 251.2) | 1 | as enacted, 1 January 2024 |
| `251-3/` | Reglement für die Benützung des Zentrums "Reithalle" (SRS 251.3) | 2 | oldest version available, then each consolidated version: 1 January 2018 to 1 October 2023 |
| `251-4/` | Reglement über die Kommission Kunst und Raum (SRS 251.4) | 1 | as enacted, 1 January 2024 |
| `251-5/` | Reglement über die Ausrichtung von Beiträgen an kulturelle Aktivitäten (SRS 251.5) | 2 | oldest version available, then each consolidated version: 1 January 2018 to 1 January 2024 |
| `251-6/` | Reglement über den Kulturfonds (SRS 251.6) | 1 | one version (the oldest available), 1 January 2018 |
| `251-8/` | Reglement über Beiträge an die Kosten der Benutzung des Areals der Olma Messen St.Gallen durch nicht-kommerzielle Veranstaltende (SRS 251.8) | 1 | as enacted, 1 January 2012 |
| `251-81/` | Vollzugsreglement zum Reglement über Beiträge an die Kosten der Benutzung des Areals der Olma Messen St.Gallen durch nicht-kommerzielle Veranstaltende (SRS 251.81) | 1 | one version (the oldest available), 1 July 2016 |
| `271-1/` | Reglement über die Nutzung der Schul-, Sport- und Freizeitanlagen (SRS 271.1) | 2 | as enacted, then each consolidated version: 1 August 2020 to 1 October 2025 |
| `271-11-vzr-anlagen/` | Vollzugsreglement zum Reglement über die Nutzung der Schul-, Sport- und Freizeitanlagen (SRS 271.11) | 1 | as enacted, 1 October 2023 |
| `271-111/` | Gebührentarif für die Nutzung der Schul-, Sport- und Freizeitanlagen (SRS 271.111) | 1 | as enacted, 1 October 2023 |
| `321-2-sono-fonds/` | Reglement über den Fonds zur Förderung der Arbeitsintegration (SRS 321.2) | 1 | as enacted, 1 February 2022 |
| `321-5/` | Reglement über die städtischen Leistungen zu Gunsten von Einrichtungen zur Betreuung und Pflege von Betagten (SRS 321.5) | 1 | as enacted, 1 January 2017 |
| `321-9/` | Reglement für die sozialen Einrichtungen der Stadt St.Gallen (SRS 321.9) | 3 | as enacted, then each consolidated version: 1 July 1998 to 1 January 2024 |
| `321-11/` | Reglement über den Billwiller-Haltmeyer-Fonds (SRS 321.11) | 1 | one version (the oldest available), 1 January 2018 |
| `321-12/` | Reglement über den Härtsch-Eberli-Fonds (SRS 321.12) | 1 | one version (the oldest available), 1 January 2018 |
| `321-13/` | Reglement über den kindes- und erwachsenenschutzrechtlichen Fonds der Stadt St.Gallen (SRS 321.13) | 2 | oldest version available, then each consolidated version: 1 January 2018 to 1 October 2024 |
| `321-14/` | Reglement über den Fels'schen Stipendienfonds (SRS 321.14) | 1 | one version (the oldest available), 1 January 2018 |
| `321-15/` | Reglement über den Stadelmann-Fonds (SRS 321.15) | 1 | one version (the oldest available), 1 January 2018 |
| `321-16/` | Reglement über den Thomann-Bittel-Fonds (SRS 321.16) | 1 | one version (the oldest available), 1 January 2018 |
| `321-17/` | Reglement über den Dr. Seel-Fonds (SRS 321.17) | 1 | one version (the oldest available), 1 January 2018 |
| `321-18/` | Reglement über den Simon Rothschild-Fonds (SRS 321.18) | 1 | one version (the oldest available), 1 January 2018 |
| `321-19/` | Reglement über den Lilly Moll-Fonds (SRS 321.19) | 1 | one version (the oldest available), 1 January 2018 |
| `321-93-benutzungsreglement-ufo-bwg/` | Reglement für die Benutzung der Unterkunft für Obdachlose (UFO) und des Betreuten Wohnens Grünhalde (BWG) (SRS 321.93) | 2 | as enacted, then each consolidated version: 1 January 1999 to 1 January 2026 |
| `321-931-gebuhrentarif-ufo-bwg/` | Gebührentarif für die Benutzung der Unterkunft für Obdachlose (UFO) und des Betreuten Wohnens Grünhalde (BWG) (SRS 321.931) | 2 | oldest version available, then each consolidated version: 1 January 2017 to 1 January 2026 |
| `331-1/` | Reglement zur Förderung gesellschaftsrelevanter Projekte und Veranstaltungen (SRS 331.1) | 2 | oldest version available, then each consolidated version: 1 January 2018 to 1 January 2025 |
| `411-1/` | Vereinbarung über die Zusammenarbeit im Bereich Bevölkerungsschutz (SRS 411.1) | 4 | oldest version available, then each consolidated version: 1 April 2005 to 1 January 2023 |
| `412-1/` | Vereinbarung über die Erfüllung polizeilicher Aufgaben auf dem Gebiet der Stadt St.Gallen (SRS 412.1) | 1 | as enacted, 1 January 2014 |
| `412-2/` | Organisations- und Dienstreglement der Stadtpolizei (SRS 412.2) | 3 | oldest version available, then each consolidated version: 1 April 2018 to 1 January 2025 |
| `412-4/` | Reglement über die Videoüberwachung auf öffentlichem Grund (SRS 412.4) | 2 | as enacted, then each consolidated version: 1 October 2007 to 1 October 2025 |
| `412-5/` | Reglement über die Videoüberwachung im Umfeld der Arena St.Gallen (SRS 412.5) | 2 | oldest version available, then each consolidated version: 1 August 2009 to 1 October 2025 |
| `412-6/` | Reglement über Massnahmen gegen Gewalt anlässlich von Sportveranstaltungen (SRS 412.6) | 1 | as enacted, 1 January 2017 |
| `412-7/` | Reglement betreffend die Übermittlung von Gefahrenmeldungen an die Alarmempfangsanlage der Stadtpolizei (SRS 412.7) | 1 | one version (the oldest available), 1 July 2001 |
| `412-8/` | Reglement über Fundsachen (SRS 412.8) | 2 | oldest version available, then each consolidated version: 1 January 2014 to 1 January 2021 |
| `412-9/` | Hundereglement (SRS 412.9) | 2 | oldest version available, then each consolidated version: 1 January 2018 to 1 November 2020 |
| `412-11/` | Polizeireglement (SRS 412.11) | 3 | oldest version available, then each consolidated version: 1 March 2011 to 1 October 2025 |
| `412-51/` | Reglement über die Videoüberwachung der Parkgaragen Kreuzbleiche und Rathaus (SRS 412.51) | 2 | as enacted, then each consolidated version: 1 January 2018 to 1 October 2025 |
| `412-111/` | Reglement über die Grundsätze der Erhebung von Gebühren durch die Stadtpolizei (SRS 412.111) | 1 | as enacted, 1 January 2015 |
| `412-112/` | Gebührentarif der Stadtpolizei (SRS 412.112) | 4 | oldest version available, then each consolidated version: 1 October 2016 to 1 January 2026 |

## Source

The SRS (systematic collection) of the city, published by the city at <https://st.gallen.tlex.ch/>. For each act it gives every consolidated version it holds, with the day each version took effect, and a change table listing each amendment: its decision date, the day it took effect, the provision it touched and its entry in the chronological collection (CRS). Annexes the collection publishes only as separate PDF files are not included.

## Dates

- Each commit is dated at **noon, Europe/Zurich, on the day the version took effect**, as the collection gives it ("in Kraft seit / von"). The decision date of each amending act is the `Enacted:` trailer.
- An act's first commit is its oldest version in the collection. It is credited to the act as enacted only when the change table shows no amendment in force before it; otherwise it is the "oldest version available", naming the earlier amendments.
- Versions that take effect after the retrieval day are on the `zukunft` branch, never merged into `main`.
- `--before="YYYY-MM-DD"` alone uses your clock's time of day; use `T23:59:59Z` or `tools/on.py`.

## Files

`<act>/art-005.md` is Art. 5 (or § 5), `art-005a.md` Art. 5a; `ingress.md` holds the title, date and preamble; `gliederung.md` the section headings; `schluss.md` the closing formula and signatures. One paragraph or list item per line. Amendment markers (`*`), footnote numbers and the "Stand" date are left out.

## How it is checked

- Every version of every act is read back from git on the day it took effect and on the day before (`tools/check_repo.py`); both must match `corpus.json`.
- The letters and digits of every version equal those of the city's own text of that version, and every article's text appears in it in order.
- Health checks: no merge commits, commit dates never go backwards, nothing dated in the future, and every commit's trailers parse.

## What "author" means

The author of a commit is the amending act, named by its entry in the chronological collection (CRS), with an e-mail address that cannot exist (`<act key>@st.gallen.tlex.ch.invalid`). Where one version holds changes by several amending acts and the change table does not say which provision each one touched, the commit names them all. The committer is always Lexifina.

## Limits

This is not an official publication. The binding text is the one the city publishes as binding. The history starts with the oldest consolidated version the collection holds for each act, which for many acts is later than the act's enactment. Only the acts listed above are included.
