# Einstieg in VS Code und GitHub – ganz einfach erklärt

* Was ist VS Code?

Visual Studio Code (VS Code) ist ein Programm, mit dem man Texte schreiben kann – besonders praktisch für Programmierer. Aber keine Sorge: Am Anfang ist es einfach ein schöner Editor, wie Word, nur für Code.

* Was ist GitHub?

GitHub ist wie ein Online-Speicher für deine Projekte. Stell dir vor, du arbeitest an einem Text oder Bild und möchtest es sicher speichern – GitHub macht genau das, aber für Programmierprojekte. Außerdem kann man dort mit anderen zusammenarbeiten.

## Schritt-für-Schritt-Anleitung

### VS Code installieren:

* Geh auf https://code.visualstudio.com
* Lade das Programm herunter und installiere es wie jede andere App.

### GitHub-Konto erstellen

* Besuche https://github.com
* Erstelle ein kostenloses Konto mit deiner E-Mail-Adresse.

### VS Code mit GitHub verbinden

* Öffne VS Code.
* Installiere die Erweiterung „GitHub“ (einfach links im Menü auf das Kästchen-Symbol klicken und nach „GitHub“ suchen).
* Melde dich in VS Code mit deinem GitHub-Konto an (das geht über ein kleines Fenster, das sich öffnet).

### Projekt klonen (herunterladen)

* Öffne VS Code
* Drücke F1 oder Ctrl+Shift+P → gib „Git: Clone“ ein
* Füge die URL ein: https://github.com/eqvis/eqvis.git
* Wähle einen Ordner, in dem das Projekt gespeichert werden soll
* VS Code fragt, ob du das Projekt öffnen willst – bestätige mit „Ja“

### Änderungen einchecken (Speichern im Projektverlauf)

Wenn eine Datei bearbeitet wurde, z. B. etwas in text.txt geändert, kann diese Änderung „eingecheckt“ werden – das heißt, sie wird im Projektverlauf gespeichert.

1. Änderungen sehen:  
  In VS Code links auf das Symbol mit den drei Linien und Punkten klicken (das ist Git).
  Dort sieht man alle geänderten Dateien.
2. Änderungen hinzufügen („add“):  
  Einfach auf das + neben der Datei klicken → das bedeutet: „Ich möchte diese Änderung speichern“.
3. Beschreibung eingeben:  
  Oben erscheint ein Feld „Message“ – hier schreibt man kurz, was man geändert hat (z. B. „Rechtschreibung verbessert“).
4. Einchecken („commit“):  
  Danach auf den Haken oben klicken → das speichert die Änderung lokal im Verlauf.
5. Hochladen zu GitHub („push“):  
  Wenn das Projekt mit GitHub verbunden ist, erscheint ein Button „Push“ oder „Synchronisieren“.  
  Draufklicken → die Änderung wird online gespeichert.

### Änderungen vergleichen

* Zwischen aktuellem Stand und letztem Commit (HEAD)  
  Rechtsklick auf die Datei → „Vergleichen mit HEAD“ → zeigt, was sich seit dem letzten Einchecken geändert hat.
* Zwischen zwei Commits  
  Links im Git-Bereich auf „Commits“ klicken (kleines Uhr-Symbol).  
  Zwei Commits auswählen → Rechtsklick → „Vergleichen“ → VS Code zeigt die Unterschiede.

