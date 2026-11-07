---
name: katechese-druckskript
description: "Katechese-Skript (.doc/.docx) in ein kurzes Druck-Skript für Joachim (Jo) umwandeln - nur das Theater, seine Rolle groß, Teresa klein, Wichtiges fett."
---

# Katechese-Druckskript für Joachim

Wenn Joachim ein Katechese-Skript (.doc/.docx/.pdf) schickt und ein druckbares Skript für sich möchte, so vorgehen:

## Vorgehen
1. Datei lesen (.doc zuerst mit soffice nach .docx konvertieren, Text mit python-docx auslesen).
2. Sprecher zuordnen: Zeilen ohne Label gehören zum vorherigen Sprecher. Joachim spielt den Geschichtenerzähler ("Jo"), Teresa ist die Moderatorin. Andere Rollen wie Teresa behandeln (klein).
3. Inhalt kürzen:
   - Einleitung oben komplett weglassen, kein Titel, keine Legende.
   - Nur das Theater behalten: von "Wo ist nur unser Bibel Geschichtenerzähler?" bis zum Bibelvers. Lied, Psalm, Kleingruppen weglassen, außer Joachim wünscht sie.
   - Lange Teresa-Texte auf ersten und letzten Satz kürzen, mit " … " dazwischen.
   - Regieanweisungen kurz halten (Freiwillige, Video, Bibelvers als eine fette Zeile mit ▶), Anweisungen in Klammern klein und kursiv.
4. Formatierung:
   - Joachims Name als "Jo:" (fett).
   - Seine Texte normal, ca. 11,5 pt; nur die wichtigen Stellen fett (Schlüsselsätze, Merksprüche, Wendepunkte, Schlusswort).
   - Teresa und alles andere klein (ca. 9 pt), Wichtiges darin (Regeln, Stichwörter wie "Bibelwurm komm heraus") fett.
   - Arial, A4, schmale Ränder, Ziel: eine Seite.
5. Text nicht verändern, auch Tippfehler nicht, nur kürzen.
6. Ausgabe als PDF und DOCX (python-docx, PDF per soffice), per SendUserFile schicken. Kurz sagen, was gekürzt wurde.
