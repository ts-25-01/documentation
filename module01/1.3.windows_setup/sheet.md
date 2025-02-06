# Windows Setup

## Was ist Windows? Was ist ein Betriebssystem?
Windows ist ein Betriebssystem (OS), das die Verbindung zwischen der Hardware und der Software eines Computers herstellt. Es verwaltet Ressourcen, führt Programme aus und bietet eine Benutzeroberfläche zur Interaktion.

**Aufgabe:**
- Recherchiere und notiere die Hauptfunktionen eines Betriebssystems.
- Vergleiche Windows mit einem anderen Betriebssystem (z.B. Linux oder macOS) hinsichtlich Bedienung und Funktionalität.

## Was müssen wir auf unserem Windows-Rechner kennen?

### Windows-Menü
Das Windows-Startmenü ist der zentrale Punkt für den Zugriff auf Programme, Einstellungen und Dateien.

**Aufgabe:**
- Öffne das Startmenü und navigiere zu den wichtigsten Einstellungen.
- Suche nach installierten Programmen und öffne eines deiner Wahl.

### Taskleiste
Die Taskleiste enthält geöffnete Programme, das Suchfeld und Systeminformationen.

**Aufgabe:**
- Fixiere eine Anwendung in der Taskleiste.
- Entferne eine nicht benötigte Anwendung aus der Taskleiste.

### Auto-Start von Programmen
Einige Programme starten automatisch mit Windows und können das System verlangsamen.

**Aufgabe:**
- Öffne den Task-Manager und überprüfe, welche Programme automatisch starten.
- Deaktiviere unnötige Auto-Start-Programme.

### Terminal
Die Eingabeaufforderung (cmd) oder PowerShell ermöglicht erweiterte Systemsteuerung und Skripting.

**Aufgabe:**
- Öffne PowerShell und lasse dir das aktuelle Verzeichnis anzeigen.
- Führe den Befehl `ipconfig` aus und notiere deine IP-Adresse.

## Wie richten wir unseren Windows-Rechner optimal für den Kurs ein?

### Windows-Updates
Aktualisierte Systeme sind sicherer und leistungsfähiger.

**Aufgabe:**
- Überprüfe in den Einstellungen, ob Updates verfügbar sind und installiere sie falls nötig.

### Datei-Explorer
Windows verwaltet Dateien über den Datei-Explorer.

**Aufgabe:**
- Erstelle einen neuen Ordner für deine IT-Projekte.
- Verschiebe eine Datei in diesen Ordner.

### Was ist ein Paketverwaltungstool wie choco?
Chocolatey ist ein Paketmanager für Windows, mit dem Software einfach installiert werden kann.

**Aufgabe:**
- Installiere Chocolatey mit folgender PowerShell-Befehl:
```powershell
Set-ExecutionPolicy Bypass -Scope Process -Force; \n[System.Net.ServicePointManager]::SecurityProtocol = [System.Net.ServicePointManager]::SecurityProtocol -bor 3072; \niwr -useb https://community.chocolatey.org/install.ps1 | iex
```
- Überprüfe die Installation mit `choco -v`.

### Welche Pakete benötigen wir?

**Aufgabe:**
- Installiere mit Chocolatey die folgenden Programme:
```powershell
choco install -y git vscode 7zip googlechrome
```
- Starte Visual Studio Code und überprüfe die Installation.

## Welche Shortcuts müssen wir kennen?
Windows bietet viele nützliche Tastenkombinationen zur Produktivitätssteigerung.

**Aufgabe:**
- Teste folgende Shortcuts und notiere ihre Funktion:
  - `Win + D` (Desktop anzeigen)
  - `Win + E` (Explorer öffnen)
  - `Win + R` (Ausführen-Fenster öffnen)
  - `Strg + Shift + Esc` (Task-Manager öffnen)
  - `Alt + Tab` (Zwischen Fenstern wechseln)

Mit diesen Grundlagen bist du bestens für die Arbeit mit Windows ausgestattet!
