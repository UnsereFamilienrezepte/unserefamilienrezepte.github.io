# Hinweise für die Arbeit an Familienrezepte

Dieses Repository sammelt Familienrezepte als Markdown. Die Rezepte liegen unter `rezepte/`; dort gelten ergänzend die Hinweise in `rezepte/AGENTS.md`.

## Rezeptübersicht

- Ergänze oder aktualisiere bei Rezeptänderungen den Link in `README.md`, soweit nötig. Ordne jedes Rezept genau einmal einer passenden Kategorie zu.
- Kennzeichne jeden Eintrag ausschließlich mit einem Symbol: 🌱 vegan, 🥚 vegetarisch oder 🍽️ sonstige. Bei Varianten zählt die Hauptvariante. Erläuterungen zu Varianten stehen im Rezept, nicht in der Liste; die Legende bleibt erhalten.
- Für diese Sammlung gilt der Auberginenauflauf auch mit Parmesan als vegetarisch. Der Hinweis auf vegetarischen Hartkäse im Rezept bleibt erhalten.
- Bewahre bestehende Rezepte und ihre Links. Füge keine Abhängigkeiten oder Build-Schritte ohne entsprechenden Auftrag hinzu.

## Prüfen und veröffentlichen

- Prüfe vor Änderungen den Git-Status und erhalte vorhandene, nicht zum Auftrag gehörende Änderungen.
- Kontrolliere betroffene Dateien, Rezeptangaben und Links; prüfe bei Änderungen der Übersicht, dass jedes Rezept genau einmal verlinkt ist und die Ziele existieren. Führe `git diff --check` aus und beachte auch neu angelegte, noch nicht verfolgte Dateien.
- Erstelle Commits und pushe nur, wenn dies beauftragt ist. Prüfe in diesem Fall den aktuellen Branch und Remote, stage nur den beauftragten Umfang und verifiziere Commit und Push getrennt.
- Behaupte keine öffentliche Erreichbarkeit allein aufgrund eines erfolgreichen Pushs. Falls Veröffentlichung beauftragt ist, prüfe Hosting-Status und Erreichbarkeit gesondert.
