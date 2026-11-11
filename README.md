# Fragenschmiede Med

Die Fragenschmiede für Gesundheits- und Pflegeberufe:
**https://davuuuud.github.io/Fragenschmiede_Med/**

Sie baut aus einem Thema eine Frage an eine KI, die Beruf, Niveau und die
Anforderungen der Prüfung kennt — für Pflegefachfrauen und -männer,
Pflegefachassistenz, Medizinische Fachangestellte, Notfallsanitäterinnen und
-sanitäter sowie Physiotherapie.

> **Vorabfassung.** Die Quellen werden noch fachlich durchgesehen.

## Wo der Quellcode liegt

**Nicht hier.** Die Fragenschmiede Med ist dieselbe Anwendung wie die
[Fragenschmiede](https://github.com/davuuuud/Fragenschmiede), nur mit anderem
Inhalt: Berufe, Quellen und einzelne Texte stehen dort unter
`src/lib/profile/med/`. Alles Übrige teilen sich beide Seiten.

Dieses Repository enthält nur den Ablauf, der den Quellcode holt, mit
`PROFIL=med` baut und hier veröffentlicht
([`.github/workflows/pages.yml`](.github/workflows/pages.yml)). Er läuft jede
Nacht, bei jedem Push und auf Knopfdruck im Reiter *Actions*.

Rückmeldungen und offene Punkte gehören deshalb ins Repository der
Fragenschmiede.
