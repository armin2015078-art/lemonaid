# Changelog

## Version 2.4.7
**Datum:** 2026.07.09

### 🐛 Fehler behoben
- Auto-Update hat `Lemonaid.exe` nicht zuverlässig ersetzt (Dialog kam nach Neustart erneut)
- Updater wartet jetzt, bis das Spiel wirklich beendet ist, bevor Dateien kopiert werden
- EXE wird per Rename-Trick ersetzt; Größe wird danach geprüft
- Installierte Version wird in `version.txt` gespeichert
- Update-Fehler werden in `%LOCALAPPDATA%\Lemonaid\update.log` protokolliert

## Version 2.4.6
**Datum:** 2026.07.09

### 🔧 Änderungen
- Zitronen Partikel

## Version 2.4.5
**Datum:** 2026.07.09

### 🔧 Änderungen
- Normal Zeit von 30 auf 20 Sekunden

### 🐛 Fehler behoben
- Crash in der Abklingen-Phase (Variable hat die Übersetzungsfunktion überschrieben)

## Version 2.4.4
**Datum:** 2026.07.09

### ✨ Neu
- UI-Sprache folgt dem System: Englisch bei englischem System, sonst Deutsch

## Version 2.4.3
**Datum:** 2026.07.09

### ✨ Neu
- Einstellungsmenü (Musik, Effekte, Bildschirmwackeln)
- Fortschritt zurücksetzen in die Einstellungen verschoben

### 🔧 Änderungen
- Versionsanzeige oben rechts

## Version 2.4.2
**Datum:** 2026.07.09

### ✨ Neu
- Shop auch aus dem Pause-Menü erreichbar
- Skin-Wechsel gilt sofort für alle Zitronen und das Raumschiff

### 🐛 Fehler behoben
- EXE-Update hat nicht korrekt angewendet
- Fortschritt konnte bei kaputten Saves crashen
- Wellen 5 und 10 kamen doppelt vor
- Pause konnte ohne NumPy abstürzen
- „Weiterspielen“ erschien schon ohne echten Fortschritt
- Spawn-Timer und Wellen-Banner wurden nicht mitgespeichert
- Zweite Spielinstanz konnte den Save überschreiben

## Version 2.4.1
**Datum:** 2026.07.09

### 🐛 Fehler behoben
- Update-Popup nicht aufgetaucht

## Version 2.4.0
**Datum:** 2026.07.09

### ✨ Neu
- Raumschiff/Zitronen Skins

### 🐛 Fehler behoben
- Fortschritt nach Update nicht gespeichert

## Version 2.3.0
**Datum:** 2026.07.09

### ✨ Neu
- Mehr Musik eingefügt

### 🔧 Änderungen
- Spiel startet maximiert
