# Ilanz/Glion (city): law history in git

The municipal law of the municipality of Ilanz/Glion (Gemeinde Ilanz/Glion, canton of Graubünden, Switzerland) as a git history: one file per article, one commit per amending act on the day it took effect, and the amending act as the commit's author. `git blame` names the act behind every paragraph; `git log` lists every change to an article; checking out a date gives the text in force that day.

It follows the shared design of [lexifina/global-law](https://github.com/lexifina/global-law). The law of the canton of Graubünden is in [lexifina/switzerland-graubunden-law](https://github.com/lexifina/switzerland-graubunden-law); federal law is in [lexifina/switzerland-law](https://github.com/lexifina/switzerland-law).

The text is in German, exactly as the municipality publishes it.

## What this repository holds

62 acts with 115 versions so far: the Gemeindeordnung (the municipality's charter) first, then the municipality's other enactments in force (ordinances, regulations, tariffs and decisions), in the order of the systematic collection, added in parts of about 50. Agreements, concessions, directives and repealed acts are not included.

| Folder | Act | Versions | History |
| --- | --- | ---: | --- |
| `11-1-gemeindeverfassung/` | Verfassung der Gemeinde Ilanz/Glion (RIG 11.1) | 1 | as enacted, 1 January 2014 |
| `12-1-amtssprachengesetz-asg/` | Gesetz über die Amtssprachen der Gemeinde Ilanz/Glion (RIG 12.1) | 1 | as enacted, 1 August 2015 |
| `13-1-parlamentsgesetz-parlg/` | Gesetz über das Gemeindeparlament der Gemeinde Ilanz/Glion (RIG 13.1) | 2 | as enacted, then each consolidated version: 1 January 2014 to 1 April 2019 |
| `13-2-organisationsgesetz-ogg/` | Organisationsgesetz der Gemeinde Ilanz/Glion (RIG 13.2) | 4 | as enacted, then each consolidated version: 15 August 2014 to 1 January 2022 |
| `13-11-parlamentsordnung-parlo/` | Geschäftsordnung des Gemeindeparlaments der Gemeinde Ilanz/Glion (RIG 13.11) | 4 | as enacted, then each consolidated version: 1 January 2014 to 1 April 2025 |
| `13-21-organisationsverordnung/` | Organisationsverordnung der Gemeinde Ilanz/Glion (RIG 13.21) | 2 | as enacted, then each consolidated version: 1 June 2015 to 1 August 2021 |
| `13-22-compliance-verordnung-cv/` | Verordnung zur Vermeidung von Interessenkonflikten und zum Verhaltenskodex der Gemeinde Ilanz/Glion (RIG 13.22) | 1 | as enacted, 1 March 2023 |
| `13-23-bibliotheksverordnung-bibliov/` | Verordnung zur Schul- und Gemeindebibliothek Ilanz/Glion (RIG 13.23) | 1 | as enacted, 1 January 2024 |
| `13-31-verordnung-jugendkommission-jukov/` | Verordnung über die Jugendkommission der Gemeinde Ilanz/Glion (RIG 13.31) | 2 | as enacted, then each consolidated version: 1 October 2022 to 1 October 2026 |
| `14-1-entschadigungsgesetz-entg/` | Gesetz über die Entschädigung von Behörden und Kommissionen der Gemeinde Ilanz/Glion (RIG 14.1) | 3 | as enacted, then each consolidated version: 1 May 2013 to 1 January 2025 |
| `15-1-einburgerungsgesetz-einbg/` | Gesetz über die Einbürgerung in die Gemeinde Ilanz/Glion (RIG 15.1) | 1 | as enacted, 1 January 2018 |
| `21-1-personalgesetz-persg/` | Personalgesetz der Gemeinde Ilanz/Glion (RIG 21.1) | 1 | as enacted, 1 January 2026 |
| `21-12-arbeitszeitverordnung-azv/` | Arbeitszeitverordnung der Gemeinde Ilanz/Glion (RIG 21.12) | 1 | as enacted, 1 January 2026 |
| `32-12-wohnkostenverordnung-wkv/` | Verordnung über die Wohnkosten von bedürftigen Personen der Gemeinde Ilanz/Glion (RIG 32.12) | 1 | as enacted, 1 January 2024 |
| `33-1-bestattungsgesetz-bestg/` | Gesetz über das Bestattungs- und Friedhofwesen der Gemeinde Ilanz/Glion (RIG 33.1) | 1 | as enacted, 1 January 2016 |
| `33-11-bestattungsverordnung-bestv/` | Verordnung über das Bestattungs- und Friedhofwesen der Gemeinde Ilanz/Glion (RIG 33.11) | 1 | as enacted, 1 January 2016 |
| `41-1-polizeigesetz-pg/` | Polizeigesetz der Gemeinde Ilanz/Glion (RIG 41.1) | 3 | as enacted, then each consolidated version: 1 September 2014 to 12 October 2021 |
| `41-12-ordnungsbussenverordnung-obv/` | Verordnung über die Ordnungsbussen der Gemeinde Ilanz/Glion (RIG 41.12) | 2 | as enacted, then each consolidated version: 1 December 2014 to 1 July 2021 |
| `42-1-feuerwehrgesetz-fwg/` | Feuerwehrgesetz der Gemeinde Ilanz/Glion (RIG 42.1) | 4 | as enacted, then each consolidated version: 1 January 2014 to 1 January 2024 |
| `42-11-feuerwehrverordnung-fwv/` | Feuerwehrverordnung der Gemeinde Ilanz/Glion (RIG 42.11) | 4 | as enacted, then each consolidated version: 1 March 2014 to 1 January 2024 |
| `43-1-bevolkerungsschutzgesetz-bsg/` | Gesetz über den Bevölkerungsschutz der Gemeinde Ilanz/Glion (RIG 43.1) | 1 | as enacted, 1 January 2022 |
| `43-11-bevolkerungsschutzverordnung-bevsv/` | Verordnung über den Bevölkerungsschutz der Gemeinde Ilanz/Glion (RIG 43.11) | 1 | as enacted, 1 January 2022 |
| `51-1-steuergesetz-stg/` | Steuergesetz der Gemeinde Ilanz/Glion (RIG 51.1) | 4 | as enacted, then each consolidated version: 1 January 2014 to 1 January 2027 |
| `52-1-gebuhrengesetz-gebg/` | Gesetz über die allgemeinen Gebühren der Gemeinde Ilanz/Glion (RIG 52.1) | 1 | as enacted, 15 August 2014 |
| `52-11-gebuhrentarifverordnung-gebv/` | Verordnung über die Gebührentarife der Gemeinde Ilanz/Glion (RIG 52.11) | 4 | as enacted, then each consolidated version: 1 April 2015 to 1 September 2022 |
| `52-12-verordnung-digitale-ortseingangstafeln-digortv/` | Verordnung über die Nutzung der digitalen Ortseingangstafeln der Gemeinde Ilanz/Glion (RIG 52.12) | 1 | as enacted, 1 May 2021 |
| `53-1-immobiliengesetz-immog/` | Gesetz über die Entwicklung und die Bewirtschaftung der Immobilien der Gemeinde Ilanz/Glion (RIG 53.1) | 2 | as enacted, then each consolidated version: 1 January 2021 to 1 January 2022 |
| `53-11-immobilienverordnung-i-immov-i/` | Verordnung über die Nutzung von Immobilien der Gemeinde Ilanz/Glion (RIG 53.11) | 5 | as enacted, then each consolidated version: 1 November 2014 to 1 October 2026 |
| `53-12-immobilienverordnung-ii-immov-ii/` | Verordnung über die Veräusserung und Vermietung von Immobilien der Gemeinde Ilanz/Glion (RIG 53.12) | 2 | as enacted, then each consolidated version: 1 January 2022 to 1 October 2026 |
| `61-1-schulgesetz-schg/` | Schulgesetz der Gemeinde Ilanz/Glion (RIG 61.1) | 2 | as enacted, then each consolidated version: 1 August 2014 to 1 February 2016 |
| `62-1-sprachforderungsgesetz-sprachg/` | Gesetz zur Förderung der romanischen Sprache der Gemeinde Ilanz/Glion (RIG 62.1) | 1 | as enacted, 1 August 2015 |
| `63-1-kulturforderungsgesetz-kfg/` | Gesetz über die Förderung der Kultur der Gemeinde Ilanz/Glion (RIG 63.1) | 1 | as enacted, 1 January 2023 |
| `63-11-kulturforderungsverordnung-kfv/` | Verordnung über die Förderung der Kultur der Gemeinde Ilanz/Glion (RIG 63.11) | 3 | as enacted, then each consolidated version: 1 January 2023 to 1 January 2026 |
| `64-1-gesundheitsgesetz-gesg/` | Gesetz über die Förderung der Gesundheit, Prävention und Sport der Gemeinde Ilanz/Glion (RIG 64.1) | 1 | as enacted, 1 January 2023 |
| `64-11-gesundheitsverordnung-gesv/` | Verordnung über die Förderung der Gesundheit, Prävention und Sport der Gemeinde Ilanz/Glion (RIG 64.11) | 2 | as enacted, then each consolidated version: 1 January 2023 to 1 July 2024 |
| `72-1-baugesetz-baug/` | Baugesetz der Gemeinde Ilanz/Glion (RIG 72.1) | 2 | as enacted, then each consolidated version: 12 October 2021 to 13 February 2023 |
| `72-2-ggbg/` | Gebührengesetz zum Baugesetz (RIG 72.2) | 2 | as enacted, then each consolidated version: 1 January 2019 to 1 December 2019 |
| `72-3-sbauvsq/` | Sonderbauvorschriften Spitalquartier (RIG 72.3) | 1 | as enacted, 26 September 2017 |
| `72-11-verordnung-zum-baugesetz-bauv/` | Verordnung zum Baugesetz der Gemeinde Ilanz/Glion (RIG 72.11) | 1 | as enacted, 1 November 2022 |
| `73-2-wasserversorgungsgesetz-wvg/` | Gesetz über die Wasserversorgung der Gemeinde Ilanz/Glion (RIG 73.2) | 2 | as enacted, then each consolidated version: 1 November 2014 to 1 January 2017 |
| `73-3-abwassergesetz-abwg/` | Gesetz über die Abwasserbehandlung der Gemeinde Ilanz/Glion (RIG 73.3) | 2 | as enacted, then each consolidated version: 15 December 2014 to 1 January 2017 |
| `73-21-wasserversorgungsverordnung-wvv/` | Verordnung über die Wasserversorgung der Gemeinde Ilanz/Glion (RIG 73.21) | 3 | as enacted, then each consolidated version: 1 December 2014 to 1 January 2018 |
| `73-31-abwasserverordnung-abwv/` | Verordnung über die Abwasserbehandlung der Gemeinde Ilanz/Glion (RIG 73.31) | 2 | as enacted, then each consolidated version: 15 December 2014 to 1 January 2017 |
| `74-1-verkehrsgesetz-vkg/` | Gesetz über die Verkehrsanordnungen und die Parkierung der Gemeinde Ilanz/Glion (RIG 74.1) | 1 | as enacted, 1 January 2024 |
| `74-2-guterstrassenbefahrungsgesetz-gsbg/` | Gesetz über das Befahren von Alp-, Güter- und Waldstrassen der Gemeinde Ilanz/Glion mit Motorfahrzeugen (RIG 74.2) | 2 | as enacted, then each consolidated version: 1 January 2022 to 1 January 2024 |
| `74-11-verkehrsverordnung-vkv/` | Verordnung über die Verkehrsanordnungen und die Parkierung der Gemeinde Ilanz/Glion (RIG 74.11) | 2 | as enacted, then each consolidated version: 1 January 2026 to 1 May 2026 |
| `74-21-guterstrassenbefahrungsverordnung-gsbv/` | Verordnung über das Befahren von Alp-, Güter- und Waldstrassen der Gemeinde Ilanz/Glion mit Motorfahrzeugen (RIG 74.21) | 2 | as enacted, then each consolidated version: 1 January 2022 to 1 January 2024 |
| `75-1-abfallgesetz-abfg/` | Gesetz über die Abfallentsorgung der Gemeinde Ilanz/Glion (RIG 75.1) | 2 | as enacted, then each consolidated version: 1 January 2020 to 1 January 2022 |
| `75-2-energiegesetz-energ/` | Energiegesetz der Gemeinde Ilanz/Glion (RIG 75.2) | 1 | as enacted, 1 January 2025 |
| `75-11-abfallverordnung-abfv/` | Verordnung über die Abfallentsorgung der Gemeinde Ilanz/Glion (RIG 75.11) | 1 | as enacted, 1 January 2020 |
| `75-21-energieverordnung-enerv/` | Energieverordnung der Gemeinde Ilanz/Glion (RIG 75.21) | 1 | as enacted, 1 January 2025 |
| `76-1-meliorationsunterhaltsgesetz-melug/` | Gesetz über den Unterhalt, Betrieb und die Nutzung der Meliorationswerke und weiterer Werke ausserhalb des Baugebiets der Gemeinde Ilanz/Glion (RIG 76.1) | 1 | as enacted, 1 January 2022 |
| `76-11-meliorationsunterhaltsverordnung-meluv/` | Verordnung über den Unterhalt, Betrieb und die Nutzung der Meliorationswerke und weiterer Werke ausserhalb des Baugebiets (RIG 76.11) | 2 | as enacted, then each consolidated version: 1 January 2022 to 1 January 2024 |
| `81-1-marktgesetz-mag/` | Gesetz über das Marktwesen der Gemeinde Ilanz/Glion (RIG 81.1) | 2 | as enacted, then each consolidated version: 15 March 2015 to 1 April 2019 |
| `81-2-ladenoffnungszeitengesetz-log/` | Gesetz über die Ladenöffnungszeiten der Gemeinde Ilanz/Glion (RIG 81.2) | 1 | as enacted, 15 March 2015 |
| `81-11-marktverordnung-mav/` | Verordnung über das Marktwesen der Gemeinde Ilanz/Glion (RIG 81.11) | 2 | as enacted, then each consolidated version: 15 March 2015 to 1 April 2019 |
| `81-21-ladenoffnungszeitenverordnung-lov/` | Verordnung über die Ladenöffnungszeiten der Gemeinde Ilanz/Glion (RIG 81.21) | 1 | as enacted, 15 March 2015 |
| `82-1-gastwirtschaftsgesetz-gawg/` | Gesetz über die Gastwirtschaften der Gemeinde Ilanz/Glion (RIG 82.1) | 1 | as enacted, 15 March 2015 |
| `82-11-gastwirtschaftsverordnung-gawv/` | Verordnung über die Gastwirtschaften der Gemeinde Ilanz/Glion (RIG 82.11) | 3 | as enacted, then each consolidated version: 15 March 2015 to 1 February 2019 |
| `83-1-tourismusgesetz-tg/` | Gesetz über Gäste- und Tourismustaxen der Gemeinde Ilanz/Glion (RIG 83.1) | 1 | as enacted, 1 January 2015 |
| `83-11-tourismusverordnung-tv/` | Verordnung über Gäste- und Tourismustaxen der Gemeinde Ilanz/Glion (RIG 83.11) | 2 | as enacted, then each consolidated version: 1 January 2015 to 1 January 2026 |
| `85-12-verordnung-jagdliche-einrichtungen-jageinv/` | Verordnung über die Erstellung von jagdlichen Einrichtungen der Gemeinde Ilanz/Glion (RIG 85.12) | 1 | as enacted, 1 January 2022 |

## Source

The RIG (systematic collection) of the municipality, published by the municipality at <https://ilanz-glion.tlex.ch/>. For each act it gives every consolidated version it holds, with the day each version took effect, and a change table listing each amendment: its decision date, the day it took effect, the provision it touched and its entry in the chronological collection (CRS). Annexes the collection publishes only as separate PDF files are not included.

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

The author of a commit is the amending act, named by its entry in the chronological collection (CRS), with an e-mail address that cannot exist (`<act key>@ilanz-glion.tlex.ch.invalid`). Where one version holds changes by several amending acts and the change table does not say which provision each one touched, the commit names them all. The committer is always Lexifina.

## Limits

This is not an official publication. The binding text is the one the municipality publishes as binding. The history starts with the oldest consolidated version the collection holds for each act, which for many acts is later than the act's enactment. Only the acts listed above are included.
