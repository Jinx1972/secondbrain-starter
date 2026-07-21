# Vault Context

Dieses Vault ist das Second Brain von **[DEIN NAME]**.

> Beim ersten Start füllt Claude die Platzhalter in eckigen Klammern gemeinsam mit dir aus. Siehe `START HIER.md`.

## Über mich

[Wird beim Einrichten ausgefüllt: Name, Rolle, Aufgabenbereich, worum es in der täglichen Arbeit geht. Das ausführliche Profil liegt danach in [[00 Kontext/Über mich]].]

## Vault-Struktur

- **00 Kontext/** – Wer ich bin, wie ich schreibe, woran ich arbeite. Zentrale Referenz für alle inhaltlichen Aufgaben. Diese Dateien lesen, bevor Texte, Mails oder Angebote entstehen.
- **01 Inbox/** – Schnelle Gedanken und unverarbeitete Notizen. Alles ohne festen Platz landet hier.
- **02 Projekte/** – Aktive Projekte mit konkretem Ziel und Enddatum. Ein Projekt startet als einzelne .md-Datei. Einen Unterordner nur anlegen, wenn mehrere Dateien dazukommen.
- **03 Bereiche/** – Laufende Verantwortungsbereiche ohne Enddatum. Jeder Bereich ist ein eigener Ordner, weil er über die Zeit wächst.
- **04 Ressourcen/** – Referenzmaterial und gesammeltes Wissen. Jedes Thema ist ein eigener Ordner.
- **05 Daily Notes/** – Tägliches Logbuch. Was passiert ist, was entschieden wurde, was offen bleibt. Gibt Claude die Kontinuität zwischen den Sitzungen.
- **06 Archiv/** – Abgeschlossene Projekte und inaktive Bereiche. Aus dem Blickfeld, aber durchsuchbar.
- **07 Anhänge/** – Bilder, PDFs, Medien. Obsidian legt eingefügte Dateien automatisch hier ab.

## Regeln für dieses Vault

- Verknüpfungen zwischen Notizen als [[Wikilinks]] setzen.
- Neue Notizen ohne klaren Platz kommen nach `01 Inbox/`.
- Notizen atomar halten: eine Idee pro Notiz. Ausnahme sind Daily Notes, die einen ganzen Tag zusammenfassen.
- Daily Notes im Format `JJJJ-MM-TT.md`, zum Beispiel `2026-07-21.md`. So sortieren sie chronologisch.
- YAML-Frontmatter verwenden: `tags`, `status` (aktiv/abgeschlossen/pausiert), `date`.
- Dateinamen in normaler Schreibweise mit Leerzeichen und Großbuchstaben: `Beschreibender Name.md`.
- Neue Projekte bekommen eine einzelne .md-Datei direkt unter `02 Projekte/`. Unterordner erst, wenn das Projekt mehrere Dateien braucht.
- Bereiche und Ressourcen sind immer Ordner, weil sie wachsen.
- Abgeschlossene Projekte wandern nach `06 Archiv/`, aber nur auf ausdrückliche Anweisung, nicht eigenständig.
- Beim Erstellen oder Verschieben von Dateien kurz begründen, warum.
- Vor dem Löschen oder Überschreiben nachfragen.
- Sprache: Deutsch. Klar und direkt, ohne Hype-Sprech und ohne leere Füllsätze.

## Automatisch speichern

Was in einer Sitzung erarbeitet, gelernt oder entschieden wird, legt Claude eigenständig ab. Ohne Aufforderung. Das ist der eigentliche Zweck dieses Vaults: Wissen sammelt sich an, statt am Ende jedes Chats zu verschwinden.

Wohin was gehört:

| Was | Wohin |
|---|---|
| Wie ich schreibe, Tonfall, Formulierungen | `00 Kontext/Schreibstil.md` |
| Projektstand, Entscheidungen, offene Punkte | die jeweilige Datei in `02 Projekte/` |
| Tool-Wissen, Abläufe, Recherche | `04 Ressourcen/` |
| Was an einem Tag passiert ist | `05 Daily Notes/JJJJ-MM-TT.md` |
| Neue Regeln fürs Vault | diese Datei |

Nach dem Speichern kurz sagen, was abgelegt wurde und wo.

## Abgrenzung zum Corporate KI Brain

Dieses Vault ist **persönlich**. Was nur mich betrifft, bleibt hier: mein Schreibstil, meine Notizen, mein Projektstand.

Was das Team betrifft, gehört ins **Corporate KI Brain** in der Google Shared Drive: Marke und Design System, Angebot, Kundenprofile, Firmenprojekte, Playbooks, Vorlagen, Prozesse. Dafür gibt es den Skill `ministry-brain`.

Faustregel: Profitiert eine zweite Person davon, gehört es ins Brain. Sonst hierher.

Wissen aus dem Brain wird hier **nie kopiert**, sondern nur als Verweis abgelegt: Link, Stand-Datum, drei bis fünf Sätze Kern, dazu die eigenen Anmerkungen. Kopiertes Firmenwissen veraltet ab dem Moment, in dem es entsteht.
