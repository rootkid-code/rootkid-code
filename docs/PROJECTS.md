# Projektkarte · rootkid/code

> **Öffentliche Übersicht, kein Release- oder Testbericht.** Es werden nur tatsächlich öffentliche Repositories verlinkt. Private Arbeiten sind als Projektkontexte dargestellt, nicht als fertige Downloads.

## Öffentlich einsehbare Repositories

### Showcase Studio

**Link:** [Showcase Studio Releases](https://github.com/rootkid-code/showcase-studio-releases)

- **Problem:** Komplexe Automationsworkflows lassen sich im technischen Editor schwer vermitteln.
- **Ansatz:** Lesende Workflow-Erkundung, visuelle Präsentation und bewusste Freigabe vor externen Exporten.
- **Technischer Kontext:** n8n, Python, FastAPI, lokale Anwendungen, Export- und Sicherheitsgrenzen.
- **Stand:** Dokumentation öffentlich; **kein offizieller Anwendungsdownload veröffentlicht**.

### Tresor / Beta Lab

**Link:** [Tresor Releases](https://github.com/rootkid-code/tresor-releases)

- **Problemraum:** Lokale Desktop-Anwendungen, Paketierung, Update- und Release-Prozesse.
- **Technischer Kontext:** Rust, Tauri, React, TypeScript.
- **Stand:** Experimentelle Beta-Testpakete. **Nur künstliche, entbehrliche Testdaten.** Keine echte sensible Datenspeicherung, kein Sicherheitszertifikat und keine Produktivfreigabe.

## Private Entwicklungsarbeiten

| Projekt | Ausgangsproblem | Arbeitsschwerpunkte |
|:--|:--|:--|
| **Kettenwerk** | Wie gelangen unstrukturierte Kundenanfragen in einen nachvollziehbaren Werkstattprozess? | UI, Rollen, Anfrage-Triage, Human-in-the-Loop, Supabase, KI |
| **KI-Atlas** | Wie lassen sich KI-Begriffe durch Beziehungen, Lernpfade und Visualisierung verständlicher machen? | Astro, Wissensdaten, interaktive Lernoberflächen |
| **SYNTHESIS** | Wie wird aus filmischer 3D-Art-Direction ein kontrollierbares Browsererlebnis? | Blender, 3D, WebGL, deterministische Kamera, Performance |
| **Career Workspace** | Wie kann KI Bewerbungsabläufe vorbereiten, ohne Qualifikationen zu erfinden? | Strukturierte Daten, Belegführung, TypeScript, Auth |
| **ProjectPilot** | Wie können mehrere Entwicklungs- und QA-Workstreams geordnet zusammenarbeiten? | GitHub-Prozesse, Reviews, Nachweise, lokale Tools |

Alle diese Projekte befinden sich in unterschiedlichen Stadien von Idee, Implementierung und Prüfung. Aus dieser Übersicht folgt **weder öffentlicher Quellcode noch Produktivreife**.

## Warum nicht einfach alles öffentlich schalten?

- Private Branches und Historien können alte Tokens, persönliche Metadaten oder Zugangsdaten enthalten.
- Bilder, Schriftarten und Lernmaterialien können fremde Nutzungsrechte besitzen.
- Ein Source-Tree zeigt Implementierungsabsicht, aber nicht automatisch reale Browser-, Plattform- oder Sicherheitstests.
- Eine öffentliche Fallstudie kann den Ansatz erklären, **ohne** sensible Infrastruktur oder unfertige APIs herauszugeben.

## Standard für neue Projektpräsentationen

1. Problem, Zielgruppe und Lösung kurz erklären.
2. Markenrechte und Herkunft jedes Assets prüfen.
3. Echte Screenshots mit Build-/Commit-Stand und synthetischen Daten erstellen.
4. Architektur und Grenzen erklären.
5. Implementiert, getestet, geplant und veröffentlicht sauber trennen.
6. Historie, Git-Metadaten, PII, Logs und Konfigurationsdaten prüfen.
7. Nur tatsächlich vorhandene Demos und Release-Dateien verlinken.

**Produktpriorität:** Zuerst verlässlich nutzbare Free-/Community-Erfahrungen. Kommerzialisierung, Preisgestaltung und Pro-Verkauf sind zurückgestellt.

[← Profil](../README.md) · [Tech-Stack](TECH_STACK.md)
