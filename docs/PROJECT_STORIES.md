# Projektgeschichten · Von der Problemstellung zum Prototyp

**Lesefassung für GitHub-Besucher.** Diese Seiten sind keine Behauptung von Produktionsinstallationen oder öffentlich verfügbarem Quellcode. Der konkrete Reifegrad unterscheidet sich je Projekt.

## 01 · Showcase Studio — n8n erklären statt nur öffnen

**Problem:** Komplexe Node-Graphen lassen sich gegenüber Menschen außerhalb des technischen Editors schwer erläutern.

**Produktidee:** Ein lokaler, lesender Präsentationsraum für Workflow-Struktur, Abschnitte und Notizen. Daten sollen vor externer Weitergabe bewusst geprüft werden.

**Engineering-Fokus:** Python/FastAPI, lokale Desktop-Distribution, Rechte- und Datenfreigaben, verständliche Visualisierung, Windows-Abnahme.

**Öffentlicher Status:** [Showcase Studio Beta 4](https://github.com/rootkid-code/showcase-studio-releases/releases/tag/v1.0.0-beta.4) ist seit **23.11.2026** als **öffentliche Vorabversion mit Windows-ZIP** verfügbar. Dies ist **keine stabile oder unabhängig bestätigte native Windows-/Security-Freigabe**. Sieben Design-Looks sind in den Beta-Release-Notes beschrieben; Make-/Zapier-Importadapter sind dagegen erst geplant.

## 02 · Tresor — Desktop-Entwicklung mit harten Grenzen

**Problemraum:** Lokal arbeitende Anwendungen benötigen durchdachte Paketierung, Updates, Datenintegrität und klare Sicherheitsannahmen.

**Ansatz:** Experimentelle Entwicklung mit Rust/Tauri und Frontend-Technologien; dokumentierte Betas für technische Erkundung.

**Engineering-Fokus:** Systemgrenzen, Update-/Release-Prozesse, unabhängige Qualität und Risikodokumentation.

**Öffentlicher Status:** [Beta-Lab](https://github.com/rootkid-code/tresor-releases) mit Testmaterial. **Keine produktive Speicherung echter, sensibler oder unersetzlicher Daten.**

## 03 · Kettenwerk — eine Werkstatt als zusammenhängender Prozess

**Problem:** Beratung, Kundenanfragen, Servicefälle, Teile, Termine und Teamarbeit liegen oft in getrennten Werkzeugen.

**Produktidee:** Fahrrad-Finder, geführte Anfrage/Triage, Auftragsboard, Werkstattstatus und kontrollierte KI-Unterstützung.

**Technischer Schwerpunkt:** React/TypeScript, Supabase, Rollen und Berechtigungen, Gemini-Anbindungen, Prozess- und UI-Gestaltung.

**Status:** Privates Entwicklungs- und Demonstrationsprojekt; keine pauschale reale Werkstatt-Produktivfreigabe.

## 04 · KI-Atlas — Wissen als vernetzter Lernraum

**Problem:** Einzelne KI-Definitionen helfen wenig, wenn Begriffe, Lerninhalte und Beispiele ohne Kontext bleiben.

**Ansatz:** Interaktiver Lernraum aus Glossar, Wissensbeziehungen, Übungen und Lernpfaden.

**Technischer Schwerpunkt:** Astro, JavaScript, strukturierter Content, Wissensgraph, Accessibility und visuelle Navigation.

**Status:** Privater Projektstand. Externe Lehrinhalte sind nicht automatisch zur öffentlichen Wiederverwendung lizenziert.

## 05 · SYNTHESIS — filmisches 3D im Browser

**Problem:** Monumentale, filmische Art-Direction und performant wiedergebbare Echtzeit-3D-Szenen passen nicht ohne Weiteres zusammen.

**Ansatz:** Szenen in Blender entwickeln, Kamera-/Bewegungslogik in WebGL nachbilden und Performance-Grenzen messen.

**Technischer Schwerpunkt:** Blender, Three.js/WebGL, glTF, Kamerapfade und nachvollziehbare Styleframe-Vergleiche.

**Status:** Privater Entwicklungsstand mit getrennten Szenen-/Abnahmephasen; kein fertiges öffentliches Spiel.

## 06 · Career Workspace — Bewerbungen mit Fakten statt Fantasie

**Problem:** KI-generierte Bewerbungen können überzeugend klingen und trotzdem unbelegte Qualifikationen enthalten.

**Ansatz:** Strukturierte Erfahrungen, überprüfbare Angaben, Workflow für Stelle → Bewertung → Entwurf → menschliche Freigabe.

**Technischer Schwerpunkt:** TypeScript, React, Supabase, Datenvalidierung, geschützte Routen, nachvollziehbare Dokumente.

**Status:** Privater Entwicklungsstand; keine realen Nutzer- oder Bewerbungsdaten öffentlich gemacht.

## 07 · ProjectPilot — bessere Zusammenarbeit zwischen Entwicklungs-Workstreams

**Problem:** Viele parallele Branches, Aufgaben und Reviews erhöhen Koordinations- und Integrationsfehler.

**Ansatz:** Ein verständliches, lokales Cockpit für Aufgabenstatus, Dateizuständigkeiten und reproduzierbare Qualitätsnachweise.

**Technischer Schwerpunkt:** GitHub-Prozesse, Rollen und Reviews, QA-Gates, lokale Werkzeuge und Bedienbarkeit.

**Status:** Konzept-/Entwicklungsprojekt; keine pauschale Release- oder Sicherheitseinordnung.

## Was Projekte hier gemeinsam haben

- **Problemorientierung** statt reiner Tool-Demonstration.
- **Gut lesbare UI** statt Entwicklerwissen als Voraussetzung.
- **Klare Freigaben** vor kritischen Aktionen.
- **Belegbare Zustände** statt fiktiver „Production Ready“-Badges.
- **Iteratives Bauen und Prüfen** über Versionskontrolle und Dokumentation.

[Zurück zum Profil](../README.md) · [Projektkarte](PROJECTS.md) · [AI-Playbook](WORKFLOW_PLAYBOOK.md)
