# SPLSH – fertige Website für GitHub Pages

Dieses Paket enthält die fertig gebaute App mit Imposter, Wer lügt, Bet Buddy und Quiz.
Du brauchst keine Installation und keinen laufenden PC. Die Besucher benötigen Internet.

## Einmalig hochladen

1. Die ZIP-Datei vollständig entpacken.
2. Auf GitHub ein neues **öffentliches Repository** erstellen, beispielsweise `spieleabend`.
   Aktiviere beim Erstellen **Add a README file**, damit der Branch `main` vorhanden ist.
3. Im Repository **Add file → Upload files** öffnen.
4. **Den gesamten Inhalt dieses entpackten Ordners** hineinziehen: `index.html`,
   `assets`, `fonts`, die Bilder und alle weiteren Dateien. Nicht die ZIP und nicht
   den übergeordneten Ordner hochladen. `index.html` muss direkt oben im Repository liegen.
5. Mit **Commit changes** auf `main` speichern. Falls GitHub stattdessen einen
   Änderungsvorschlag anlegt, diesen anschliessend in `main` übernehmen.
6. **Settings → Pages** öffnen. Unter **Build and deployment** einstellen:
   - Source: **Deploy from a branch**
   - Branch: **main**
   - Folder: **/ (root)**
   Dann **Save** drücken.
7. Warten, bis GitHub unter Pages den veröffentlichten Link anzeigt, und diesen
   auf dem Handy öffnen. Der Link sieht etwa so aus:
   `https://DEIN-GITHUB-NAME.github.io/spieleabend/`.

Die Website wird von GitHub bereitgestellt. Dein Computer kann ausgeschaltet bleiben.
Alle Mitspielenden spielen weiterhin gemeinsam auf einem Handy; dies ist kein
Online-Mehrspielermodus mit getrennten Geräten. Auf dem Handy kannst du den Link
zusätzlich als Lesezeichen speichern.

## Wenn etwas fehlt

- Eine ZIP-Datei im Repository allein ist keine veröffentlichte Website: zuerst entpacken.
- Wird nur diese Anleitung angezeigt, kontrolliere, ob `index.html` direkt im
  Repository liegt und Pages auf `main` und `/ (root)` eingestellt ist.
- Fehlen Bilder oder Schriften, auch die Ordner `assets` und `fonts` und alle PNG-Dateien hochladen.
- Der Repositoryname ist frei wählbar. Die Dateinamen und Unterordner im Paket beibehalten.
- Bei späteren Updates den Inhalt des neuen Upload-Pakets ins gleiche Repository hochladen.

Stand: Version 6.2 mit beiden gelieferten Quizlisten: 17.000 Einträge mit
14.278 verschiedenen Fragetexten über alle Altersgruppen. Die ergänzte Datei
liefert 13.000 Fragen für 13 Kategorien, je 250 pro Kategorie und Altersgruppe.
Antwortpositionen sind
zufällig und ausgewogen verteilt. Bet Buddy bestätigt das erreichte Ziel automatisch.
Auswahlmenüs sind deckend und die mobile Spielauswahl hat korrigierte Rundungen.
Beim Zurückkehren aus einem Spiel bleiben Spielkarte und Auswahlleiste synchron.
Die Vorsätze Tiervergleich und Sportduell samt Nummern werden ausgeblendet.
Die Website wurde lokal
geprüft; das Hochladen und Aktivieren von Pages erfolgt erst durch dich.

Offizielle Anleitungen: [Dateien hochladen](https://docs.github.com/en/repositories/working-with-files/managing-files/adding-a-file-to-a-repository)
und [GitHub Pages aktivieren](https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site).
