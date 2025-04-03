# ZigBee WC-Fenstersensor - Node-RED Flow

## Überblick
Dieser Node-RED Flow dient zur Überwachung eines ZigBee-basierten WC-Fenstersensors. Er erfasst den Status des Fensters (geöffnet/geschlossen/Zeit überschritten in geöffnetem Zustand) und den Batteriestand des Sensors. Bei relevanten Zustandsänderungen oder wenn der Kontakt länger als eine einstellbare Zeit geöffnet ist werden Benachrichtigungen per Pushover gesendet.

## Funktionen
- **Erfassung des Fensterstatus**: Erkennt, ob das Fenster geöffnet oder geschlossen ist.
- **Batteriestatus-Check**: Überwacht den Batteriestand des Sensors.
- **Benachrichtigungssystem**: Sendet Pushover-Benachrichtigungen, wenn das Fenster geöffnet wird oder der Batteriestand niedrig ist und wenn der Kontakt länger als eine einstellbare Zeit geöffnet ist.

## Anforderungen
- Node-RED installiert
- ZigBee2MQTT installiert mit Koordinator
- ZigBee-Sensor kompatibel mit ZigBee2MQTT und Node-RED
- Pushover Account mit Zugangsdaten zur Nutzung der Benachrichtigungsfunktion

## Installation
1. Node-RED und ZigBee2MQTT auf dem gewünschten System installieren.
2. Den Flow in Node-RED importieren.
3. Pushover-Zugangsdaten eintragen.
4. Flow aktivieren und testen.

## Nutzung
- Der Flow läuft automatisch im Hintergrund und überwacht den Sensor.
- Falls das Fenster geöffnet wird oder die Batterie schwach ist und wenn der Kontakt länger als eine einstellbare Zeit geöffnet ist, erfolgt eine Push-Benachrichtigung.

## Lizenz
Dieses Projekt steht unter der GNU-Lizenz.

## Kontakt
Bei Fragen oder Verbesserungen gerne ein Issue auf GitHub erstellen oder einen Pull Request einreichen.

