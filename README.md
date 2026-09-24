# Case Pilot System – Konzept & Planung

Planungsunterlagen für das **Case Pilot System**, mein Abschlussprojekt der Ausbildung **Software Developer:in Java am WIFI Wien** (2025, mit sehr gutem Erfolg bestanden).

Das Case Pilot System ist eine Desktop-Anwendung für Sozialbetreuer:innen: Klient:innen, Termine und Betreuungsverläufe an einem Ort verwalten, statt in verstreuten Listen und Notizen.

> **Zum Code:** Die fertige Anwendung (Java 17, JavaFX, Spring Boot, JPA, MySQL) liegt im Repository **[client-pilot](https://github.com/Badr-Emil/client-pilot)**.
> Dieses Repository enthält die Konzeptphase vom November 2024, bevor die Umsetzung begann.

## Dokumentation

| Dokument | Inhalt |
|---|---|
| [Anforderungsdokument](Dokumentation/Anforderungsdokument_Badr.pdf) | Funktionale und nicht-funktionale Anforderungen, technische Anforderungen, Systemarchitektur, Benutzergruppen, Risiken und Annahmen (11 Seiten) |
| [ER-Diagramm](Dokumentation/ER_Diagram_Badr.pdf) | Datenmodell mit Klient:innen, Terminen und Historie |
| [Klassendiagramm](Dokumentation/Klassendiagramm_Badr.pdf) | Aufbau der Anwendung in Klassen und Schichten |
| [Use-Case-Diagramm](Dokumentation/User_case_diagram_Badr.pdf) | Was Sozialbetreuer:innen mit dem System tun können |

## Geplante Funktionen

- **Klientenverwaltung:** anlegen, bearbeiten, löschen und auflisten
- **Terminverwaltung:** Termine pro Klient:in planen und verwalten
- **Historienverwaltung:** Betreuungsverlauf je Klient:in dokumentieren

Alle drei Bereiche sind in [client-pilot](https://github.com/Badr-Emil/client-pilot) umgesetzt.

## Vorgehen

1. **Anforderungsanalyse:** User Stories aus Sicht der Sozialbetreuer:innen, priorisiert und mit Anforderungs-ID, damit jede Anforderung später getestet werden kann
2. **Modellierung:** Use Cases, Datenmodell (ER) und Klassenstruktur mit UML
3. **Umsetzung:** Java-Anwendung in Schichtenarchitektur, siehe [client-pilot](https://github.com/Badr-Emil/client-pilot)
4. **Abschluss:** Präsentation und mündliche Prüfung vor der Prüfungskommission

## Autor

**Said Emil Badr** · Java Backend & KI-Automatisierung · [saidemilbadr.me](https://saidemilbadr.me)
