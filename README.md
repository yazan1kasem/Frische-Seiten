# Frische Seiten – Windows-basierte Anwendung zur Bezirksverwaltung

![image](https://github.com/user-attachments/assets/bcaedde6-64c5-4e36-a0ed-4d6c190dd083)

*Abbildung: Hauptansicht der Applikation*

## Projektübersicht

Dieses Projekt ist eine Windows-Desktop-Anwendung zur Verwaltung geografischer Bezirksdaten. Es wurde mit .NET Framework erstellt und ist als `.exe`-Anwendung ausführbar. Die Anwendung basiert auf einer Microsoft Access-Datenbank und erlaubt das Einlesen, Bearbeiten und Auswerten von Bezirksinformationen über eine grafische Benutzeroberfläche.

Die Software wurde mit dem Ziel entwickelt, eine einfache, benutzerfreundliche Lösung für die Verwaltung strukturierter XML- und Datenbankinformationen bereitzustellen, etwa zur Verwendung in Bildungseinrichtungen, Verwaltungsumgebungen oder als internes Tool zur Visualisierung geografischer Informationen.

## Hauptfunktionen

- Auslesen und Verarbeiten von XML-Dateien (`districts.xml`)
- Speicherung von Daten in MS Access-Datenbanken (`.accdb`, `.mdb`)
- Windows-Forms-UI für einfache Bedienbarkeit
- Unterstützung für verschiedene Versionen durch `.exe.config`-Datei
- Kompilierte Anwendung verfügbar (`Frische_Seiten.exe`)

## Technologie-Stack

| Komponente         | Technologie                      |
|--------------------|----------------------------------|
| Programmiersprache | C# (Windows Forms)               |
| Framework          | .NET Framework                   |
| Datenbank          | Microsoft Access (`.mdb`, `.accdb`) |
| Konfiguration      | XML-basiert (`.exe.config`)      |
| Verpackung         | Zip-Archiv (`Frische_SeitenV14j.zip`) für Distribution |

## Projektstruktur

```
Frische-Seiten/
├── Frische_Seiten.exe              → Kompilierte Hauptanwendung
├── Frische_Seiten.exe.config       → Konfiguration für Runtime-Einstellungen
├── Frische_Seiten.pdb              → Debug-Symboldatei
├── Frische_SeitenV14j.zip          → Verteilbares Gesamtpaket
├── districts.xml                   → Beispieldaten (Bezirke, geografische Einträge)
├── frische seiten.accdb            → Access-Datenbank (neuere Version)
├── frische seiten.mdb              → Access-Datenbank (ältere Version)
```

## Systemanforderungen

- Windows-Betriebssystem (Windows 10 oder neuer empfohlen)
- .NET Framework (Version je nach Build)
- Microsoft Access oder kompatibler Treiber für `.accdb`/`.mdb`

## Installation & Ausführung

1. Repository herunterladen oder das `.zip`-Paket entpacken.
2. Die Datei `Frische_Seiten.exe` ausführen.
3. Optional: Die Datei `Frische_Seiten.exe.config` anpassen für benutzerdefinierte Einstellungen.
4. Die Datei `districts.xml` als Datenquelle verwenden oder eigene XML-Dateien einbinden.

## Hinweise zur Weiterentwicklung

Die aktuelle Version ist primär als Desktoplösung konzipiert. Eine Weiterentwicklung könnte eine Migration auf eine Web- oder Cross-Plattform-Lösung (z. B. WPF mit .NET Core oder Electron) umfassen sowie die Anbindung an modernere relationale Datenbanksysteme (z. B. PostgreSQL oder SQLite).

## Lizenz

Dieses Projekt wurde zu Demonstrations- und Ausbildungszwecken erstellt. Lizenzangaben sind dem Repository nicht explizit beigefügt.
