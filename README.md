# AM HomeHub

**Dein Smart Home vom Windows-PC steuern.**

Eine unabhängige Anwendung von **Andreas Münch**, hauptsächlich für Bosch Smart Home. Mit Geräteübersicht nach Räumen, Licht- und Rollladensteuerung, Raumheizung, Kontakten, Batteriemeldungen sowie Automationen und Szenarien. Eine optionale Matter-Testfassung ergänzt weitere Geräte.

## Herunterladen und installieren

**[Aktuelles Release und Windows-Setup öffnen](https://github.com/Bastl23/AM-HomeHub/releases/latest)**

1. Unter **Assets** die Datei **HomeControl-<Version>-Setup.exe** herunterladen.
2. Setup starten und den Installationsassistenten durchlaufen.
3. **AM HomeHub** über das Windows-Startmenü öffnen.
4. Im Menü **Controller einrichten** den eigenen Bosch-Controller verbinden.

**Kein GitHub-Konto, keine Freigabe und ab Version 0.25.1 kein GitHub-Token für Updates erforderlich.** Die Dateinamen beginnen aus Kompatibilitätsgründen weiterhin mit HomeControl. Das Programm heißt AM HomeHub.

## Voraussetzungen

- Windows auf einem 64-Bit-x64-PC; die .NET-Laufzeit ist im Paket enthalten.
- Ein eingerichteter, im eigenen Netzwerk erreichbarer Bosch Smart Home Controller II.
- Bereits in der Bosch-App angelernte Geräte.
- Zur ersten Kopplung: Controller-IP, Controller-Systempasswort und Zugriff auf die Taste am Controller.

Die Gerätefunktionen hängen von den durch den Controller bereitgestellten Diensten ab. Die Bosch-App bleibt für Geräteverwaltung und das Bearbeiten von Regeln zuständig.

## Anleitung und Updates

Die ausführliche Anleitung liegt dem Release als PDF bei und ist zusätzlich im Programm unter **Menü → Bedienungsanleitung** offline aufrufbar.

Unter **Menü → Updates** kannst du die automatische Prüfung beim Programmstart einschalten oder manuell prüfen. Ein vorhandenes Update wird erst nach deiner Bestätigung installiert. Ältere Versionen bis 0.25.0 einmal mit dem öffentlichen Setup aktualisieren, um auf die öffentliche Updatequelle zu wechseln. Vorhandene Kopplung und Einstellungen bleiben erhalten.

Das ZIP ist die portable Alternative: vollständig entpacken und HomeControl.exe starten. Die automatisch von GitHub angebotenen Source-code-Archive sind keine Installationspakete. Dieses Repository enthält ausschließlich Downloads und Anwenderhinweise; der Programmquellcode ist nicht enthalten.

## Hinweise

AM HomeHub ist kein offizielles Produkt der Robert Bosch Smart Home GmbH. Bosch, Philips Hue, Apple und weitere Marken gehören ihren jeweiligen Rechteinhabern. Die Matter-Anbindung ist eine nicht Matter-zertifizierte Testfassung; reine HomeKit-Geräte werden dadurch nicht unterstützt.

© 2026 Andreas Münch
