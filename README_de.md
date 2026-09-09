# LaserCut KonturFix v2.8.0

**LaserCut KonturFix** ist eine mehrsprachige Windows-Desktopsoftware zur Vorbereitung von Bildern und KI-Motiven für Lasercutter. Sie erzeugt saubere, geglättete und geprüfte SVG- oder DXF-Konturen, verbindet bei Bedarf lose Inseln mit Brücken und unterstützt Gravurbilder mit einer getrennten schneidbaren Außenkontur.

## Download

[LaserCut_KonturFix_v2_8_0_multilingual_Setup.exe herunterladen](https://github.com/Stoni66/LaserCut_KonturFix-Releases/releases/download/v2.8.0/LaserCut_KonturFix_v2_8_0_multilingual_Setup.exe)

[Release-Beschreibung und Details zu v2.8.0](https://github.com/Stoni66/LaserCut_KonturFix-Releases/releases/tag/v2.8.0)

Der Installer enthält eine 30-tägige Testphase, eine Desktop-Verknüpfung, die vollständige Offline-Hilfe und ein Deinstallationsprogramm.

## Neu in v2.8.0

- Lokaler Promptgenerator für Schnittmotive mit Material, Materialstärke, Abmessungen, Detailgrad und optionalem Außenrahmen
- Automatische ImageGen-Vorgaben für reine Schwarz-Weiß-Motive, Mindeststrukturen, wenige Inseln und brückenfreundliche Konturen
- Lokaler Promptgenerator für Gravurmotive mit Gravurstil, Detailgrad und wählbarer Zuschnittform
- Materialspezifische Graustufen- und Kontrastregeln für Acryl, Holz/MDF, Schiefer, Glas, Metall und Leder
- Fertige Prompts können kopiert und anschließend im passenden spezialisierten ChatGPT-Assistenten verwendet werden
- Erweiterte HTML-Hilfe und automatisierte Tests für beide Promptgeneratoren

Die Promptgeneratoren erzeugen keine Bilder innerhalb der Anwendung. Sie erstellen aus den gewählten technischen Vorgaben einen optimierten Prompt. Das eigentliche Motiv wird optional in ChatGPT erzeugt, gespeichert und anschließend wieder in LaserCut KonturFix geladen.

## Hauptfunktionen

- PNG-, JPG-, BMP- und TIFF-Dateien laden
- Schnittmotive aus Schwarz-Weiß-Masken erzeugen
- **Gravur + Außenkontur** mit eingebettetem Rasterbild und separater Schnittkontur
- Intelligente Hierarchie für Außenkonturen, Innenlöcher und verschachtelte Formen
- Drei Konturmodi: nur außen, außen plus Innenlöcher oder alle Konturen
- Automatische, kollisionsgeprüfte Brücken mit optional automatisch berechneter Breite
- Brücken direkt in der Vorschau manuell setzen und gezielt löschen
- Automatische Glättung pro Kontur mit einstellbaren Grenzwerten
- Drei Exportqualitäten: schnell, hoch bis 3000 Pixel oder Originalauflösung
- Automatische Exportprüfung mit verständlichen Warnungen und Reparaturvorschlägen
- PNG-, SVG- und DXF-Export
- Rückgängig/Wiederholen mit bis zu 20 Bearbeitungszuständen
- Vollständige Projekte als `.lkfproj` speichern und später weiterbearbeiten
- Oberfläche und Offline-Hilfe in Deutsch, Englisch, Französisch, Italienisch und Spanisch
- Offline-Lizenzierung mit digitaler Ed25519-Signatur

## Typischer Arbeitsablauf

1. Eigenes Bild laden oder mit einem der lokalen Promptgeneratoren einen geeigneten ImageGen-Prompt erstellen.
2. Schnittmotiv oder **Gravur + Außenkontur** wählen.
3. Schwarz-Schwelle, Invertierung, Glättung und Kleinteilentfernung einstellen.
4. Maske und Konturen erzeugen.
5. Inseln automatisch verbinden und Brücken bei Bedarf manuell korrigieren.
6. Motivbreite und Exportqualität festlegen.
7. Vorschau und Exportprüfung kontrollieren.
8. Als PNG, SVG oder DXF exportieren.

## Konturfarben

- Grün: innere Schnittkonturen, zuerst schneiden
- Rot: äußere Schnittkontur, zuletzt schneiden
- Blau: Gravur beziehungsweise Gravurvorschau
- Grau: ignorierte Hilfskonturen
- Gelb: gesetzte Brücken in der Vorschau

Die Farben unterstützen die Kontrolle. Die endgültige Zuordnung von Leistung, Geschwindigkeit, Fokus und Bearbeitungsreihenfolge erfolgt weiterhin in der jeweiligen Lasersoftware.

## Datenschutz und Internetzugriff

Bildverarbeitung, Konturerzeugung, Projekte und Lizenzprüfung arbeiten lokal. Bilder und Lizenzdaten werden nicht automatisch an ChatGPT oder andere Onlinedienste übertragen. Eine Internetverbindung und gegebenenfalls eine ChatGPT-Anmeldung werden nur benötigt, wenn ein optionaler ChatGPT-Link geöffnet wird.

## Lizenzierung

Die Software kann 30 Tage getestet werden. Für die weitere Nutzung ist eine Lizenz erforderlich. Die Aktivierung erfolgt vollständig offline und ist an die Installations-ID gebunden. Die Kundenanwendung enthält ausschließlich den öffentlichen Ed25519-Prüfschlüssel; privates Schlüsselmaterial ist nicht Bestandteil des Installers.

## Kompatibilität und Systemvoraussetzungen

- Windows 10 oder Windows 11
- 64-Bit-System
- Typische Zielprogramme: Trotec Ruby, LightBurn, RDWorks, Epilog, xTool und andere Programme mit SVG- oder DXF-Import
- Internet nur für die optionalen ChatGPT-Funktionen

Maschinen interpretieren Farben, Linienbreiten und Geometrien unterschiedlich. Jede exportierte Datei muss deshalb vor der Fertigung in der Zielsoftware kontrolliert und zunächst mit sicheren Maschinenparametern getestet werden.

## Autor

Entwickelt von Oswald Steiner.
