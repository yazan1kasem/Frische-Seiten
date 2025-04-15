# Frische Seiten – Windows-basierte Anwendung zur Bezirksverwaltung

![image](https://github.com/user-attachments/assets/bcaedde6-64c5-4e36-a0ed-4d6c190dd083)

*Abbildung: Hauptansicht der Applikation*

## Projektübersicht

„Frische Seiten“ ist eine Windows-Desktop-Anwendung zur gezielten Suche nach Friseursalons in ganz Wien. Die Applikation ermöglicht Nutzerinnen und Nutzern, passende Friseure anhand verschiedener Kriterien wie Preis, Bezirk, Haartyp (z. B. lockig, glatt, dick, dünn) und Kundenbewertungen zu filtern und sortieren.

Das Ziel der Anwendung ist es, eine einfache und übersichtliche Plattform bereitzustellen, mit der man den optimalen Friseur für die eigenen Bedürfnisse schnell und effizient findet. Die Anwendung wurde mit dem .NET Framework entwickelt und nutzt Microsoft Access zur Datenspeicherung.

## Hauptfunktionen

- Suche nach Friseursalons in Wien basierend auf:
  - Preis
  - Bezirkszugehörigkeit
  - Spezialisierung auf Haartypen
  - Kundenbewertungen
- Sortierfunktion nach günstigstem Preis
- Benutzerfreundliche Windows-Forms-Oberfläche
- Verknüpfung mit einer Access-Datenbank für flexible Datenpflege
- XML-Unterstützung für externe Datenquellen (z. B. `districts.xml`)

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
├── districts.xml                   → Bezirksinformationen für Wien
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
4. Die Datenbankdateien (`.accdb`/`.mdb`) sowie `districts.xml` als Grundlage für die Suche verwenden.

## Hinweise zur Weiterentwicklung

Eine mögliche Weiterentwicklung könnte die Migration auf eine Web- oder Cross-Plattform-Lösung (z. B. WPF mit .NET Core oder Electron) sein sowie die Anbindung an moderne relationale Datenbanksysteme (z. B. PostgreSQL oder SQLite). Ebenso wäre eine Integration von Online-Bewertungen und Google Maps APIs denkbar.
