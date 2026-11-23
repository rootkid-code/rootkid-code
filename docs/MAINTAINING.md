# Profil-Governance · rootkid/code

**Repository:** `rootkid-code/rootkid-code` · öffentliches GitHub-Profil, `README.md` als Einstieg.

## Informationsarchitektur

| Ebene | Dateien | Verantwortung |
|:--|:--|:--|
| Deutsche Hauptseite | `README.md` | Klare, kurze Story mit wahrheitsgemäßen Produktständen |
| Englische Version | `docs/README.en.md` | Gleiche Schwerpunktsetzung, keine widersprüchlichen Statusangaben |
| Statuspanel | `assets/mission-control-*.svg` | Statisch, keine „Live“-Behauptungen |
| KI-Ökosystem | `assets/ai-workbench-*.svg`, `docs/AI_TOOLBOX.md` | Textreferenzen und Nachweisstufen, keine Herstellerlogos |
| Stack | `assets/stack-atlas-*.svg`, `docs/TECH_STACK.md` | Verifizierbare Technologien, ohne Skill-Prozentzahlen |
| Bauablauf | `assets/build-loop-*.svg`, `docs/BUILD_PRINCIPLES.md` | Arbeitsweise, kein behauptetes Testergebnis |
| Projektstories | `docs/PROJECT_STORIES.md`, `docs/PROJECTS.md` | Reifegrade, Rechte und Verfügbarkeit transparent darstellen |
| Architektur-Playbook | `docs/WORKFLOW_PLAYBOOK.md` | Sicherer Konzept-Workflow, kein behaupteter Produktivbetrieb |
| Markenführung | `docs/BRAND_GUIDE.md`, `docs/BRAND_POLICY.md` | Originaldesign, Drittmarken- und Nutzungsgrenzen |
| Account-Einstellungen | `docs/PROFILE_SETTINGS.md` | Native Bio/Status/Busy/Pins nur direkt im GitHub-UI |

## Generelle Qualitätsregeln

- **Klarnamen, persönliche E-Mail-Adressen, Kunden-/Familieninhalte, Secrets und echte Tokens** nicht veröffentlichen.
- Keine privaten Repos als öffentlich verfügbar ausgeben; keine nicht existierenden Download-Dateien verlinken.
- Keine Einbindung von Drittanbieter-Statistiken oder „Trophy“-Widgets mit Tracking oder falschen Zahlen.
- Anbieter als sachliche Textreferenzen nutzen; **keine** kopierten Firmenlogos oder fremden Marken-Assets in neue Panels aufnehmen.
- Ein Logo aus dem lokalen Kettenwerk-Assetverzeichnis begründet **keine** Lizenz zur öffentlichen Zweitverwendung.
- **Ausdrücklich:** kommerzieller Pro-/Verkaufsfokus bleibt auf HOLD.
- Alte Git-Commit-Objekte enthalten historische Autorenmetadaten und gegebenenfalls frühere Assets; das aktuelle `main` bereinigt diese Historie **nicht** rückwirkend.

## PR-Checkliste

1. Beide Sprachversionen behalten denselben inhaltlichen Status.
2. Jede relative Markdown-/HTML-Verlinkung zeigt auf eine existierende Datei.
3. SVGs sind wohlgeformtes XML ohne `script`, `foreignObject`, Remote-Bilder oder nicht benötigte Spezialfunktionen.
4. Visuelle GitHub-Abnahme Dark/Light/Desktop/Mobil wird **tatsächlich** durchgeführt oder ehrlich als offen markiert.
5. Tool-Nennungen werden mit einem verifizierbaren Code-/Dokumentations-/Planungsbezug begründet.
6. Keine externen Markenlogos, fremden Schriftdateien, APIschlüssel oder personenbezogenen Metadaten neu einchecken.
7. Projekt-Claims (insbesondere Datenschutz, Testergebnis, Release) werden vor Merge überprüft.
8. Git-Änderung bleibt klein und nachvollziehbar; keine unnötigen Actions/CI-Minuten.

## Altdateien und Git-Historie

Frühere `assets/tech/*.svg` sowie die abgelöste `assets/tech-landscape-*.svg` sind nicht länger Teil der aktuellen öffentlichen Hauptversion. Der Inhalt älterer Commit-Objekte kann weiterhin erreichbar bleiben. **Kein Force-Push oder blindes Löschen der Historie**, solange andere Repositories, Links oder Nachweise darauf beruhen.

[← Profil](../README.md)
