---
tags: [onboarding, setup]
status: aktiv
---

# START HIER

Diese Notiz richtet sich an Claude, nicht an dich. Du musst sie nicht lesen.

**Was du tust:** Öffne den Claudian-Chat in Obsidian, schreib den folgenden Satz hinein und schick ihn ab.

```
Lies START HIER.md und führe mich durch die Einrichtung.
```

Danach stellt Claude dir ein paar Fragen und baut daraus dein persönliches Kontext-Profil. Das dauert etwa zehn Minuten. Wenn du fertig bist, kannst du diese Notiz löschen.

---

## Regieanweisung an Claude

Du richtest gerade ein frisches Second Brain für eine neue Person ein. Sie hat Obsidian und Claudian installiert und schreibt dir zum ersten Mal. Vorwissen über Vaults, Markdown oder KI-Werkzeuge darfst du nicht voraussetzen.

**Grundhaltung:** Eine Frage pro Nachricht. Warte die Antwort ab. Keine Listen mit acht Fragen auf einmal, das überfordert. Duze die Person. Erkläre kurz, warum du etwas fragst.

### Schritt 1: Begrüßung und Einordnung

Erkläre in drei bis vier Sätzen, was hier passiert:

Dieses Vault ist ein Ordner mit Textdateien. Du als Claude kannst darin lesen und schreiben. Alles, was ihr gemeinsam erarbeitet, bleibt darin liegen und steht beim nächsten Mal wieder zur Verfügung. Anders als ein normaler Chat, der nach dem Schließen weg ist.

Sag dazu, dass ihr jetzt gemeinsam das Kontext-Profil anlegt, damit du weißt, mit wem du arbeitest.

### Schritt 2: Fragen stellen

Frage nacheinander, einzeln:

1. Name und Rolle bei Ministry. Was macht die Person den Großteil ihrer Zeit?
2. Woran arbeitet sie gerade konkret? Zwei bis drei laufende Projekte reichen.
3. Für welche Bereiche ist sie dauerhaft verantwortlich, ohne dass es ein Ende gibt?
4. Wofür will sie Claude vor allem einsetzen? Texte, Recherche, Struktur, Auswertung, etwas anderes?
5. Wie schreibt sie? Eher knapp oder ausführlich, sachlich oder persönlich, duzen oder siezen? Bitte um ein Beispiel: eine Mail oder einen Absatz, den sie selbst verfasst hat.

Wenn eine Antwort dünn ausfällt, hake einmal nach. Aber bohre nicht.

### Schritt 3: Dateien anlegen

Lege aus den Antworten an:

- `00 Kontext/Über mich.md` mit Name, Rolle, Aufgabenbereich, Arbeitsweise. Frontmatter: `tags: [kontext]`.
- `00 Kontext/Schreibstil.md` mit den Beobachtungen zum Stil. Falls ein Textbeispiel vorliegt, leite konkrete Merkmale daraus ab statt allgemeiner Aussagen: Satzlänge, Ansprache, typische Wendungen, was die Person vermeidet.
- Für jedes genannte Projekt eine Datei in `02 Projekte/`. Frontmatter: `tags`, `status: aktiv`, `date`. Inhalt: Ziel, aktueller Stand, nächster Schritt.
- Für jeden genannten Bereich einen Ordner in `03 Bereiche/` mit einer Übersichtsnotiz darin.
- Die heutige Daily Note in `05 Daily Notes/` mit einem kurzen Eintrag, dass das Vault heute eingerichtet wurde.

Ersetze anschließend in `CLAUDE.md` die Platzhalter in eckigen Klammern durch die echten Angaben. Alle. Es darf keine eckige Klammer stehen bleiben.

### Schritt 4: Firmenwissen anbinden

Weise darauf hin, dass es zusätzlich das **Corporate KI Brain** gibt, die gemeinsame Wissensbasis des Teams in der Google Shared Drive. Dort liegen Design System, Vorlagen, Kundenprofile und Playbooks.

Sag dazu: Wenn der Skill `ministry-brain` installiert ist, kannst du darauf zugreifen. Ist er es nicht, führt das Dokument „Start hier: Claude bei Ministry einrichten" im Brain durch die Installation.

Erkläre die Trennung in einem Satz: Persönliches bleibt in diesem Vault, Firmenwissen liegt im Brain, und aus dem Brain wird hier nur verwiesen, nie kopiert.

### Schritt 5: Abschluss

Zeige, was du angelegt hast. Erkläre die drei Handgriffe für den Alltag:

- **Etwas festhalten:** „Merk dir das" oder „schreib das ins Second Brain".
- **Tag abschließen:** „Fass den Tag zusammen" legt die Daily Note an.
- **Etwas wiederfinden:** einfach danach fragen, du durchsuchst das Vault selbst.

Zum Schluss der Hinweis, dass diese Notiz jetzt gelöscht werden kann.
