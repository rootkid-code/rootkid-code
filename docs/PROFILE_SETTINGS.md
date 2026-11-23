# GitHub-Profil · Bio, Status, Privatsphäre

Die Profil-README ist **öffentlich aktiv**. Der native GitHub-Profilname, die **Bio**, der **Status** und angeheftete Repositories lassen sich jedoch nicht über die hier verfügbare GitHub-Verbindung bearbeiten. Diese Einstellungen können direkt in GitHub gesetzt werden.

## Bio · Empfohlener deutscher Text

```text
Ich baue KI-Workflows, Automationen & digitale Produkte – mit Sinn für klare UX, gute Prozesse und Technik, die wirklich hilft. ⚡
```

GitHub erlaubt in der Bio bis zu **160 Zeichen**. Die vorgeschlagene Fassung bleibt darunter.

**Anzeigename:** `rootkid / code` · Unternehmensfeld: vorerst leer · Standort: optional nicht öffentlich · Website: erst eintragen, wenn eine freigegebene Seite erreichbar ist.

## Nativer GitHub-Status (What's happening)

**Empfohlen:**

- Emoji: `⚡`
- Text: `Vibe Coding: AN · Reality Check: PFLICHT 🧪`
- Verfügbarkeit: **nicht Busy**, solange du nicht bewusst eingeschränkte Verfügbarkeit signalisieren möchtest
- Ablauf: **Nicht automatisch löschen** / ohne Ablauf, sofern du den Spruch dauerhaft zeigen möchtest
- Sichtbar für: **Everyone**, wenn er für alle Profilbesucher erscheinen soll

**Weitere Varianten:**

| Situation | Emoji | Text |
|:--|:--|:--|
| Standard · humorvoll | ⚡ | `Vibe Coding: AN · Reality Check: PFLICHT 🧪` |
| Fokusphase | 🎧 | `Im Flow. Bugs dürfen sich hinten anstellen.` |
| Deep Work | 🧠 | `Ideen werden zu Code. Bitte nicht erschrecken.` |
| Pausenmodus | ☕ | `Kompiliere Gedanken. Kaffee ist eine Dependency.` |
| Kurze Auszeit | 🌴 | `Offline-Modus: Menschen statt Maschinen.` |

Die GitHub-Vorschläge **Focusing, Working from home, Vacation, Sick, Busy** sind Vorlagen beziehungsweise Verfügbarkeitsoptionen; der eigentliche Statustext ist frei formulierbar. **Busy** signalisiert begrenzte Verfügbarkeit und ist keine dekorative Stufe in einer Fortschrittsanzeige.

**So einstellen:** Profilbild rechts oben → **Set status** → unter **What's happening** Text eintragen → Smiley wählen → ggf. **Busy**, **Expiration** und **Visible to** festlegen → speichern.

Der grafische „Mission-Control“-Balken in der README ist davon unabhängig und **statisch**. Er aktualisiert sich nicht automatisch anhand deiner GitHub-Verfügbarkeit oder Aktivität.

## Profilpins

Unter **Your profile → Customize your pins**:

- `showcase-studio-releases` – öffentliche Dokumentation **und [Beta 4 als Windows-ZIP](https://github.com/rootkid-code/showcase-studio-releases/releases/tag/v1.0.0-beta.4)**; noch kein Stable-Release
- `tresor-releases` – experimentelle Testversionen, keine Echtdaten

Weitere Projekte erst nach gesonderter Freigabe und Bereinigung öffentlich verknüpfen.

## E-Mail-Privatsphäre

Frühere **öffentliche Git-Commits** enthalten eine persönliche Autoren-E-Mail in ihren Metadaten. Die neue pseudonyme README ändert die bestehende Git-Historie nicht.

Für neue Commits:

1. GitHub → **Settings → Emails** → **Keep my email addresses private** aktivieren, sofern verfügbar.
2. Dort die tatsächlich angezeigte, kontospezifische GitHub-`noreply`-Adresse verwenden; keine Adresse raten.
3. Lokal `git config --global user.name "rootkid-code"` und `git config --global user.email "<deine echte GitHub-noreply-Adresse>"` konfigurieren.
4. Bei Verbindungen und Bots die tatsächlich geschriebenen Git-Autorenmetadaten anschließend prüfen.

**Wichtig:** Alte Commit-Metadaten sind durch diese Einstellungen nicht rückwirkend bereinigt. Eine Historienbereinigung müsste getrennt geplant und ihre Nebenwirkungen geprüft werden.

[← Profil](../README.md)
