# Review 1 Python

## Beurteiltes Projekt

|       | Bitte ausfüllen |
|-------|-----------------|
| Review von (ZHAW-Kürzel) | brodydan        |
| Review durch (ZHAW-Kürzel) | singhsuk        |
| Datum Review, von/bis | 25.03.2025      |

## Review

| Thema                                                                      | Skala | Mängel*                                                                                               | Verbesserungsmöglichkeiten*                                                                                 |
|----------------------------------------------------------------------------|-------|-------------------------------------------------------------------------------------------------------|-------------------------------------------------------------------------------------------------------------|
| Datenquelle klar definiert (Projekt 2: zusätzlich Abgrenzung zu Projekt 1) | 2     | NaN-Werte in der Datenbank                                                                            | NaN-Werte sollten am besten mit dem Median oder einer ähnlichen Methode ergänzt werden                      |
| Scraping vorhanden                                                         | 3     | -                                                                                                     | -                                                                                                           |
| Scraping automatisiert                                                     | 0     | Fehlend                                                                                                 | *Es muss ein Workflow mit GitHub Actions erstellt werden                                                    |
| Datensatz vorhanden                                                        | 2     | Zwar vorhanden, aber es sollten noch mehr Daten gescrapt werden – 1000 Datensätze könnten zu wenig sein | Weitere Daten scrapen                                                                                       |
| Erstellung Datensatz automatisiert, Verwendung Datenbank                   | 3     | -                                                                                                     | -                                                                                                           |
| Datensatz-Grösse ausreichend, Aufteilung Train/Test, Kennzahlen vorhanden  | 2     | Kennzahlen fehlen noch                                                                                | Kennzahlen der Modelle berechnen                                                                            |
| Modell vorhanden                                                           | 1     | Vorhanden, aber noch ungenaue Vorhersagen                                                             | Es sollte noch Feature Engineering durchgeführt und weitere Modelle neben dem RandomForest trainiert werden |
| Modell-Versionierung vorhanden (ModelOps)                                  | 1     | Zwar vorhanden, aber momentan nur lokal in einem File                                                 | Sollte am besten in einer File Storage wie Azure Blob gespeichert werden (steht noch aus)                   |
| App: auf lokalem Rechner gestartet und funktional                          | 3     | Keine – Scraper, Backend und Frontend funktionieren                                                   | -                                                                                                           |
| App: mehrere unterschiedliche Testcases durch Reviewer ausführbar          | 2     | -                                                                                                     | App sollte noch auf Azure deployed werden (steht noch an)                                                   |
| Deployment: Falls bereits vorhanden, funktional und automatisiert          | 0     | Fehlend                                                                                                | *(vorgehen ist klar, noch keine Zeit gehabt)                                                                |
| Code: Git-Repository vorhanden, Arbeiten mit Branches / Commits            | 2     | Es wird mit Commits gearbeitet, jedoch kein Feature-Branch verwendet                                  | Zusätzlich mit Branches arbeiten                                                                            |
| Code: Dependency Management, Dockerfile, Build funktional                  | 2     | Projekt wurde mit Poetry aufgesetzt, nicht mit requirements.txt – Pipeline fehlt noch                 | Eine Pipeline zur automatischen Build-Generierung sollte noch erstellt werden                               |

\* wenn fehlend: mögliche Schwierigkeiten und Lösungen besprechen

## Skala

| Skala |                 |
|-------|-----------------|
| 0     | fehlt           |
| 1     | mit Lücken      |
| 2     | alles vorhanden |
| 3     | übertroffen     |

## Hinweise

Der Projekt-Review fliesst nicht in die Beurteilung der Leistungsnachweise ein, soll aber dem Studierenden dazu dienen, bis zur Abgabe noch Verbesserungsmöglichkeiten zu erkennen. Der Review *des fremden Projektes* muss als Teil des *eigenen* Lernjournals abgegeben werden.