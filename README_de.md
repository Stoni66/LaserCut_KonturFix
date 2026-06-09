# LaserCut KonturFix v2.5.0

**LaserCut KonturFix** ist eine Windows-Desktopsoftware zur Vorbereitung von Bildern und KI-Motiven fuer Lasercutter. Die App erzeugt aus Bilddateien saubere SVG- oder DXF-Daten, verbindet bei Bedarf lose Inseln mit Bruecken und kann seit v2.5.0 auch Gravurbilder mit schneidbarer Aussenkontur exportieren.

## Hauptfunktionen

- PNG, JPG, BMP und TIFF laden
- Schnittmotive aus Schwarz-Weiss-Masken erzeugen
- Gravurmodus mit eingebettetem Rasterbild und roter Aussenkontur
- SVG- und DXF-Export fuer Laserprogramme
- optimiertes PNG als Kontrollbild speichern
- Schwarz-Schwelle, Invertierung, Glaettung und Kleinteil-Entfernung
- Inseln automatisch mit Bruecken verbinden
- Brueckenbreite und maximale Brueckenlaenge einstellen
- Motivbreite in Millimetern festlegen
- SVG-Pfade glaetten und vereinfachen
- mehrsprachige Oberflaeche in Deutsch, Englisch, Franzoesisch, Italienisch und Spanisch
- Sprache wird gespeichert und beim naechsten Start wieder geladen
- Lizenzsystem mit Installations-ID, Lizenzanforderung und Aktivierung
- Installer mit Desktop-Verknuepfung und Deinstallation
- integrierte Hilfe und Quickinfos fuer die wichtigsten Bedienelemente

## Neu in v2.5.0

- Neuer Ausgabemodus **Gravur + Aussenkontur**
- Die Gravur bleibt als Rasterbild im SVG erhalten
- Nur die groesste geschlossene Aussenkontur wird als rote Schnittlinie erzeugt
- Zweiter GPT-Button fuer Gravurmotive mit schneidbarem Rahmen
- Umbenannter GPT-Button **Schnittmotiv erstellen** fuer klassische Schneidmotive
- Dynamische Quickinfos fuer Maske und SVG-Export je nach Ausgabemodus
- Aktualisierte Hilfe direkt in der App
- Nuitka-basierte Programmversion vorbereitet

## Custom-GPT-Schaltflaechen

**Schnittmotiv erstellen** oeffnet einen spezialisierten GPT fuer laserschneidbare Cut-Out-Motive:

https://chatgpt.com/g/g-689b206008608191843591bc9d8eec44-laser-cutter-designs-cutting

**Gravurmotiv erstellen** oeffnet einen spezialisierten GPT fuer Gravurbilder mit schneidbarem Rahmen:

https://chatgpt.com/g/g-6a220529bf9c81918c19433cccca2c31-create-engraving-motifs

Fuer beide Funktionen ist mindestens ein kostenloser ChatGPT-Account erforderlich. Der Benutzer muss im Browser angemeldet sein.

## Workflow fuer Schnittmotive

1. Bild laden oder Schnittmotiv per GPT erzeugen
2. Ausgabemodus **Schnittmotiv** waehlen
3. Schwarz-Schwelle, Glaettung und Kleinteile einstellen
4. Maske erstellen
5. Inseln bei Bedarf verbinden
6. SVG-Vorschau pruefen
7. Motivbreite festlegen
8. SVG oder DXF speichern

## Workflow fuer Gravurmotive

1. Gravurmotiv per GPT erzeugen oder eigenes Bild laden
2. Ausgabemodus **Gravur + Aussenkontur** waehlen
3. Maske erstellen
4. Aussenkontur in der Vorschau pruefen
5. SVG speichern
6. Die SVG kann anschliessend in NestCheck geladen und genestet werden

## Exportfarben

- Rot: Schnittkontur
- Blau: Gravur bzw. Gravurvorschau
- Grau: ignorierte Hilfskonturen

Im Gravurmodus enthaelt die SVG ein eingebettetes Rasterbild fuer die Gravur und eine rote Aussenkontur fuer den Schnitt.

## Kompatibilitaet

LaserCut KonturFix ist fuer typische Laser-Workflows ausgelegt, darunter Trotec Ruby, LightBurn, RDWorks, Epilog, xTool und andere Programme, die SVG oder DXF importieren koennen. Da Maschinen Farben und Linienstaerken unterschiedlich interpretieren koennen, sollte jede Datei vor dem Schnitt in der Zielsoftware kontrolliert werden.

## Installation

Der Windows-Installer heisst:

```text
LaserCut_KonturFix_v2_5_0_multilingual_Setup.exe
```

Direktdownload:

https://github.com/Stoni66/LaserCut_KonturFix/releases/download/v2_5_0/LaserCut_KonturFix_v2_5_0_multilingual_Setup.exe

Nach der Installation kann die App ueber Desktop-Verknuepfung oder Startmenue gestartet werden. Ein Deinstallationsprogramm ist enthalten.

## Lizenzierung

Die Software kann in einer Testphase genutzt werden. Fuer die dauerhafte Nutzung wird eine Lizenz benoetigt. Der Lizenzbereich enthaelt Name/Firma, E-Mail-Adresse, Installations-ID und Lizenzcode. Die Lizenzanforderung kann direkt aus der App vorbereitet werden.

## Systemvoraussetzungen

- Windows 10 oder neuer
- 64-Bit-System empfohlen
- Internetverbindung fuer die GPT-Schaltflaechen
- ChatGPT-Account fuer die Motiv-GPTs

## Autor

Designed by Oswald Steiner
