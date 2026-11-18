# Hinweise für die Arbeit an Familienrezepte

Dieses Repository sammelt Familienrezepte als Markdown.

## Rezepte aufnehmen und ändern

- Jedes Rezept liegt als eigene Markdown-Datei unter `rezepte/`. Verwende einen kurzen, kleingeschriebenen Dateinamen mit Bindestrichen und ersetze Umlaute entsprechend, zum Beispiel `kaese-lauch-suppe.md`.
- Übernimm Zutaten, Mengen, Zubereitung und weitere Angaben aus der angegebenen Quelle sorgfältig. Erhalte persönliche Hinweise und Varianten; erfinde keine Angaben. Ist eine Quelldatei genannt, lies sie vor der Übernahme.
- Ergänze beziehungsweise aktualisiere den Link in `README.md`.
- Bewahre die bestehenden Rezepte. Füge keine Abhängigkeiten oder Build-Schritte ohne entsprechenden Auftrag hinzu.

## Prüfen und veröffentlichen

- Prüfe vor Änderungen den Git-Status und erhalte vorhandene, nicht zu deinem Auftrag gehörende Änderungen.
- Kontrolliere die betroffenen Dateien und Links sowie die Rezeptangaben. Führe `git diff --check` aus; beachte auch neu angelegte, noch nicht verfolgte Dateien.
- Erstelle Commits und pushe nur, wenn dies beauftragt ist. Prüfe in diesem Fall den aktuellen Branch und Remote, stage nur den beauftragten Umfang und verifiziere Commit und Push getrennt.
- Behaupte keine öffentliche Erreichbarkeit allein aufgrund eines erfolgreichen Pushs. Falls Veröffentlichung beauftragt ist, prüfe den tatsächlichen Hosting-Status und die Erreichbarkeit gesondert.
