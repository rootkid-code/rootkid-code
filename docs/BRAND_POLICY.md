# Marken- und Asset-Politik · rootkid/code

**Ziel:** Technologiekompetenz verständlich zeigen, **ohne** fremde Logos als eigenes Branding oder als Partnerschaftssignal zu verwenden.

## Was die Profilgrafiken tatsächlich enthalten

- Der Header und die Panels `assets/profile-hero-*.svg`, `assets/mission-control-*.svg`, `assets/ai-workbench-*.svg`, `assets/stack-atlas-*.svg` und `assets/build-loop-*.svg` sind **eigene redaktionelle Vektorgrafiken**.
- Anbieter wie OpenAI, Anthropic, DeepSeek, Google, n8n, React oder Supabase werden **nur sachlich als Text** genannt.
- Eigene generische Formen, Farbflächen und Prozesssymbole sind **keine nachgezeichneten Herstellerlogos**.
- Öffentlich verlinkte Projekte nutzen ihre **eigenen vorhandenen Projektgrafiken** (Showcase Studio, Tresor).

## Warum die alte Logo-Wand entfernt wurde

Die vorherige Profilversion enthielt unter `assets/tech/` acht kopierte Drittmarken-SVGs (u. a. React, TypeScript, Supabase, Gemini). Dass eine SVG im eigenen privaten Projekt vorhanden war, beweist **keine** Freigabe zur erneuten Veröffentlichung.

Weil ein fremdes Markenlogo für die Aussage „Ich habe das Werkzeug in Projekten verwendet“ **nicht nötig** ist, wird diese Grafikreihe aus dem **aktuellen öffentlichen Git-Baum entfernt**. Die neue Darstellung verwendet neutrale, selbst gestaltete Text-Karten und eine sachliche Tabelle.

**Git-Historie:** Ein normaler Commit kann diese alten SVG-Dateien aus dem aktuellen `main` entfernen; frühere Commit-Objekte können weiterhin existieren und über historische SHAs erreichbar sein. Eine vollständige historische Bereinigung wäre ein anderes, risikobehaftetes Vorhaben und wird nicht ungeprüft ausgeführt.

## Offizielle Richtlinien beachten

- **OpenAI:** [Brand Guidelines](https://openai.com/brand/) – Namen und Logos sind geschützte Marken; keine unautorisierte Integration in die eigene Marke, keine vorgetäuschte Billigung.
- **Anthropic:** [Legal Center / Trademark Guidelines](https://www.anthropic.com/legal) – keine irreführende Partnerschafts- oder Sponsorendarstellung.
- **DeepSeek:** [Open Platform Terms](https://cdn.deepseek.com/policies/en-US/deepseek-open-platform-terms-of-service.html) und [Brand Asset Guidelines](https://github.com/deepseek-ai/awesome-deepseek-integration/blob/main/docs/_logo%20svg/guidelines.md) – Logo-Verwendung nur unter engen Bedingungen; sachliche Referenzierung ohne Übernahme der Assets ist die risikoärmere Profilgestaltung.
- Auch die Zeichen anderer Hersteller haben eigene Inhaber und Richtlinien.

**Keine Rechtsberatung oder Zusage absoluter Rechtsfreiheit:** Gesetze, Markenrichtlinien und die Umstände einer konkreten Werbung können sich ändern. Bei kommerzieller Verwendung oder einem Markenstreit empfiehlt sich eine fachkundige Rechtsprüfung.

## Veröffentlichungscheck

1. Braucht der Besucher für das Verständnis **wirklich** ein Fremdlogo? Wenn nein: Text benutzen.
2. Ist die Nennung sachlich korrekt und durch einen Projektbezug belegbar?
3. Entsteht durch Größe, Reihenfolge, Badge-Design oder Sprache der Eindruck einer Partnerschaft?
4. Werden Logos, Schriftarten, Screenshots oder Daten aus fremden Quellen ohne Lizenz reproduziert?
5. Können neue Assets in GitHub hell/dunkel lesbar dargestellt werden?
6. Wurden Autorenmetadaten und historische Dateien getrennt von aktuellen README-Texten betrachtet?

[Zurück zum Profil](../README.md) · [KI-Toolbox](AI_TOOLBOX.md) · [Brand Guide](BRAND_GUIDE.md)
