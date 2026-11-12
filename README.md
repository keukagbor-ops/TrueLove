# True Love

**Ein persönliches Unreal-Engine-Lernprojekt für ein Spiel über Liebe und gemeinsame Erlebnisse.**

True Love befindet sich am Anfang der Entwicklung. Dieses Repository dokumentiert **Version 1: den ersten Prototyp und die technische Grundlage** für die weitere Arbeit an der Spielidee.

## Aktueller Stand · v1

- Unreal-Engine-Projekt mit Engine-Zuordnung **5.8**.
- Intro-Level `Lvl_IntroRoom` als Startkarte.
- First-Person-Basis mit Blueprint-Assets für Charakter, Kamera, Player Controller und Game Mode.
- Enhanced-Input-Assets für Bewegung, Blicksteuerung und Springen.
- Vorhandene Level-, Material- und Umgebungsassets.
- FBX-Export des Intro-Raums unter `SourceAssets/Environment/`.

Der Prototyp baut auf einer Unreal-First-Person- und Demo-Vorlage auf. Die vorhandenen Vorlagen und Assets bilden die Grundlage; die eigene Liebesgeschichte und die dazugehörigen Spielmechaniken sind die geplante Weiterentwicklung. Version 1 ist ein früher Editor-Projektstand.

## Projekt öffnen

1. Das Repository klonen oder als ZIP herunterladen und entpacken:

   ```bash
   git clone https://github.com/keukagbor-ops/TrueLove.git
   ```

2. `TrueLove.uproject` mit einer passenden Unreal-Engine-Installation öffnen. In der Projektdatei ist **5.8** hinterlegt.
3. Falls das Intro-Level nicht automatisch erscheint, `/Game/DemoTemplate/_Core/Lvl_IntroRoom` öffnen.
4. Mit **Play** im Editor den vorhandenen Prototyp ausprobieren.

Die in der Projektdatei aktivierten Plugins müssen in der Engine-Installation verfügbar sein: `ModelingToolsEditorMode`, `Landmass`, `InEditorDocumentation` und `AIAssistant`.

## Aufbau

```text
TrueLove.uproject            Unreal-Projektdatei
Config/                     Projekteinstellungen
Content/                    Karten, Blueprints, Input und weitere Assets
SourceAssets/Environment/    FBX-Export des Intro-Raums
CHANGELOG.md                Dokumentierte Entwicklungsstände
```

Die Blueprint-Logik liegt in binären `.uasset`-Dateien und wird im Unreal Editor betrachtet und bearbeitet. Zu diesem Stand gehört kein eigenes C++-Modul.

## Geplante Richtung

- Den Intro-Raum zu einem persönlichen Einstieg in die Geschichte ausarbeiten.
- Interaktionen und Dialoge rund um die Beziehung entwickeln.
- Eine kleine, zusammenhängende spielbare Szene fertigstellen.

Diese Punkte beschreiben die weitere Idee und sind noch keine zugesagten Funktionen von Version 1.

## Assets und Nutzung

Das Projekt enthält Unreal-Vorlagen und zugehörige Assets. Deren Rechte liegen bei den jeweiligen Rechteinhabern; dieses Repository vergibt dafür keine zusätzliche Lizenz. Engine-Dateien, lokale Editor-Daten, Cache und Build-Ergebnisse gehören nicht zum Repository.

## Entwicklungsstand

**v1.0.0-prototype · 12. November 2026** — erster öffentlich dokumentierter Projektstand. Der Snapshot wurde für die Veröffentlichung auf Dateiebene geprüft. Ein vollständiger Playtest und ein exportierter Spiel-Build sind für diesen Stand noch nicht dokumentiert.
